        <BgCurvedRoad points={[[0, -35], [5, -80], [-8, -140], [10, -200], [0, -300]]} width={3.5} />
        <BgCurvedRoad points={[[0, 35], [-10, 90], [8, 150], [-5, 220], [10, 320]]} width={3.5} />
        <BgCurvedRoad points={[[-35, 0], [-80, -8], [-140, 10], [-210, -5], [-320, 8]]} width={3.5} />
        <BgCurvedRoad points={[[35, 0], [90, 10], [150, -8], [220, 5], [330, -10]]} width={3.5} />

        {/* Diagonal curvy roads */}
        <BgCurvedRoad points={[[60, -60], [100, -90], [140, -130], [180, -180], [250, -260]]} width={2.5} />
        <BgCurvedRoad points={[[-65, 60], [-110, 100], [-160, 150], [-200, 220], [-270, 300]]} width={2.5} />
        <BgCurvedRoad points={[[70, 65], [120, 100], [160, 140], [220, 200]]} width={2} />
        <BgCurvedRoad points={[[-70, -70], [-120, -110], [-170, -160], [-230, -230]]} width={2} />

        {/* Curving cross streets - near ring */}
        <BgCurvedRoad points={[[-160, -100], [-100, -95], [-50, -105], [0, -100], [50, -95], [100, -105]]} width={2.5} />
        <BgCurvedRoad points={[[50, -120], [100, -115], [150, -125], [200, -120], [280, -110]]} width={2} />
        <BgCurvedRoad points={[[-180, 90], [-120, 85], [-60, 95], [0, 90], [40, 85]]} width={2.5} />
        <BgCurvedRoad points={[[60, 100], [110, 95], [160, 105], [220, 100], [300, 95]]} width={2} />
        <BgCurvedRoad points={[[-100, -180], [-105, -120], [-95, -60], [-100, 0]]} width={2.5} />
        <BgCurvedRoad points={[[-110, 60], [-105, 110], [-115, 160], [-110, 220], [-105, 300]]} width={2} />
        <BgCurvedRoad points={[[100, -180], [95, -120], [105, -70], [100, -20]]} width={2} />
        <BgCurvedRoad points={[[110, 50], [105, 100], [115, 160], [110, 230], [105, 310]]} width={2.5} />

        {/* Smaller winding side roads */}
        <BgCurvedRoad points={[[-140, -70], [-145, -100], [-135, -130], [-140, -160]]} width={1.5} />
        <BgCurvedRoad points={[[130, 70], [125, 100], [135, 130], [130, 160]]} width={1.5} />
        <BgCurvedRoad points={[[-80, -140], [-100, -135], [-130, -145], [-160, -140]]} width={1.5} />
        <BgCurvedRoad points={[[80, 130], [110, 125], [140, 135], [170, 130]]} width={1.5} />
        <BgCurvedRoad points={[[150, -80], [145, -110], [155, -140], [150, -170]]} width={1.5} />
        <BgCurvedRoad points={[[-60, 130], [-55, 160], [-65, 190], [-60, 220]]} width={1.5} />
        <BgCurvedRoad points={[[70, -80], [100, -85], [130, -75], [160, -80]]} width={1.5} />
        <BgCurvedRoad points={[[-70, 120], [-100, 115], [-130, 125], [-160, 120]]} width={1.5} />

        {/* Far-out curvy roads (sparse, get lost in fog) */}
        <BgCurvedRoad points={[[-250, -50], [-300, -40], [-360, -55], [-420, -45]]} width={2} />
        <BgCurvedRoad points={[[250, 50], [310, 60], [370, 45], [440, 55]]} width={2} />
        <BgCurvedRoad points={[[50, -250], [60, -310], [45, -370], [55, -440]]} width={2} />
        <BgCurvedRoad points={[[-50, 250], [-40, 300], [-55, 360], [-45, 420]]} width={2} />
        <BgCurvedRoad points={[[200, -200], [250, -250], [310, -300]]} width={1.5} />
        <BgCurvedRoad points={[[-200, 200], [-260, 260], [-320, 310]]} width={1.5} />
        <BgCurvedRoad points={[[-200, -200], [-260, -250], [-310, -310]]} width={1.5} />
        <BgCurvedRoad points={[[200, 200], [250, 260], [300, 320]]} width={1.5} />
