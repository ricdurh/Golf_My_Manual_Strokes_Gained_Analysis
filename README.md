# Personal Golf Strokes Gained
I've analyzed data from manually tracking personal golf stats in Excel:
- 168 holes tracking strokes gained from Mark Broadie's "Every Shot Counts" [book](https://www.amazon.com/Every-Shot-Counts-Revolutionary-Performance/dp/1592407501)
- ~25% include distance and direction result based on the intended shot (ex: long and left)


## Shot Location Frequency Bubble Map and Table by Distance and Lie, with Average Strokes Gained

![](/images/_bubble_map.png)


![](/images/_shots_sg_table.png)


## Strokes Gained by Distance from Off the Green
Here is a distribution of the strokes gained by distance to the hole for shots from off the green. The colors indicate the lie of the shot (T=Tee, R=Rough, F=Fairway, X=Recovery, S=Sand).

![](/images/SG_dist_not_on_green.png)

## Strokes Gained on the Green
This shows the distribution of strokes gained from shots on the green. The pattern for positive strokes gained inside 30 feet is due to the binary nature of a made putt having certain strokes gained, and a missed putt from these distances resulting in some level of negative strokes gained.

![](/images/SG_green.png)

## Strokes Gained by Hole and Lie
This shows the distribution of strokes gained by hole and lie.

![](/images/SG_by_Hole_and_Lie.png)

## Putting Strokes Gained by Distance (feet)
This shows the boxplots of putting strokes gained by distance in feet. A boxplot shows the distribution of data. These boxplots show dots as outliers on the low and high sides, then the outer regions and the middle of the rectangle represent the 25th, 50th, and 75th percentiles of the distribution.

![](/images/Putting_SG_by_dist.png)

## Greenside Rough Under 20 Yards
This shows the boxplots for shots under 20 yards in the rough by club. For a period, I switched between using a 60 and 62-degree wedge.

![](/images/Greenside_Rough.png)

## Fairway Outside 70 Yards
These two graphs show shots from the fairway outside 70 yards.

![](/images/FW_outside_70_yards.png)

![](/images/W_outside_70_yards_2.png)



### Heatmap of Shot Results (based on intended target) with Average Strokes Gained
For ~25% of the shots, there's data on where the shot went relative to the intended target. This results in a 7x7 matrix with distance on the y-axis and direction on the x-axis. The frequency is shown by the color from light to dark indicating low to high frequency.

![](/images/heatmap_1.png)
