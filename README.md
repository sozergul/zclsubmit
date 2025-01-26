    USAGE:

    " GET
    http://sap.company.com:portnumber/sap/bc/zsubmitalv/getData?report=MB52&variant=APK&s_spart=10&matnr_low=G2003M01&matnr_high=G3003M01

    " POST (JSON)
    http://sap.company.com:portnumber/sap/bc/zsubmitalv/getData
    {
        "report": "MB52",
        "variant": "APK",
        "s_spart": "10",
        "matnr":
        {
            "from": "G2003M01",
            "to": "G3003M01"
        }
    }
