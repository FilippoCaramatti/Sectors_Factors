eu_sectors_data.rename({"EXV2.DE" : "Communication Services",
    "ESIC.DE": "Consumer Discretionary",
    "^ESIS.F": "Consumer Staples", 
    "ESIE.DE": "Energy",
    "ESIF.DE": "Financials",
    "ESIH.DE": "Health Care",
    "ESIN.DE": "Industrials",
    "ESIT.DE": "Information Technology",
    "EXV8.DE": "Materials",
    "^EXH9.DE": "Utilities",
    "EXSA.DE": "STOXX Europe 600"
    }, axis=1, inplace=True
)