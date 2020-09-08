# VuslatSenaEmre-dartSnippet

{
	"stateless": {
	  "prefix": "fless",
	  "body": [
		"import 'package:flutter/material.dart';",
		"class $1 extends StatelessWidget {",
		"\t@override",
		"\tWidget build(BuildContext context) {",
		"\t\treturn Container(",
		"\t\t\t$2",
		"\t\t);",
		"\t}",
		"}"
	  ],
	  "description": "Statles widget are available"
	},
  
	"stateful": {
	  "prefix": "ffull",
	  "body": [
		"import 'package:flutter/material.dart';",
		"class $1 extends StatefulWidget {",
		"\t@override",
		" \t_$1State createState() => _$1State();",
		"}",
  
		"class _$1State extends State<$1> {",
		" \t@override",
		" \tWidget build(BuildContext context) {",
		"\t\treturn Container(",
		" \t\t\t$2",
		"\t\t);",
		"\t}",
		"} "
	  ],
	  "description": "Stateful widget are available"
	},

	"bubble sort": {
		"scope": "java",
		"prefix": "bubble_Sort",
		"body": [
			"int n = arr.length; ",
			"for (int i = 0; i < n-1; i++) ",
				"for (int j = 0; j < n-i-1; j++) ",
					"if (arr[j] > arr[j+1]) ",
				"{ ",
						"int temp = arr[j]; ";
						"arr[j] = arr[j+1]; ";
						"arr[j+1] = temp;";
					"}",
			],
			"description": "New array applying Buble Sort Algorithm"
		}


  }
