    USAGE:

    " GET
    http://sap.company.com:portnumber/sap/bc/zsubmitalv/getData?report=MB52&variant=APK&s_spart=10&matnr_low=T2003M01&matnr_high=T3003M01

    " POST (JSON)
    http://sap.company.com:portnumber/sap/bc/zsubmitalv/getData
    {
        "report": "MB52",
        "variant": "APK",
        "s_spart": "10",
        "matnr":
        {
            "from": "T2003M01",
            "to": "T3003M01"
        }
    }
