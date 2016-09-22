# Resource profile

"recurso": {
	"type": "object",
	"properties": {
		"tipo": {"type":"string", 
			"index": "not_analyzed",
			"enum" : ["doc","img","data","page","map","vid","som","col"]},
		"titulo":{"type":"string", "index": "not_analyzed"},
		"autor":{"type":"array",
			"items": {"type": string, "index": "not_analyzed"}
		},
		"descricao": {"type":"string"),
		"taxon":{"type":"array",
			"items": {"type": string, "index": "not_analyzed"}
		},		
		"espaco":{"type":"array",
			"items": {"type": string, "index": "not_analyzed"}
		},
		"tema":{"type":"array",
			"items": {"type": string, "index": "not_analyzed"}
		},
		"tempo": {"type":"date"}
		"url":{"type":"string"},
	}
	"required": ["titulo", "url"]
},
