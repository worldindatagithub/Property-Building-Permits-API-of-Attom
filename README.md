# Property Building Permits API of Attom #
The Attom property building permits API allows developers to retrieve information about properties and their associated building permits. This API can be used to obtain basic property details such as address and ownership information, as well as more detailed information about building permits, including the date of issuance and the type of work covered by the permit. By using this API, developers can easily access comprehensive data about properties and building permits, making it a useful tool for a variety of applications.


[Property Building Permits API](https://www.worldindata.com/api/Attom-property-building-permits-api)

The Worldindata API marketplace is a platform that showcases third party APIs and aims to make it easier for users to understand and utilize these APIs. The marketplace features a wide range of APIs from different categories, and provides detailed documentation and resources to help users get started with each API. Whether you are a developer looking to build a new application or a business looking for data to support your operations, the Worldindata API marketplace can help you find the API solutions you need.


## Industry, Sectors, and Customers for the API ##

**Industry and Sectors**
- Real estate
- Hospitality
- Accommodation
- Property listing
- and more

**Client Types**
- Property listing platforms and websites
- Real estate analysts
- Accommodation services
- and more



## API JSON output, Objects and Parameters ##
The GET /property/buildingpermits endpoint allows users to retrieve detailed information about building permits for a specific property, including the date of issuance, the type of work covered by the permit, and more.



**Filter Parameters**
- Accept
- Address1
- Address2

```
{
  "status": {
    "version": "1.0.0",
    "code": 0,
    "msg": "SuccessWithResult",
    "total": 1,
    "page": 1,
    "pagesize": 10,
    "transactionID": "74d5e6c62c35e54d8467ff3d4fefb4df"
  },
  "property": [
    {
      "identifier": {
        "Id": 184713191,
        "fips": "08031",
        "apn": "02192-04-018-000",
        "attomId": 184713191
      },
      "lot": {
        "lotSize1": 0.1076676
      },
      "address": {
        "country": "US",
        "countrySubd": "CO",
        "line1": "4529 WINONA CT",
        "line2": "DENVER, CO 80212",
        "locality": "DENVER",
        "matchCode": "ExaStr",
        "oneLine": "4529 WINONA CT, DENVER, CO 80212",
        "postal1": "80212",
        "postal2": "2512",
        "postal3": "C037"
      },
      "location": {
        "accuracy": "Rooftop",
        "latitude": "39.778926",
        "longitude": "-105.047775",
        "distance": 0,
        "geoId": "CO08031, CS0891007, DB0803360, ND0000119198, ND0004861239, PL0820000, SB0000076114, SB0000076155, SB0000076161, SB0000135819, SB0000143772, ZI80212",
        "geoIdV4": {
          "PL": "7de845f7ba9b234a2c5adfca1db76c64",
          "ZI": "0149d0a55ef2d6b71071a39f4e13d6eb",
          "CS": "4c0507d0d7894d2d48e4e03e1c0240fc",
          "N1": "b26d02d9330761156fc0cfd4ed8bf9a1",
          "N2": "27e220314436f6edd5e606ddcd28156d"
        }
      },
      "summary": {
        "propClass": "Single Family Residence / Townhouse",
        "propSubType": "Residential",
        "propType": "SFR",
        "yearBuilt": 1900,
        "propLandUse": "SFR",
        "propIndicator": 10
      },
      "building": {
        "size": {
          "universalSize": 934
        },
        "rooms": {
          "bathsTotal": 1,
          "beds": 2
        }
      },
      "buildingPermits": [
        {
          "effectiveDate": "2013-04-04",
          "permitNumber": "00347672",
          "jobValue": 2000,
          "fees": 35,
          "businessName": "Doctor Fix-it Plumbing, Heating & Electr",
          "homeOwnerName": "Stcherbak,lidia"
        },
        {
          "effectiveDate": "2017-05-17",
          "permitNumber": "2016-ELEC-0004720",
          "status": "withdrawn",
          "description": "R/r air conditioning",
          "type": "Electrical permit",
          "projectName": "Electrical Permit",
          "fees": 20,
          "businessName": "Positively Electric INC",
          "homeOwnerName": "Mattice,michael Scott"
        },
        {
          "effectiveDate": "2016-05-27",
          "permitNumber": "2016-MECH-0003896",
          "status": "final",
          "description": "R/r air conditioning",
          "type": "Mechanical permit",
          "projectName": "Mechanical Permit",
          "fees": 59,
          "businessName": "Seasonal Comfort Systems LLC",
          "homeOwnerName": "Mattice,michael Scott"
        },
        {
          "effectiveDate": "2016-06-17",
          "permitNumber": "2015-ROOFSIDE-0014621",
          "status": "final",
          "description": "Re/re: 4529 winona ct",
          "type": "Roofing and siding permit",
          "projectName": "Roofing Permit",
          "fees": 91,
          "businessName": "Reitz Roofing INC",
          "homeOwnerName": "Mattice,michael Scott"
        },
        {
          "effectiveDate": "2017-09-22",
          "permitNumber": "2017-ROOFSIDE-0013232",
          "status": "final",
          "description": "Tear off existing material house and garage redeck garage only and reroof house and garage. Pitch 7 & 3/12 (ice and water all)",
          "type": "Roofing and siding permit",
          "projectName": "Aca Roofing Permit",
          "jobValue": 9447,
          "fees": 99,
          "businessName": "J&K Roofing INC",
          "homeOwnerName": "Mattice,michael Scott"
        },
        {
          "effectiveDate": "2015-06-04",
          "permitNumber": "2013-MECH-0000347672",
          "status": "issued",
          "type": "Mechanical permit",
          "projectName": "Permit # 00347672",
          "fees": 35,
          "businessName": "Doctor FIX IT Plumbing Heating &E",
          "homeOwnerName": "Stcherbak, Lidia"
        },
        {
          "effectiveDate": "2018-11-30",
          "permitNumber": "2018-ELEC-0014039",
          "status": "final",
          "description": "200 amp service change and 50 amp sub-panel to garage",
          "type": "Electrical permit",
          "projectName": "Aca Electrical Permit",
          "jobValue": 4000,
          "fees": 51,
          "businessName": "Positively Electric INC",
          "homeOwnerName": "Mattice,michael Scott"
        }
      ],
      "vintage": {
        "lastModified": "2022-01-24",
        "pubDate": "2022-04-14"
      }
    }
  ]
}

```

**Objects**
- Property
- Identifier
- ObPropId
- Fips
- Apn
- AttomId
- Lot
- Lotsize1
- BuildingPermits
- EffectiveDate
- PermitNumber
- Status
- Description
- Type
- ProjectName
- Fees
- BusinessName
- HomeOwnerName
- LastModified
- PubDate

## Software Development Kits ##
The Attom real estate building permits data is available through Software Development Kits (SDKs) in a variety of programming languages, including JAVA, Python, PHP, Ruby, and JavaScript. These SDKs make it easy for developers to integrate the building permits data into their applications, regardless of the programming language they prefer to use.


### Disclaimer of infringement ###
Worldindata is a platform that connects developers with data providers and aims to make the data in the world more user friendly. While we are big fans of the property building permits API and Attom, we do not own the data and are not responsible for its accuracy or availability. The data is provided by third parties, and Worldindata simply acts as a conduit to make it easier for developers to access and use this data. We recommend that users carefully review the terms of use and any applicable licenses before accessing or using the data.


[Worldindata](https://www.worldindata.com)
