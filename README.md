# FormatDate

    useEffect(() => {
        const data0 = dayjs("2024-10-12 12:00:00").utc()
        const data1 = dayjs(data0).tz("America/Toronto")
        const data2 = dayjs(data1).tz("Asia/Bangkok")

        console.log('data2:', data2.format("YYYY-MM-DD HH:mm:ss"))
        console.log('data1:', data1.format("YYYY-MM-DD HH:mm:ss"))
    }, [])
