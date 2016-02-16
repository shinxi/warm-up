Type:
	Bar
		c3:
		var chart = c3.generate({
		        data: {
		          columns: [
		            ['data1', 1030, 1200, 1100, 1400, 1150, 1250],
		            ['data2', 2130, 2100, 2140, 2200, 2150, 1850]
		//           ['data1', 30, 200, 100, 400, 150, 250],
		//           ['data2', 130, 100, 140, 200, 150, 50]
		          ],
		          type: 'bar',
		          onclick: function (d, element) { console.log("onclick", d, element); },
		          onmouseover: function (d) { console.log("onmouseover", d); },
		          onmouseout: function (d) { console.log("onmouseout", d); }
		        },
		        axis: {
		          x: {
		            type: 'categorized'
		          }
		        },
		        bar: {
		          width: {
		            ratio: 0.3,
		//            max: 30
		          },
		        }
		      })
	Line
		c3: line/spline/step?/area-step?/?scatter
		chart.js: line
		c3.generate({
		        data: {
		          columns: [
		            ['data1', 30, 200, 100, 400, 150, 250],
		            ['data2', 50, 20, 10, 40, 15, 25]
		          ],
		          onclick: function (d, element) { console.log("onclick", d, element); },
		          onmouseover: function (d) { console.log("onmouseover", d); },
		          onmouseout: function (d) { console.log("onmouseout", d); },
		        },

		          types: {
		            data1: 'spline/step?/area-step?',
		            data2: 'spline'
		          }
		})

		var lineChartData = {
			labels : ["January","February","March","April","May","June","July"],
			datasets : [
				{
					label: "My First dataset",
					fillColor : "rgba(220,220,220,0.2)",
					strokeColor : "rgba(220,220,220,1)",
					pointColor : "rgba(220,220,220,1)",
					pointStrokeColor : "#fff",
					pointHighlightFill : "#fff",
					pointHighlightStroke : "rgba(220,220,220,1)",
					data : [randomScalingFactor(),randomScalingFactor(),randomScalingFactor(),randomScalingFactor(),randomScalingFactor(),randomScalingFactor(),randomScalingFactor()]
				},
				{
					label: "My Second dataset",
					fillColor : "rgba(151,187,205,0.2)",
					strokeColor : "rgba(151,187,205,1)",
					pointColor : "rgba(151,187,205,1)",
					pointStrokeColor : "#fff",
					pointHighlightFill : "#fff",
					pointHighlightStroke : "rgba(151,187,205,1)",
					data : [randomScalingFactor(),randomScalingFactor(),randomScalingFactor(),randomScalingFactor(),randomScalingFactor(),randomScalingFactor(),randomScalingFactor()]
				}
			]

		}
		new Chart(ctx).Line(lineChartData, {
			responsive: true
		});
	Pie
		c3: a number, or a list of numbers
		customization: global hook: beforeInit, afterInit
		sort?
		c3.generate({
	        data: {
	          columns: [
	//            ["setosa", 0.2, 0.2, 0.2, 0.2, 0.2, 0.4, 0.3, 0.2, 0.2, 0.1, 0.2, 0.2, 0.1, 0.1, 0.2, 0.4, 0.4, 0.3, 0.3, 0.3, 0.2, 0.4, 0.2, 0.5, 0.2, 0.2, 0.4, 0.2, 0.2, 0.2, 0.2, 0.4, 0.1, 0.2, 0.2, 0.2, 0.2, 0.1, 0.2, 0.2, 0.3, 0.3, 0.2, 0.6, 0.4, 0.3, 0.2, 0.2, 0.2, 0.2],
	            ["versicolor", 1.4, 1.5, 1.5, 1.3, 1.5, 1.3, 1.6, 1.0, 1.3, 1.4, 1.0, 1.5, 1.0, 1.4, 1.3, 1.4, 1.5, 1.0, 1.5, 1.1, 1.8, 1.3, 1.5, 1.2, 1.3, 1.4, 1.4, 1.7, 1.5, 1.0, 1.1, 1.0, 1.2, 1.6, 1.5, 1.6, 1.5, 1.3, 1.3, 1.3, 1.2, 1.4, 1.2, 1.0, 1.3, 1.2, 1.3, 1.3, 1.1, 1.3],
	            ["virginica", 2.5, 1.9, 2.1, 1.8, 2.2, 2.1, 1.7, 1.8, 1.8, 2.5, 2.0, 1.9, 2.1, 2.0, 2.4, 2.3, 1.8, 2.2, 2.3, 1.5, 2.3, 2.0, 2.0, 1.8, 2.1, 1.8, 1.8, 1.8, 2.1, 1.6, 1.9, 2.0, 2.2, 1.5, 1.4, 2.3, 2.4, 1.8, 1.8, 2.1, 2.4, 2.3, 1.9, 2.3, 2.5, 2.3, 1.9, 2.0, 2.3, 1.8],
	            ["setosa", 30],
	//            ["versicolor", 40],
	//            ["virginica", 50],
	          ],
	          type : 'pie',
	          onmouseover: function (d, i) { console.log("onmouseover", d, i, this); },
	          onmouseout: function (d, i) { console.log("onmouseout", d, i, this); },
	          onclick: function (d, i) { console.log("onclick", d, i, this); },
	        },
	        axis: {
	          x: {
	            label: 'Sepal.Width'
	          },
	          y: {
	            label: 'Petal.Width'
	          }
	        }
	      });

	      chartjs: animation
	      var pieData = [
				{
					value: 300,
					color:"#F7464A",
					highlight: "#FF5A5E",
					label: "Red"
				},
				{
					value: 50,
					color: "#46BFBD",
					highlight: "#5AD3D1",
					label: "Green"
				},
				{
					value: 100,
					color: "#FDB45C",
					highlight: "#FFC870",
					label: "Yellow"
				},
				{
					value: 40,
					color: "#949FB1",
					highlight: "#A8B3C5",
					label: "Grey"
				},
				{
					value: 120,
					color: "#4D5360",
					highlight: "#616774",
					label: "Dark Grey"
				}

			]
			var ctx = document.getElementById("chart-area").getContext("2d");
			window.myPie = new Chart(ctx).Pie(pieData);

	Radar
