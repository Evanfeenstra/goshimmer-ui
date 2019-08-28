# shimmer UI

**Web interface for IOTA Shimmer prototype, including**

 - real-time logs
 - TPS chart
 - Viewing raw transactions
 - 3D graph of current neighbors

 Now you can view your node's status from anywhere! Looks good on mobile too :)

 ![](https://raw.githubusercontent.com/Evanfeenstra/goshimmer-ui/master/css/shimmer-ui-gif.gif)


In the root folder of goshimmer, run:
```
git clone https://github.com/Evanfeenstra/goshimmer-ui.git plugins/ui
```

then in **main.go**, import the package:
```
"github.com/iotaledger/goshimmer/plugins/ui"
```

and add the plugin to main()
```
ui.PLUGIN,
```

build
```
go build -o shimmer
```

and run
```
./shimmer --node-enable-plugins "ui spammer"
```

### navigate to **[localhost:8080/ui](http://localhost:8080/ui)** in your browser!

# for secure acess:

**[goshimmer-webauth](https://github.com/Evanfeenstra/goshimmer-webauth)**
