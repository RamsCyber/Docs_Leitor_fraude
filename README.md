# Docs_Leitor_fraude




#Cartão_Leitor_fraude
Arquivo Json do leitor de cartão:
{
	"status": "succeeded",
	"createdDateTime": "2024-11-30T21:33:51Z",
	"lastUpdatedDateTime": "2024-11-30T21:33:51Z",
	"analyzeResult": {
		"apiVersion": "2024-07-31-preview",
		"modelId": "prebuilt-creditCard",
		"stringIndexType": "utf16CodeUnit",
		"content": "BANK NAME\n5\n1234 5678 9012 3456\n5\n5\n.\nCARBHOLDER NAME\n122\nshutterstock",
		"pages": [
			{
				"pageNumber": 1,
				"angle": -0.04170000180602074,
				"width": 203,
				"height": 248,
				"unit": "pixel",
				"words": [
					{
						"content": "BANK",
						"polygon": [
							50,
							40,
							65,
							40,
							65,
							48,
							50,
							48
						],
						"confidence": 0.976,
						"span": {
							"offset": 0,
							"length": 4
						}
					},
					{
						"content": "NAME",
						"polygon": [
							66,
							40,
							84,
							40,
							84,
							48,
							66,
							48
						],
						"confidence": 0.631,
						"span": {
							"offset": 5,
							"length": 4
						}
					},
					{
						"content": "5",
						"polygon": [
							101,
							68,
							105,
							68,
							106,
							73,
							101,
							73
						],
						"confidence": 0.096,
						"span": {
							"offset": 10,
							"length": 1
						}
					},
					{
						"content": "1234",
						"polygon": [
							51,
							77,
							70,
							77,
							71,
							85,
							51,
							85
						],
						"confidence": 0.99,
						"span": {
							"offset": 12,
							"length": 4
						}
					},
					{
						"content": "5678",
						"polygon": [
							77,
							77,
							97,
							77,
							97,
							85,
							77,
							85
						],
						"confidence": 0.936,
						"span": {
							"offset": 17,
							"length": 4
						}
					},
					{
						"content": "9012",
						"polygon": [
							102,
							77,
							124,
							77,
							124,
							85,
							102,
							85
						],
						"confidence": 0.989,
						"span": {
							"offset": 22,
							"length": 4
						}
					},
					{
						"content": "3456",
						"polygon": [
							131,
							77,
							152,
							77,
							152,
							85,
							131,
							85
						],
						"confidence": 0.762,
						"span": {
							"offset": 27,
							"length": 4
						}
					},
					{
						"content": "5",
						"polygon": [
							74,
							90,
							81,
							90,
							81,
							96,
							74,
							95
						],
						"confidence": 0.064,
						"span": {
							"offset": 32,
							"length": 1
						}
					},
					{
						"content": "5",
						"polygon": [
							90,
							88,
							101,
							88,
							101,
							94,
							90,
							94
						],
						"confidence": 0.093,
						"span": {
							"offset": 34,
							"length": 1
						}
					},
					{
						"content": ".",
						"polygon": [
							126,
							90,
							130,
							90,
							130,
							96,
							126,
							96
						],
						"confidence": 0.073,
						"span": {
							"offset": 36,
							"length": 1
						}
					},
					{
						"content": "CARBHOLDER",
						"polygon": [
							51,
							99,
							83,
							98,
							83,
							104,
							51,
							105
						],
						"confidence": 0.567,
						"span": {
							"offset": 38,
							"length": 10
						}
					},
					{
						"content": "NAME",
						"polygon": [
							84,
							98,
							99,
							98,
							99,
							104,
							84,
							104
						],
						"confidence": 0.633,
						"span": {
							"offset": 49,
							"length": 4
						}
					},
					{
						"content": "122",
						"polygon": [
							146,
							157,
							154,
							158,
							154,
							163,
							146,
							163
						],
						"confidence": 0.483,
						"span": {
							"offset": 54,
							"length": 3
						}
					},
					{
						"content": "shutterstock",
						"polygon": [
							9,
							237,
							54,
							236,
							54,
							245,
							9,
							245
						],
						"confidence": 0.6,
						"span": {
							"offset": 58,
							"length": 12
						}
					}
				],
				"lines": [
					{
						"content": "BANK NAME",
						"polygon": [
							50,
							40,
							84,
							40,
							84,
							48,
							50,
							48
						],
						"spans": [
							{
								"offset": 0,
								"length": 9
							}
						]
					},
					{
						"content": "5",
						"polygon": [
							101,
							68,
							105,
							68,
							105,
							73,
							101,
							73
						],
						"spans": [
							{
								"offset": 10,
								"length": 1
							}
						]
					},
					{
						"content": "1234 5678 9012 3456",
						"polygon": [
							51,
							76,
							152,
							77,
							152,
							85,
							51,
							85
						],
						"spans": [
							{
								"offset": 12,
								"length": 19
							}
						]
					},
					{
						"content": "5",
						"polygon": [
							74,
							90,
							80,
							90,
							80,
							96,
							74,
							95
						],
						"spans": [
							{
								"offset": 32,
								"length": 1
							}
						]
					},
					{
						"content": "5",
						"polygon": [
							90,
							88,
							101,
							88,
							101,
							94,
							90,
							94
						],
						"spans": [
							{
								"offset": 34,
								"length": 1
							}
						]
					},
					{
						"content": ".",
						"polygon": [
							126,
							90,
							130,
							90,
							130,
							95,
							126,
							96
						],
						"spans": [
							{
								"offset": 36,
								"length": 1
							}
						]
					},
					{
						"content": "CARBHOLDER NAME",
						"polygon": [
							51,
							98,
							98,
							98,
							98,
							104,
							51,
							105
						],
						"spans": [
							{
								"offset": 38,
								"length": 15
							}
						]
					},
					{
						"content": "122",
						"polygon": [
							146,
							157,
							154,
							158,
							154,
							163,
							145,
							163
						],
						"spans": [
							{
								"offset": 54,
								"length": 3
							}
						]
					},
					{
						"content": "shutterstock",
						"polygon": [
							9,
							236,
							54,
							236,
							54,
							245,
							9,
							245
						],
						"spans": [
							{
								"offset": 58,
								"length": 12
							}
						]
					}
				],
				"spans": [
					{
						"offset": 0,
						"length": 70
					}
				]
			}
		],
		"styles": [
			{
				"confidence": 0.6,
				"spans": [
					{
						"offset": 32,
						"length": 1
					}
				],
				"isHandwritten": true
			},
			{
				"confidence": 0.5,
				"spans": [
					{
						"offset": 36,
						"length": 1
					}
				],
				"isHandwritten": true
			}
		],
		"documents": [
			{
				"docType": "creditCard",
				"boundingRegions": [
					{
						"pageNumber": 1,
						"polygon": [
							0,
							0,
							203,
							0,
							203,
							248,
							0,
							248
						]
					}
				],
				"fields": {
					"CardHolderName": {
						"type": "string",
						"valueString": "CARBHOLDER NAME",
						"content": "CARBHOLDER NAME",
						"boundingRegions": [
							{
								"pageNumber": 1,
								"polygon": [
									51,
									98,
									99,
									98,
									99,
									105,
									51,
									105
								]
							}
						],
						"confidence": 0.222,
						"spans": [
							{
								"offset": 38,
								"length": 15
							}
						]
					},
					"CardNumber": {
						"type": "string",
						"valueString": "1234 5678 9012 3456",
						"content": "1234 5678 9012 3456",
						"boundingRegions": [
							{
								"pageNumber": 1,
								"polygon": [
									51,
									77,
									152,
									77,
									152,
									85,
									51,
									85
								]
							}
						],
						"confidence": 0.454,
						"spans": [
							{
								"offset": 12,
								"length": 19
							}
						]
					},
					"CardVerificationValue": {
						"type": "string",
						"valueString": "122",
						"content": "122",
						"boundingRegions": [
							{
								"pageNumber": 1,
								"polygon": [
									146,
									157,
									154,
									158,
									154,
									163,
									146,
									163
								]
							}
						],
						"confidence": 0.241,
						"spans": [
							{
								"offset": 54,
								"length": 3
							}
						]
					},
					"IssuingBank": {
						"type": "string",
						"valueString": "BANK NAME",
						"content": "BANK NAME",
						"boundingRegions": [
							{
								"pageNumber": 1,
								"polygon": [
									50,
									40,
									84,
									40,
									84,
									48,
									50,
									48
								]
							}
						],
						"confidence": 0.31,
						"spans": [
							{
								"offset": 0,
								"length": 9
							}
						]
					}
				},
				"confidence": 1,
				"spans": [
					{
						"offset": 0,
						"length": 70
					}
				]
			}
		],
		"contentFormat": "text"
	}
}

