<?php
	// include config so we have access to our creds
	include( 'config.php' );

	if ( isset( $_GET['code'] ) ) { // we are being redirected back from IG with a code
		$params = array( // post parmas 
			'client_id' => IG_CLIENT_ID,
			'client_secret' => IG_CLIENT_SECRET,
			'grant_type' => 'authorization_code',
			'redirect_uri' => IG_REDIRECT_URI,
			'code' => $_GET['code']
		);

		// call IG access_token endpoint with params to get a valid access token
		$ch = curl_init( 'https://api.instagram.com/oauth/access_token' );
		curl_setopt( $ch, CURLOPT_RETURNTRANSFER, true );
		curl_setopt( $ch, CURLOPT_CUSTOMREQUEST, 'POST' );
		curl_setopt( $ch, CURLOPT_POSTFIELDS, $params );
		curl_setopt( $ch, CURLOPT_SSL_VERIFYPEER, FALSE );
		$response_raw = curl_exec( $ch );
		$response = json_decode( $response_raw, true );
		curl_close( $ch );

		// display our repsonse from IG
		echo '<pre>';
		print_r( $response );
		echo '</pre>';
	}
?>

<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Austin Duggin</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
  <script type="text/javascript" src="script.js"></script>
</head>

<body>
  <p id="top"></p>
  
  <!--Navigation Menu-->
  <ul class="nav">
    <li><a class="active" href="index.html">Home</a></li>
    <li><a href="search.html">Search</a></li>
    <li><a href="https://www.linkedin.com/in/grace-metri-419478264" target="_blank"><img
          src=""></a></li>
  </ul>

  <!--Main Panel with Content-->
  <div class="main">  
  <h1>Instagram</h1>
<a href="https://api.instagram.com/oauth/authorize/?client_id=<?php echo IG_CLIENT_ID; ?>&redirect_uri=<?php echo IG_REDIRECT_URI; ?>&response_type=code">
	GET CODE
</a>

  </div>
  

  <!--Bookmark to top of page -->
  <a href="#top">
    <div class="circle">
      &#x2912;
    </div>
  </a>


</body>

</html>