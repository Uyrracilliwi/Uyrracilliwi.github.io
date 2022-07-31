<html>
    <head>
        <script src='https://d3js.org/d3.v4.min.js'></script>
        <style>
            * {box-sizing: border-box;}
            
            #head{
              height: 100px;
              background: black;
              color: white
            }
            
            #para {
              float: left;
              width: 650px;
              height: 1000px; 
              background: #ccc;
              padding: 10px;
              font-size: 20;
              
          }
     
            #footer {
              background-color:black;
              color:white;
              clear:both;
              text-align:center;
            padding:5px;	 	 
          }
      
          .btn-group .button {
            background-color: #4CAF50; /* Green */
            border: none;
            color: white;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            cursor: pointer;
          }    

          .chart{
            text-align: center;
            height: 720px;
          }
        </style>
    </head>
    <body>
        <div id="head">
          <h2> Electricity consumption in the United States </h2>
          <p> Electricity is an essential part of modern life and important to the U.S. economy. </p>
        </div>
    
    
        <!--Here are bottoms-->
        <fieldset>
            <legend>Page Options</legend>
            <div class="btn-group">
                <botton class = "button">previous</botton>
                <botton class = "button" onclick="location='page1.html'">1</botton>
                <botton class = "button" onclick="location='page2.html'">2</botton>
                <botton class = "button" onclick="location='page3.html'">3</botton>
                <botton class = "button" onclick="location='page2.html'">next</botton>
              </div>
        </fieldset>
        
    
        <!--Here are paragraph-->
        <div id="para">
          <p> Here is an overview of the US electricity consumption in 2021 by state. The consumption is ranked by order, 
            the bigger consumption states will more likely appear in the middle. In this bubble chart on the right, Texas is represented 
            by the hugest bubble, which tells us Texas consumes the most electricity. You can play around with the feature in the graph option field. 
            You can select the number to see the top consumption states. There is a feature to change the value to the percentage as well.
          </p>
          <p>
            The question you might ask is why the consumption varies by state. More generally speaking, the question might be, 
            what are the main reasons that affect electricity consumption?
          </p>
        </div>
    
        <!--Here are main plots-->
        <div id = "main">
          <!--Scene 1: bubble chart-->
          <div id="chart" class="chart" style="overflow: hidden;"></div>
            <fieldset>
                <legend>Graph Options</legend>
            
                <h3 class=first-h3>Number of Bubbles to show</h3>
                <div><select id=limit></select></div>
            
                <h3>Total Electricity Usage/Percentage Electricity Usage</h3>
                <select id="shuffle">
                    <option value="0">Total Electricity Usage</option>
                    <option value="1">Percentage Electricity Usage</option>
                </select>
                
                <h3>Background Color</h3>  
                <select id=bg>
                  <option value="#e0e0e0">Gray</option>
                  <option value="#eeeeee">Gray 2</option>
                  <option value="#111111">Dark</option>
                </select>
            </fieldset>
            <script>
                const defaultLimit = 25;
        
                // setup controls
                // const satInput = document.querySelector('#sat');
                // const lumInput = document.querySelector('#lum');
                const limitSelect = document.querySelector('#limit');
                const shuffleSelect = document.querySelector('#shuffle');
                const options = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25];
                options.forEach((val, i) => limitSelect.options[i] = new Option(val));
                limitSelect.selectedIndex = defaultLimit - 1;
                const bgSelect = document.querySelector('#bg');
                bgSelect.selectedIndex = 0;
                limitSelect.addEventListener('change', render);
                bgSelect.addEventListener('change', render);
                shuffleSelect.addEventListener('change', render);
        
                render();
        
                function render() {
        
                let idx = 0;
                const limit = limitSelect.selectedIndex + 1;
                const bgColor = bgSelect.options[bgSelect.selectedIndex].value;
                const doShuffle = shuffleSelect.selectedIndex === 1;
                document.querySelector('#chart').innerHTML = '';
                
                var json = {
                'children': [
                    {name: 'Texas', value: 473514913},
                    {name: 'Florida', value: 250827799},
                    {name: 'Pennsylvania', value: 230143279},
                    {name: 'California', value: 193074930},
                    {name: 'Illinois', value:173394525},
                    {name: 'Alabama', value: 137542702},
                    {name: 'New York', value: 129430271},
                    {name: 'North Carolina', value: 124363443},
                    {name: 'Ohio', value: 120992733},
                    {name: 'Georgia', value: 120126001},
                    {name: 'Washington', value: 116114468},
                    {name: 'Arizona', value: 109305057},
                    {name: 'Michigan', value: 106624721},
                    {name: 'Virginia', value: 103056183},   
                    {name: 'Louisiana', value: 100773771},
                    {name: 'South Carolina', value: 98528797},
                    {name: 'Indiana', value: 89956915},
                    {name: 'Oklahoma', value: 82297832},
                    {name: 'Tennessee', value: 80566010},
                    {name: 'Missouri', value: 72567869},
                    {name: 'Mississippi', value: 66581788},
                    {name: 'Oregon', value: 63624782},
                    {name: 'Kentucky', value: 63539007},
                    {name: 'Wisconsin', value: 61448545},
                    {name: 'New Jersey', value: 61106458}
                ].slice(0, limit)
                }

                /*
                    {name: 'Iowa', value: 59636671},
                    {name: 'West Virginia', value: 56661533},
                    {name: 'Minnesota', value: 56510143},
                    {name: 'Arkansas', value: 54641259},
                    {name: 'Kansas', value: 54541831},
                    {name: 'Colorado', value: 54115011},
                    {name: 'North Dakota', value: 42176424},
                    {name: 'Wyoming', value: 42010989},
                    {name: 'Connecticut', value: 41190572},
                    {name: 'Nevada', value: 40424745},
                    {name: 'Utah', value: 37087309},
                    {name: 'Nebraska', value: 36848681},
                    {name: 'Maryland', value: 36029204},
                    {name: 'New Mexico', value: 34075584},
                    {name: 'Montana', value: 23353290},
                    {name: 'Massachusetts', value: 18214141},
                    {name: 'Idaho', value: 17686135},
                    {name: 'New Hampshire', value: 16350578},
                    {name: 'South Dakota', value: 14146539},
                    {name: 'Maine', value: 10001870},
                    {name: 'Hawaii', value: 9079019},
                    {name: 'Rhode Island', value: 8894940},
                    {name: 'Alaska', value: 6276441},
                    {name: 'Delaware', value: 5205372},
                    {name: 'Vermont', value: 2156407}
                */
                if (doShuffle) {
                  var json = {
                    'children': [
                        {name: 'Texas', value: 11.81},
                        {name: 'Florida', value: 6.26},
                        {name: 'Pennsylvania', value: 5.74},
                        {name: 'California', value: 4.81},
                        {name: 'Illinois', value: 4.32},
                        {name: 'Alabama', value: 3.43},
                        {name: 'New York', value: 3.23},
                        {name: 'North Carolina', value: 3.10},
                        {name: 'Ohio', value: 3.01},
                        {name: 'Georgia', value: 2.99},
                        {name: 'Washington', value: 2.89},
                        {name: 'Arizona', value: 2.73},
                        {name: 'Michigan', value: 2.66},
                        {name: 'Virginia', value: 2.57},   
                        {name: 'Louisiana', value: 2.51},
                        {name: 'South Carolina', value: 2.45},
                        {name: 'Indiana', value: 2.24},
                        {name: 'Oklahoma', value: 2.05},
                        {name: 'Tennessee', value: 2.01},
                        {name: 'Missouri', value: 1.81},
                        {name: 'Mississippi', value: 1.66},
                        {name: 'Oregon', value: 1.58},
                        {name: 'Kentucky', value: 1.58},
                        {name: 'Wisconsin', value: 1.53},
                        {name: 'New Jersey', value: 1.52}
                    ].slice(0, limit)
                }
                       
                }
                const values = json.children.map(d => d.value);
                const min = Math.min.apply(null, values);
                const max = Math.max.apply(null, values);
                const total = json.children.length;
        
                document.body.style.backgroundColor = bgColor;  
                
                var diameter = 725,
                    color = d3.scaleOrdinal(d3.schemeCategory20c);
        
                var bubble = d3.pack()
                .size([diameter, diameter])
                .padding(0);
                
                var margin = {
                left: 25,
                right: 25,
                top: 25,
                bottom: 25
                }
        
                var svg = d3.select('#chart').append('svg')
                .attr('viewBox','0 0 ' + (diameter + margin.right) + ' ' + diameter)
                .attr('width', (diameter + margin.right))
                .attr('height', diameter)
                .attr('class', 'chart-svg');
        
                var root = d3.hierarchy(json)
                .sum(function(d) { return d.value; });
                // .sort(function(a, b) { return b.value - a.value; });
        
                bubble(root);
        
                var node = svg.selectAll('.node')
                .data(root.children)
                .enter()
                .append('g').attr('class', 'node')
                .attr('transform', function(d) { return 'translate(' + d.x + ' ' + d.y + ')'; })
                .append('g').attr('class', 'graph');

                node.append("circle")
                .attr("r", function(d) { return d.r; })
                .style("fill", getItemColor)
             
        
                //.on('mouseover', tip.show)
                //.on('mouseout', tip.hide);
                //node.call(tip);
                
                
                node.append("text")
                .attr("dy", "0.2em")
                .style("text-anchor", "middle")
                .style('font-family', 'Roboto')
                .style('font-size', getFontSizeForItem)
                .text(getLabel)
                .style("fill", "#ffffff")
                .style('pointer-events', 'none');
                if (doShuffle) {
                  node.append("text")
                  .attr("dy", "1.3em")
                  .style("text-anchor", "middle")
                  .style('font-family', 'Roboto')
                  .style('font-weight', '100')
                  .style('font-size', getFontSizeForItem)
                  .text(getValueText1)
                  .style("fill", "#ffffff")
                  .style('pointer-events', 'none'); 
                }else{
                
                node.append("text")
                .attr("dy", "1.3em")
                .style("text-anchor", "middle")
                .style('font-family', 'Roboto')
                .style('font-weight', '100')
                .style('font-size', getFontSizeForItem)
                .text(getValueText)
                .style("fill", "#ffffff")
                .style('pointer-events', 'none');  
                }
                
                function getItemColor(item) {
                return getColor(idx++, json.children.length);
                }
                function getColor(idx, total) {
                const colorList = ['F05A24','EF4E4A','EE3F65','EC297B','E3236C','D91C5C','BC1E60','9E1F63','992271','952480',
                                  '90278E','7A2A8F','652D90','502980','3B2671','262261','27286D','292D78','2A3384','2B388F',
                                  '2A4F9F','2965AF','277CC0','2692D0','25A9E0'];
                const colorLookup = [
                    [0,4,10,18,24], // 5
                    [0,3,6,9,11,13,15,18,20,24], //10 
                    [0,3,4,6,7,9,11,13,14,15,17,18,20,22,24], //15
                    [0,2,3,4,6,7,8,9,11,12,13,14,15,17,18,19,20,22,23,24], //20
                    [0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24] //25
                ];  
                for (const idxList of colorLookup) {
                    if (idxList.length >= total) {
                    return '#' + colorList[idxList[idx]];
                    }
                }
                }
        
        
                function getLabel(item) {
                    if (item.data.value < max / 10) {
                    return '';
                    }
                    return truncate(item.data.name);
                }
                function getValueText(item) {
                    if (item.data.value < max / 5) {
                    return '';
                    }
                    return item.data.value + " MWh";
                }

                function getValueText1(item) {
                    if (item.data.value < max / 5) {
                    return '';
                    }
                    return item.data.value + " %";
                }
                function truncate(label) {
                    const max = 11;
                    if (label.length > max) {
                    label = label.slice(0, max) + '...';
                    }
                    return label;
                }
                function getFontSizeForItem(item) {
                    return getFontSize(item.data.value, min, max, total);
                }
                function getFontSize(value, min, max, total) {
                    const minPx = 6;
                    const maxPx = 25;
                    const pxRange = maxPx - minPx;
                    const dataRange = max - min;
                    const ratio = pxRange / dataRange;
                    const size = Math.min(maxPx, Math.round(value * ratio) + minPx);
                    return `${size}px`;
                }
                }
            </script>  
          </div>
    
        <!--Here is footer-->
        <div id="footer">
          Copyright 2022 fovever
        </div>
    </body> 
</html>
