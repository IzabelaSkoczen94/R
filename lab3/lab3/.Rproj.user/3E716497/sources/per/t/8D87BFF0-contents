library(ahp)
#ahpFile <- system.file("extdata", "laptopy.ahp", package="ahp")
ahpFile <- "C:/Users/Izuś/Desktop/jezyk R/lab3/lab3/laptopy.ahp"
laptopyAhp <- Load(ahpFile)
print(laptopyAhp, priority = function(x) x$sparent$priority["total", x$name])
Calculate(laptopyAhp)
Analyze(laptopyAhp)
AnalyzeTable(laptopyAhp)