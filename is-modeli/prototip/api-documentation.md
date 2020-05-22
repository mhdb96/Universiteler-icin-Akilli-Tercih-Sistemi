# API Documentation

{% api-method method="get" host="uatsapi.xdebuggers.com" path="/api/department" %}
{% api-method-summary %}
Retrieve all departments 
{% endapi-method-summary %}

{% api-method-description %}
Returns an array of all the departments
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All the departments received successfully.
{% endapi-method-response-example-description %}

```javascript
[
    {
        "name": "Bilişim Sistemleri Mühendisliği",
        "description": "Bu bölüm Teknoloji fakültesinde yer almaktadır.",
        "satisfaction": "75%",
        "courses": [
            {
                "_id": "5ec65c13d179a91abcf4996b",
                "name": "Veritabanı Yönetim Sistemleri"
            },
            {
                "_id": "5ec65c13d179a91abcf4996c",
                "name": "Makine Öğrenmesi"
            },
            {
                "_id": "5ec65c13d179a91abcf4996d",
                "name": "Veri Yapıları ve Algoritmaları"
            }
        ],
        "jobs": [
            {
                "_id": "5ec65c13d179a91abcf4996e",
                "name": "Yazılım Mühendisliği"
            },
            {
                "_id": "5ec65c13d179a91abcf4996f",
                "name": "Web Developer"
            },
            {
                "_id": "5ec65c13d179a91abcf49970",
                "name": "Veri Bilim Uzmanı"
            }
        ],
        "skills": [
            {
                "_id": "5ec65c13d179a91abcf49971",
                "name": "Analitik düşünme kabiliyetine sahip olmak"
            },
            {
                "_id": "5ec65c13d179a91abcf49972",
                "name": "Yaratıcılık ve eleştirel düşünce yapısına sahip olmak"
            },
            {
                "_id": "5ec65c13d179a91abcf49973",
                "name": "Detay odaklı çalışmak ve uzun süre konsantrasyon sağlayabilmek"
            }
        ],
        "universities": [
            {
                "_id": "5ec65c13d179a91abcf49974",
                "name": "Kocaeli Üniversitesi"
            },
            {
                "_id": "5ec65c13d179a91abcf49975",
                "name": "Sakarya Üniversitesi"
            },
            {
                "_id": "5ec65c13d179a91abcf49976",
                "name": "İstanbul Teknik Üniversitesi"
            }
        ],
        "__v": 0,
        "id": "5ec65c13d179a91abcf4996a"
    },
    {
        "name": "Psikoloji",
        "description": "Psikoloji bölümü, akademik ve klinik standartlar çizgisinde işlenen konulara çok yönlü yaklaşmayı ve bu konuları eleştirel bir bakış açısı ile değerlendirme becerisi kazandırmayı amaçlamaktadır. Psikoloji bölümünde akademik eğitimi takip eden klinik deneyimler, edinilen bu bilgilerin dinamik olarak uygulanabilme becerisini güçlendirmeyi hedeflemektedir.",
        "satisfaction": "80%",
        "courses": [
            {
                "_id": "5ec794010e13ff1344e389eb",
                "name": "Psikolojiye Giriş-I"
            }
        ],
        "skills": [
            {
                "_id": "5ec794010e13ff1344e389ec",
                "name": "Görevlendirildiği alanda psikolojik destek vermek"
            }
        ],
        "jobs": [
            {
                "_id": "5ec794010e13ff1344e389ed",
                "name": "Psikolog"
            }
        ],
        "universities": [
            {
                "_id": "5ec794010e13ff1344e389ee",
                "name": "Kocaeli Üniversitesi"
            },
            {
                "_id": "5ec794010e13ff1344e389ef",
                "name": "İstanbul Teknik Üniversitesi"
            },
            {
                "_id": "5ec794010e13ff1344e389f0",
                "name": "Sakarya Üniversitesi"
            },
            {
                "_id": "5ec794010e13ff1344e389f1",
                "name": "Boğaziçi Üniversitesi"
            }
        ],
        "__v": 0,
        "id": "5ec794010e13ff1344e389ea"
    },
    {
        "name": "Endüstri Mühendisliği",
        "description": "Endüstri Mühendisliği; insan, makine, bilişim, donanım ve enerjiden oluşan bütünleşik sistemlerin tasarımı, iyileştirilmesi ve kurulması ile ilgilenir. Bu sistemlerden elde edilen sonuçların belirlenmesi, öngürülmesi ve değerlendirilmesi için mühendislik analiz ve tasarım ilke ve yöntemlerinin yanısıra matematiksel, fiziksel ve sosyal bilimlerdeki uzmanlaşmış bilgi ve yetenekten yararlanan mühendislik bilim dalıdır",
        "satisfaction": "75%",
        "courses": [
            {
                "_id": "5ec7945b0e13ff1344e389f3",
                "name": "Veri Yapıları ve Algoritmalar"
            }
        ],
        "skills": [
            {
                "_id": "5ec7945b0e13ff1344e389f4",
                "name": "Yeni gelişen teknolojiyi takip etmek"
            }
        ],
        "jobs": [
            {
                "_id": "5ec7945b0e13ff1344e389f5",
                "name": "Endüstri Mühendisliği"
            }
        ],
        "universities": [
            {
                "_id": "5ec7945b0e13ff1344e389f6",
                "name": "Kocaeli Üniversitesi"
            },
            {
                "_id": "5ec7945b0e13ff1344e389f7",
                "name": "İstanbul Teknik Üniversitesi"
            },
            {
                "_id": "5ec7945b0e13ff1344e389f8",
                "name": "Sakarya Üniversitesi"
            },
            {
                "_id": "5ec7945b0e13ff1344e389f9",
                "name": "Boğaziçi Üniversitesi"
            }
        ],
        "__v": 0,
        "id": "5ec7945b0e13ff1344e389f2"
    },
    {
        "name": "Bilişim Sistemleri Mühendisliği",
        "description": "Bu bölüm Teknoloji fakültesinde yer almaktadır.",
        "satisfaction": "75%",
        "courses": [
            {
                "_id": "5ec79a479b65d954888249f4",
                "name": "Veritabanı Yönetim Sistemleri"
            },
            {
                "_id": "5ec79a479b65d954888249f5",
                "name": "Makine Öğrenmesi"
            },
            {
                "_id": "5ec79a479b65d954888249f6",
                "name": "Veri Yapıları ve Algoritmaları"
            }
        ],
        "jobs": [
            {
                "_id": "5ec79a479b65d954888249f7",
                "name": "Yazılım Mühendisliği"
            },
            {
                "_id": "5ec79a479b65d954888249f8",
                "name": "Web Developer"
            },
            {
                "_id": "5ec79a479b65d954888249f9",
                "name": "Veri Bilim Uzmanı"
            }
        ],
        "skills": [
            {
                "_id": "5ec79a479b65d954888249fa",
                "name": "Analitik düşünme kabiliyetine sahip olmak"
            },
            {
                "_id": "5ec79a479b65d954888249fb",
                "name": "Yaratıcılık ve eleştirel düşünce yapısına sahip olmak"
            },
            {
                "_id": "5ec79a479b65d954888249fc",
                "name": "Detay odaklı çalışmak ve uzun süre konsantrasyon sağlayabilmek"
            }
        ],
        "universities": [
            {
                "_id": "5ec79a479b65d954888249fd",
                "name": "Kocaeli Üniversitesi"
            },
            {
                "_id": "5ec79a479b65d954888249fe",
                "name": "Sakarya Üniversitesi"
            },
            {
                "_id": "5ec79a479b65d954888249ff",
                "name": "İstanbul Teknik Üniversitesi"
            }
        ],
        "__v": 0,
        "id": "5ec79a479b65d954888249f3"
    }
]
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="uatsapi.xdebuggers.com" path="/api/department/:id" %}
{% api-method-summary %}
Get one
{% endapi-method-summary %}

{% api-method-description %}
return a specific department.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="id" type="string" required=true %}
Department's id
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```javascript
{
    "name": "Bilişim Sistemleri Mühendisliği",
    "description": "Bu bölüm Teknoloji fakültesinde yer almaktadır.",
    "satisfaction": "75%",
    "courses": [
        {
            "_id": "5ec65c13d179a91abcf4996b",
            "name": "Veritabanı Yönetim Sistemleri"
        },
        {
            "_id": "5ec65c13d179a91abcf4996c",
            "name": "Makine Öğrenmesi"
        },
        {
            "_id": "5ec65c13d179a91abcf4996d",
            "name": "Veri Yapıları ve Algoritmaları"
        }
    ],
    "jobs": [
        {
            "_id": "5ec65c13d179a91abcf4996e",
            "name": "Yazılım Mühendisliği"
        },
        {
            "_id": "5ec65c13d179a91abcf4996f",
            "name": "Web Developer"
        },
        {
            "_id": "5ec65c13d179a91abcf49970",
            "name": "Veri Bilim Uzmanı"
        }
    ],
    "skills": [
        {
            "_id": "5ec65c13d179a91abcf49971",
            "name": "Analitik düşünme kabiliyetine sahip olmak"
        },
        {
            "_id": "5ec65c13d179a91abcf49972",
            "name": "Yaratıcılık ve eleştirel düşünce yapısına sahip olmak"
        },
        {
            "_id": "5ec65c13d179a91abcf49973",
            "name": "Detay odaklı çalışmak ve uzun süre konsantrasyon sağlayabilmek"
        }
    ],
    "universities": [
        {
            "_id": "5ec65c13d179a91abcf49974",
            "name": "Kocaeli Üniversitesi"
        },
        {
            "_id": "5ec65c13d179a91abcf49975",
            "name": "Sakarya Üniversitesi"
        },
        {
            "_id": "5ec65c13d179a91abcf49976",
            "name": "İstanbul Teknik Üniversitesi"
        }
    ],
    "__v": 0,
    "id": "5ec65c13d179a91abcf4996a"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="uatsapi.xdebuggers.com" path="/api/department" %}
{% api-method-summary %}
Create Department
{% endapi-method-summary %}

{% api-method-description %}
Create new department.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-body-parameters %}
{% api-method-parameter name="skills" type="array" required=true %}
Department's skills array
{% endapi-method-parameter %}

{% api-method-parameter name="universities" type="array" required=true %}
Department's universities array.
{% endapi-method-parameter %}

{% api-method-parameter name="name" type="string" required=true %}
Department's name.
{% endapi-method-parameter %}

{% api-method-parameter name="description" type="string" required=true %}
Department's description.
{% endapi-method-parameter %}

{% api-method-parameter name="satisfaction" type="string" required=true %}
Department's satisfaction percentage.
{% endapi-method-parameter %}

{% api-method-parameter name="courses" type="array" required=true %}
Department's courses array.
{% endapi-method-parameter %}

{% api-method-parameter name="jobs" type="array" required=true %}
Department's jobs array 
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Department created successfully.
{% endapi-method-response-example-description %}

```javascript
{
    "_id": "5ec79a479b65d954888249f3",
    "name": "Bilişim Sistemleri Mühendisliği",
    "description": "Bu bölüm Teknoloji fakültesinde yer almaktadır.",
    "satisfaction": "75%",
    "courses": [
        {
            "_id": "5ec79a479b65d954888249f4",
            "name": "Veritabanı Yönetim Sistemleri"
        },
        {
            "_id": "5ec79a479b65d954888249f5",
            "name": "Makine Öğrenmesi"
        },
        {
            "_id": "5ec79a479b65d954888249f6",
            "name": "Veri Yapıları ve Algoritmaları"
        }
    ],
    "jobs": [
        {
            "_id": "5ec79a479b65d954888249f7",
            "name": "Yazılım Mühendisliği"
        },
        {
            "_id": "5ec79a479b65d954888249f8",
            "name": "Web Developer"
        },
        {
            "_id": "5ec79a479b65d954888249f9",
            "name": "Veri Bilim Uzmanı"
        }
    ],
    "skills": [
        {
            "_id": "5ec79a479b65d954888249fa",
            "name": "Analitik düşünme kabiliyetine sahip olmak"
        },
        {
            "_id": "5ec79a479b65d954888249fb",
            "name": "Yaratıcılık ve eleştirel düşünce yapısına sahip olmak"
        },
        {
            "_id": "5ec79a479b65d954888249fc",
            "name": "Detay odaklı çalışmak ve uzun süre konsantrasyon sağlayabilmek"
        }
    ],
    "universities": [
        {
            "_id": "5ec79a479b65d954888249fd",
            "name": "Kocaeli Üniversitesi"
        },
        {
            "_id": "5ec79a479b65d954888249fe",
            "name": "Sakarya Üniversitesi"
        },
        {
            "_id": "5ec79a479b65d954888249ff",
            "name": "İstanbul Teknik Üniversitesi"
        }
    ],
    "__v": 0
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



