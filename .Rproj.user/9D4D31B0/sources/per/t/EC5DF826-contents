p <- ggplot(df, aes(x=tomatoMeter, y=audienceScore)) + 
  geom_point(aes(size=Profit,color=Profit)) + 
  labs(y="Audience Score", x="TomatoMeter") + 
  scale_color_gradient(low = "lightblue", high = "darkblue",name=" ",limits=c(0,2922917914),breaks=c(300000000,600000000,900000000,1200000000,1500000000,1800000000,2100000000,2400000000,2700000000,3000000000),labels=scales::dollar_format()) + 
  scale_size(labels=scales::dollar_format(),range=c(1,20),name="Box Office Earnings",breaks=c(600000000,1200000000,1800000000,2400000000,3000000000)) +
  expand_limits(x=c(0,100),y=c(0,100)) +
  ggtitle("\n 1000 Highest Grossing Movies by Rotten Tomatoes Score - All Time \n") +
  theme(text = element_text(size = 30),plot.title = element_text(face = "bold"),legend.key.height=unit(3,'cm'))