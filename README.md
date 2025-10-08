# Ex04 Places Around Me
# Date:03.10.2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html
<html>
<head>
    <title>Map</title>
</head>
<body>
    <h1></h1>
    <img src="Screenshot 2025-10-01 195037.png" usemap="#image-map">
    <map name="image-map">
    <area target="" alt="Perambalur New Bustand" title="Perambalur New Bustand" href="bus stand.html" coords="519,126,248,25" shape="rect">
    <area target="" alt="Dhanalakshmi Srinivasan Hotels" title="Dhanalakshmi Srinivasan Hotels" href="hotel.html" coords="214,532,96" shape="circle">
    <area target="" alt="library,perambalur" title="library,perambalur" href="library.html" coords="1142,290,931,247" shape="rect">
    <area target="" alt="employment office" title="employment office" href="employment.html" coords="1233,409,1048,347" shape="rect">
    <area target="" alt="naturals salon" title="naturals salon" href="naturals.html" coords="519,603,362,561" shape="rect">
</map>
</body>
</html>

bus stand.html
<html>
<head>

    <title>perambalur bus stand</title>
</head>
<body bgcolor="violet" align="center">
    <h1>Perambalur City</h1>
    <h2>bus stand</h2>
    <hr>
    <h3 style="line-height:3">
        the main bus terminal serving the town of Perambalur is the New Bus Stand,
        which is centrally located on New Bus Stand Road in the Sungu Pettai area. 
        As a crucial transportation hub for the district, the bus stand connects Perambalur
        to various parts of Tamil Nadu and neighboring states. It serves as a transit
        point for numerous routes operated by both the government-run Tamil Nadu State
        Transport Corporation (TNSTC) and several private bus operators. The terminal is
        a significant transit point for those traveling to major cities like Chennai,
        Trichy, Salem, and Bangalore. Local town buses also operate from the bus stand,
        linking Perambalur to its surrounding villages and towns. The bus stand,
        which is open 24 hours a day, handles a high volume of passenger traffic,
        especially during peak hours in the morning and evening. The New Bus Stand 
        features multiple bus bays to accommodate a large number of buses 
        simultaneously. While the terminal is spacious and provides access from 
        nearby highways, some reviewers have noted concerns about cleanliness and 
        congestion, particularly during rush hours.</h3>

</body>
</html>

employment.html
<html>
<head>

    <title>office</title>
</head>
<body bgcolor="brown" align="center">
    <h1>Perambalur City</h1>
    <h2>employment office</h2>
    <hr>
    <h3 style="line-height:2.3">
        The District Employment and Career Guidance Centre in Perambalur, 
        located at Perambalur South, opposite the District Central Library,
        serves as a crucial hub for job seekers and employers. As part of the
        Tamil Nadu government's initiative, the former District Employment 
        Offices were re-branded in 2019 to reflect a broader scope of activities 
        beyond simple registration. The main objective of the centre is to enhance 
        the employability of local youth through comprehensive career guidance and 
        counselling services. To achieve this, the office provides free coaching classes,
        study materials, and library facilities for individuals preparing for competitive
        examinations such as TNPSC, UPSC, and others. The centre's services have been 
        largely digitized, allowing candidates to register their educational 
        qualifications, renew their registrations, and update their profiles online
        via the official web portal, www.tnvelaivaaippu.gov.in. For those who prefer
        in-person service, e-service centres are available across the district</h3>

</body>
</html>

hotel.html
<html>
<head>

    <title>Hotel</title>
</head>
<body bgcolor="hotpink" align="center">
    <h1>Perambalur City</h1>
    <h2>Dhanalakshmi Srinivasan Hotels</h2>
    <hr>
    <h3 style="line-height: 2.5;">
    The Dhanalakshmi Srinivasan Hotel in Perambalur district is a well-regarded 
    three-star establishment, offering a comfortable and comprehensive experience 
    for both business and leisure travelers. Positioned conveniently on Collector's
    Office Road and near the New Bus Stand Road, it boasts a central location that 
    makes it easily accessible and a popular choice for those visiting the area.
    The hotel is particularly valued for its strong infrastructure and excellent 
    amenities, providing great value for money, especially when compared to hotels in
    nearby cities like Trichy. Upon entering, guests are greeted with a warm and 
    inviting atmosphere, characterized by attractive interiors and furnishings that 
    create a cozy yet upscale ambiance. The accommodation options include simply 
    furnished rooms and spacious suites that are consistently praised for their 
    cleanliness, modern amenities, and comfortable beds, ensuring a restful stay.
    Many rooms are equipped with facilities such as reliable air conditioning and 
    round-the-clock hot water, with some guests highlighting the ample space available.
    Beyond the guest rooms, the hotel features a highly-rated on-site restaurant, 
    which is a major draw for visitors. It serves a wide variety of food options,
    including good quality breakfast, lunch, and dinner buffets that cater to both
    vegetarian and non-vegetarian palates. For those looking to unwind, the hotel 
    also provides an excellent bar with good service and a relaxing lounge area. 
    The property is well-equipped to host events of all sizes, featuring well-designed
    and decorated banquet halls for weddings and other celebrations, as well as 
    spacious and clean conference centers for corporate functions. Families traveling
    with children will appreciate the inclusion of a small play area on the premises. 
    Adding to the convenience, the hotel offers a range of services such as room service,
    laundry service, and an airport shuttle. The hospitality is consistently noted as
    exceptional, with humble and respectful staff members who are always eager to assist
    guests.
</h3>

    
</hr>
    </body>
</body>
</body>
</html>

library.html
<html>
<head>

    <title>library</title>
</head>
<body bgcolor="yellow" align="center">
    <h1>Perambalur City</h1>
    <h2>library</h2>
    <hr>
    <h3  style="line-height:3" >
        The District Central Library is the primary hub of knowledge
        and reading for the residents of Perambalur and its surrounding areas,
        functioning as part of the broader Tamil Nadu Public Library system. 
        This central library and its branches cater to a wide audience, including
        students, researchers, competitive exam aspirants, and general readers. 
        Located conveniently within the district, the library system aims to provide 
        accessible and free literary resources to everyone. The collections typically
        include a vast array of books covering various subjects such as literature,
        science, history, and fiction, catering to different age groups and interests. 
        In addition to books, the libraries often provide access to newspapers, 
        magazines, and other periodicals to keep readers informed about current events. 
        The libraries also serve as important resources for students preparing for
        competitive examinations, offering a quiet and conducive environment for study. 
        Many libraries are equipped with dedicated reading sections and provide access to
        materials specifically tailored for exams like TNPSC, UPSC, and others.
    </h3>

</body>
</html>

naturals.html
<html>
<head>

    <title>saloon</title>
</head>
<body bgcolor="green" align="center">
    <h1>Perambalur City</h1>
    <h2>naturals saloon</h2>
    <hr>
    <h3 style="line-height:3" >
    Naturals is a well-known and reputable chain of salons and 
    spas with a branch conveniently located in Perambalur. The 
    salon is situated on the first floor of the Amma Complex on 
    Thuraimangalam Road, positioned opposite Sivagam Hero Motors. 
    It is part of a larger network of over 800 salons across India,
    known for providing premium, hygienic, and affordable beauty and 
    grooming services. The Perambalur outlet offers a comprehensive range
    of services for both men and women, aiming to be a one-stop destination
    for all beauty and wellness needs. 
    For hair care, the salon offers expert cuts, styling, hair coloring, and 
    specialized treatments like Hair Spas, Keratin, and Smoothening. Skincare options
    include luxurious facials, deep cleansing, hydration treatments, and exfoliation
    services. The body care menu features relaxing massages, manicures, pedicures,
    and waxing services. The Perambalur branch is also noted for its bridal and groom
    grooming services
    </h3>

</body>
</html>
```

# OUTPUT!












![alt text](<Screenshot 2025-10-01 195037-1.png>)

![alt text](<Screenshot 2025-10-08 002907.png>)

![alt text](<Screenshot 2025-10-08 003114.png>)
![alt text](<Screenshot 2025-10-08 212241.png>)


![alt text](<Screenshot 2025-10-08 212306.png>)

![alt text](<Screenshot 2025-10-08 212659.png>)








# RESULT
The program for implementing image maps using HTML is executed successfully.
