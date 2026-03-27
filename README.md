
fitness <-data.frame(
  day=1:12,
  steps=c(3000,35000,4000,5000,6000,7000,8000,8500,9000,9500,10000,11000),
  calories=c(150,170,190,230,260,300,340,360,380,400,430,470)
)
barplot(fitness$steps,fitness$calories)
plot(fitness$steps)
lines(fitness$steps)
hist(fitness$steps)
