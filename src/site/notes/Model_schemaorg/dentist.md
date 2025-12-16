---
{"@context":"https://schema.org","@type":"[[schema.Dentist]]","name":"City Smiles","description":"Dental care service that you and your family can trust","slogan":"Let your teeth shine","telephone":"+12015869799","email":"city.smilel.dental@example.com","address":"[[dentist_PostalAddress]]","paymentAccepted":"Cash, Credit Card","openingHours":"Mo-Sa 9:00-12:00","priceRange":"$$","aggregateRating":"[[dentist_AggregateRating]]","image":"https://homepages.cae.wisc.edu/~ece533/images/lena.png","hasReview":["[[review1]]","[[review2]]"],"dg-publish":true,"created_at":"2025-12-16T16:44:00","updated_at":"2025-12-16T16:45:08+02:00","permalink":"/model-schemaorg/dentist/","dgPassFrontmatter":true,"created":"2025-12-16T16:44:00","updated":"2025-12-16T16:45:08+02:00"}
---

## JSON-LD example with schema.org vocabulary


### Classes Metadata
![[classes.base]]

### Properties Metadata
![[properties.base]]

### Instances
![[instances.base]]

### JSON-LD Code
```jsonld
 {
        "@context": "https://schema.org",
        "@type": "Dentist",
        "name": "City Smiles",
        "description": "Dental care service",
        "slogan": "Let your teeth shine",
        "openingHours": "Mo-Sa 9:00-12:00",
        "telephone": "+12025550198",
        "email": "city.smiles.dental@example.com",
        "address": {
            "@type": "PostalAddress",
            "addressLocality": "Detroit",
            "addressRegion": "MI",
            "postalCode": "48226",
            "streetAddress": "1001  Eagle Drive"
        },
        "paymentAccepted": "Cash, Credit Card",
        "priceRange": "$",
        "aggregateRating": {
            "@type": "AggregateRating",
            "ratingValue": 4.5,
            "reviewCount": 22
        },
        "image": "https://homepages.cae.wisc.edu/~ece533/images/lena.png",
        "review": [
            {
                "@type": "Review",
                "author": "Liam",
                "datePublished": "2020-06-26",
                "description": "Great prices, excellent service",
                "name": "Great dental clinic",
                "reviewRating": {
                    "@type": "Rating",
                    "ratingValue": 5
                }
            },
            {
                "@type": "Review",
                "author": "David",
                "datePublished": "2020-05-16",
                "description": "I am totally satisfied with the quality of service, but the waiting time should be reduced",
                "name": "Waiting time",
                "reviewRating": {
                    "@type": "Rating",
                    "ratingValue": 4
                }
            }
        ]
    }
```