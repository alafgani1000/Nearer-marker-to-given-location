# Nearer-marker-to-given-location
<br />
1.Add the places that you want in location array. i.e. add lat, long.<br />
e.g. 	var locations = [
	  ['Viman Nagar',18.574674, 73.912417, 1],
	  ['Pimpari Chinchwad',18.630026, 73.803868, 2],
	  ['Hinjewadi',18.592884, 73.741360, 3],
	  ['Kothrud',18.507608, 73.795669,4],
	  ['Kondwa',18.470501, 73.891788,5]
	  
	];
<br />
2.Add lat and long for area locality.<br />
  e.g.function initialize() {
	  var haightAshbury = new google.maps.LatLng(18.596815, 73.763575); // Locality Area
	  var mapOptions = {
		zoom: 12,
		center: haightAshbury,
		mapTypeId: google.maps.MapTypeId.TERRAIN
	  };
<br />   
3.Add your API Key in following url.<br />
    <script async defer
    src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initialize">
    </script>
<br />   
4.To find your api key goto following url:<br />
  https://developers.google.com/maps/documentation/embed/get-api-key
