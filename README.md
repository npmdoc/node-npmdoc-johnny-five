# api documentation for  [johnny-five (v0.10.7)](https://johnny-five.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-johnny-five.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-johnny-five) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-johnny-five.svg)](https://travis-ci.org/npmdoc/node-npmdoc-johnny-five)
#### The JavaScript Robotics and Hardware Programming Framework. Use with: Arduino (all models), Electric Imp, Beagle Bone, Intel Galileo & Edison, Linino One, Pinoccio, pcDuino3, Raspberry Pi, Particle/Spark Core & Photon, Tessel 2, TI Launchpad and more!

[![NPM](https://nodei.co/npm/johnny-five.png?downloads=true)](https://www.npmjs.com/package/johnny-five)

[![apidoc](https://npmdoc.github.io/node-npmdoc-johnny-five/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-johnny-five%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-johnny-five/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-johnny-five/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-johnny-five/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rick Waldron",
        "email": "waldron.rick@gmail.com"
    },
    "browser": {
        "galileo-io": false
    },
    "bugs": {
        "url": "https://github.com/rwaldron/johnny-five/issues"
    },
    "contributors": [
        {
            "name": "Adam Hyland",
            "email": "protonk@gmail.com"
        },
        {
            "name": "Andreas Haugstrup Pedersen",
            "email": "haugstrup@podio.com"
        },
        {
            "name": "Andrew Homeyer",
            "email": "homeyer@gmail.com"
        },
        {
            "name": "Ben Gillies",
            "email": "bengillies@gmail.com"
        },
        {
            "name": "Carl Danley",
            "email": "carldanley@gmail.com"
        },
        {
            "name": "Chris Williams",
            "email": "chris@saferaging.com"
        },
        {
            "name": "Colin Vernon",
            "email": "colin@littlebits.cc"
        },
        {
            "name": "Corey Daniels",
            "email": "corey@skookum.com"
        },
        {
            "name": "FotoVerite",
            "email": "mzbphoto@gmail.com"
        },
        {
            "name": "Francis Gulotta",
            "email": "wizard@roborooter.com"
        },
        {
            "name": "Irene Ros",
            "email": "irene@bocoup.com"
        },
        {
            "name": "Jonathan Beri",
            "email": "jmberi@gmail.com"
        },
        {
            "name": "Julian Gautier",
            "email": "julian.gautier@alumni.neumont.edu"
        },
        {
            "name": "Linus Larsson",
            "email": "linus@devshm.net"
        },
        {
            "name": "Mike Breen",
            "email": "hardbap@gmail.com"
        },
        {
            "name": "Mike Harsch",
            "email": "mike@harschsystems.com"
        },
        {
            "name": "Mike Sherov",
            "email": "mike.sherov@gmail.com"
        },
        {
            "name": "Paul Tagliamonte",
            "email": "paultag@sunlightfoundation.com"
        },
        {
            "name": "Rahul Ravikumar",
            "email": "rahulrav@a2z.com"
        },
        {
            "name": "Randall A. Gordon",
            "email": "randall@randallagordon.com"
        },
        {
            "name": "Rebecca Murphey",
            "email": "rmurphey@gmail.com"
        },
        {
            "name": "Ryan Neufeld",
            "email": "ryan@neucode.org"
        },
        {
            "name": "Scott González",
            "email": "scott.gonzalez@gmail.com"
        },
        {
            "name": "Swift",
            "email": "theycallmeswift@gmail.com"
        },
        {
            "name": "Travis Thieman",
            "email": "travis.thieman@gmail.com"
        },
        {
            "name": "Vincent Agnano",
            "email": "vincent.agnano@scopyleft.fr"
        },
        {
            "name": "Cole",
            "email": "mcg42387@gmail.com"
        },
        {
            "name": "Divan Visagie",
            "email": "visagiedivan@gmail.com"
        },
        {
            "name": "Sara Gorecki",
            "email": "sgorecki@gmail.com"
        },
        {
            "name": "Raquel Velez",
            "email": "rockbot01@gmail.com"
        },
        {
            "name": "Tim Walker",
            "email": "tim.twalker@gmail.com"
        },
        {
            "name": "Toby Miller",
            "email": "tmiller@localhost.localhost"
        },
        {
            "name": "Richard Key",
            "email": "rich@busyrich.com"
        },
        {
            "name": "Patrick Clark",
            "email": "pat@hellop.at"
        },
        {
            "name": "Boros Márton",
            "email": "martonboros@gmail.com"
        },
        {
            "name": "Jeremy Morrell",
            "email": "morrell.jeremy@gmail.com"
        },
        {
            "name": "Bob Holt",
            "email": "bobholt@gmail.com"
        },
        {
            "name": "Dwayn Matthies",
            "email": "dwayn.matthies@gmail.com"
        },
        {
            "name": "AJ Fisher",
            "email": "ajfisher.td@gmail.com"
        },
        {
            "name": "Julian Duque",
            "email": "julianduquej@gmail.com"
        },
        {
            "name": "Daan van Berkel",
            "email": "daan.v.berkel.1980@gmail.com"
        },
        {
            "name": "Oli Evans",
            "email": "oli@zilla.org.uk"
        },
        {
            "name": "Cory Gackenheimer",
            "email": "cory.gack@gmail.com"
        },
        {
            "name": "Ray Pierce",
            "email": "ray@digitalpierce.com"
        },
        {
            "name": "Jonathan Clem",
            "email": "jonathan@jclem.net"
        },
        {
            "name": "achingbrain",
            "email": "alex@achingbrain.net"
        },
        {
            "name": "Jeff Albrecht",
            "email": "jeffa@iea-software.com"
        },
        {
            "name": "Isaac Durazo",
            "email": "isaacdurazo@gmail.com"
        },
        {
            "name": "Pawel Szymczykowski",
            "email": "makenai@gmail.com"
        },
        {
            "name": "Alex Crooks",
            "email": "alexcrooks@gmail.com"
        },
        {
            "name": "Donovan Buck",
            "email": "donovan@donovan.bz"
        },
        {
            "name": "Taha Hesham",
            "email": "taha@wizylabs.com"
        },
        {
            "name": "Alfonso de la Osa",
            "email": "fonz@botverse.com"
        },
        {
            "name": "Donald Averill"
        },
        {
            "name": "Bryan Hughes",
            "email": "bryan@theoreticalideations.com"
        },
        {
            "name": "Robert Myers",
            "email": "rmyers@euro-pro.com"
        },
        {
            "name": "David Resseguie",
            "email": "david@resseguie.com"
        },
        {
            "name": "Lyza Danger Gardner",
            "email": "lyza@lyza.com"
        },
        {
            "name": "Adam Magaluk",
            "email": "AdamMagaluK@gmail.com"
        },
        {
            "name": "Udo Kramer",
            "email": "optikfluffel@gmail.com"
        },
        {
            "name": "Joseph Weakley",
            "email": "joew@samjoe.com"
        },
        {
            "name": "Dean McDonnell",
            "email": "mcdonnelldean@outlook.com"
        },
        {
            "name": "Jonathan Petitcolas",
            "email": "petitcolas.jonathan@gmail.com"
        },
        {
            "name": "Chinmay Pendharkar",
            "email": "notthetup@gmail.com"
        },
        {
            "name": "Brian Genisio",
            "email": "BrianGenisio@Gmail.com"
        },
        {
            "name": "Anna Gerber",
            "email": "anna.m.gerber@gmail.com"
        },
        {
            "name": "Derek Wheelden",
            "email": "derek.wheelden@gmail.com"
        },
        {
            "name": "Sean Hussey",
            "email": "sean@seanhussey.com"
        },
        {
            "name": "ralphtheninja",
            "email": "ralphtheninja@riseup.net"
        },
        {
            "name": "SotirisValogiannis",
            "email": "omiloparmenos@gmail.com"
        },
        {
            "name": "Sue Lockwood",
            "email": "deathbearbrown@gmail.com"
        },
        {
            "name": "Henri Cavalcante",
            "email": "contato@henrimichel.com.br"
        },
        {
            "name": "Dany Shaanan",
            "email": "danyshaanan@gmail.com"
        },
        {
            "name": "Rachel Hazes"
        },
        {
            "name": "DeShawn Williams",
            "email": "deshawn.b.williams@gmail.com"
        },
        {
            "name": "Michał",
            "email": "bartmichu@gmail.com"
        },
        {
            "name": "Steve Kinney",
            "email": "hello@stevekinney.net"
        },
        {
            "name": "H. Phil Duby",
            "email": "philduby@phriendly.net"
        },
        {
            "name": "Vincent Rubiolo",
            "email": "vincent.libre@cryostase.eu"
        },
        {
            "name": "Jory Burson",
            "email": "jory@bocoup.com"
        },
        {
            "name": "Corey Frang",
            "email": "gnarf@gnarf.net"
        },
        {
            "name": "TRAHOMOTO",
            "email": "trahomoto@i.ua"
        },
        {
            "name": "Don McCurdy",
            "email": "don.r.mccurdy@gmail.com"
        },
        {
            "name": "Marcus Wittig",
            "email": "WittigMarcus@gmail.com"
        },
        {
            "name": "KatieK",
            "email": "KatieK2@users.noreply.github.com"
        },
        {
            "name": "Iryna Shestak",
            "email": "shestak.irina@gmail.com"
        },
        {
            "name": "Nathan Loding",
            "email": "nathan@nloding.com"
        },
        {
            "name": "Eric Lewis",
            "email": "eric.andrew.lewis@gmail.com"
        },
        {
            "name": "Prayag Verma",
            "email": "prayag.verma@gmail.com"
        },
        {
            "name": "Stefan Hüsges",
            "email": "Tronsha@gmx.de"
        },
        {
            "name": "Jean-Philippe Côté",
            "email": "jp@cote.cc"
        },
        {
            "name": "byronhulcher",
            "email": "byronhulcher@gmail.com"
        },
        {
            "name": "John Lennard",
            "email": "john@yakmoo.se"
        },
        {
            "name": "Dario Diaz",
            "email": "darioo.diaz1@gmail.com"
        },
        {
            "name": "Kimio Kosaka",
            "email": "kim@dhcp209.kosmac.or.jp"
        },
        {
            "name": "Ashley Williams",
            "email": "ashley666ashley@gmail.com"
        },
        {
            "name": "kilida",
            "email": "kilidapatch@gmail.com"
        },
        {
            "name": "Rhys van der Waerden",
            "email": "rhys.vdw@gmail.com"
        },
        {
            "name": "eiji.ienaga",
            "email": "e-ienaga@esm.co.jp"
        },
        {
            "name": "Doug Cone",
            "email": "nullvariable@users.noreply.github.com"
        },
        {
            "name": "Andrew Nicolaou",
            "email": "me@andrewnicolaou.co.uk"
        },
        {
            "name": "shimnex",
            "email": "shimdal@yahoo.ca"
        }
    ],
    "dependencies": {
        "browser-serialport": "latest",
        "chalk": "latest",
        "color-convert": "~1.2.2",
        "ease-component": "latest",
        "es6-shim": "latest",
        "firmata": "latest",
        "lodash.clonedeep": "^4.3.0",
        "lodash.debounce": "^4.0.3",
        "nanotimer": "0.3.10",
        "serialport": "^4.0.0",
        "temporal": "latest"
    },
    "description": "The JavaScript Robotics and Hardware Programming Framework. Use with: Arduino (all models), Electric Imp, Beagle Bone, Intel Galileo & Edison, Linino One, Pinoccio, pcDuino3, Raspberry Pi, Particle/Spark Core & Photon, Tessel 2, TI Launchpad and more!",
    "devDependencies": {
        "async": "~0.9.0",
        "copy-paste": "^1.3.0",
        "coveralls": "^2.11.9",
        "grunt": "~0.4.5",
        "grunt-cli": "~0.1.13",
        "grunt-contrib-jshint": "~1.0.0",
        "grunt-contrib-nodeunit": "~0.4.1",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-jsbeautifier": "~0.2.10",
        "grunt-jscs": "~2.3.0",
        "keypress": "latest",
        "mock-firmata": "latest",
        "nyc": "^10.2.0",
        "optimist": "~0.6.1",
        "shelljs": "^0.3.0",
        "sinon": "~1.10.2"
    },
    "directories": {},
    "dist": {
        "shasum": "7dfc02cbfbaa78c349e9fa4bf041f0ec90eb189d",
        "tarball": "https://registry.npmjs.org/johnny-five/-/johnny-five-0.10.7.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "562d37b659f5132c82d7e5e8dd670169b20143d9",
    "homepage": "https://johnny-five.io",
    "keywords": [
        "arduino",
        "raspberry pi",
        "raspberrypi",
        "usb",
        "serial",
        "serialport",
        "firmata",
        "robot",
        "spark",
        "spark core",
        "spark-io",
        "particle",
        "photon",
        "i2c",
        "raspberry pi",
        "rpi",
        "raspi-io",
        "intel galileo",
        "galileo",
        "galileo-io",
        "intel edison",
        "edison",
        "tessel 2",
        "pcduino",
        "MPU6050",
        "ADXL345",
        "ADXL335",
        "MMA8462Q",
        "MPL3115A2",
        "Weather Shield Arduino",
        "Weather Shield Photon",
        "BMP180",
        "Edison Arduino Block",
        "Edison GPIO Block",
        "Edison I2C Block",
        "Edison PWM Block",
        "RedBoard",
        "Ludus Protoshield",
        "Ludus Protoshield Wireless",
        "Ardumoto",
        "HMC5883L",
        "Speed controller",
        "PCF8575",
        "HTU21D",
        "Joystick",
        "Thumb Joystick",
        "Joystick",
        "16x2 LCD",
        "20x4 LCD",
        "LED",
        "Diffused LED",
        "RGB LED",
        "Infrared Sensor",
        "PIR Motion Sensor",
        "Hobby Motor",
        "Infrared Proximity Sensor",
        "LIDAR-Lite v2",
        "Ultrasonic Range Finder",
        "LV-MaxSonar-EZ0",
        "LV-MaxSonar-EZ3",
        "HRLV-MaxSonar-EZ0",
        "SparkFun Sensor Kit",
        "SparkFun Essential Sensor Kit",
        "Servo",
        "Continuous Rotation",
        "Metal Gear",
        "High Torque",
        "Hitec HS-805BB",
        "Hitec HS-425BB",
        "Hitec HS-422",
        "Hitec HS-646WP",
        "Hitec HS-85MG",
        "Hitec HS-625MG",
        "Hitec HS-35HD",
        "Hitec HS-755HB",
        "Temperature",
        "DS18B20",
        "TMP36",
        "ANALOG",
        "MMA7361",
        "MMA7660",
        "ESPLORA",
        "MPU-6050",
        "TINKERKIT",
        "MPL115A2",
        "DEFAULT",
        "EV3",
        "NXT",
        "ISL29125",
        "HMC6352",
        "GP2Y0A21YK",
        "GP2D120XJ00F",
        "GP2Y0A02YK0F",
        "GP2Y0A41SK0F",
        "2Y0A21",
        "2D120X",
        "2Y0A02",
        "OA41SK",
        "0A21",
        "0A02",
        "MCP23017",
        "MCP23008",
        "PCF8574",
        "PCA9685",
        "PCF8591",
        "MUXSHIELD2",
        "PCF8574A",
        "SI7020",
        "GY-521",
        "GY521",
        "MPR121QR2",
        "VKEY",
        "AT42QT1070",
        "MPR121",
        "QTOUCH",
        "JHD1313M1",
        "PARALLEL",
        "HD44780",
        "PCF8574T",
        "PCF8574AT",
        "LCD2004",
        "LCD1602",
        "LCM1602",
        "MJKDZ",
        "BLINKM",
        "HT16K33",
        "TSL2561",
        "ALS-PT19",
        "ALSPT19",
        "Shift Register",
        "74HC595",
        "Shift Register 8-Bit SN74HC595",
        "MCP9808"
    ],
    "license": "MIT",
    "main": "lib/johnny-five",
    "maintainers": [
        {
            "name": "rwaldron",
            "email": "waldron.rick@gmail.com"
        }
    ],
    "name": "johnny-five",
    "optionalDependencies": {
        "browser-serialport": "latest",
        "firmata": "latest",
        "serialport": "^4.0.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/rwaldron/johnny-five.git"
    },
    "scripts": {
        "coveralls": "nyc --reporter=lcov grunt nodeunit && cat ./coverage/lcov.info | coveralls",
        "test": "grunt",
        "test-cover": "nyc grunt nodeunit"
    },
    "version": "0.10.7"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module johnny-five](#apidoc.module.johnny-five)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Accelerometer (opts)](#apidoc.element.johnny-five.Accelerometer)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Altimeter (opts)](#apidoc.element.johnny-five.Altimeter)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Analog (opts)](#apidoc.element.johnny-five.Analog)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Animation (target)](#apidoc.element.johnny-five.Animation)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Animation.TemporalFallback (animation)](#apidoc.element.johnny-five.Animation.TemporalFallback)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Barometer (opts)](#apidoc.element.johnny-five.Barometer)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Board (opts)](#apidoc.element.johnny-five.Board)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Board.Component (opts, componentOpts)](#apidoc.element.johnny-five.Board.Component)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Board.Pins (board)](#apidoc.element.johnny-five.Board.Pins)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Board.range (lower, upper, tick)](#apidoc.element.johnny-five.Board.range)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Boards (opts)](#apidoc.element.johnny-five.Boards)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Button (opts)](#apidoc.element.johnny-five.Button)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Buttons (numsOrObjects)](#apidoc.element.johnny-five.Buttons)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Buttons.super_ (numsOrObjects)](#apidoc.element.johnny-five.Buttons.super_)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Color (opts)](#apidoc.element.johnny-five.Color)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Compass (opts)](#apidoc.element.johnny-five.Compass)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Digital (opts)](#apidoc.element.johnny-five.Digital)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>ESC (opts)](#apidoc.element.johnny-five.ESC)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>ESCs (numsOrObjects)](#apidoc.element.johnny-five.ESCs)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Expander (opts)](#apidoc.element.johnny-five.Expander)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Expander.super_ ()](#apidoc.element.johnny-five.Expander.super_)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>GPS (opts)](#apidoc.element.johnny-five.GPS)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Gripper (opts)](#apidoc.element.johnny-five.Gripper)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Gyro (opts)](#apidoc.element.johnny-five.Gyro)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Hygrometer (opts)](#apidoc.element.johnny-five.Hygrometer)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>IMU (opts)](#apidoc.element.johnny-five.IMU)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>IR ()](#apidoc.element.johnny-five.IR)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Joystick (opts)](#apidoc.element.johnny-five.Joystick)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Keypad (opts)](#apidoc.element.johnny-five.Keypad)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>LCD (opts)](#apidoc.element.johnny-five.LCD)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Led (opts)](#apidoc.element.johnny-five.Led)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Led.RGB (opts)](#apidoc.element.johnny-five.Led.RGB)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Led.RGBs (numsOrObjects)](#apidoc.element.johnny-five.Led.RGBs)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>LedControl (opts)](#apidoc.element.johnny-five.LedControl)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Leds (numsOrObjects)](#apidoc.element.johnny-five.Leds)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Light (opts)](#apidoc.element.johnny-five.Light)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Luxmeter (options)](#apidoc.element.johnny-five.Luxmeter)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Magnetometer (options)](#apidoc.element.johnny-five.Magnetometer)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Motion (opts)](#apidoc.element.johnny-five.Motion)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Motion.Collection (numsOrObjects)](#apidoc.element.johnny-five.Motion.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Motor (opts)](#apidoc.element.johnny-five.Motor)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Motors (numsOrObjects)](#apidoc.element.johnny-five.Motors)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Multi (opts)](#apidoc.element.johnny-five.Multi)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Nunchuk (opts)](#apidoc.element.johnny-five.Nunchuk)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Piezo (opts)](#apidoc.element.johnny-five.Piezo)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Pin (opts)](#apidoc.element.johnny-five.Pin)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Ping (opts)](#apidoc.element.johnny-five.Ping)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Pins (numsOrObjects)](#apidoc.element.johnny-five.Pins)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Proximity (opts)](#apidoc.element.johnny-five.Proximity)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Proximity.Collection (numsOrObjects)](#apidoc.element.johnny-five.Proximity.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Relay (opts)](#apidoc.element.johnny-five.Relay)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Relays (numsOrObjects)](#apidoc.element.johnny-five.Relays)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Repl (opts)](#apidoc.element.johnny-five.Repl)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Sensor (opts)](#apidoc.element.johnny-five.Sensor)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Sensors (numsOrObjects)](#apidoc.element.johnny-five.Sensors)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Servo (opts)](#apidoc.element.johnny-five.Servo)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Servos (numsOrObjects)](#apidoc.element.johnny-five.Servos)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>ShiftRegister (opts)](#apidoc.element.johnny-five.ShiftRegister)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>ShiftRegister.Collection (numsOrObjects)](#apidoc.element.johnny-five.ShiftRegister.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Sonar (opts)](#apidoc.element.johnny-five.Sonar)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Stepper (opts)](#apidoc.element.johnny-five.Stepper)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Switch (opts)](#apidoc.element.johnny-five.Switch)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Switches (numsOrObjects)](#apidoc.element.johnny-five.Switches)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Temperature (opts)](#apidoc.element.johnny-five.Temperature)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Thermometer (opts)](#apidoc.element.johnny-five.Thermometer)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Touchpad (opts)](#apidoc.element.johnny-five.Touchpad)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Wii (opts)](#apidoc.element.johnny-five.Wii)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>evshield (options)](#apidoc.element.johnny-five.evshield)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>orientation (opts)](#apidoc.element.johnny-five.orientation)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>reflectancearray (opts)](#apidoc.element.johnny-five.reflectancearray)
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Animation.TemporalFallback.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Animation.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Board.Pins.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Board.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Boards.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Buttons.super_.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Collection.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>ESC.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>ESCs.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Fn
1.  object <span class="apidocSignatureSpan">johnny-five.</span>GPS.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Gripper.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Gyro.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>IMU.Drivers
1.  object <span class="apidocSignatureSpan">johnny-five.</span>IR.Reflect
1.  object <span class="apidocSignatureSpan">johnny-five.</span>IR.Reflect.Array.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>LCD.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Led.RGB.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Led.RGBs.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Led.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>LedControl.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Leds.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Light.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Motor.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Motors.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Piezo.Parsers
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Piezo.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Pin.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Ping.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Pins.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Proximity.Collection.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Proximity.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Relay.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Relays.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Repl.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Sensor.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Sensors.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Servo.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Servos.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>ShiftRegister.Collection.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>ShiftRegister.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Sonar.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Stepper.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Thermometer.Drivers
1.  object <span class="apidocSignatureSpan">johnny-five.</span>Wii.Components
1.  object <span class="apidocSignatureSpan">johnny-five.</span>evshield.prototype
1.  object <span class="apidocSignatureSpan">johnny-five.</span>sleep

#### [module johnny-five.Accelerometer](#apidoc.module.johnny-five.Accelerometer)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Accelerometer (opts)](#apidoc.element.johnny-five.Accelerometer.Accelerometer)
1.  [function <span class="apidocSignatureSpan">johnny-five.Accelerometer.</span>super_ ()](#apidoc.element.johnny-five.Accelerometer.super_)

#### [module johnny-five.Altimeter](#apidoc.module.johnny-five.Altimeter)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Altimeter (opts)](#apidoc.element.johnny-five.Altimeter.Altimeter)
1.  [function <span class="apidocSignatureSpan">johnny-five.Altimeter.</span>super_ ()](#apidoc.element.johnny-five.Altimeter.super_)

#### [module johnny-five.Animation](#apidoc.module.johnny-five.Animation)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Animation (target)](#apidoc.element.johnny-five.Animation.Animation)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.</span>Segment (options)](#apidoc.element.johnny-five.Animation.Segment)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.</span>TemporalFallback (animation)](#apidoc.element.johnny-five.Animation.TemporalFallback)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.</span>super_ ()](#apidoc.element.johnny-five.Animation.super_)
1.  string <span class="apidocSignatureSpan">johnny-five.Animation.</span>keys
1.  string <span class="apidocSignatureSpan">johnny-five.Animation.</span>normalize
1.  string <span class="apidocSignatureSpan">johnny-five.Animation.</span>render

#### [module johnny-five.Animation.TemporalFallback](#apidoc.module.johnny-five.Animation.TemporalFallback)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.</span>TemporalFallback (animation)](#apidoc.element.johnny-five.Animation.TemporalFallback.TemporalFallback)

#### [module johnny-five.Animation.TemporalFallback.prototype](#apidoc.module.johnny-five.Animation.TemporalFallback.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.TemporalFallback.prototype.</span>stop ()](#apidoc.element.johnny-five.Animation.TemporalFallback.prototype.stop)

#### [module johnny-five.Animation.prototype](#apidoc.module.johnny-five.Animation.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>calculateProgress (calledAt)](#apidoc.element.johnny-five.Animation.prototype.calculateProgress)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>enqueue (opts)](#apidoc.element.johnny-five.Animation.prototype.enqueue)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>findIndices (progress)](#apidoc.element.johnny-five.Animation.prototype.findIndices)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>loopFunction (loop)](#apidoc.element.johnny-five.Animation.prototype.loopFunction)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>next ()](#apidoc.element.johnny-five.Animation.prototype.next)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>normalizeKeyframes ()](#apidoc.element.johnny-five.Animation.prototype.normalizeKeyframes)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>pause ()](#apidoc.element.johnny-five.Animation.prototype.pause)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>play ()](#apidoc.element.johnny-five.Animation.prototype.play)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>speed (speed)](#apidoc.element.johnny-five.Animation.prototype.speed)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>stop ()](#apidoc.element.johnny-five.Animation.prototype.stop)
1.  [function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>tweenedValue (indices, progress)](#apidoc.element.johnny-five.Animation.prototype.tweenedValue)

#### [module johnny-five.Barometer](#apidoc.module.johnny-five.Barometer)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Barometer (opts)](#apidoc.element.johnny-five.Barometer.Barometer)
1.  [function <span class="apidocSignatureSpan">johnny-five.Barometer.</span>super_ ()](#apidoc.element.johnny-five.Barometer.super_)

#### [module johnny-five.Board](#apidoc.module.johnny-five.Board)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Board (opts)](#apidoc.element.johnny-five.Board.Board)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>Array (opts)](#apidoc.element.johnny-five.Board.Array)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>Collection (opts)](#apidoc.element.johnny-five.Board.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>Component (opts, componentOpts)](#apidoc.element.johnny-five.Board.Component)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>Controller (controller, options)](#apidoc.element.johnny-five.Board.Controller)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>Event (event)](#apidoc.element.johnny-five.Board.Event)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>Options (arg)](#apidoc.element.johnny-five.Board.Options)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>Pins (board)](#apidoc.element.johnny-five.Board.Pins)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>Virtual (opts)](#apidoc.element.johnny-five.Board.Virtual)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>constrain (value, lower, upper)](#apidoc.element.johnny-five.Board.constrain)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>fmap (value, fromLow, fromHigh, toLow, toHigh)](#apidoc.element.johnny-five.Board.fmap)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>map (value, fromLow, fromHigh, toLow, toHigh)](#apidoc.element.johnny-five.Board.map)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>mount (arg)](#apidoc.element.johnny-five.Board.mount)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>range (lower, upper, tick)](#apidoc.element.johnny-five.Board.range)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>super_ ()](#apidoc.element.johnny-five.Board.super_)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>uid ()](#apidoc.element.johnny-five.Board.uid)

#### [module johnny-five.Board.Component](#apidoc.module.johnny-five.Board.Component)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>Component (opts, componentOpts)](#apidoc.element.johnny-five.Board.Component.Component)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.Component.</span>initialization (opts)](#apidoc.element.johnny-five.Board.Component.initialization)

#### [module johnny-five.Board.Pins](#apidoc.module.johnny-five.Board.Pins)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>Pins (board)](#apidoc.element.johnny-five.Board.Pins.Pins)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.Pins.</span>Error (opts)](#apidoc.element.johnny-five.Board.Pins.Error)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.Pins.</span>fromAnalog (pin)](#apidoc.element.johnny-five.Board.Pins.fromAnalog)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.Pins.</span>identity (pins, needle)](#apidoc.element.johnny-five.Board.Pins.identity)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.Pins.</span>isFirmata (board)](#apidoc.element.johnny-five.Board.Pins.isFirmata)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.Pins.</span>normalize (opts, board)](#apidoc.element.johnny-five.Board.Pins.normalize)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.Pins.</span>translate (pin, type)](#apidoc.element.johnny-five.Board.Pins.translate)
1.  object <span class="apidocSignatureSpan">johnny-five.Board.Pins.</span>translations

#### [module johnny-five.Board.Pins.prototype](#apidoc.module.johnny-five.Board.Pins.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.Pins.prototype.</span>isAnalog (pin)](#apidoc.element.johnny-five.Board.Pins.prototype.isAnalog)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.Pins.prototype.</span>isDigital (pin)](#apidoc.element.johnny-five.Board.Pins.prototype.isDigital)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.Pins.prototype.</span>isInput (pin)](#apidoc.element.johnny-five.Board.Pins.prototype.isInput)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.Pins.prototype.</span>isOutput (pin)](#apidoc.element.johnny-five.Board.Pins.prototype.isOutput)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.Pins.prototype.</span>isPwm (pin)](#apidoc.element.johnny-five.Board.Pins.prototype.isPwm)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.Pins.prototype.</span>isServo (pin)](#apidoc.element.johnny-five.Board.Pins.prototype.isServo)

#### [module johnny-five.Board.prototype](#apidoc.module.johnny-five.Board.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>analogRead ()](#apidoc.element.johnny-five.Board.prototype.analogRead)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>analogWrite ()](#apidoc.element.johnny-five.Board.prototype.analogWrite)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>digitalRead ()](#apidoc.element.johnny-five.Board.prototype.digitalRead)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>digitalWrite ()](#apidoc.element.johnny-five.Board.prototype.digitalWrite)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>error ()](#apidoc.element.johnny-five.Board.prototype.error)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>fail ()](#apidoc.element.johnny-five.Board.prototype.fail)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>i2cConfig ()](#apidoc.element.johnny-five.Board.prototype.i2cConfig)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>i2cRead ()](#apidoc.element.johnny-five.Board.prototype.i2cRead)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>i2cReadOnce ()](#apidoc.element.johnny-five.Board.prototype.i2cReadOnce)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>i2cWrite ()](#apidoc.element.johnny-five.Board.prototype.i2cWrite)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>i2cWriteReg ()](#apidoc.element.johnny-five.Board.prototype.i2cWriteReg)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>info ()](#apidoc.element.johnny-five.Board.prototype.info)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>log ()](#apidoc.element.johnny-five.Board.prototype.log)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>loop (time, callback)](#apidoc.element.johnny-five.Board.prototype.loop)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>pinMode ()](#apidoc.element.johnny-five.Board.prototype.pinMode)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>pwmWrite ()](#apidoc.element.johnny-five.Board.prototype.pwmWrite)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>queryPinState ()](#apidoc.element.johnny-five.Board.prototype.queryPinState)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>samplingInterval (ms)](#apidoc.element.johnny-five.Board.prototype.samplingInterval)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>sendI2CConfig ()](#apidoc.element.johnny-five.Board.prototype.sendI2CConfig)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>sendI2CReadRequest ()](#apidoc.element.johnny-five.Board.prototype.sendI2CReadRequest)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>sendI2CWriteRequest ()](#apidoc.element.johnny-five.Board.prototype.sendI2CWriteRequest)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialClose ()](#apidoc.element.johnny-five.Board.prototype.serialClose)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialConfig ()](#apidoc.element.johnny-five.Board.prototype.serialConfig)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialFlush ()](#apidoc.element.johnny-five.Board.prototype.serialFlush)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialListen ()](#apidoc.element.johnny-five.Board.prototype.serialListen)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialRead ()](#apidoc.element.johnny-five.Board.prototype.serialRead)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialStop ()](#apidoc.element.johnny-five.Board.prototype.serialStop)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialWrite ()](#apidoc.element.johnny-five.Board.prototype.serialWrite)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialize (reducer)](#apidoc.element.johnny-five.Board.prototype.serialize)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>servoConfig ()](#apidoc.element.johnny-five.Board.prototype.servoConfig)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>servoWrite ()](#apidoc.element.johnny-five.Board.prototype.servoWrite)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>shiftOut (dataPin, clockPin, isBigEndian, value)](#apidoc.element.johnny-five.Board.prototype.shiftOut)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>snapshot (reducer)](#apidoc.element.johnny-five.Board.prototype.snapshot)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>stepperConfig ()](#apidoc.element.johnny-five.Board.prototype.stepperConfig)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>stepperStep ()](#apidoc.element.johnny-five.Board.prototype.stepperStep)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>sysexCommand ()](#apidoc.element.johnny-five.Board.prototype.sysexCommand)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>sysexResponse ()](#apidoc.element.johnny-five.Board.prototype.sysexResponse)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>wait (time, callback)](#apidoc.element.johnny-five.Board.prototype.wait)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>warn ()](#apidoc.element.johnny-five.Board.prototype.warn)

#### [module johnny-five.Board.range](#apidoc.module.johnny-five.Board.range)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.</span>range (lower, upper, tick)](#apidoc.element.johnny-five.Board.range.range)
1.  [function <span class="apidocSignatureSpan">johnny-five.Board.range.</span>prefixed (prefix)](#apidoc.element.johnny-five.Board.range.prefixed)

#### [module johnny-five.Boards](#apidoc.module.johnny-five.Boards)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Boards (opts)](#apidoc.element.johnny-five.Boards.Boards)
1.  [function <span class="apidocSignatureSpan">johnny-five.Boards.</span>super_ ()](#apidoc.element.johnny-five.Boards.super_)

#### [module johnny-five.Boards.prototype](#apidoc.module.johnny-five.Boards.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>add ()](#apidoc.element.johnny-five.Boards.prototype.add)
1.  [function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>byId (id)](#apidoc.element.johnny-five.Boards.prototype.byId)
1.  [function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>each (callbackFn)](#apidoc.element.johnny-five.Boards.prototype.each)
1.  [function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>error ()](#apidoc.element.johnny-five.Boards.prototype.error)
1.  [function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>fail ()](#apidoc.element.johnny-five.Boards.prototype.fail)
1.  [function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>forEach ()](#apidoc.element.johnny-five.Boards.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>includes ()](#apidoc.element.johnny-five.Boards.prototype.includes)
1.  [function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>indexOf ()](#apidoc.element.johnny-five.Boards.prototype.indexOf)
1.  [function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>info ()](#apidoc.element.johnny-five.Boards.prototype.info)
1.  [function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>log ()](#apidoc.element.johnny-five.Boards.prototype.log)
1.  [function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>map ()](#apidoc.element.johnny-five.Boards.prototype.map)
1.  [function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>slice ()](#apidoc.element.johnny-five.Boards.prototype.slice)
1.  [function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>warn ()](#apidoc.element.johnny-five.Boards.prototype.warn)

#### [module johnny-five.Button](#apidoc.module.johnny-five.Button)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Button (opts)](#apidoc.element.johnny-five.Button.Button)
1.  [function <span class="apidocSignatureSpan">johnny-five.Button.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Button.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Button.</span>super_ ()](#apidoc.element.johnny-five.Button.super_)

#### [module johnny-five.Buttons](#apidoc.module.johnny-five.Buttons)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Buttons (numsOrObjects)](#apidoc.element.johnny-five.Buttons.Buttons)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Buttons.super_)

#### [module johnny-five.Buttons.super_](#apidoc.module.johnny-five.Buttons.super_)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Buttons.super_.super_)

#### [module johnny-five.Buttons.super_.prototype](#apidoc.module.johnny-five.Buttons.super_.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>add ()](#apidoc.element.johnny-five.Buttons.super_.prototype.add)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>addListener (type, listener)](#apidoc.element.johnny-five.Buttons.super_.prototype.addListener)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>emit (type)](#apidoc.element.johnny-five.Buttons.super_.prototype.emit)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>eventNames ()](#apidoc.element.johnny-five.Buttons.super_.prototype.eventNames)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>getMaxListeners ()](#apidoc.element.johnny-five.Buttons.super_.prototype.getMaxListeners)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>listenerCount (type)](#apidoc.element.johnny-five.Buttons.super_.prototype.listenerCount)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>listeners (type)](#apidoc.element.johnny-five.Buttons.super_.prototype.listeners)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>on (type, listener)](#apidoc.element.johnny-five.Buttons.super_.prototype.on)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>once (type, listener)](#apidoc.element.johnny-five.Buttons.super_.prototype.once)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>prependListener (type, listener)](#apidoc.element.johnny-five.Buttons.super_.prototype.prependListener)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>prependOnceListener (type, listener)](#apidoc.element.johnny-five.Buttons.super_.prototype.prependOnceListener)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>removeAllListeners (type)](#apidoc.element.johnny-five.Buttons.super_.prototype.removeAllListeners)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>removeListener (type, listener)](#apidoc.element.johnny-five.Buttons.super_.prototype.removeListener)
1.  [function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>setMaxListeners (n)](#apidoc.element.johnny-five.Buttons.super_.prototype.setMaxListeners)
1.  undefined <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>domain

#### [module johnny-five.Collection](#apidoc.module.johnny-five.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Collection.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Collection.</span>Emitter (numsOrObjects)](#apidoc.element.johnny-five.Collection.Emitter)
1.  [function <span class="apidocSignatureSpan">johnny-five.Collection.</span>installMethodForwarding (target, source)](#apidoc.element.johnny-five.Collection.installMethodForwarding)

#### [module johnny-five.Collection.prototype](#apidoc.module.johnny-five.Collection.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>add ()](#apidoc.element.johnny-five.Collection.prototype.add)
1.  [function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>byId (id)](#apidoc.element.johnny-five.Collection.prototype.byId)
1.  [function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>each (callbackFn)](#apidoc.element.johnny-five.Collection.prototype.each)
1.  [function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>forEach ()](#apidoc.element.johnny-five.Collection.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>includes ()](#apidoc.element.johnny-five.Collection.prototype.includes)
1.  [function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>indexOf ()](#apidoc.element.johnny-five.Collection.prototype.indexOf)
1.  [function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>map ()](#apidoc.element.johnny-five.Collection.prototype.map)
1.  [function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>slice ()](#apidoc.element.johnny-five.Collection.prototype.slice)

#### [module johnny-five.Color](#apidoc.module.johnny-five.Color)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Color (opts)](#apidoc.element.johnny-five.Color.Color)
1.  [function <span class="apidocSignatureSpan">johnny-five.Color.</span>hexCode (rgb)](#apidoc.element.johnny-five.Color.hexCode)
1.  [function <span class="apidocSignatureSpan">johnny-five.Color.</span>super_ ()](#apidoc.element.johnny-five.Color.super_)

#### [module johnny-five.Compass](#apidoc.module.johnny-five.Compass)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Compass (opts)](#apidoc.element.johnny-five.Compass.Compass)
1.  [function <span class="apidocSignatureSpan">johnny-five.Compass.</span>Scale (gauss)](#apidoc.element.johnny-five.Compass.Scale)
1.  [function <span class="apidocSignatureSpan">johnny-five.Compass.</span>super_ ()](#apidoc.element.johnny-five.Compass.super_)
1.  object <span class="apidocSignatureSpan">johnny-five.Compass.</span>Points

#### [module johnny-five.ESC](#apidoc.module.johnny-five.ESC)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>ESC (opts)](#apidoc.element.johnny-five.ESC.ESC)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESC.</span>Array (numsOrObjects)](#apidoc.element.johnny-five.ESC.Array)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESC.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.ESC.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESC.</span>super_ ()](#apidoc.element.johnny-five.ESC.super_)

#### [module johnny-five.ESC.prototype](#apidoc.module.johnny-five.ESC.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESC.prototype.</span>brake ()](#apidoc.element.johnny-five.ESC.prototype.brake)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESC.prototype.</span>forward (speed)](#apidoc.element.johnny-five.ESC.prototype.forward)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESC.prototype.</span>fwd (speed)](#apidoc.element.johnny-five.ESC.prototype.fwd)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESC.prototype.</span>rev (speed)](#apidoc.element.johnny-five.ESC.prototype.rev)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESC.prototype.</span>reverse (speed)](#apidoc.element.johnny-five.ESC.prototype.reverse)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESC.prototype.</span>speed (speed)](#apidoc.element.johnny-five.ESC.prototype.speed)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESC.prototype.</span>stop ()](#apidoc.element.johnny-five.ESC.prototype.stop)

#### [module johnny-five.ESCs](#apidoc.module.johnny-five.ESCs)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>ESCs (numsOrObjects)](#apidoc.element.johnny-five.ESCs.ESCs)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESCs.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.ESCs.super_)

#### [module johnny-five.ESCs.prototype](#apidoc.module.johnny-five.ESCs.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESCs.prototype.</span>brake ()](#apidoc.element.johnny-five.ESCs.prototype.brake)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESCs.prototype.</span>forward ()](#apidoc.element.johnny-five.ESCs.prototype.forward)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESCs.prototype.</span>fwd ()](#apidoc.element.johnny-five.ESCs.prototype.fwd)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESCs.prototype.</span>rev ()](#apidoc.element.johnny-five.ESCs.prototype.rev)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESCs.prototype.</span>reverse ()](#apidoc.element.johnny-five.ESCs.prototype.reverse)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESCs.prototype.</span>speed ()](#apidoc.element.johnny-five.ESCs.prototype.speed)
1.  [function <span class="apidocSignatureSpan">johnny-five.ESCs.prototype.</span>stop ()](#apidoc.element.johnny-five.ESCs.prototype.stop)

#### [module johnny-five.Expander](#apidoc.module.johnny-five.Expander)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Expander (opts)](#apidoc.element.johnny-five.Expander.Expander)
1.  [function <span class="apidocSignatureSpan">johnny-five.Expander.</span>byAddress (address)](#apidoc.element.johnny-five.Expander.byAddress)
1.  [function <span class="apidocSignatureSpan">johnny-five.Expander.</span>byController (name)](#apidoc.element.johnny-five.Expander.byController)
1.  [function <span class="apidocSignatureSpan">johnny-five.Expander.</span>get (required)](#apidoc.element.johnny-five.Expander.get)
1.  [function <span class="apidocSignatureSpan">johnny-five.Expander.</span>hasController (key)](#apidoc.element.johnny-five.Expander.hasController)
1.  [function <span class="apidocSignatureSpan">johnny-five.Expander.</span>super_ ()](#apidoc.element.johnny-five.Expander.super_)

#### [module johnny-five.Expander.super_](#apidoc.module.johnny-five.Expander.super_)
1.  [function <span class="apidocSignatureSpan">johnny-five.Expander.</span>super_ ()](#apidoc.element.johnny-five.Expander.super_.super_)

#### [module johnny-five.Fn](#apidoc.module.johnny-five.Fn)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>_BV (bit)](#apidoc.element.johnny-five.Fn._BV)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>bitSize (n)](#apidoc.element.johnny-five.Fn.bitSize)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>bitValue (bit)](#apidoc.element.johnny-five.Fn.bitValue)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>bv (bit)](#apidoc.element.johnny-five.Fn.bv)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>cloneDeep (value)](#apidoc.element.johnny-five.Fn.cloneDeep)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>constrain (value, lower, upper)](#apidoc.element.johnny-five.Fn.constrain)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>debounce (func, wait, options)](#apidoc.element.johnny-five.Fn.debounce)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>fma (a, b, c)](#apidoc.element.johnny-five.Fn.fma)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>fmap (value, fromLow, fromHigh, toLow, toHigh)](#apidoc.element.johnny-five.Fn.fmap)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>fscale (value, fromLow, fromHigh, toLow, toHigh)](#apidoc.element.johnny-five.Fn.fscale)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>inRange (value, lower, upper)](#apidoc.element.johnny-five.Fn.inRange)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>int16 (msb, lsb)](#apidoc.element.johnny-five.Fn.int16)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>int24 (b16, b8, b0)](#apidoc.element.johnny-five.Fn.int24)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>int32 (b24, b16, b8, b0)](#apidoc.element.johnny-five.Fn.int32)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>map (value, fromLow, fromHigh, toLow, toHigh)](#apidoc.element.johnny-five.Fn.map)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>range (lower, upper, tick)](#apidoc.element.johnny-five.Fn.range)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s10 (value)](#apidoc.element.johnny-five.Fn.s10)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s12 (value)](#apidoc.element.johnny-five.Fn.s12)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s16 (value)](#apidoc.element.johnny-five.Fn.s16)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s20 (value)](#apidoc.element.johnny-five.Fn.s20)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s24 (value)](#apidoc.element.johnny-five.Fn.s24)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s32 (value)](#apidoc.element.johnny-five.Fn.s32)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s4 (value)](#apidoc.element.johnny-five.Fn.s4)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s8 (value)](#apidoc.element.johnny-five.Fn.s8)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>scale (value, fromLow, fromHigh, toLow, toHigh)](#apidoc.element.johnny-five.Fn.scale)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>square (x)](#apidoc.element.johnny-five.Fn.square)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>sum (values)](#apidoc.element.johnny-five.Fn.sum)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>toFixed (number, digits)](#apidoc.element.johnny-five.Fn.toFixed)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u10 (value)](#apidoc.element.johnny-five.Fn.u10)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u12 (value)](#apidoc.element.johnny-five.Fn.u12)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u16 (value)](#apidoc.element.johnny-five.Fn.u16)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u20 (value)](#apidoc.element.johnny-five.Fn.u20)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u24 (value)](#apidoc.element.johnny-five.Fn.u24)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u32 (value)](#apidoc.element.johnny-five.Fn.u32)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u4 (value)](#apidoc.element.johnny-five.Fn.u4)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u8 (value)](#apidoc.element.johnny-five.Fn.u8)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>uid ()](#apidoc.element.johnny-five.Fn.uid)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>uint16 (msb, lsb)](#apidoc.element.johnny-five.Fn.uint16)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>uint24 (b16, b8, b0)](#apidoc.element.johnny-five.Fn.uint24)
1.  [function <span class="apidocSignatureSpan">johnny-five.Fn.</span>uint32 (b24, b16, b8, b0)](#apidoc.element.johnny-five.Fn.uint32)
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>DEG_TO_RAD
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_0
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_1
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_10
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_11
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_12
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_13
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_14
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_15
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_16
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_17
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_18
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_19
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_2
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_20
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_21
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_22
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_23
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_24
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_25
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_26
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_27
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_28
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_29
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_3
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_30
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_31
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_32
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_33
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_34
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_35
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_36
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_37
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_38
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_39
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_4
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_40
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_41
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_42
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_43
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_44
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_45
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_46
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_47
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_48
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_49
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_5
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_50
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_51
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_52
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_53
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_6
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_7
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_8
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>POW_2_9
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>RAD_TO_DEG
1.  number <span class="apidocSignatureSpan">johnny-five.Fn.</span>TAU

#### [module johnny-five.GPS](#apidoc.module.johnny-five.GPS)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>GPS (opts)](#apidoc.element.johnny-five.GPS.GPS)
1.  [function <span class="apidocSignatureSpan">johnny-five.GPS.</span>super_ ()](#apidoc.element.johnny-five.GPS.super_)

#### [module johnny-five.GPS.prototype](#apidoc.module.johnny-five.GPS.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.GPS.prototype.</span>initialize (opts)](#apidoc.element.johnny-five.GPS.prototype.initialize)
1.  [function <span class="apidocSignatureSpan">johnny-five.GPS.prototype.</span>listen ()](#apidoc.element.johnny-five.GPS.prototype.listen)
1.  [function <span class="apidocSignatureSpan">johnny-five.GPS.prototype.</span>parseNmeaSentence (sentence)](#apidoc.element.johnny-five.GPS.prototype.parseNmeaSentence)
1.  [function <span class="apidocSignatureSpan">johnny-five.GPS.prototype.</span>sendCommand (string)](#apidoc.element.johnny-five.GPS.prototype.sendCommand)

#### [module johnny-five.Gripper](#apidoc.module.johnny-five.Gripper)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Gripper (opts)](#apidoc.element.johnny-five.Gripper.Gripper)

#### [module johnny-five.Gripper.prototype](#apidoc.module.johnny-five.Gripper.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Gripper.prototype.</span>close ()](#apidoc.element.johnny-five.Gripper.prototype.close)
1.  [function <span class="apidocSignatureSpan">johnny-five.Gripper.prototype.</span>open ()](#apidoc.element.johnny-five.Gripper.prototype.open)
1.  [function <span class="apidocSignatureSpan">johnny-five.Gripper.prototype.</span>set ()](#apidoc.element.johnny-five.Gripper.prototype.set)

#### [module johnny-five.Gyro](#apidoc.module.johnny-five.Gyro)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Gyro (opts)](#apidoc.element.johnny-five.Gyro.Gyro)
1.  [function <span class="apidocSignatureSpan">johnny-five.Gyro.</span>super_ ()](#apidoc.element.johnny-five.Gyro.super_)

#### [module johnny-five.Gyro.prototype](#apidoc.module.johnny-five.Gyro.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Gyro.prototype.</span>recalibrate ()](#apidoc.element.johnny-five.Gyro.prototype.recalibrate)

#### [module johnny-five.Hygrometer](#apidoc.module.johnny-five.Hygrometer)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Hygrometer (opts)](#apidoc.element.johnny-five.Hygrometer.Hygrometer)
1.  [function <span class="apidocSignatureSpan">johnny-five.Hygrometer.</span>super_ ()](#apidoc.element.johnny-five.Hygrometer.super_)

#### [module johnny-five.IMU](#apidoc.module.johnny-five.IMU)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>IMU (opts)](#apidoc.element.johnny-five.IMU.IMU)
1.  [function <span class="apidocSignatureSpan">johnny-five.IMU.</span>super_ ()](#apidoc.element.johnny-five.IMU.super_)
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.</span>Drivers

#### [module johnny-five.IMU.Drivers](#apidoc.module.johnny-five.IMU.Drivers)
1.  [function <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>clear ()](#apidoc.element.johnny-five.IMU.Drivers.clear)
1.  [function <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>get (board, driverName, opts)](#apidoc.element.johnny-five.IMU.Drivers.get)
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>BME280
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>BMP085
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>BMP180
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>BMP280
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>BNO055
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>DHT11_I2C_NANO_BACKPACK
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>DHT21_I2C_NANO_BACKPACK
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>DHT22_I2C_NANO_BACKPACK
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>DHT_I2C_NANO_BACKPACK
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>GY521
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>HIH6130
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>HTU21D
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>MPL115A2
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>MPL3115A2
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>MPU6050
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>MS5611
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>SHT31D
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>SI7020
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>SI7021
1.  object <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>TH02

#### [module johnny-five.IR](#apidoc.module.johnny-five.IR)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>IR ()](#apidoc.element.johnny-five.IR.IR)
1.  [function <span class="apidocSignatureSpan">johnny-five.IR.</span>Distance ()](#apidoc.element.johnny-five.IR.Distance)
1.  [function <span class="apidocSignatureSpan">johnny-five.IR.</span>Motion ()](#apidoc.element.johnny-five.IR.Motion)
1.  [function <span class="apidocSignatureSpan">johnny-five.IR.</span>Proximity ()](#apidoc.element.johnny-five.IR.Proximity)
1.  object <span class="apidocSignatureSpan">johnny-five.IR.</span>Reflect

#### [module johnny-five.IR.Reflect](#apidoc.module.johnny-five.IR.Reflect)
1.  [function <span class="apidocSignatureSpan">johnny-five.IR.Reflect.</span>Array (opts)](#apidoc.element.johnny-five.IR.Reflect.Array)
1.  [function <span class="apidocSignatureSpan">johnny-five.IR.Reflect.</span>Collection (opts)](#apidoc.element.johnny-five.IR.Reflect.Collection)

#### [module johnny-five.IR.Reflect.Array.prototype](#apidoc.module.johnny-five.IR.Reflect.Array.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.IR.Reflect.Array.prototype.</span>calibrate ()](#apidoc.element.johnny-five.IR.Reflect.Array.prototype.calibrate)
1.  [function <span class="apidocSignatureSpan">johnny-five.IR.Reflect.Array.prototype.</span>calibrateUntil (predicate)](#apidoc.element.johnny-five.IR.Reflect.Array.prototype.calibrateUntil)
1.  [function <span class="apidocSignatureSpan">johnny-five.IR.Reflect.Array.prototype.</span>disable ()](#apidoc.element.johnny-five.IR.Reflect.Array.prototype.disable)
1.  [function <span class="apidocSignatureSpan">johnny-five.IR.Reflect.Array.prototype.</span>enable ()](#apidoc.element.johnny-five.IR.Reflect.Array.prototype.enable)
1.  [function <span class="apidocSignatureSpan">johnny-five.IR.Reflect.Array.prototype.</span>loadCalibration (calibration)](#apidoc.element.johnny-five.IR.Reflect.Array.prototype.loadCalibration)

#### [module johnny-five.Joystick](#apidoc.module.johnny-five.Joystick)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Joystick (opts)](#apidoc.element.johnny-five.Joystick.Joystick)
1.  [function <span class="apidocSignatureSpan">johnny-five.Joystick.</span>super_ ()](#apidoc.element.johnny-five.Joystick.super_)

#### [module johnny-five.Keypad](#apidoc.module.johnny-five.Keypad)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Keypad (opts)](#apidoc.element.johnny-five.Keypad.Keypad)
1.  [function <span class="apidocSignatureSpan">johnny-five.Keypad.</span>super_ ()](#apidoc.element.johnny-five.Keypad.super_)

#### [module johnny-five.LCD](#apidoc.module.johnny-five.LCD)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>LCD (opts)](#apidoc.element.johnny-five.LCD.LCD)
1.  number <span class="apidocSignatureSpan">johnny-five.LCD.</span>NEGATIVE
1.  number <span class="apidocSignatureSpan">johnny-five.LCD.</span>POSITIVE
1.  object <span class="apidocSignatureSpan">johnny-five.LCD.</span>Characters

#### [module johnny-five.LCD.prototype](#apidoc.module.johnny-five.LCD.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>autoscroll ()](#apidoc.element.johnny-five.LCD.prototype.autoscroll)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>backlight (highOrLow)](#apidoc.element.johnny-five.LCD.prototype.backlight)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>blink ()](#apidoc.element.johnny-five.LCD.prototype.blink)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>clear ()](#apidoc.element.johnny-five.LCD.prototype.clear)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>command (mode, value)](#apidoc.element.johnny-five.LCD.prototype.command)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>createChar (name, charMap)](#apidoc.element.johnny-five.LCD.prototype.createChar)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>cursor (row, col)](#apidoc.element.johnny-five.LCD.prototype.cursor)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>hilo (callback)](#apidoc.element.johnny-five.LCD.prototype.hilo)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>home ()](#apidoc.element.johnny-five.LCD.prototype.home)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>noAutoscroll ()](#apidoc.element.johnny-five.LCD.prototype.noAutoscroll)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>noBacklight ()](#apidoc.element.johnny-five.LCD.prototype.noBacklight)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>noBlink ()](#apidoc.element.johnny-five.LCD.prototype.noBlink)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>noCursor ()](#apidoc.element.johnny-five.LCD.prototype.noCursor)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>off ()](#apidoc.element.johnny-five.LCD.prototype.off)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>on ()](#apidoc.element.johnny-five.LCD.prototype.on)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>print (message, opts)](#apidoc.element.johnny-five.LCD.prototype.print)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>send (value)](#apidoc.element.johnny-five.LCD.prototype.send)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>setCursor (col, row)](#apidoc.element.johnny-five.LCD.prototype.setCursor)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>useChar (name)](#apidoc.element.johnny-five.LCD.prototype.useChar)
1.  [function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>write (charCode)](#apidoc.element.johnny-five.LCD.prototype.write)

#### [module johnny-five.Led](#apidoc.module.johnny-five.Led)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Led (opts)](#apidoc.element.johnny-five.Led.Led)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.</span>Array (numsOrObjects)](#apidoc.element.johnny-five.Led.Array)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Led.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.</span>Digits (opts)](#apidoc.element.johnny-five.Led.Digits)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.</span>Matrix (opts)](#apidoc.element.johnny-five.Led.Matrix)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.</span>RGB (opts)](#apidoc.element.johnny-five.Led.RGB)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.</span>RGBs (numsOrObjects)](#apidoc.element.johnny-five.Led.RGBs)

#### [module johnny-five.Led.RGB](#apidoc.module.johnny-five.Led.RGB)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.</span>RGB (opts)](#apidoc.element.johnny-five.Led.RGB.RGB)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGB.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Led.RGB.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGB.</span>ToRGB (red, green, blue)](#apidoc.element.johnny-five.Led.RGB.ToRGB)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGB.</span>ToScaledRGB (intensity, colors)](#apidoc.element.johnny-five.Led.RGB.ToScaledRGB)
1.  object <span class="apidocSignatureSpan">johnny-five.Led.RGB.</span>colors

#### [module johnny-five.Led.RGB.prototype](#apidoc.module.johnny-five.Led.RGB.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>blink (duration, callback)](#apidoc.element.johnny-five.Led.RGB.prototype.blink)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>color (red, green, blue)](#apidoc.element.johnny-five.Led.RGB.prototype.color)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>intensity (intensity)](#apidoc.element.johnny-five.Led.RGB.prototype.intensity)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>off ()](#apidoc.element.johnny-five.Led.RGB.prototype.off)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>on ()](#apidoc.element.johnny-five.Led.RGB.prototype.on)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>stop ()](#apidoc.element.johnny-five.Led.RGB.prototype.stop)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>strobe (duration, callback)](#apidoc.element.johnny-five.Led.RGB.prototype.strobe)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>toggle ()](#apidoc.element.johnny-five.Led.RGB.prototype.toggle)

#### [module johnny-five.Led.RGBs](#apidoc.module.johnny-five.Led.RGBs)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.</span>RGBs (numsOrObjects)](#apidoc.element.johnny-five.Led.RGBs.RGBs)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Led.RGBs.super_)

#### [module johnny-five.Led.RGBs.prototype](#apidoc.module.johnny-five.Led.RGBs.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>blink (duration, callback)](#apidoc.element.johnny-five.Led.RGBs.prototype.blink)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>color ()](#apidoc.element.johnny-five.Led.RGBs.prototype.color)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>intensity ()](#apidoc.element.johnny-five.Led.RGBs.prototype.intensity)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>off ()](#apidoc.element.johnny-five.Led.RGBs.prototype.off)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>on ()](#apidoc.element.johnny-five.Led.RGBs.prototype.on)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>stop ()](#apidoc.element.johnny-five.Led.RGBs.prototype.stop)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>strobe ()](#apidoc.element.johnny-five.Led.RGBs.prototype.strobe)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>toggle ()](#apidoc.element.johnny-five.Led.RGBs.prototype.toggle)

#### [module johnny-five.Led.prototype](#apidoc.module.johnny-five.Led.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>blink (duration, callback)](#apidoc.element.johnny-five.Led.prototype.blink)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>brightness (brightness)](#apidoc.element.johnny-five.Led.prototype.brightness)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>fade (val, duration, callback)](#apidoc.element.johnny-five.Led.prototype.fade)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>fadeIn (duration, callback)](#apidoc.element.johnny-five.Led.prototype.fadeIn)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>fadeOut (duration, callback)](#apidoc.element.johnny-five.Led.prototype.fadeOut)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>intensity (intensity)](#apidoc.element.johnny-five.Led.prototype.intensity)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>off ()](#apidoc.element.johnny-five.Led.prototype.off)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>on ()](#apidoc.element.johnny-five.Led.prototype.on)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>pulse (duration, callback)](#apidoc.element.johnny-five.Led.prototype.pulse)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>stop ()](#apidoc.element.johnny-five.Led.prototype.stop)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>strobe (duration, callback)](#apidoc.element.johnny-five.Led.prototype.strobe)
1.  [function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>toggle ()](#apidoc.element.johnny-five.Led.prototype.toggle)

#### [module johnny-five.LedControl](#apidoc.module.johnny-five.LedControl)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>LedControl (opts)](#apidoc.element.johnny-five.LedControl.LedControl)
1.  object <span class="apidocSignatureSpan">johnny-five.LedControl.</span>COLORS
1.  object <span class="apidocSignatureSpan">johnny-five.LedControl.</span>DEFAULTS
1.  object <span class="apidocSignatureSpan">johnny-five.LedControl.</span>DIGIT_CHARS
1.  object <span class="apidocSignatureSpan">johnny-five.LedControl.</span>DIRECTIONS
1.  object <span class="apidocSignatureSpan">johnny-five.LedControl.</span>MATRIX_CHARS
1.  object <span class="apidocSignatureSpan">johnny-five.LedControl.</span>MATRIX_DIMENSIONS
1.  object <span class="apidocSignatureSpan">johnny-five.LedControl.</span>OP

#### [module johnny-five.LedControl.prototype](#apidoc.module.johnny-five.LedControl.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>brightness (addr, val)](#apidoc.element.johnny-five.LedControl.prototype.brightness)
1.  [function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>char ()](#apidoc.element.johnny-five.LedControl.prototype.char)
1.  [function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>column (addr, col, value)](#apidoc.element.johnny-five.LedControl.prototype.column)
1.  [function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>device (addr)](#apidoc.element.johnny-five.LedControl.prototype.device)
1.  [function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>digit (addr, position, chr)](#apidoc.element.johnny-five.LedControl.prototype.digit)
1.  [function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>draw (addr, chr)](#apidoc.element.johnny-five.LedControl.prototype.draw)
1.  [function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>each (callbackfn)](#apidoc.element.johnny-five.LedControl.prototype.each)
1.  [function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>off (addr)](#apidoc.element.johnny-five.LedControl.prototype.off)
1.  [function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>on (addr)](#apidoc.element.johnny-five.LedControl.prototype.on)
1.  [function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>print (message, opts)](#apidoc.element.johnny-five.LedControl.prototype.print)
1.  [function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>setLed ()](#apidoc.element.johnny-five.LedControl.prototype.setLed)

#### [module johnny-five.Leds](#apidoc.module.johnny-five.Leds)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Leds (numsOrObjects)](#apidoc.element.johnny-five.Leds.Leds)
1.  [function <span class="apidocSignatureSpan">johnny-five.Leds.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Leds.super_)

#### [module johnny-five.Leds.prototype](#apidoc.module.johnny-five.Leds.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>blink (duration, callback)](#apidoc.element.johnny-five.Leds.prototype.blink)
1.  [function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>brightness ()](#apidoc.element.johnny-five.Leds.prototype.brightness)
1.  [function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>fade (duration, callback)](#apidoc.element.johnny-five.Leds.prototype.fade)
1.  [function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>fadeIn (duration, callback)](#apidoc.element.johnny-five.Leds.prototype.fadeIn)
1.  [function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>fadeOut (duration, callback)](#apidoc.element.johnny-five.Leds.prototype.fadeOut)
1.  [function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>intensity ()](#apidoc.element.johnny-five.Leds.prototype.intensity)
1.  [function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>off ()](#apidoc.element.johnny-five.Leds.prototype.off)
1.  [function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>on ()](#apidoc.element.johnny-five.Leds.prototype.on)
1.  [function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>pulse (duration, callback)](#apidoc.element.johnny-five.Leds.prototype.pulse)
1.  [function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>stop ()](#apidoc.element.johnny-five.Leds.prototype.stop)
1.  [function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>strobe ()](#apidoc.element.johnny-five.Leds.prototype.strobe)
1.  [function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>toggle ()](#apidoc.element.johnny-five.Leds.prototype.toggle)

#### [module johnny-five.Light](#apidoc.module.johnny-five.Light)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Light (opts)](#apidoc.element.johnny-five.Light.Light)
1.  [function <span class="apidocSignatureSpan">johnny-five.Light.</span>super_ ()](#apidoc.element.johnny-five.Light.super_)

#### [module johnny-five.Light.prototype](#apidoc.module.johnny-five.Light.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Light.prototype.</span>within (range, unit, callback)](#apidoc.element.johnny-five.Light.prototype.within)

#### [module johnny-five.Motion](#apidoc.module.johnny-five.Motion)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Motion (opts)](#apidoc.element.johnny-five.Motion.Motion)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motion.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Motion.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motion.</span>super_ ()](#apidoc.element.johnny-five.Motion.super_)

#### [module johnny-five.Motion.Collection](#apidoc.module.johnny-five.Motion.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motion.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Motion.Collection.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motion.Collection.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Motion.Collection.super_)

#### [module johnny-five.Motor](#apidoc.module.johnny-five.Motor)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Motor (opts)](#apidoc.element.johnny-five.Motor.Motor)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.</span>Array (numsOrObjects)](#apidoc.element.johnny-five.Motor.Array)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Motor.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.</span>super_ ()](#apidoc.element.johnny-five.Motor.super_)
1.  object <span class="apidocSignatureSpan">johnny-five.Motor.</span>SHIELD_CONFIGS

#### [module johnny-five.Motor.prototype](#apidoc.module.johnny-five.Motor.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>brake (duration)](#apidoc.element.johnny-five.Motor.prototype.brake)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>disable ()](#apidoc.element.johnny-five.Motor.prototype.disable)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>enable ()](#apidoc.element.johnny-five.Motor.prototype.enable)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>forward (speed)](#apidoc.element.johnny-five.Motor.prototype.forward)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>fwd (speed)](#apidoc.element.johnny-five.Motor.prototype.fwd)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>initialize ()](#apidoc.element.johnny-five.Motor.prototype.initialize)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>release ()](#apidoc.element.johnny-five.Motor.prototype.release)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>resume ()](#apidoc.element.johnny-five.Motor.prototype.resume)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>rev (speed)](#apidoc.element.johnny-five.Motor.prototype.rev)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>reverse (speed)](#apidoc.element.johnny-five.Motor.prototype.reverse)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>setPWM (pin, value)](#apidoc.element.johnny-five.Motor.prototype.setPWM)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>setPin (pin, value)](#apidoc.element.johnny-five.Motor.prototype.setPin)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>speed (opts)](#apidoc.element.johnny-five.Motor.prototype.speed)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>start (speed)](#apidoc.element.johnny-five.Motor.prototype.start)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>stop ()](#apidoc.element.johnny-five.Motor.prototype.stop)

#### [module johnny-five.Motors](#apidoc.module.johnny-five.Motors)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Motors (numsOrObjects)](#apidoc.element.johnny-five.Motors.Motors)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Motors.super_)

#### [module johnny-five.Motors.prototype](#apidoc.module.johnny-five.Motors.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>brake ()](#apidoc.element.johnny-five.Motors.prototype.brake)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>disable ()](#apidoc.element.johnny-five.Motors.prototype.disable)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>enable ()](#apidoc.element.johnny-five.Motors.prototype.enable)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>forward ()](#apidoc.element.johnny-five.Motors.prototype.forward)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>fwd ()](#apidoc.element.johnny-five.Motors.prototype.fwd)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>initialize ()](#apidoc.element.johnny-five.Motors.prototype.initialize)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>release ()](#apidoc.element.johnny-five.Motors.prototype.release)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>resume ()](#apidoc.element.johnny-five.Motors.prototype.resume)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>rev ()](#apidoc.element.johnny-five.Motors.prototype.rev)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>reverse ()](#apidoc.element.johnny-five.Motors.prototype.reverse)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>setPWM ()](#apidoc.element.johnny-five.Motors.prototype.setPWM)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>setPin ()](#apidoc.element.johnny-five.Motors.prototype.setPin)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>speed ()](#apidoc.element.johnny-five.Motors.prototype.speed)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>start ()](#apidoc.element.johnny-five.Motors.prototype.start)
1.  [function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>stop ()](#apidoc.element.johnny-five.Motors.prototype.stop)

#### [module johnny-five.Piezo](#apidoc.module.johnny-five.Piezo)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Piezo (opts)](#apidoc.element.johnny-five.Piezo.Piezo)
1.  [function <span class="apidocSignatureSpan">johnny-five.Piezo.</span>ToFrequency (tone)](#apidoc.element.johnny-five.Piezo.ToFrequency)
1.  [function <span class="apidocSignatureSpan">johnny-five.Piezo.</span>ToSong (stringSong, beats)](#apidoc.element.johnny-five.Piezo.ToSong)
1.  [function <span class="apidocSignatureSpan">johnny-five.Piezo.</span>ToTone (frequency)](#apidoc.element.johnny-five.Piezo.ToTone)
1.  [function <span class="apidocSignatureSpan">johnny-five.Piezo.</span>defaultOctave (octave)](#apidoc.element.johnny-five.Piezo.defaultOctave)
1.  [function <span class="apidocSignatureSpan">johnny-five.Piezo.</span>isValidOctave (octave)](#apidoc.element.johnny-five.Piezo.isValidOctave)
1.  object <span class="apidocSignatureSpan">johnny-five.Piezo.</span>Frequencies
1.  object <span class="apidocSignatureSpan">johnny-five.Piezo.</span>Notes
1.  object <span class="apidocSignatureSpan">johnny-five.Piezo.</span>Parsers

#### [module johnny-five.Piezo.Parsers](#apidoc.module.johnny-five.Piezo.Parsers)
1.  [function <span class="apidocSignatureSpan">johnny-five.Piezo.Parsers.</span>beatFromNote (note)](#apidoc.element.johnny-five.Piezo.Parsers.beatFromNote)
1.  [function <span class="apidocSignatureSpan">johnny-five.Piezo.Parsers.</span>hzFromInput (input)](#apidoc.element.johnny-five.Piezo.Parsers.hzFromInput)

#### [module johnny-five.Piezo.prototype](#apidoc.module.johnny-five.Piezo.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Piezo.prototype.</span>frequency (frequency, duration)](#apidoc.element.johnny-five.Piezo.prototype.frequency)
1.  [function <span class="apidocSignatureSpan">johnny-five.Piezo.prototype.</span>note (note, duration)](#apidoc.element.johnny-five.Piezo.prototype.note)
1.  [function <span class="apidocSignatureSpan">johnny-five.Piezo.prototype.</span>off ()](#apidoc.element.johnny-five.Piezo.prototype.off)
1.  [function <span class="apidocSignatureSpan">johnny-five.Piezo.prototype.</span>play (tune, callback)](#apidoc.element.johnny-five.Piezo.prototype.play)
1.  [function <span class="apidocSignatureSpan">johnny-five.Piezo.prototype.</span>stop ()](#apidoc.element.johnny-five.Piezo.prototype.stop)
1.  [function <span class="apidocSignatureSpan">johnny-five.Piezo.prototype.</span>tone (tone, duration)](#apidoc.element.johnny-five.Piezo.prototype.tone)

#### [module johnny-five.Pin](#apidoc.module.johnny-five.Pin)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Pin (opts)](#apidoc.element.johnny-five.Pin.Pin)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pin.</span>Array (numsOrObjects)](#apidoc.element.johnny-five.Pin.Array)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pin.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Pin.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pin.</span>isAnalog (opts)](#apidoc.element.johnny-five.Pin.isAnalog)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pin.</span>isPrefixed (value, prefixes)](#apidoc.element.johnny-five.Pin.isPrefixed)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pin.</span>read (pin, callback)](#apidoc.element.johnny-five.Pin.read)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pin.</span>super_ ()](#apidoc.element.johnny-five.Pin.super_)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pin.</span>write (pin, val)](#apidoc.element.johnny-five.Pin.write)

#### [module johnny-five.Pin.prototype](#apidoc.module.johnny-five.Pin.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pin.prototype.</span>high ()](#apidoc.element.johnny-five.Pin.prototype.high)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pin.prototype.</span>low ()](#apidoc.element.johnny-five.Pin.prototype.low)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pin.prototype.</span>query (callback)](#apidoc.element.johnny-five.Pin.prototype.query)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pin.prototype.</span>read (valOrCallback)](#apidoc.element.johnny-five.Pin.prototype.read)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pin.prototype.</span>write (valOrCallback)](#apidoc.element.johnny-five.Pin.prototype.write)

#### [module johnny-five.Ping](#apidoc.module.johnny-five.Ping)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Ping (opts)](#apidoc.element.johnny-five.Ping.Ping)
1.  [function <span class="apidocSignatureSpan">johnny-five.Ping.</span>super_ ()](#apidoc.element.johnny-five.Ping.super_)

#### [module johnny-five.Ping.prototype](#apidoc.module.johnny-five.Ping.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Ping.prototype.</span>within (range, unit, callback)](#apidoc.element.johnny-five.Ping.prototype.within)

#### [module johnny-five.Pins](#apidoc.module.johnny-five.Pins)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Pins (numsOrObjects)](#apidoc.element.johnny-five.Pins.Pins)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pins.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Pins.super_)

#### [module johnny-five.Pins.prototype](#apidoc.module.johnny-five.Pins.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pins.prototype.</span>high ()](#apidoc.element.johnny-five.Pins.prototype.high)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pins.prototype.</span>low ()](#apidoc.element.johnny-five.Pins.prototype.low)
1.  [function <span class="apidocSignatureSpan">johnny-five.Pins.prototype.</span>write ()](#apidoc.element.johnny-five.Pins.prototype.write)

#### [module johnny-five.Proximity](#apidoc.module.johnny-five.Proximity)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Proximity (opts)](#apidoc.element.johnny-five.Proximity.Proximity)
1.  [function <span class="apidocSignatureSpan">johnny-five.Proximity.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Proximity.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Proximity.</span>super_ ()](#apidoc.element.johnny-five.Proximity.super_)
1.  object <span class="apidocSignatureSpan">johnny-five.Proximity.</span>Controllers

#### [module johnny-five.Proximity.Collection](#apidoc.module.johnny-five.Proximity.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Proximity.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Proximity.Collection.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Proximity.Collection.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Proximity.Collection.super_)

#### [module johnny-five.Proximity.Collection.prototype](#apidoc.module.johnny-five.Proximity.Collection.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Proximity.Collection.prototype.</span>within ()](#apidoc.element.johnny-five.Proximity.Collection.prototype.within)

#### [module johnny-five.Proximity.prototype](#apidoc.module.johnny-five.Proximity.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Proximity.prototype.</span>within (range, unit, callback)](#apidoc.element.johnny-five.Proximity.prototype.within)

#### [module johnny-five.Relay](#apidoc.module.johnny-five.Relay)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Relay (opts)](#apidoc.element.johnny-five.Relay.Relay)
1.  [function <span class="apidocSignatureSpan">johnny-five.Relay.</span>Array (numsOrObjects)](#apidoc.element.johnny-five.Relay.Array)
1.  [function <span class="apidocSignatureSpan">johnny-five.Relay.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Relay.Collection)

#### [module johnny-five.Relay.prototype](#apidoc.module.johnny-five.Relay.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Relay.prototype.</span>close ()](#apidoc.element.johnny-five.Relay.prototype.close)
1.  [function <span class="apidocSignatureSpan">johnny-five.Relay.prototype.</span>off ()](#apidoc.element.johnny-five.Relay.prototype.off)
1.  [function <span class="apidocSignatureSpan">johnny-five.Relay.prototype.</span>on ()](#apidoc.element.johnny-five.Relay.prototype.on)
1.  [function <span class="apidocSignatureSpan">johnny-five.Relay.prototype.</span>open ()](#apidoc.element.johnny-five.Relay.prototype.open)
1.  [function <span class="apidocSignatureSpan">johnny-five.Relay.prototype.</span>toggle ()](#apidoc.element.johnny-five.Relay.prototype.toggle)

#### [module johnny-five.Relays](#apidoc.module.johnny-five.Relays)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Relays (numsOrObjects)](#apidoc.element.johnny-five.Relays.Relays)
1.  [function <span class="apidocSignatureSpan">johnny-five.Relays.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Relays.super_)

#### [module johnny-five.Relays.prototype](#apidoc.module.johnny-five.Relays.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Relays.prototype.</span>close ()](#apidoc.element.johnny-five.Relays.prototype.close)
1.  [function <span class="apidocSignatureSpan">johnny-five.Relays.prototype.</span>off ()](#apidoc.element.johnny-five.Relays.prototype.off)
1.  [function <span class="apidocSignatureSpan">johnny-five.Relays.prototype.</span>on ()](#apidoc.element.johnny-five.Relays.prototype.on)
1.  [function <span class="apidocSignatureSpan">johnny-five.Relays.prototype.</span>open ()](#apidoc.element.johnny-five.Relays.prototype.open)
1.  [function <span class="apidocSignatureSpan">johnny-five.Relays.prototype.</span>toggle ()](#apidoc.element.johnny-five.Relays.prototype.toggle)

#### [module johnny-five.Repl](#apidoc.module.johnny-five.Repl)
1.  boolean <span class="apidocSignatureSpan">johnny-five.Repl.</span>isActive
1.  boolean <span class="apidocSignatureSpan">johnny-five.Repl.</span>isBlocked
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Repl (opts)](#apidoc.element.johnny-five.Repl.Repl)
1.  [function <span class="apidocSignatureSpan">johnny-five.Repl.</span>super_ ()](#apidoc.element.johnny-five.Repl.super_)
1.  object <span class="apidocSignatureSpan">johnny-five.Repl.</span>ref

#### [module johnny-five.Repl.prototype](#apidoc.module.johnny-five.Repl.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Repl.prototype.</span>close ()](#apidoc.element.johnny-five.Repl.prototype.close)
1.  [function <span class="apidocSignatureSpan">johnny-five.Repl.prototype.</span>initialize (callback)](#apidoc.element.johnny-five.Repl.prototype.initialize)
1.  [function <span class="apidocSignatureSpan">johnny-five.Repl.prototype.</span>inject (obj)](#apidoc.element.johnny-five.Repl.prototype.inject)

#### [module johnny-five.Sensor](#apidoc.module.johnny-five.Sensor)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Sensor (opts)](#apidoc.element.johnny-five.Sensor.Sensor)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensor.</span>Analog (opts)](#apidoc.element.johnny-five.Sensor.Analog)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensor.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Sensor.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensor.</span>Digital (opts)](#apidoc.element.johnny-five.Sensor.Digital)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensor.</span>super_ ()](#apidoc.element.johnny-five.Sensor.super_)

#### [module johnny-five.Sensor.prototype](#apidoc.module.johnny-five.Sensor.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensor.prototype.</span>booleanAt (barrier)](#apidoc.element.johnny-five.Sensor.prototype.booleanAt)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensor.prototype.</span>disable ()](#apidoc.element.johnny-five.Sensor.prototype.disable)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensor.prototype.</span>enable ()](#apidoc.element.johnny-five.Sensor.prototype.enable)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensor.prototype.</span>fscaleTo (low, high)](#apidoc.element.johnny-five.Sensor.prototype.fscaleTo)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensor.prototype.</span>scale (low, high)](#apidoc.element.johnny-five.Sensor.prototype.scale)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensor.prototype.</span>scaleTo (low, high)](#apidoc.element.johnny-five.Sensor.prototype.scaleTo)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensor.prototype.</span>within (range, unit, callback)](#apidoc.element.johnny-five.Sensor.prototype.within)

#### [module johnny-five.Sensors](#apidoc.module.johnny-five.Sensors)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Sensors (numsOrObjects)](#apidoc.element.johnny-five.Sensors.Sensors)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensors.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Sensors.super_)

#### [module johnny-five.Sensors.prototype](#apidoc.module.johnny-five.Sensors.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensors.prototype.</span>booleanAt ()](#apidoc.element.johnny-five.Sensors.prototype.booleanAt)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensors.prototype.</span>disable ()](#apidoc.element.johnny-five.Sensors.prototype.disable)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensors.prototype.</span>enable ()](#apidoc.element.johnny-five.Sensors.prototype.enable)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensors.prototype.</span>fscaleTo ()](#apidoc.element.johnny-five.Sensors.prototype.fscaleTo)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensors.prototype.</span>scale ()](#apidoc.element.johnny-five.Sensors.prototype.scale)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensors.prototype.</span>scaleTo ()](#apidoc.element.johnny-five.Sensors.prototype.scaleTo)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sensors.prototype.</span>within ()](#apidoc.element.johnny-five.Sensors.prototype.within)

#### [module johnny-five.Servo](#apidoc.module.johnny-five.Servo)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Servo (opts)](#apidoc.element.johnny-five.Servo.Servo)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.</span>Array (numsOrObjects)](#apidoc.element.johnny-five.Servo.Array)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Servo.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.</span>Continuous (pinOrOpts)](#apidoc.element.johnny-five.Servo.Continuous)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.</span>super_ ()](#apidoc.element.johnny-five.Servo.super_)

#### [module johnny-five.Servo.prototype](#apidoc.module.johnny-five.Servo.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>ccw (rate)](#apidoc.element.johnny-five.Servo.prototype.ccw)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>center (time, rate)](#apidoc.element.johnny-five.Servo.prototype.center)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>clockWise (rate)](#apidoc.element.johnny-five.Servo.prototype.clockWise)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>counterClockwise (rate)](#apidoc.element.johnny-five.Servo.prototype.counterClockwise)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>cw (rate)](#apidoc.element.johnny-five.Servo.prototype.cw)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>home ()](#apidoc.element.johnny-five.Servo.prototype.home)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>max (time, rate)](#apidoc.element.johnny-five.Servo.prototype.max)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>min (time, rate)](#apidoc.element.johnny-five.Servo.prototype.min)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>move (degrees, time)](#apidoc.element.johnny-five.Servo.prototype.move)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>step (degrees, time)](#apidoc.element.johnny-five.Servo.prototype.step)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>stop ()](#apidoc.element.johnny-five.Servo.prototype.stop)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>sweep (opts)](#apidoc.element.johnny-five.Servo.prototype.sweep)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>to (degrees, time, rate)](#apidoc.element.johnny-five.Servo.prototype.to)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>write (degrees, time)](#apidoc.element.johnny-five.Servo.prototype.write)

#### [module johnny-five.Servos](#apidoc.module.johnny-five.Servos)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Servos (numsOrObjects)](#apidoc.element.johnny-five.Servos.Servos)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servos.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Servos.super_)

#### [module johnny-five.Servos.prototype](#apidoc.module.johnny-five.Servos.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>ccw ()](#apidoc.element.johnny-five.Servos.prototype.ccw)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>center ()](#apidoc.element.johnny-five.Servos.prototype.center)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>clockWise ()](#apidoc.element.johnny-five.Servos.prototype.clockWise)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>counterClockwise ()](#apidoc.element.johnny-five.Servos.prototype.counterClockwise)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>cw ()](#apidoc.element.johnny-five.Servos.prototype.cw)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>home ()](#apidoc.element.johnny-five.Servos.prototype.home)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>max ()](#apidoc.element.johnny-five.Servos.prototype.max)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>min ()](#apidoc.element.johnny-five.Servos.prototype.min)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>move ()](#apidoc.element.johnny-five.Servos.prototype.move)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>step ()](#apidoc.element.johnny-five.Servos.prototype.step)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>stop ()](#apidoc.element.johnny-five.Servos.prototype.stop)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>sweep ()](#apidoc.element.johnny-five.Servos.prototype.sweep)
1.  [function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>to ()](#apidoc.element.johnny-five.Servos.prototype.to)

#### [module johnny-five.ShiftRegister](#apidoc.module.johnny-five.ShiftRegister)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>ShiftRegister (opts)](#apidoc.element.johnny-five.ShiftRegister.ShiftRegister)
1.  [function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.ShiftRegister.Collection)

#### [module johnny-five.ShiftRegister.Collection](#apidoc.module.johnny-five.ShiftRegister.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.ShiftRegister.Collection.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.Collection.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.ShiftRegister.Collection.super_)

#### [module johnny-five.ShiftRegister.Collection.prototype](#apidoc.module.johnny-five.ShiftRegister.Collection.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.Collection.prototype.</span>clear ()](#apidoc.element.johnny-five.ShiftRegister.Collection.prototype.clear)
1.  [function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.Collection.prototype.</span>display ()](#apidoc.element.johnny-five.ShiftRegister.Collection.prototype.display)
1.  [function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.Collection.prototype.</span>reset ()](#apidoc.element.johnny-five.ShiftRegister.Collection.prototype.reset)
1.  [function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.Collection.prototype.</span>send ()](#apidoc.element.johnny-five.ShiftRegister.Collection.prototype.send)

#### [module johnny-five.ShiftRegister.prototype](#apidoc.module.johnny-five.ShiftRegister.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.prototype.</span>clear ()](#apidoc.element.johnny-five.ShiftRegister.prototype.clear)
1.  [function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.prototype.</span>display (value)](#apidoc.element.johnny-five.ShiftRegister.prototype.display)
1.  [function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.prototype.</span>reset ()](#apidoc.element.johnny-five.ShiftRegister.prototype.reset)
1.  [function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.prototype.</span>send (value)](#apidoc.element.johnny-five.ShiftRegister.prototype.send)

#### [module johnny-five.Sonar](#apidoc.module.johnny-five.Sonar)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Sonar (opts)](#apidoc.element.johnny-five.Sonar.Sonar)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sonar.</span>super_ ()](#apidoc.element.johnny-five.Sonar.super_)

#### [module johnny-five.Sonar.prototype](#apidoc.module.johnny-five.Sonar.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Sonar.prototype.</span>within (range, unit, callback)](#apidoc.element.johnny-five.Sonar.prototype.within)

#### [module johnny-five.Stepper](#apidoc.module.johnny-five.Stepper)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Stepper (opts)](#apidoc.element.johnny-five.Stepper.Stepper)

#### [module johnny-five.Stepper.prototype](#apidoc.module.johnny-five.Stepper.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>accel (value)](#apidoc.element.johnny-five.Stepper.prototype.accel)
1.  [function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>ccw ()](#apidoc.element.johnny-five.Stepper.prototype.ccw)
1.  [function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>cw ()](#apidoc.element.johnny-five.Stepper.prototype.cw)
1.  [function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>decel (value)](#apidoc.element.johnny-five.Stepper.prototype.decel)
1.  [function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>direction (value)](#apidoc.element.johnny-five.Stepper.prototype.direction)
1.  [function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>rpm (rpm)](#apidoc.element.johnny-five.Stepper.prototype.rpm)
1.  [function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>speed (speed)](#apidoc.element.johnny-five.Stepper.prototype.speed)
1.  [function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>step (stepsOrOpts, callback)](#apidoc.element.johnny-five.Stepper.prototype.step)

#### [module johnny-five.Switch](#apidoc.module.johnny-five.Switch)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Switch (opts)](#apidoc.element.johnny-five.Switch.Switch)
1.  [function <span class="apidocSignatureSpan">johnny-five.Switch.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Switch.Collection)
1.  [function <span class="apidocSignatureSpan">johnny-five.Switch.</span>super_ ()](#apidoc.element.johnny-five.Switch.super_)

#### [module johnny-five.Switches](#apidoc.module.johnny-five.Switches)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Switches (numsOrObjects)](#apidoc.element.johnny-five.Switches.Switches)
1.  [function <span class="apidocSignatureSpan">johnny-five.Switches.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Switches.super_)

#### [module johnny-five.Thermometer](#apidoc.module.johnny-five.Thermometer)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Thermometer (opts)](#apidoc.element.johnny-five.Thermometer.Thermometer)
1.  [function <span class="apidocSignatureSpan">johnny-five.Thermometer.</span>super_ ()](#apidoc.element.johnny-five.Thermometer.super_)
1.  object <span class="apidocSignatureSpan">johnny-five.Thermometer.</span>Drivers

#### [module johnny-five.Thermometer.Drivers](#apidoc.module.johnny-five.Thermometer.Drivers)
1.  [function <span class="apidocSignatureSpan">johnny-five.Thermometer.Drivers.</span>clear ()](#apidoc.element.johnny-five.Thermometer.Drivers.clear)
1.  [function <span class="apidocSignatureSpan">johnny-five.Thermometer.Drivers.</span>get (board, driverName, opts)](#apidoc.element.johnny-five.Thermometer.Drivers.get)
1.  object <span class="apidocSignatureSpan">johnny-five.Thermometer.Drivers.</span>DS18B20
1.  object <span class="apidocSignatureSpan">johnny-five.Thermometer.Drivers.</span>MAX31850K

#### [module johnny-five.Wii](#apidoc.module.johnny-five.Wii)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>Wii (opts)](#apidoc.element.johnny-five.Wii.Wii)
1.  [function <span class="apidocSignatureSpan">johnny-five.Wii.</span>Classic (opts)](#apidoc.element.johnny-five.Wii.Classic)
1.  [function <span class="apidocSignatureSpan">johnny-five.Wii.</span>Nunchuk (opts)](#apidoc.element.johnny-five.Wii.Nunchuk)
1.  [function <span class="apidocSignatureSpan">johnny-five.Wii.</span>super_ ()](#apidoc.element.johnny-five.Wii.super_)
1.  object <span class="apidocSignatureSpan">johnny-five.Wii.</span>Components

#### [module johnny-five.Wii.Components](#apidoc.module.johnny-five.Wii.Components)
1.  [function <span class="apidocSignatureSpan">johnny-five.Wii.Components.</span>Accelerometer (controller)](#apidoc.element.johnny-five.Wii.Components.Accelerometer)
1.  [function <span class="apidocSignatureSpan">johnny-five.Wii.Components.</span>Button (which, controller)](#apidoc.element.johnny-five.Wii.Components.Button)
1.  [function <span class="apidocSignatureSpan">johnny-five.Wii.Components.</span>Joystick (controller)](#apidoc.element.johnny-five.Wii.Components.Joystick)

#### [module johnny-five.evshield](#apidoc.module.johnny-five.evshield)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>evshield (options)](#apidoc.element.johnny-five.evshield.evshield)
1.  [function <span class="apidocSignatureSpan">johnny-five.evshield.</span>isRawSensor (port)](#apidoc.element.johnny-five.evshield.isRawSensor)
1.  [function <span class="apidocSignatureSpan">johnny-five.evshield.</span>shieldPort (pin)](#apidoc.element.johnny-five.evshield.shieldPort)
1.  [function <span class="apidocSignatureSpan">johnny-five.evshield.</span>super_ ()](#apidoc.element.johnny-five.evshield.super_)
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Analog_Bytes
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>BAM1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>BAM2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>BANK_A
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>BANK_B
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>BAS1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>BAS2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>BBM1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>BBM2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>BBS1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>BBS2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>BTN_PRESS
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Bump
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Bump_Bytes
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>CENTER_RGB_LED
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>CMD_A_M1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>CMD_A_M2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>CMD_B_M1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>CMD_B_M2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>COMMAND
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>CONTROL_BRK
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>CONTROL_GO
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>CONTROL_ON
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>CONTROL_RAMP
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>CONTROL_RELATIVE
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>CONTROL_SPEED
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>CONTROL_TACHO
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>CONTROL_TIME
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>ColorMeasure
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>ColorMeasure_Bytes
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>ENCODER_PID
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Light
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Light_Bytes
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>M1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>M2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>MM
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Mode
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Motor_1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Motor_2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Motor_Both
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Motor_Completion_Dont_Wait
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Motor_Completion_Wait_For
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Motor_Forward
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Motor_Move_Absolute
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Motor_Move_Relative
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Motor_Next_Action_Brake
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Motor_Next_Action_BrakeHold
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Motor_Next_Action_Float
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Motor_Reset
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Motor_Reverse
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Motor_Stop
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>PASS_COUNT
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>POSITION_M1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>POSITION_M2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Proximity
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Proximity_Bytes
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>RGB_LED
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>S1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>S1_ANALOG
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>S1_MODE
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>S1_OFFSET
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>S2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>S2_ANALOG
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>S2_MODE
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>S2_OFFSET
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>SETPT_M1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>SETPT_M2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>SPEED_M1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>SPEED_M2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>SPEED_PID
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>STATUS_BREAK
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>STATUS_M1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>STATUS_M2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>STATUS_MOVING
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>STATUS_OVERLOAD
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>STATUS_RAMP
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>STATUS_SPEED
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>STATUS_STALL
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>STATUS_TACHO
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>STATUS_TIME
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Speed_Full
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Speed_Medium
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Speed_Slow
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>TASKS_M1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>TASKS_M2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>TIME_M1
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>TIME_M2
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>TOLERANCE
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Touch
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Touch_Bytes
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_ANALOG
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_DATABIT0_HIGH
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_EV3
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_EV3_COLOR
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_EV3_COLOR_REFRAW
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_EV3_COLOR_RGBRAW
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_EV3_LIGHT
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_EV3_LIGHT_REFLECTED
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_EV3_TOUCH
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_I2C
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_NONE
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_NXT_COLOR
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_NXT_COLORBLUE
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_NXT_COLORGREEN
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_NXT_COLORNONE
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_NXT_COLORRED
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_NXT_COLOR_RGBRAW
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_NXT_LIGHT
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_NXT_LIGHT_REFLECTED
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Type_SWITCH
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>Ultrasonic
1.  number <span class="apidocSignatureSpan">johnny-five.evshield.</span>VOLTAGE

#### [module johnny-five.evshield.prototype](#apidoc.module.johnny-five.evshield.prototype)
1.  [function <span class="apidocSignatureSpan">johnny-five.evshield.prototype.</span>read (port, register, numBytes, callback)](#apidoc.element.johnny-five.evshield.prototype.read)
1.  [function <span class="apidocSignatureSpan">johnny-five.evshield.prototype.</span>setup (port, type)](#apidoc.element.johnny-five.evshield.prototype.setup)
1.  [function <span class="apidocSignatureSpan">johnny-five.evshield.prototype.</span>write (port, register, data)](#apidoc.element.johnny-five.evshield.prototype.write)

#### [module johnny-five.orientation](#apidoc.module.johnny-five.orientation)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>orientation (opts)](#apidoc.element.johnny-five.orientation.orientation)
1.  [function <span class="apidocSignatureSpan">johnny-five.orientation.</span>super_ ()](#apidoc.element.johnny-five.orientation.super_)

#### [module johnny-five.reflectancearray](#apidoc.module.johnny-five.reflectancearray)
1.  [function <span class="apidocSignatureSpan">johnny-five.</span>reflectancearray (opts)](#apidoc.element.johnny-five.reflectancearray.reflectancearray)
1.  [function <span class="apidocSignatureSpan">johnny-five.reflectancearray.</span>super_ ()](#apidoc.element.johnny-five.reflectancearray.super_)

#### [module johnny-five.sleep](#apidoc.module.johnny-five.sleep)
1.  [function <span class="apidocSignatureSpan">johnny-five.sleep.</span>nano (ns)](#apidoc.element.johnny-five.sleep.nano)



# <a name="apidoc.module.johnny-five"></a>[module johnny-five](#apidoc.module.johnny-five)

#### <a name="apidoc.element.johnny-five.Accelerometer"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Accelerometer (opts)](#apidoc.element.johnny-five.Accelerometer)
- description and source-code
```javascript
function Accelerometer(opts) {
  if (!(this instanceof Accelerometer)) {
    return new Accelerometer(opts);
  }

  var controller = null;

  var state = {
    enabled: true,
    x: {
      value: 0,
      previous: 0,
      stash: [],
      orientation: null,
      inclination: null,
      acceleration: null,
      calibration: []
    },
    y: {
      value: 0,
      previous: 0,
      stash: [],
      orientation: null,
      inclination: null,
      acceleration: null,
      calibration: []
    },
    z: {
      value: 0,
      previous: 0,
      stash: [],
      orientation: null,
      inclination: null,
      acceleration: null,
      calibration: []
    }
  };

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.ANALOG;
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toGravity) {
    this.toGravity = opts.toGravity || function(raw) {
      return raw;
    };
  }

  if (!this.enabledChanged) {
    this.enabledChanged = function() {};
  }

  priv.set(this, state);

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      var isChange = false;

      if (!state.enabled) {
        return;
      }

      Object.keys(data).forEach(function(axis) {
        var value = data[axis];
        var sensor = state[axis];

        if (opts.autoCalibrate && sensor.calibration.length < calibrationSize) {
          var axisIndex = axes.indexOf(axis);
          sensor.calibration.push(value);

          if (!Array.isArray(state.zeroV)) {
            state.zeroV = [];
          }

          state.zeroV[axisIndex] = sum(sensor.calibration) / sensor.calibration.length;
          if (axis === aZ) {
            state.zeroV[axisIndex] -= state.sensitivity;
          }
        }

        // The first run needs to prime the "stash"
        // of data values.
        if (sensor.stash.length === 0) {
          for (var i = 0; i < 5; i++) {
            sensor.stash[i] = value;
          }
        }

        sensor.previous = sensor.value;
        sensor.stash.shift();
        sensor.stash.push(value);

        sensor.value = (sum(sensor.stash) / 5) | 0;

        if (this.acceleration !== sensor.acceleration) {
          sensor.acceleration = this.acceleration;
          isChange = true;
          this.emit("acceleration", sensor.acceleration);
        }

        if (this.orientation !== sensor.orientation) {
          sensor.orientation = this.orientation;
          isChange = true;
          this.emit("orientation", sensor.orientation);
        }

        if (this.inclination !== sensor.inclination) {
          sensor.inclination = this.inclination;
          isChange = true;
          this.emit("inclination", sensor.inclination);
        }
      }, this);

      this.emit("data", {
        x: state.x.value,
        y: state.y.value,
        z: state.z.value
      });

      if (isChange) {
        this.emit("change", {
          x: this.x,
          y: this.y,
          z: this.z
        });
      }
    }.bind(this));
  }

  Object.defineProperties(this, {
    hasAxis: {
      writable: true,
      value: function(axis) {
        /* istanbul ignore next */
        return state[axis] ? state[axis].stash.length > 0 : false;
      }
    },
    enable: {
      value: function() {
        state.enabled = true;
        this.enabledChanged(true);
        return this;
      }
    },
    disable: {
      value: function() {
        state.enabled = false;
        this.enabledChanged(false);
        return this;
      }
    },
    zeroV: {
      get: function() {
        return state.zeroV;
      }
    },
    /**
     * [read-only] Calculated pitch value
     * @property pitch
     * @type Number
     */
    pitch: {
      get: function() {
        var x = this.x;
        var y = this.y;
        var z = this.z;
        var r ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Altimeter"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Altimeter (opts)](#apidoc.element.johnny-five.Altimeter)
- description and source-code
```javascript
function Altimeter(opts) {
  if (!(this instanceof Altimeter)) {
    return new Altimeter(opts);
  }

  var controller = null;
  var freq;
  var last = null;
  var raw = null;
  var state = {};

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  freq = opts.freq || 25;


  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    throw new Error("Altimeter expects a valid controller");
  }

  priv.set(this, state);

  Board.Controller.call(this, controller, opts);

  if (!this.toMeters) {
    this.toMeters = opts.toMeters || function(x) {
      return x;
    };
  }

  var descriptors = {
    meters: {
      get: function() {
        return this.toMeters(raw);
      }
    },
    feet: {
      get: function() {
        return Fn.toFixed(this.meters * 3.28084, 2);
      }
    }
  };
  // Convenience aliases
  descriptors.m = descriptors.meters;
  descriptors.ft = descriptors.feet;

  Object.defineProperties(this, descriptors);


<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw == null) {
      return;
    }

    var data = {};
    data.m = data.meters = this.meters;
    data.ft = data.feet = this.feet;

    this.emit("data", data);

    /* istanbul ignore else */
    if (this.meters !== last) {
      last = this.meters;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Analog"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Analog (opts)](#apidoc.element.johnny-five.Analog)
- description and source-code
```javascript
Analog = function (opts) {
  return new module.exports.Sensor(opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Animation (target)](#apidoc.element.johnny-five.Animation)
- description and source-code
```javascript
function Animation(target) {

  // Necessary to avoid loading temporal unless necessary
  if (!temporal) {
    temporal = require("temporal");
  }

  if (!(this instanceof Animation)) {
    return new Animation(target);
  }

  Animation.Segment.call(this);

  this.defaultTarget = target;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation.TemporalFallback"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Animation.TemporalFallback (animation)](#apidoc.element.johnny-five.Animation.TemporalFallback)
- description and source-code
```javascript
Animation.TemporalFallback = function (animation) {
  this.interval = setInterval(function() {
    animation.loopFunction({
      calledAt: Date.now()
    });
  }, animation.rate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Barometer"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Barometer (opts)](#apidoc.element.johnny-five.Barometer)
- description and source-code
```javascript
function Barometer(opts) {
  if (!(this instanceof Barometer)) {
    return new Barometer(opts);
  }

  var controller = null;
  var last = null;
  var raw = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var freq = opts.freq || 25;

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    // controller = Controllers["ANALOG"];
    throw new Error("Missing Barometer controller");
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toPressure) {
    this.toPressure = opts.toPressure || function(raw) {
      return raw;
    };
  }

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  Object.defineProperties(this, {
    pressure: {
      get: function() {
        return toFixed(this.toPressure(raw), 4);
      }
    }
  });

  setInterval(function() {
    if (raw === null) {
      return;
    }

    var data = {
      pressure: this.pressure
    };

    this.emit("data", data);

    if (this.pressure !== last) {
      last = this.pressure;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Board (opts)](#apidoc.element.johnny-five.Board)
- description and source-code
```javascript
function Board(opts) {

  if (!(this instanceof Board)) {
    return new Board(opts);
  }

  // Ensure opts is an object
  opts = opts || {};

  // Used to define the board instance's own
  // properties in the REPL's scope.
  var replContext = {};

  // It's feasible that an IO-Plugin may emit
  // "connect" and "ready" events out of order.
  // This is used to enforce the order, by
  // postponing the "ready" event if the IO-Plugin
  // hasn't emitted a "connect" event. Once
  // the "connect" event is emitted, the
  // postponement is lifted and the board may
  // proceed with emitting the events in the
  // correct order.
  var isPostponed = false;

  // Initialize this Board instance with
  // param specified properties.
  Object.assign(this, opts);

  this.timer = null;

  this.isConnected = false;

  // Easily track state of hardware
  this.isReady = false;

  // Initialize instance property to reference io board
  this.io = this.io || null;

  // Registry of components
  this.register = [];

  // Pins, Addr (alt Pin name), Addresses
  this.occupied = [];

  // Registry of drivers by address (i.e. I2C Controllers)
  this.Drivers = {};

  // Identify for connect hardware cache
  if (!this.id) {
    this.id = Fn.uid();
  }

  // If no debug flag, default to true
  if (typeof this.debug === UNDEFINED) {
    this.debug = true;
  }

  // If no repl flag, default to true
  if (typeof this.repl === UNDEFINED) {
    this.repl = true;
  }

  // If no sigint flag, default to true
  if (typeof this.sigint === UNDEFINED) {
    this.sigint = true;
  }

  // Specially processed pin capabilities object
  // assigned when physical board has reported
  // "ready" via Firmata or IO-Plugin.
  this.pins = null;

  // Create a Repl instance and store as
  // instance property of this io/board.
  // This will reduce the amount of boilerplate
  // code required to _always_ have a Repl
  // session available.
  //
  // If a sesssion exists, use it
  // (instead of creating a new session)
  //
<span class="apidocCodeCommentSpan">  /* istanbul ignore if */
</span>  if (this.repl) {
    /* istanbul ignore if */
    if (Repl.ref) {
      /* istanbul ignore next */
      replContext[this.id] = this;
      /* istanbul ignore next */
      Repl.ref.on("ready", function() {
        /* istanbul ignore next */
        Repl.ref.inject(replContext);
      });
      /* istanbul ignore next */
      this.repl = Repl.ref;
    } else {
      replContext[this.id] = replContext.board = this;
      this.repl = new Repl(replContext);
    }
  }

  if (opts.io) {
    // If you already have a connected io instance
    this.io = opts.io;
    this.isReady = opts.io.isReady;
    this.transport = this.io.transport || null;
    this.port = this.io.name;
    this.pins = Board.Pins(this);
  } else {

    if (this.port && opts.port) {
      Serial.connect.call(this, this.port, finalizeAndBroadcast);
    } else {
      Serial.detect.call(this, function(path) {
        Serial.connect.call(this, path, finalizeAndBroadcast);
      });
    }
  }

  // Either an IO instance was provided or isOnBoard is true
  if (!opts.port && this.io !== null) {
    /* istanbul ignore next */
    this.info("Device(s)", chalk.grey(this.io.name || "unknown"));

    ["connect", "ready"].forEach(function(type) {
      this.io.once(type, function() {
        // Since connection and readiness happen asynchronously,
        // it's actually possible for Johnny-Five to receive the
        // events out of order and that should be ok.
        if (type === "ready" && !this.isConnected) {
          isPostponed = true;
        } else {
          // Will emit the "connect" and "ready" events
          // if received in order. If out of order, this
          // will only emit the "connect" event. The
          // "ready" event will be handled in the next
          // condition's consequent.
          finalizeAndBroadcast.call(this, null, type, this.io);
        }

        if (type === "connect" && isPostponed) {
          finalizeAndBroadcast.call(this, null, "ready", this.io);
        }
      }.bind(this));

      if (this.io.isReady) { ...
```
- example usage
```shell
...

## Hello Johnny

The ubiquitous "Hello World" program of the microcontroller and SoC world is "blink an LED". The following code demonstrates how
 this is done using the Johnny-Five framework.

'''javascript
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
...
```

#### <a name="apidoc.element.johnny-five.Board.Component"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Board.Component (opts, componentOpts)](#apidoc.element.johnny-five.Board.Component)
- description and source-code
```javascript
Board.Component = function (opts, componentOpts) {
  if (typeof opts === UNDEFINED) {
    opts = {};
  }

  if (typeof componentOpts === UNDEFINED) {
    componentOpts = {};
  }

  // Board specific properties
  this.board = Board.mount(opts);
  this.io = this.board.io;

  // Component/Module instance properties
  this.id = opts.id || Board.uid();
  this.custom = opts.custom || {};

  var originalPins;

  if (typeof opts.pin === "number" || typeof opts.pin === "string") {
    originalPins = [opts.pin];
  } else {
    if (Array.isArray(opts.pins)) {
      originalPins = opts.pins.slice();
    } else {
      if (typeof opts.pins === "object" && opts.pins !== null) {

        var pinset = opts.pins || opts.pin;

        originalPins = [];
        for (var p in pinset) {
          originalPins.push(pinset[p]);
        }
      }
    }
  }


  if (opts.controller) {

    if (typeof opts.controller === "string") {
      opts.controller = opts.controller.replace(/-/g, "");
    }

    if (!Expander) {
      Expander = require("./expander");
    }

    if (Expander.hasController(opts.controller)) {
      componentOpts = {
        normalizePin: false,
        requestPin: false,
      };
    }
  }

  componentOpts = Board.Component.initialization(componentOpts);

  if (componentOpts.normalizePin) {
    opts = Board.Pins.normalize(opts, this.board);
  }

  // var requesting = [];

  if (typeof opts.pins !== UNDEFINED) {
    this.pins = opts.pins || [];

    // if (Array.isArray(this.pins)) {
    //   requesting = requesting.concat(
    //     this.pins.map(function(pin) {
    //       return {
    //         value: pin,
    //         type: "pin"
    //       };
    //     })
    //   );
    // } else {
    //   requesting = requesting.concat(
    //     Object.keys(this.pins).map(function(key) {
    //       return {
    //         value: this.pins[key],
    //         type: "pin"
    //       };
    //     }, this)
    //   );
    // }
  }

  if (typeof opts.pin !== UNDEFINED) {
    this.pin = opts.pin;
    // requesting.push({
    //   value: this.pin,
    //   type: "pin"
    // });
  }

  // TODO: Figure out what is using this
<span class="apidocCodeCommentSpan">  /* istanbul ignore if */
</span>  if (typeof opts.emitter !== UNDEFINED) {
    /* istanbul ignore next */
    this.emitter = opts.emitter;
    // requesting.push({
    //   value: this.emitter,
    //   type: "emitter"
    // });
  }

  if (typeof opts.address !== UNDEFINED) {
    this.address = opts.address;
    // requesting.forEach(function(request) {
    //   request.address = this.address;
    // }, this);
  }

  if (typeof opts.controller !== UNDEFINED) {
    this.controller = opts.controller;
    // requesting.forEach(function(request) {
    //   request.controller = this.controller;
    // }, this);
  }

  // TODO: Figure out what is using this
  /* istanbul ignore if */
  if (typeof opts.bus !== UNDEFINED) {
    /* istanbul ignore next */
    this.bus = opts.bus;
    // requesting.forEach(function(request) {
    //   request.bus = this.bus;
    // }, this);
  }

  // if (componentOpts.requestPin) {
  //   // With the pins being requested for use by this component,
  //   // compare with the list of pins that are already known to be
  //   // in use by other components. If any are known to be in use,
  //   // produce a warning for the user.
  //   requesting.forEach(function(request, index) {
  //     var hasController = typeof request.controller !== UNDEFINED;
  //     var hasAddress = typeof request.address !== UNDEFINED;
  //     var isOccupied = false;
  //     var message = "";

  //     request.value = originalPins[index];

  //     if (this.board.occupied.length) {
  //       isOccupied = this.board.occupied.some(function(occupied) {
  //         var isPinOccupied = request.value === occupied.value && request.type === occupied.type;

  //         if (typeof occupied.controller !== UNDEFINED) {
  //           if (hasController) {
  //             return isPinOccupied && (request.controller === occupied.controller);
  //           }
  //           return false;
  //         }

  //         if (typeof occupied.addre ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Pins"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Board.Pins (board)](#apidoc.element.johnny-five.Board.Pins)
- description and source-code
```javascript
function Pins(board) {
  if (!(this instanceof Pins)) {
    return new Pins(board);
  }

  var io = board.io;
  var pins = io.pins.slice();
  var length = pins.length;
  var type = pinsToType[length] || "OTHER";

  board.type = type;

  // Copy pin data to index
  for (var i = 0; i < length; i++) {
    this[i] = pins[i];
  }

  Object.defineProperties(this, {
    type: {
      value: type
    },
    length: {
      value: length
    }
  });

  // If an IO Plugin or Expander defines
  // these, override the default
  [
    "isInput",
    "isOutput",
    "isAnalog",
    "isPwm",
    "isServo",
  ].forEach(function(isType) {
    if (io[isType]) {
      this[isType] = io[isType];
    }
  }, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.range"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Board.range (lower, upper, tick)](#apidoc.element.johnny-five.Board.range)
- description and source-code
```javascript
Board.range = function (lower, upper, tick) {

  if (arguments.length === 1) {
    upper = lower - 1;
    lower = 0;
  }

  lower = lower || 0;
  upper = upper || 0;
  tick = tick || 1;

  var len = Math.max(Math.ceil((upper - lower) / tick), 0),
    idx = 0,
    range = [];

  while (idx <= len) {
    range[idx++] = lower;
    lower += tick;
  }

  return range;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Boards"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Boards (opts)](#apidoc.element.johnny-five.Boards)
- description and source-code
```javascript
function Boards(opts) {
  if (!(this instanceof Boards)) {
    return new Boards(opts);
  }

  var ports;

  // new Boards([ ...Array of board opts ])
  if (Array.isArray(opts)) {
    ports = opts.slice();
    opts = {
      ports: ports,
    };
  }

  // new Boards({ ports: [ ...Array of board opts ], .... })
<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (!Array.isArray(opts) && typeof opts === "object" && opts.ports !== undefined) {
    ports = opts.ports;
  }

  // new Boards(non-Array?)
  // new Boards({ ports: non-Array? })
  /* istanbul ignore if */
  if (!Array.isArray(ports)) {
    throw new Error("Expected ports to be an array");
  }

  if (typeof opts.debug === UNDEFINED) {
    opts.debug = true;
  }

  if (typeof opts.repl === UNDEFINED) {
    opts.repl = true;
  }

  var initialized = {};
  var noRepl = ports.some(function(port) { return port.repl === false; });
  var noDebug = ports.some(function(port) { return port.debug === false; });

  this.length = ports.length;
  this.debug = opts.debug;
  this.repl = opts.repl;

  // If any of the port definitions have
  // explicitly shut off debug output, bubble up
  // to the Boards instance
  /* istanbul ignore else */
  if (noDebug) {
    this.debug = false;
  }

  // If any of the port definitions have
  // explicitly shut off the repl, bubble up
  // to the Boards instance
  /* istanbul ignore else */
  if (noRepl) {
    this.repl = false;
  }

  var expecteds = ports.map(function(port, index) {
    var portOpts;

    if (typeof port === "string") {
      portOpts = {};

      // If the string matches a known valid port
      // name pattern, then assume this is what
      // the user code intended.
      if (rport.test(port)) {
        portOpts.port = port;
      } else {
        // Otherwise they expect Johnny-Five to figure
        // out what ports to use and intended this
        // value to be used an id
        portOpts.id = port;
      }
    } else {
      portOpts = port;
    }

    // Shut off per-board repl instance creation
    portOpts.repl = false;

    this[index] = initialized[portOpts.id] = new Board(portOpts);

    // "error" event is not async, register immediately
    this[index].on("error", function(error) {
      this.emit("error", error);
    }.bind(this));

    return new Promise(function(resolve) {
      this[index].on("ready", function() {
        resolve(initialized[portOpts.id]);
      });
    }.bind(this));
  }, this);

  Promise.all(expecteds).then(function(boards) {
    Object.assign(this, boards);

    this.each(function(board) {
      board.info("Board ID: ", chalk.green(board.id));
    });

    // If the Boards instance requires a REPL,
    // make sure it's created before calling "ready"
    if (this.repl) {
      this.repl = new Repl(
        Object.assign({}, initialized, {
          board: this
        })
      );
      this.repl.initialize(function() {
        this.emit("ready", initialized);
      }.bind(this));
    } else {
      // Otherwise, call ready immediately
      this.emit("ready", initialized);
    }
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Button"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Button (opts)](#apidoc.element.johnny-five.Button)
- description and source-code
```javascript
function Button(opts) {
  if (!(this instanceof Button)) {
    return new Button(opts);
  }

  var pinValue;
  var raw;
  var invert = false;
  var downValue = 1;
  var upValue = 0;
  var controller = null;
  var state = {
    interval: null,
    last: null
  };

  // Create a debounce boundary on event triggers
  // this avoids button events firing on
  // press noise and false positives
  var trigger = Fn.debounce(function(key) {
    aliases[key].forEach(function(type) {
      this.emit(type);
    }, this);
  }, 7);

  pinValue = typeof opts === "object" ? opts.pin : opts;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  opts.pinValue = pinValue;

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.DEFAULT;
  }

  Board.Controller.call(this, controller, opts);

  // 'holdtime' is used by an interval to determine
  // if the button has been released within a specified
  // time frame, in milliseconds.
  this.holdtime = opts.holdtime || 500;

  // 'opts.isPullup' is included as part of an effort to
  // phase out "isFoo" options properties
  this.pullup = opts.pullup || opts.isPullup || false;

  this.pulldown = opts.pulldown || opts.isPulldown || false;

  // Turns out some button circuits will send
  // 0 for up and 1 for down, and some the inverse,
  // so we can invert our function with this option.
  // Default to invert in pullup mode, but use opts.invert
  // if explicitly defined (even if false)
  invert = typeof opts.invert !== "undefined" ?
    opts.invert : (this.pullup || false);

  if (invert) {
    downValue = downValue ^ 1;
    upValue = upValue ^ 1;
  }

  state.last = upValue;

  // Create a "state" entry for privately
  // storing the state of the button
  priv.set(this, state);

  Object.defineProperties(this, {
    value: {
      get: function() {
        return Number(this.isDown);
      }
    },
    invert: {
      get: function() {
        return invert;
      },
      set: function(value) {
        invert = value;
        downValue = invert ? 0 : 1;
        upValue = invert ? 1 : 0;

        state.last = upValue;
      }
    },
    downValue: {
      get: function() {
        return downValue;
      },
      set: function(value) {
        downValue = value;
        upValue = value ^ 1;
        invert = value ? true : false;

        state.last = upValue;
      }
    },
    upValue: {
      get: function() {
        return upValue;
      },
      set: function(value) {
        upValue = value;
        downValue = value ^ 1;
        invert = value ? true : false;

        state.last = downValue;
      }
    },
    isDown: {
      get: function() {
        return this.toBoolean(raw);
      }
    }
  });

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      // Update the raw data value, which
      // is used by isDown = toBoolean()
      raw = data;

      if (!this.isDown) {
        /* istanbul ignore else */
        if (state.interval) {
          clearInterval(state.interval);
        }
        trigger.call(this, "up");
      }

      if (this.isDown) {
        trigger.call(this, "down");

        state.interval = setInterval(function() {
          /* istanbul ignore else */
          if (this.isDown) {
            this.emit("hold");
          }
        }.bind(this), this.holdtime);
      }

      state.last = data;
    }.bind(this));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Buttons"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Buttons (numsOrObjects)](#apidoc.element.johnny-five.Buttons)
- description and source-code
```javascript
function Buttons(numsOrObjects) {
  if (!(this instanceof Buttons)) {
    return new Buttons(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Button
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Buttons.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Buttons.super_ (numsOrObjects)](#apidoc.element.johnny-five.Buttons.super_)
- description and source-code
```javascript
Buttons.super_ = function (numsOrObjects) {

  // Create private state ahead of super call
  priv.set(this, {
    timing: {
      last: Date.now()
    }
  });

  Collection.call(this, numsOrObjects);

  // If the Collection.Emitter was created
  // with a Shared Properties object, then
  // we should abide by the freq or period
  // properties...
  var interval = null;
  var period = 5;

  if (!Array.isArray(numsOrObjects) &&
      (typeof numsOrObjects === "object" && numsOrObjects !== null))  {

    period = numsOrObjects.freq || numsOrObjects.period || period;

    // _However_, looking to the future, we
    // need to start thinking about replacing
    // the garbage named _freq_ (the value is
    // actually a period), with real _frequency_
    // in Hz.

    // If provided, convert frequency to period
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (numsOrObjects.frequency) {
      period = (1 / numsOrObjects.frequency) * 1000;
    }
  }

  Object.defineProperties(this, {
    period: {
      get: function() {
        return period;
      },
      set: function(value) {
        if (period !== value) {
          period = value;
        }

        if (interval) {
          clearInterval(interval);
        }

        interval = setInterval(function() {
          this.emit("data", this);
        }.bind(this), period);
      }
    },
  });

  this.period = period;

  this.on("newListener", function(event) {
    if (event === "change" || event === "data") {
      return;
    }

    this.forEach(function(input) {
      input.on(event, function(data) {
        this.emit(event, input, data);
      }.bind(this));
    }, this);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Collection)
- description and source-code
```javascript
function Collection(numsOrObjects) {
  var Type = this.type;
  var initObjects = [];

  this.length = 0;

  if (Array.isArray(numsOrObjects)) {
    initObjects = numsOrObjects;
  } else {
    // Initialize with a Shared Properties object
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (Array.isArray(numsOrObjects.pins)) {
      var keys = Object.keys(numsOrObjects).filter(function(key) {
        return key !== "pins";
      });
      initObjects = numsOrObjects.pins.map(function(pin) {
        var obj = {};

        if (Array.isArray(pin)) {
          obj.pins = pin;
        } else {
          obj.pin = pin;
        }

        return keys.reduce(function(accum, key) {
          accum[key] = numsOrObjects[key];
          return accum;
        }, obj);
      });
    }
  }

  /* istanbul ignore else */
  if (initObjects.length) {
    while (initObjects.length) {
      var numOrObject = initObjects.shift();

      // When a Type exists, respect it!
      if (typeof Type === "function") {
        if (!(numOrObject instanceof Type || numOrObject instanceof this.constructor)) {
          numOrObject = new Type(numOrObject);
        }
      }

      this.add(numOrObject);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Color"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Color (opts)](#apidoc.element.johnny-five.Color)
- description and source-code
```javascript
function Color(opts) {

  if (!(this instanceof Color)) {
    return new Color(opts);
  }

  var controller = null;
  var state = {};
  var freq = opts.freq || 25;
  var raw = 0;
  var last = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (typeof opts.controller === "string") {
    controller = Controllers[opts.controller];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    throw new Error("Color expects a valid controller");
  }

  priv.set(this, state);

  Board.Controller.call(this, controller, opts);

  if (!this.toRGB) {
    this.toRGB = opts.toRGB || function(x) {
      return x;
    };
  }

  Object.defineProperties(this, {
    value: {
      get: function() {
        return raw;
      }
    },
    rgb: {
      get: function() {
        return this.toRGB(raw).reduce(function(accum, value, index) {
          accum[colorNames[index]] = value;
          return accum;
        }, {});
      }
    }
  });

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw === undefined) {
      return;
    }

    var data = {
      rgb: this.rgb,
    };

    this.emit("data", data);

    if (raw !== last) {
      last = raw;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Compass"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Compass (opts)](#apidoc.element.johnny-five.Compass)
- description and source-code
```javascript
function Compass(opts) {

  if (!(this instanceof Compass)) {
    return new Compass(opts);
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var freq = opts.freq || 25;
  var controller = null;
  var raw = {
    x: null,
    y: null,
    z: null,
  };
  var state = {
    x: 0,
    y: 0,
    z: 0,
    scale: 0,
    register: 0,
    heading: 0
  };

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    throw new Error("Compass expects a valid controller");
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toScaledHeading) {
    this.toScaledHeading = opts.toScaledHeading || function(raw) {
      return raw;
    };
  }

  priv.set(this, state);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw.x === null) {
      return;
    }
    var isChange = false;

    state.x = raw.x;
    state.y = raw.y;
    state.z = raw.z;

    var heading = this.heading;

    if (heading !== state.heading) {
      state.heading = heading;
      isChange = true;
    }

    this.emit("data", {
      heading: state.heading
    });

    if (isChange) {
      this.emit("change", {
        heading: state.heading
      });
    }
  }.bind(this), freq);

  Object.defineProperties(this, {
<span class="apidocCodeCommentSpan">    /**
     * [read-only] Bearing information
     * @name bearing
     * @property
     * @type Object
     *
     *
        name
        abbr
        low
        mid
        high
        heading
     *
     */
</span>
    bearing: {
      get: function() {
        var length = Compass.Points.length;
        var heading = Math.floor(this.heading);
        var point;

        for (var i = 0; i < length; i++) {
          point = Compass.Points[i];

          if (point.range.includes(heading)) {
            // Specify fields to return to avoid returning the
            // range array (too much noisy data)
            return {
              name: point.name,
              abbr: point.abbr,
              low: point.low,
              high: point.high,
              heading: heading
            };
          }
        }
      }
    },

    /**
     * [read-only] Heading (azimuth)
     * @name heading
     * @property
     * @type number
     */
    heading: {
      get: function() {
        return this.toScaledHeading(raw);
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Digital"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Digital (opts)](#apidoc.element.johnny-five.Digital)
- description and source-code
```javascript
Digital = function (opts) {
  var pin;

  if (typeof opts === "number" || typeof opts === "string") {
    pin = opts;
    opts = {
      type: "digital",
      pin: pin
    };
  } else {
    opts.type = opts.type || "digital";
  }

  return new module.exports.Sensor(opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESC"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>ESC (opts)](#apidoc.element.johnny-five.ESC)
- description and source-code
```javascript
function ESC(opts) {
  if (!(this instanceof ESC)) {
    return new ESC(opts);
  }

  var controller = null;
  var pinValue;
  var device;
  var state = {
    // All speed history for this ESC
    // history = [
    //   {
    //     timestamp: Date.now(),
    //     speed: speed
    //   }
    // ];
    history: [],
    value: 0
  };

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  priv.set(this, state);

  this.startAt = typeof opts.startAt !== "undefined" ? opts.startAt : null;
  this.neutral = opts.neutral;
  this.range = opts.range || [0, 100];
  this.pwmRange = opts.pwmRange || [544, 2400];
  this.interval = null;

  // StandardFirmata on Arduino allows controlling
  // servos from analog pins.
  // If we're currently operating with an Arduino
  // and the user has provided an analog pin name
  // (eg. "A0", "A5" etc.), parse out the numeric
  // value and capture the fully qualified analog
  // pin number.
  if (typeof opts.controller === "undefined" && Pins.isFirmata(this)) {
    if (typeof pinValue === "string" && pinValue[0] === "A") {
      pinValue = this.io.analogPins[+pinValue.slice(1)];
    }

    pinValue = +pinValue;

    // If the board's default pin normalization
    // came up with something different, use the
    // the local value.
    if (!Number.isNaN(pinValue) && this.pin !== pinValue) {
      this.pin = pinValue;
    }
  }

  // Allow users to pass in custom device types
  device = typeof opts.device === "string" ?
    Devices[opts.device] : opts.device;

  if (!device) {
    device = Devices.FORWARD;
  }

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (!controller) {
    controller = Controllers.DEFAULT;
  }

  Object.defineProperties(this, Object.assign({}, device, controller, {
    value: {
      get: function() {
        return state.value;
      }
    },
    history: {
      get: function() {
        return state.history.slice(-5);
      }
    },
    last: {
      get: function() {
        return state.history[state.history.length - 1] || {
          last: null
        };
      }
    }
  }));

  this.initialize(opts);

  if (this.deviceName !== "FORWARD") {
    if (Number.isNaN(+this.neutral)) {
      throw new Error("Directional speed controllers require a neutral point from 0-100 (number)");
    }

    this.startAt = this.neutral;
  }

  // Match either null or undefined, but not 0
  if (this.startAt !== null && this.startAt !== undefined) {
    this.speed(this.startAt);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESCs"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>ESCs (numsOrObjects)](#apidoc.element.johnny-five.ESCs)
- description and source-code
```javascript
function ESCs(numsOrObjects) {
  if (!(this instanceof ESCs)) {
    return new ESCs(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: ESC
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Expander"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Expander (opts)](#apidoc.element.johnny-five.Expander)
- description and source-code
```javascript
function Expander(opts) {
  if (!(this instanceof Expander)) {
    return new Expander(opts);
  }

  Base.call(this);

  var expander = null;
  var addressError = "Expander cannot reuse an active address";
  var controller = null;
  var state = {};
  var controllerValue;

  if (typeof opts === "string") {
    controllerValue = opts;
  }

  Board.Component.call(
    this, opts = Board.Options(opts), {
      normalizePin: false,
      requestPin: false
    }
  );

  expander = active.get(this.address);

  if (expander) {
    if (this.bus && (expander.bus !== undefined && expander.bus === this.bus)) {
      addressError += " on this bus";
    }
    throw new Error(addressError);
  }

  if (typeof opts.controller === "undefined" && controllerValue) {
    opts.controller = controllerValue;
  }

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    throw new Error("Expander expects a valid controller");
  }

  Board.Controller.call(this, controller, opts);

  priv.set(this, state);

  if (typeof this.initialize === "function") {
    this.initialize(opts);
  }

  active.set(this.address, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Expander.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Expander.super_ ()](#apidoc.element.johnny-five.Expander.super_)
- description and source-code
```javascript
function Base() {
  Emitter.call(this);

  this.HIGH = 1;
  this.LOW = 0;
  this.isReady = false;

  this.MODES = {};
  this.pins = [];
  this.analogPins = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.GPS"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>GPS (opts)](#apidoc.element.johnny-five.GPS)
- description and source-code
```javascript
function GPS(opts) {

  var breakout, receiver, chip, state;

  if (!(this instanceof GPS)) {
    return new GPS(opts);
  }

  // Allow users to pass in a 2 element array for rx and tx pins
  if (Array.isArray(opts)) {
    opts = {
      pins: {
        rx: opts[0],
        tx: opts[1],
        onOff: opts[2]
      }
    };
  }

  if (typeof opts.pins === "undefined") {
    opts.pins = {};
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );



  // Get user values for breakout, receiver and chip
  breakout = opts.breakout || {};
  receiver = opts.receiver;
  chip = opts.chip;

  // If a breakout is defined check for receiver and chip
  if (Breakouts[breakout]) {
    if (!receiver && Breakouts[breakout].receiver) {
      receiver = Breakouts[breakout].receiver.value;
    }

    if (!chip && Breakouts[breakout].chip) {
      chip = Breakouts[breakout].chip.value;
    }
  }

  // If a receiver was defined or derived but chip was not
  if (!chip) {
    if (receiver && Receivers[receiver].chip) {
      chip = Receivers[receiver].chip.value;
    } else {
      chip = "DEFAULT";
    }
  }

  // Allow users to pass in custom chip types
  chip = typeof chip === "string" ?
    Chips[chip] : opts.chip;

  // Allow users to pass in custom receiver types
  receiver = typeof receiver === "string" ?
    Receivers[receiver] : opts.receiver;

  // Chip decorates the instance
  Object.defineProperties(this, chip);

  // Receiver decorates this instance
  if (receiver) {
    Object.defineProperties(this, receiver);
  }

  // breakout decorates the instance
  if (opts.breakout) {
    breakout = typeof opts.breakout === "string" ?
      Breakouts[opts.breakout] : opts.breakout;

    Board.Controller.call(this, breakout, opts);
  }

  // If necessary set default property values
  this.fixed = opts.fixed || 6;
  this.baud = opts.baud || this.baud;

  // Create a "state" entry for privately
  // storing the state of the instance
  state = {
    sat: {},
    latitude: 0.0,
    longitude: 0.0,
    altitude: 0.0,
    speed: 0.0,
    course: 0.0,
    frequency: 1,
    lowPowerMode: false
  };

  priv.set(this, state);

  // Getters for private state values
  Object.defineProperties(this, {
    latitude: {
      get: function() {
        return state.latitude;
      }
    },
    longitude: {
      get: function() {
        return state.longitude;
      }
    },
    altitude: {
      get: function() {
        return state.altitude;
      }
    },
    sat: {
      get: function() {
        return state.sat;
      }
    },
    speed: {
      get: function() {
        return state.speed;
      }
    },
    course: {
      get: function() {
        return state.course;
      }
    },
    time: {
      get: function() {
        return state.time;
      }
    }
  });

  if (this.initialize) {
    this.initialize(opts);
  }

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Gripper"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Gripper (opts)](#apidoc.element.johnny-five.Gripper)
- description and source-code
```javascript
function Gripper(opts) {

  if (!(this instanceof Gripper)) {
    return new Gripper(opts);
  }

  // Default options mode, assume only when opts is a pin number
  if (typeof opts === "number") {
    opts = {
      servo: {
        pin: opts,
        range: [0, 180]
      },
      scale: [0, 10]
    };
  }

  // Default set() args to 0-10
  this.scale = opts.scale || [0, 10];

  // Setup servo
  // Allows pre-constructed servo or creating new servo.
  // Defaults for new Servo creation fall back to Servo defaults
  this.servo = opts.servo instanceof Servo ?
    opts.servo : new Servo(opts.servo);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Gyro"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Gyro (opts)](#apidoc.element.johnny-five.Gyro)
- description and source-code
```javascript
function Gyro(opts) {
  if (!(this instanceof Gyro)) {
    return new Gyro(opts);
  }

  var controller = null;
  var isCalibrated = false;
  var sampleSize = 100;

  var state = {
    x: {
      angle: 0,
      value: 0,
      previous: 0,
      calibration: [],
      stash: [0, 0, 0, 0, 0],
      center: 0,
      hasValue: false
    },
    y: {
      angle: 0,
      value: 0,
      previous: 0,
      calibration: [],
      stash: [0, 0, 0, 0, 0],
      center: 0,
      hasValue: false
    },
    z: {
      angle: 0,
      value: 0,
      previous: 0,
      calibration: [],
      stash: [0, 0, 0, 0, 0],
      center: 0,
      hasValue: false
    }
  };

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.ANALOG;
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toNormal) {
    this.toNormal = opts.toNormal || function(raw) {
      return raw;
    };
  }

  if (!this.toDegreesPerSecond) {
    this.toDegreesPerSecond = opts.toDegreesPerSecond || function(raw) {
      return raw;
    };
  }

  priv.set(this, state);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      var isChange = false;

      Object.keys(data).forEach(function(axis) {
        var value = data[axis];
        var sensor = state[axis];

        sensor.previous = sensor.value;
        sensor.stash.shift();
        sensor.stash.push(value);
        sensor.hasValue = true;
        sensor.value = (sum(sensor.stash) / 5) | 0;

        if (!isCalibrated &&
          (state.x.calibration.length === sampleSize &&
            state.y.calibration.length === sampleSize &&
            (this.z === undefined || state.z.calibration.length === sampleSize))) {

          isCalibrated = true;
          state.x.center = (sum(state.x.calibration) / sampleSize) | 0;
          state.y.center = (sum(state.y.calibration) / sampleSize) | 0;
          state.z.center = (sum(state.z.calibration) / sampleSize) | 0;

          state.x.calibration.length = 0;
          state.y.calibration.length = 0;
          state.z.calibration.length = 0;
        } else {
          if (sensor.calibration.length < sampleSize) {
            sensor.calibration.push(value);
          }
        }

        if (sensor.previous !== sensor.value) {
          isChange = true;
        }
      }, this);

      if (isCalibrated) {
        state.x.angle += this.rate.x / 100;
        state.y.angle += this.rate.y / 100;
        state.z.angle += this.rate.z / 100;

        this.emit("data", {
          x: this.x,
          y: this.y,
          z: this.z
        });

        if (isChange) {
          this.emit("change", {
            x: this.x,
            y: this.y,
            z: this.z
          });
        }
      }
    }.bind(this));
  }

  Object.defineProperties(this, {
    isCalibrated: {
      get: function() {
        return isCalibrated;
      },
      set: function(value) {
        if (typeof value === "boolean") {
          isCalibrated = value;
        }
      }
    },
    pitch: {
      get: function() {
        return {
          rate: toFixed(this.rate.y, 2),
          angle: toFixed(state.y.angle, 2)
        };
      }
    },
    roll: {
      get: function() {
        return {
          rate: toFixed(this.rate.x, 2),
          angle: toFixed(state.x.angle, 2)
        };
      }
    },
    yaw: {
      get: function() {
        return {
          rate: this.z !== undefined ? toFixed(this.rate.z, 2) : 0,
          angle: this.z !== undefined ? toFixed(state.z.angle, 2) : 0
        };
      }
    },
    x: {
      get: function() {
        return toFixed(this.toNormal(state.x.value), 4);
      }
    },
    y: {
      get: function() {
        return toFixed(this.toNormal(state.y.value), 4);
      }
    },
    z: {
      get: function() {
        return state.z.hasValue ? toFixed(this.toNormal(state. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Hygrometer"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Hygrometer (opts)](#apidoc.element.johnny-five.Hygrometer)
- description and source-code
```javascript
function Hygrometer(opts) {
  if (!(this instanceof Hygrometer)) {
    return new Hygrometer(opts);
  }

  var controller = null;
  var last = null;
  var raw = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var freq = opts.freq || 25;

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    throw new Error("Missing Hygrometer controller");
  }

  priv.set(this, {});

  Board.Controller.call(this, controller, opts);

  if (!this.toRelativeHumidity) {
    this.toRelativeHumidity = opts.toRelativeHumidity || function(x) {
      return x;
    };
  }

  var propDescriptors = {
    relativeHumidity: {
      get: function() {
        return this.toRelativeHumidity(raw);
      }
    }
  };
  // Convenience aliases
  propDescriptors.RH = propDescriptors.relativeHumidity;

  Object.defineProperties(this, propDescriptors);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw == null) {
      return;
    }

    if (Number.isNaN(this.relativeHumidity)) {
      return;
    }

    var data = {};
    data.RH = data.relativeHumidity = this.relativeHumidity;

    this.emit("data", data);

    if (this.relativeHumidity !== last) {
      last = this.relativeHumidity;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.IMU"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>IMU (opts)](#apidoc.element.johnny-five.IMU)
- description and source-code
```javascript
function IMU(opts) {

  if (!(this instanceof IMU)) {
    return new IMU(opts);
  }

  var controller, state;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    throw new Error("Missing IMU/Multi controller");
  }

  this.freq = opts.freq || 20;

  state = {};
  priv.set(this, state);

  Board.Controller.call(this, controller, opts);

  if (typeof this.initialize === "function") {
    this.initialize(opts);
  }

  // The IMU/Multi isn't considered "ready"
  // until one of the components has notified via
  // a change event.
  this.isReady = false;

  setInterval(function() {
    if (this.isReady) {
      this.emit("data", this);
    }
  }.bind(this), this.freq);

  var awaiting = this.components.slice();

  if (this.components && this.components.length > 0) {
    this.components.forEach(function(component) {
      if (!(this[component] instanceof Emitter)) {
        return;
      }

      this[component].on("change", function() {
        if (awaiting.length) {
          var index = awaiting.indexOf(component);

          if (index !== -1) {
            awaiting.splice(index, 1);
          }
        }

        if (!awaiting.length && !this.isReady) {
          this.isReady = true;
        }

        if (this.isReady) {
          this.emit("change", this, component);
        }
      }.bind(this));
    }, this);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.IR"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>IR ()](#apidoc.element.johnny-five.IR)
- description and source-code
```javascript
IR = function () {
  throw new Error("IR has been removed. Use Motion or Proximity instead.");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Joystick"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Joystick (opts)](#apidoc.element.johnny-five.Joystick)
- description and source-code
```javascript
function Joystick(opts) {
  if (!(this instanceof Joystick)) {
    return new Joystick(opts);
  }

  var controller = null;

  var state = {
    x: {
      invert: false,
      value: 0,
      previous: 0,
      zeroV: 0,
      calibrated: false
    },
    y: {
      invert: false,
      value: 0,
      previous: 0,
      zeroV: 0,
      calibrated: false
    }
  };

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.ANALOG;
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toAxis) {
    this.toAxis = opts.toAxis || function(raw) {
      return raw;
    };
  }

  state.x.zeroV = opts.zeroV === undefined ? 0 : (opts.zeroV.x || 0);
  state.y.zeroV = opts.zeroV === undefined ? 0 : (opts.zeroV.y || 0);

  state.x.invert = opts.invertX || opts.invert || false;
  state.y.invert = opts.invertY || opts.invert || false;

  priv.set(this, state);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      var isChange = false;
      var computed = {
        x: null,
        y: null
      };

      Object.keys(data).forEach(function(axis) {
        var value = data[axis];
        var sensor = state[axis];

        // Set the internal ADC reading value...
        sensor.value = value;

        if (!state[axis].calibrated) {
          state[axis].calibrated = true;
          state[axis].zeroV = value;
          isChange = true;
        }

        // ... Get the computed axis value.
        computed[axis] = this[axis];

        var absAxis = Math.abs(computed[axis]);
        var absPAxis = Math.abs(sensor.previous);

        if ((absAxis < absPAxis) ||
          (absAxis > absPAxis)) {
          isChange = true;
        }

        sensor.previous = computed[axis];
      }, this);

      this.emit("data", {
        x: computed.x,
        y: computed.y
      });

      if (isChange) {
        this.emit("change", {
          x: computed.x,
          y: computed.y
        });
      }
    }.bind(this));
  }

  Object.defineProperties(this, {
    x: {
      get: function() {
        return this.toAxis(state.x.value, "x") * (state.x.invert ? -1 : 1);
      }
    },
    y: {
      get: function() {
        return this.toAxis(state.y.value, "y") * (state.y.invert ? -1 : 1);
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Keypad"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Keypad (opts)](#apidoc.element.johnny-five.Keypad)
- description and source-code
```javascript
function Keypad(opts) {

  if (!(this instanceof Keypad)) {
    return new Keypad(opts);
  }

  // Initialize a Device instance on a Board
  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var raw = null;
  var controller = null;
  var state = {
    touches: null,
    timeout: null,
    length: null,
    keys: null,
    mapping: null,
    holdtime: null,
  };

  var trigger = Fn.debounce(function(type, value) {
    var event = {
      type: type,
      which: value,
      timestamp: Date.now()
    };
    aliases[type].forEach(function(type) {
      this.emit(type, event);
    }, this);

    this.emit("change", Object.assign({}, event));
  }, 5);


  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.ANALOG;
  }

  Board.Controller.call(this, controller, opts);

  state.holdtime = opts.holdtime ? opts.holdtime : 500;

  priv.set(this, state);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {

      raw = data;

      var now = Date.now();
      var indices = this.toIndices(data);
      var kLength = state.length;

      var lists = {
        down: [],
        hold: [],
        up: [],
      };

      var target = null;
      var alias = null;

      for (var k = 0; k < kLength; k++) {
        alias = this.toAlias(k);

        if (indices.includes(k)) {
          if (state.touches[k].value === 0) {

            state.touches[k].timeout = now + state.holdtime;
            lists.down.push(alias);

          } else if (state.touches[k].value === 1) {
            if (state.touches[k].timeout !== null && now > state.touches[k].timeout) {
              state.touches[k].timeout = now + state.holdtime;
              lists.hold.push(alias);
            }
          }

          state.touches[k].value = 1;
        } else {
          if (state.touches[k].value === 1) {
            state.touches[k].timeout = null;
            lists.up.push(alias);
          }
          state.touches[k].value = 0;
        }
        target = null;
        alias = null;
      }

      Object.keys(lists).forEach(function(key) {
        var list = lists[key];

        if (list.length) {
          trigger.call(this, key, list);
        }
      }, this);
    }.bind(this));
  }

  Object.defineProperties(this, {
    isMultitouch: {
      get: function() {
        return state.isMultitouch;
      }
    },
    value: {
      get: function() {
        return raw;
      }
    },
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>LCD (opts)](#apidoc.element.johnny-five.LCD)
- description and source-code
```javascript
function LCD(opts) {

  if (!(this instanceof LCD)) {
    return new LCD(opts);
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var controller = null;

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.PARALLEL;
  }

  Board.Controller.call(this, controller, opts);

  this.ctype = opts.controller;

  if (this.initialize) {
    this.initialize(opts);
  }

  Object.defineProperties(this, {
    characters: {
      get: function() {
        return Object.assign({}, priv.get(this).characters);
      },
    },
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Led (opts)](#apidoc.element.johnny-five.Led)
- description and source-code
```javascript
function Led(opts) {
  if (!(this instanceof Led)) {
    return new Led(opts);
  }

  var pinValue = typeof opts === "object" ? opts.pin : opts;
  var controller = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.DEFAULT;
  }

  Object.defineProperties(this, controller);

  var state = {
    isAnode: opts.isAnode,
    isOn: false,
    isRunning: false,
    value: null,
    direction: 1,
    mode: null,
    intensity: 0,
    interval: null
  };

  priv.set(this, state);

  Object.defineProperties(this, {
    value: {
      get: function() {
        return state.value;
      }
    },
    mode: {
      get: function() {
        return state.mode;
      }
    },
    isOn: {
      get: function() {
        return !!state.value;
      }
    },
    isRunning: {
      get: function() {
        return state.isRunning;
      }
    },
    animation: {
      get: function() {
        return state.animation;
      }
    }
  });

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (typeof this.initialize === "function") {
    this.initialize(opts, pinValue);
  }
}
```
- example usage
```shell
...

'''javascript
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''

<img src="https://github.com/rwaldron/johnny-five/raw/master/assets/led-blink.gif">
...
```

#### <a name="apidoc.element.johnny-five.Led.RGB"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Led.RGB (opts)](#apidoc.element.johnny-five.Led.RGB)
- description and source-code
```javascript
function RGB(opts) {
  if (!(this instanceof RGB)) {
    return new RGB(opts);
  }

  var controller = null;

  if (Array.isArray(opts)) {
    // RGB([Byte, Byte, Byte]) shorthand
    // Convert to opts.pins array definition
    opts = {
      pins: opts
    };
    // If opts.pins is an object, convert to array
  } else if (typeof opts.pins === "object" && !Array.isArray(opts.pins)) {
    opts.pins = [opts.pins.red, opts.pins.green, opts.pins.blue];
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.DEFAULT;
  }


  // The default color is #ffffff, but the light will be off
  var state = {
    red: 255,
    green: 255,
    blue: 255,
    intensity: 100,
    isAnode: opts.isAnode || false,
    interval: null
  };

  // red, green, and blue store the raw color set via .color()
  // values takes state into account, such as on/off and intensity
  state.values = {
    red: state.red,
    green: state.green,
    blue: state.blue
  };

  priv.set(this, state);

  Board.Controller.call(this, controller, opts);

  Object.defineProperties(this, {
    isOn: {
      get: function() {
        return RGB.colors.some(function(color) {
          return state[color] > 0;
        });
      }
    },
    isRunning: {
      get: function() {
        return !!state.interval;
      }
    },
    isAnode: {
      get: function() {
        return state.isAnode;
      }
    },
    values: {
      get: function() {
        return Object.assign({}, state.values);
      }
    },
    update: {
      value: function(colors) {
        var state = priv.get(this);

        colors = colors || this.color();

        state.values = RGB.ToScaledRGB(state.intensity, colors);

        this.write(state.values);

        Object.assign(state, colors);
      }
    }
  });

  this.initialize(opts);
  this.off();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGBs"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Led.RGBs (numsOrObjects)](#apidoc.element.johnny-five.Led.RGBs)
- description and source-code
```javascript
function RGBs(numsOrObjects) {
  if (!(this instanceof RGBs)) {
    return new RGBs(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: RGB
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LedControl"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>LedControl (opts)](#apidoc.element.johnny-five.LedControl)
- description and source-code
```javascript
function LedControl(opts) {

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

<span class="apidocCodeCommentSpan">  /*
   device instance uses an interface from Controllers:
   either MAX 7219 (default) or HT16K33
   */
</span>  var controller = null;

  if (typeof opts.controller === "string") {
    controller = Controllers[opts.controller];
  } else {
    controller = opts.controller;
  }

  if (typeof controller === "undefined") {
    controller = Controllers.DEFAULT;
  }

  // functions from Controller interface

  this.clear = controller.clear;
  this.led = controller.led;
  this.row = controller.row;
  this.scanLimit = controller.scanLimit;
  this.send = controller.send;
  this.sendDigit = controller.sendDigit;
  this.initialize = controller.initialize;

  // controller specific op codes
  this.OP = controller.OP;

  // digit indexes may be ordered left to right (1) or reversed (-1)
  this.digitOrder = 1;

  // Does the device have a built-in colon?
  /* istanbul ignore else */
  if (!this.isMatrix) {
    this.colon = opts.colon || false;
  }

  // extra functions for HT16K33 devices only
  if (controller.writeDisplay) {
    this.writeDisplay = controller.writeDisplay;
  }
  if (controller.blink) {
    this.blink = controller.blink;
  }
  /*
    devices variable indicates number of connected LED devices
    Here's an example of multiple devices:
    http://tronixstuff.com/2013/10/11/tutorial-arduino-max7219-led-display-driver-ic/
   */
  var devices = opts.devices || (opts.addresses ? opts.addresses.length : 1);

  this.memory = Array(64).fill(0);

  opts.dims = opts.dims || LedControl.MATRIX_DIMENSIONS["8x8"];
  if (typeof opts.dims === "string") {
    opts.dims = LedControl.MATRIX_DIMENSIONS[opts.dims];
  }
  if (Array.isArray(opts.dims)) {
    opts.dims = {
      rows: opts.dims[0],
      columns: opts.dims[1],
    };
  }
  var state = {
    devices: devices,
    digits: opts.digits || 8,
    isMatrix: !!opts.isMatrix,
    isBicolor: !!opts.isBicolor,
    rows: opts.dims.rows,
    columns: opts.dims.columns
  };

  if (!(state.columns === 8 || state.columns === 16) || !(state.rows === 8 || state.rows === 16) || (state.columns + state.rows ===
32)) {
    throw new Error("Invalid matrix dimensions specified: must be 8x8, 16x8 or 8x16");
  }

  Object.defineProperties(this, {
    devices: {
      get: function() {
        return state.devices;
      }
    },
    digits: {
      get: function() {
        return state.digits;
      }
    },
    isMatrix: {
      get: function() {
        return state.isMatrix;
      }
    },
    isBicolor: {
      get: function() {
        return state.isBicolor;
      }
    },
    rows: {
      get: function() {
        return state.rows;
      }
    },
    columns: {
      get: function() {
        return state.columns;
      }
    }
  });

  priv.set(this, state);
  controller.initialize.call(this, opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Leds"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Leds (numsOrObjects)](#apidoc.element.johnny-five.Leds)
- description and source-code
```javascript
function Leds(numsOrObjects) {
  if (!(this instanceof Leds)) {
    return new Leds(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Led
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Light"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Light (opts)](#apidoc.element.johnny-five.Light)
- description and source-code
```javascript
function Light(opts) {

  if (!(this instanceof Light)) {
    return new Light(opts);
  }

  var controller = null;
  var state = {};
  var raw = 0;
  var last = 0;
  var freq = opts.freq || 25;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (typeof opts.controller === "string") {
    controller = Controllers[opts.controller];
  } else {
    controller = opts.controller || Controllers.DEFAULT;
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toIntensityLevel) {
    this.toIntensityLevel = opts.toIntensityLevel || function(x) {
      return x;
    };
  }

  if (!this.toLux) {
    this.toLux = opts.toLux || function(x) {
      return x;
    };
  }

  Object.defineProperties(this, {
    value: {
      get: function() {
        return raw;
      },
    },
    level: {
      get: function() {
        return this.toIntensityLevel(raw);
      },
    },
  });

  priv.set(this, state);

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  if (typeof this.lux === "undefined") {
    Object.defineProperty(this, "lux", {
      get: function() {
        return this.toLux(raw);
      },
    });
  }

  var data = {
    level: 0,
    lux: 0,
  };

  setInterval(function() {
    data.level = this.level;
    data.lux = this.lux;

    this.emit("data", data);

    if (raw !== last) {
      last = raw;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Luxmeter"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Luxmeter (options)](#apidoc.element.johnny-five.Luxmeter)
- description and source-code
```javascript
Luxmeter = function (options) {
  return new module.exports.Light(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Magnetometer"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Magnetometer (options)](#apidoc.element.johnny-five.Magnetometer)
- description and source-code
```javascript
Magnetometer = function (options) {
  return new module.exports.Compass(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motion"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Motion (opts)](#apidoc.element.johnny-five.Motion)
- description and source-code
```javascript
function Motion(opts) {

  if (!(this instanceof Motion)) {
    return new Motion(opts);
  }

  var freq = opts.freq || 25;
  var last = false;
  var controller;
  var state;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (typeof opts.controller === "string") {
    controller = Controllers[opts.controller];
  } else {
    controller = opts.controller || Controllers["PIR"];
  }

  Board.Controller.call(this, controller, opts);

  state = {
    value: false,
    isCalibrated: false
  };

  priv.set(this, state);

  Object.defineProperties(this, {
<span class="apidocCodeCommentSpan">    /**
     * [read-only] Current sensor state
     * @property detectedMotion
     * @type Boolean
     */
</span>    detectedMotion: {
      get: function() {
        return this.toBoolean(state.value);
      }
    },
    /**
     * [read-only] Sensor calibration status
     * @property isCalibrated
     * @type Boolean
     */
    isCalibrated: {
      get: function() {
        return state.isCalibrated;
      }
    },
  });

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      state.value = data;
    });
  }

  setInterval(function() {
    var isChange = false;
    var eventData = {
      timestamp: Date.now(),
      detectedMotion: this.detectedMotion,
      isCalibrated: state.isCalibrated
    };

    if (state.isCalibrated && this.detectedMotion && !last) {
      this.emit("motionstart", eventData);
    }

    if (state.isCalibrated && !this.detectedMotion && last) {
      this.emit("motionend", eventData);
    }

    if (last !== this.detectedMotion) {
      isChange = true;
    }

    this.emit("data", eventData);

    if (isChange) {
      this.emit("change", eventData);
    }

    last = this.detectedMotion;
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motion.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Motion.Collection (numsOrObjects)](#apidoc.element.johnny-five.Motion.Collection)
- description and source-code
```javascript
Motion.Collection = function (numsOrObjects) {
  if (!(this instanceof Motion.Collection)) {
    return new Motion.Collection(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Motion
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Motor (opts)](#apidoc.element.johnny-five.Motor)
- description and source-code
```javascript
function Motor(opts) {

  var device, controller, state;

  if (!(this instanceof Motor)) {
    return new Motor(opts);
  }

  Board.Component.call(
    this, this.opts = Board.Options(opts)
  );

  controller = opts.controller || null;

  // Derive device based on pins passed
  if (typeof this.opts.device === "undefined") {

    this.opts.device = (typeof this.opts.pins === "undefined" && typeof this.opts.register !== "object") ?
      "NONDIRECTIONAL" : "DIRECTIONAL";

    if (this.opts.pins && (this.opts.pins.cdir || this.opts.pins.length > 2)) {
      this.opts.device = "CDIR";
    }

    if (typeof controller === "string" &&
      (controller.startsWith("EVS") || controller.startsWith("GROVE_I2C"))) {
      this.opts.device = "DIRECTIONAL";
    }
  }

  // Allow users to pass in custom device types
  device = typeof this.opts.device === "string" ?
    Devices[this.opts.device] : this.opts.device;

  this.threshold = typeof this.opts.threshold !== "undefined" ?
    this.opts.threshold : 30;

  this.invertPWM = typeof this.opts.invertPWM !== "undefined" ?
    this.opts.invertPWM : false;

  Object.defineProperties(this, device);

  if (this.opts.register) {
    this.opts.controller = "ShiftRegister";
  }

<span class="apidocCodeCommentSpan">  /**
   * Note: Controller decorates the device. Used for adding
   * special controllers (i.e. PCA9685)
   **/
</span>  if (this.opts.controller) {
    controller = typeof this.opts.controller === "string" ?
      Controllers[this.opts.controller] : this.opts.controller;

    Board.Controller.call(this, controller, opts);
  }

  // current just wraps a Sensor
  if (this.opts.current) {
    this.opts.current.board = this.board;
    this.current = new Sensor(this.opts.current);
  }

  // Create a "state" entry for privately
  // storing the state of the motor
  state = {
    isOn: false,
    currentSpeed: typeof this.opts.speed !== "undefined" ?
      this.opts.speed : 128,
    braking: false,
    enabled: true
  };

  priv.set(this, state);

  Object.defineProperties(this, {
    // Calculated, read-only motor on/off state
    // true|false
    isOn: {
      get: function() {
        return state.isOn;
      }
    },
    currentSpeed: {
      get: function() {
        return state.currentSpeed;
      }
    },
    braking: {
      get: function() {
        return state.braking;
      }
    },
    enabled: {
      get: function() {
        return state.enabled;
      }
    }
  });

  // We need to store and initialize the state of the dir pin(s)
  this.direction = {
    value: 1
  };

  if (this.initialize) {
    this.initialize(opts);
  }

  this.enable();
  this.dir(this.direction);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Motors (numsOrObjects)](#apidoc.element.johnny-five.Motors)
- description and source-code
```javascript
function Motors(numsOrObjects) {
  if (!(this instanceof Motors)) {
    return new Motors(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Motor
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Multi"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Multi (opts)](#apidoc.element.johnny-five.Multi)
- description and source-code
```javascript
function IMU(opts) {

  if (!(this instanceof IMU)) {
    return new IMU(opts);
  }

  var controller, state;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    throw new Error("Missing IMU/Multi controller");
  }

  this.freq = opts.freq || 20;

  state = {};
  priv.set(this, state);

  Board.Controller.call(this, controller, opts);

  if (typeof this.initialize === "function") {
    this.initialize(opts);
  }

  // The IMU/Multi isn't considered "ready"
  // until one of the components has notified via
  // a change event.
  this.isReady = false;

  setInterval(function() {
    if (this.isReady) {
      this.emit("data", this);
    }
  }.bind(this), this.freq);

  var awaiting = this.components.slice();

  if (this.components && this.components.length > 0) {
    this.components.forEach(function(component) {
      if (!(this[component] instanceof Emitter)) {
        return;
      }

      this[component].on("change", function() {
        if (awaiting.length) {
          var index = awaiting.indexOf(component);

          if (index !== -1) {
            awaiting.splice(index, 1);
          }
        }

        if (!awaiting.length && !this.isReady) {
          this.isReady = true;
        }

        if (this.isReady) {
          this.emit("change", this, component);
        }
      }.bind(this));
    }, this);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Nunchuk"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Nunchuk (opts)](#apidoc.element.johnny-five.Nunchuk)
- description and source-code
```javascript
Nunchuk = function (opts) {
  opts = opts || {};
  opts.device = "RVL-004";

  return new Wii(opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Piezo"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Piezo (opts)](#apidoc.element.johnny-five.Piezo)
- description and source-code
```javascript
function Piezo(opts) {

  if (!(this instanceof Piezo)) {
    return new Piezo(opts);
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var controller = null;

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.DEFAULT;
  }

  Object.defineProperties(this, controller);

  Board.Controller.call(this, controller, opts);

  // Piezo instance properties
  var state = {
    isPlaying: false,
    timeout: null,
    address: null,
  };

  priv.set(this, state);

  Object.defineProperties(this, {
    isPlaying: {
      get: function() {
        return state.isPlaying;
      }
    }
  });

  if (typeof this.initialize === "function") {
    this.initialize(opts);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Pin"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Pin (opts)](#apidoc.element.johnny-five.Pin)
- description and source-code
```javascript
function Pin(opts) {
  if (!(this instanceof Pin)) {
    return new Pin(opts);
  }
  if (opts === undefined || (typeof opts === "object" &&
      opts.addr === undefined && opts.pin === undefined)) {
    throw new Error("Pins must have a pin number");
  }

  var pinValue = typeof opts === "object" ? (opts.addr || opts.pin || 0) : opts;
  var isAnalogInput = Pin.isAnalog(opts);
  var isDTOA = false;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  opts.addr = opts.addr || opts.pin;

  if (this.io.analogPins.includes(pinValue)) {
    isAnalogInput = false;
    isDTOA = true;
  }

  var isPin = typeof opts !== "object";
  var addr = isDTOA ? pinValue : (isPin ? opts : opts.addr);
  var type = opts.type || (isAnalogInput ? "analog" : "digital");

  // Create a private side table
  var state = {
    mode: null,
    last: null,
    value: 0
  };

  priv.set(this, state);

  // Create read-only "addr(address)" property
  Object.defineProperties(this, {
    type: {
      get: function() {
        return type;
      }
    },
    addr: {
      get: function() {
        return addr;
      }
    },
    value: {
      get: function() {
        return state.value;
      }
    },
    mode: {
      set: function(mode) {
        var state = priv.get(this);
        state.mode = mode;
        this.io.pinMode(this.addr, mode);
      },
      get: function() {
        return priv.get(this).mode;
      }
    }
  });

  this.mode = typeof opts.as !== "undefined" ? opts.as :
    (typeof opts.mode !== "undefined" ? opts.mode : (isAnalogInput ? 0x02 : 0x01));

  this.freq = typeof opts.freq !== "undefined" ? opts.freq : 20;

  if (this.mode === 0 || this.mode === 2) {
    read(this);
  }

  if (type === "digital") {
    Object.defineProperties(this, {
      isHigh: {
        get: function() {
          return !!state.value;
        }
      },
      isLow: {
        get: function() {
          return !state.value;
        }
      },
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Ping"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Ping (opts)](#apidoc.element.johnny-five.Ping)
- description and source-code
```javascript
function Ping(opts) {

  if (!(this instanceof Ping)) {
    return new Ping(opts);
  }

  var last = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  this.pin = opts && opts.pin || 7;
  this.freq = opts.freq || 20;
  // this.pulse = opts.pulse || 250;

  var state = {
    value: null
  };

  // Private settings object
  var settings = {
    pin: this.pin,
    value: this.io.HIGH,
    pulseOut: 5
  };

  this.io.setMaxListeners(100);

  // Interval for polling pulse duration as reported in microseconds
  setInterval(function() {
    this.io.pingRead(settings, function(microseconds) {
      state.value = microseconds;
    });
  }.bind(this), 225);

  // Interval for throttled event
  setInterval(function() {
    if (state.value === null) {
      return;
    }

    // The "read" event has been deprecated in
    // favor of a "data" event.
    this.emit("data", state.value);

    // If the state.value for this interval is not the same as the
    // state.value in the last interval, fire a "change" event.
    if (state.value !== last) {
      this.emit("change", state.value);
    }

    // Store state.value for comparison in next interval
    last = state.value;

    // Reset samples;
    // samples.length = 0;
  }.bind(this), this.freq);

  Object.defineProperties(this, {
    value: {
      get: function() {
        return state.value;
      }
    },
    // Based on the round trip travel time in microseconds,
    // Calculate the distance in inches and centimeters
    inches: {
      get: function() {
        return toFixed(state.value / 74 / 2, 2);
      }
    },
    in: {
      get: function() {
        return this.inches;
      }
    },
    cm: {
      get: function() {
        return toFixed(state.value / 29 / 2, 3);
      }
    }
  });

  priv.set(this, state);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Pins"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Pins (numsOrObjects)](#apidoc.element.johnny-five.Pins)
- description and source-code
```javascript
function Pins(numsOrObjects) {
  if (!(this instanceof Pins)) {
    return new Pins(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Pin
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Proximity"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Proximity (opts)](#apidoc.element.johnny-five.Proximity)
- description and source-code
```javascript
function Proximity(opts) {

  if (!(this instanceof Proximity)) {
    return new Proximity(opts);
  }

  var controller = null;
  var state = {};
  var raw = 0;
  var freq = opts.freq || 25;
  var last = 0;
  var pinValue = typeof opts === "object" ? opts.pin : opts;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (typeof opts.controller === "string") {
    controller = Controllers[opts.controller];
  } else {
    controller = opts.controller || Controllers["GP2Y0A21YK"];
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toCm) {
    this.toCm = opts.toCm || function(x) {
      return x;
    };
  }

  priv.set(this, state);

  Object.defineProperties(this, {
<span class="apidocCodeCommentSpan">    /**
     * [read-only] Calculated centimeter value
     * @property centimeters
     * @type Number
     */
</span>    centimeters: {
      get: function() {
        return this.toCm(raw);
      }
    },
    cm: {
      get: function() {
        return this.centimeters;
      }
    },
    /**
     * [read-only] Calculated inch value
     * @property inches
     * @type Number
     */
    inches: {
      get: function() {
        return toFixed(this.centimeters * 0.39, 2);
      }
    },
    in: {
      get: function() {
        return this.inches;
      }
    },
  });

  if (typeof this.initialize === "function") {
    opts.pinValue = pinValue;
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw === undefined) {
      return;
    }

    var data = {
      cm: this.cm,
      centimeters: this.centimeters,
      in: this.in,
      inches: this.inches
    };

    this.emit("data", data);

    if (raw !== last) {
      last = raw;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Proximity.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Proximity.Collection (numsOrObjects)](#apidoc.element.johnny-five.Proximity.Collection)
- description and source-code
```javascript
Proximity.Collection = function (numsOrObjects) {
  if (!(this instanceof Proximity.Collection)) {
    return new Proximity.Collection(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Proximity
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Relay"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Relay (opts)](#apidoc.element.johnny-five.Relay)
- description and source-code
```javascript
function Relay(opts) {

  var state;

  if (!(this instanceof Relay)) {
    return new Relay(opts);
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  opts.type = opts.type || "NO";

  state = {
    isInverted: opts.type === "NC",
    isOn: false,
    value: null,
  };

  priv.set(this, state);

  Object.defineProperties(this, {
    value: {
      get: function() {
        return Number(this.isOn);
      }
    },
    type: {
      get: function() {
        return state.isInverted ? "NC" : "NO";
      }
    },
    isOn: {
      get: function() {
        return state.isOn;
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Relays"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Relays (numsOrObjects)](#apidoc.element.johnny-five.Relays)
- description and source-code
```javascript
function Relays(numsOrObjects) {
  if (!(this instanceof Relays)) {
    return new Relays(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Relay
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Repl"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Repl (opts)](#apidoc.element.johnny-five.Repl)
- description and source-code
```javascript
function Repl(opts) {
  if (!Repl.isActive) {
    Repl.isActive = true;

    if (!(this instanceof Repl)) {
      return new Repl(opts);
    }

    // Store context values in instance property
    // this will be used for managing scope when
    // injecting new values into an existing Repl
    // session.
    this.context = {};
    this.ready = false;

    var state = {
      opts: opts,
      board: opts.board,
    };

    priv.set(this, state);

    // Store an accessible copy of the Repl instance
    // on a static property. This is later used by the
    // Board constructor to automattically setup Repl
    // sessions for all programs, which reduces the
    // boilerplate requirement.
    Repl.ref = this;
  } else {
    return Repl.ref;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensor"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Sensor (opts)](#apidoc.element.johnny-five.Sensor)
- description and source-code
```javascript
function Sensor(opts) {

  if (!(this instanceof Sensor)) {
    return new Sensor(opts);
  }

  // Defaults to 10-bit resolution
  var resolution = 0x3FF;
  var raw = null;
  var last = -1;
  var samples = [];

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (!opts.type) {
    opts.type = "analog";
  }

  if (this.io.RESOLUTION &&
      (this.io.RESOLUTION.ADC &&
        (this.io.RESOLUTION.ADC !== resolution))) {
    resolution = this.io.RESOLUTION.ADC;
  }

  // Set the pin to ANALOG (INPUT) mode
  this.mode = opts.type === "digital" ?
    this.io.MODES.INPUT :
    this.io.MODES.ANALOG;

  this.io.pinMode(this.pin, this.mode);

  // Create a "state" entry for privately
  // storing the state of the sensor
  var state = {
    enabled: typeof opts.enabled === "undefined" ? true : opts.enabled,
    booleanBarrier: opts.type === "digital" ? 0 : null,
    intervalId: null,
    scale: null,
    value: 0,
    median: 0,
    freq: opts.freq || 25,
    previousFreq: opts.freq || 25,
  };
  // Put a reference where the prototype methods defined in this file have access
  priv.set(this, state);

  // Sensor instance properties
  this.range = opts.range || [0, resolution];
  this.limit = opts.limit || null;
  this.threshold = opts.threshold === undefined ? 1 : opts.threshold;
  this.isScaled = false;

  this.io[opts.type + "Read"](this.pin, function(data) {
    raw = data;

    // Only append to the samples when noise filtering can/will be used
    if (opts.type !== "digital") {
      samples.push(raw);
    }
  }.bind(this));

  // Throttle
  // TODO: The event (interval) processing function should be outside of the Sensor
  // constructor function (with appropriate passed (and bound?) arguments), to
  // avoid creating a separate copy (of the function) for each Sensor instance.
  var eventProcessing = function() {
    var err, boundary;

    err = null;

    // For digital sensors, skip the analog
    // noise filtering provided below.
    if (opts.type === "digital") {
      this.emit("data", raw);

<span class="apidocCodeCommentSpan">      /* istanbul ignore else */
</span>      if (last !== raw) {
        this.emit("change", raw);
        last = raw;
      }
      return;
    }

    // Keep the previous calculated value if there were no new readings
    if (samples.length > 0) {
      // Filter the accumulated sample values to reduce analog reading noise
      state.median = median(samples);
    }

    this.emit("data", state.median);

    // If the filtered (state.median) value for this interval is at least ± the
    // configured threshold from last, fire change events
    if (state.median <= (last - this.threshold) || state.median >= (last + this.threshold)) {
      this.emit("change", state.median);
      // Update the instance-local 'last' value (only) when a new change event
      // has been emitted.  For comparison in the next interval
      last = state.median;
    }

    if (this.limit) {
      if (state.median <= this.limit[0]) {
        boundary = "lower";
      }
      if (state.median >= this.limit[1]) {
        boundary = "upper";
      }

      if (boundary) {
        this.emit("limit", {
          boundary: boundary,
          value: state.median
        });
        this.emit("limit:" + boundary, state.median);
      }
    }

    // Reset samples
    samples.length = 0;
  }.bind(this); // ./function eventProcessing()


  Object.defineProperties(this, {
    raw: {
      get: function() {
        return raw;
      }
    },
    analog: {
      get: function() {
        if (opts.type === "digital") {
          return raw;
        }

        return raw === null ? 0 :
          Fn.map(this.raw, 0, resolution, 0, 255) | 0;
      },
    },
    constrained: {
      get: function() {
        if (opts.type === "digital") {
          return raw;
        }

        return raw === null ? 0 :
          Fn.constrain(this.raw, 0, 255);
      }
    },
    boolean: {
      get: function() {
        var state = priv.get(this);
        var booleanBarrier = state.booleanBarrier;
        var scale = state.scale || [0, resolution];

        if (boolean ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensors"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Sensors (numsOrObjects)](#apidoc.element.johnny-five.Sensors)
- description and source-code
```javascript
function Sensors(numsOrObjects) {
  if (!(this instanceof Sensors)) {
    return new Sensors(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Sensor
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Servo (opts)](#apidoc.element.johnny-five.Servo)
- description and source-code
```javascript
function Servo(opts) {

  if (!(this instanceof Servo)) {
    return new Servo(opts);
  }

  var history = [];
  var pinValue = typeof opts === "object" ? opts.pin : opts;
  var controller = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  this.range = opts.range || [0, 180];
  this.deadband = opts.deadband || [90, 90];
  this.fps = opts.fps || 100;
  this.offset = opts.offset || 0;
  this.mode = this.io.MODES.SERVO;
  this.interval = null;
  this.value = null;

  // StandardFirmata on Arduino allows controlling
  // servos from analog pins.
  // If we're currently operating with an Arduino
  // and the user has provided an analog pin name
  // (eg. "A0", "A5" etc.), parse out the numeric
  // value and capture the fully qualified analog
  // pin number.
  if (typeof opts.controller === "undefined" && Pins.isFirmata(this)) {
    if (typeof pinValue === "string" && pinValue[0] === "A") {
      pinValue = this.io.analogPins[+pinValue.slice(1)];
    }

    pinValue = +pinValue;

    // If the board's default pin normalization
    // came up with something different, use the
    // the local value.
    if (!Number.isNaN(pinValue) && this.pin !== pinValue) {
      this.pin = pinValue;
    }
  }


  // The type of servo determines certain alternate
  // behaviours in the API
  this.type = opts.type || "standard";

  // Invert the value of all servoWrite operations
  // eg. 80 => 100, 90 => 90, 0 => 180
  if (opts.isInverted) {
    console.warn("The 'isInverted' property has been renamed 'invert'");
  }
  this.invert = opts.isInverted || opts.invert || false;

  // Allow "setup"instructions to come from
  // constructor options properties
  this.startAt = 90;

  // Collect all movement history for this servo
  // history = [
  //   {
  //     timestamp: Date.now(),
  //     degrees: degrees
  //   }
  // ];

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.Standard;
  }

  priv.set(this, {
    history: history
  });

  Board.Controller.call(this, controller, opts);

  Object.defineProperties(this, {
    history: {
      get: function() {
        return history.slice(-5);
      }
    },
    last: {
      get: function() {
        return history[history.length - 1];
      }
    },
    position: {
      get: function() {
        return history.length ? history[history.length - 1].degrees : -1;
      }
    }
  });

  this.initialize(opts);

  // If "startAt" is defined and center is falsy
  // set servo to min or max degrees
  if (opts.startAt !== undefined) {
    this.startAt = opts.startAt;
    this.to(opts.startAt);
  }

  // If "center" true set servo to 90deg
  if (opts.center) {
    this.center();
  }

  if (opts.type === "continuous") {
    this.stop();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servos"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Servos (numsOrObjects)](#apidoc.element.johnny-five.Servos)
- description and source-code
```javascript
function Servos(numsOrObjects) {
  if (!(this instanceof Servos)) {
    return new Servos(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Servo
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ShiftRegister"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>ShiftRegister (opts)](#apidoc.element.johnny-five.ShiftRegister)
- description and source-code
```javascript
function ShiftRegister(opts) {
  if (!(this instanceof ShiftRegister)) {
    return new ShiftRegister(opts);
  }

  if (Array.isArray(opts)) {
    // [Data, Clock, Latch, Reset]
    opts = {
      pins: {
        data: opts[0],
        clock: opts[1],
        latch: opts[2],
        reset: opts.length === 4 ? opts[3] : null,
      }
    };
  } else if (typeof opts.pins === "object" && Array.isArray(opts.pins)) {
    opts.pins = {
      data: opts.pins[0],
      clock: opts.pins[1],
      latch: opts.pins[2],
      reset: opts.pins.length === 4 ? opts.pins[3] : null,
    };
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  this.size = opts.size || 1;
  this.pins.reset = typeof opts.pins.reset !== "undefined" ? opts.pins.reset : null;

  var isAnode = typeof opts.isAnode !== "undefined" ? opts.isAnode : false;
  var clear = isAnode ? 255 : 0;
  var state = {
    isAnode: isAnode,
    value: new Array(this.size).fill(clear),
    encoded: encoded[isAnode ? "anode" : "cathode"],
    clear: clear,
  };

  priv.set(this, state);

  Object.defineProperties(this, {
    isAnode: {
      get: function() {
        return isAnode;
      }
    },
    value: {
      get: function() {
        return state.value;
      }
    },
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ShiftRegister.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>ShiftRegister.Collection (numsOrObjects)](#apidoc.element.johnny-five.ShiftRegister.Collection)
- description and source-code
```javascript
function ShiftRegisters(numsOrObjects) {
  if (!(this instanceof ShiftRegisters)) {
    return new ShiftRegisters(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: ShiftRegister
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sonar"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Sonar (opts)](#apidoc.element.johnny-five.Sonar)
- description and source-code
```javascript
function Sonar(opts) {

  if (!(this instanceof Sonar)) {
    return new Sonar(opts);
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var device, state;

  // Sonar instance properties
  this.freq = opts.freq || 100;
  this.value = null;

  state = {
    last: 0,
    median: 0,
    samples: []
  };

  priv.set(this, state);

  if (typeof opts.device === "string") {
    device = Devices[opts.device];
  } else {
    device = opts.device;
  }

  if (typeof device === "undefined") {
    device = Devices.DEFAULT;
  }

  device.initialize.call(this, opts);

  if (!device.descriptor.inches) {
    device.descriptor.inches = {
      get: function() {
        return +(this.cm * 0.39).toFixed(2);
      }
    };
  }

  device.descriptor.in = device.descriptor.inches;

  Object.defineProperties(this, device.descriptor);

  // Throttle
  setInterval(function() {
    // Nothing read since previous interval
    if (state.samples.length === 0) {
      return;
    }

    state.median = state.samples.sort()[Math.floor(state.samples.length / 2)];
    this.value = state.median;

    this.emit("data", state.median);

    // If the state.median value for this interval is not the same as the
    // state.median value in the last interval, fire a "change" event.
    //
    if (state.last && state.median &&
      (state.median.toFixed(1) !== state.last.toFixed(1))) {
      this.emit("change", state.median);
    }

    // Store this media value for comparison
    // in next interval
    state.last = state.median;

    // Reset state.samples;
    state.samples.length = 0;
  }.bind(this), this.freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Stepper"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Stepper (opts)](#apidoc.element.johnny-five.Stepper)
- description and source-code
```javascript
function Stepper(opts) {
  var state, params = [];

  if (!(this instanceof Stepper)) {
    return new Stepper(opts);
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (!isSupported(this.io)) {
    throw new Error(
      "Stepper is not supported"
    );
  }

  if (!opts.pins) {
    throw new Error(
      "Stepper requires a 'pins' object or array"
    );
  }

  if (!opts.stepsPerRev) {
    throw new Error(
      "Stepper requires a 'stepsPerRev' number value"
    );
  }

  steppers.set(this.board, steppers.get(this.board) || []);
  this.id = steppers.get(this.board).length;

  if (this.id >= MAXSTEPPERS) {
    throw new Error(
      "Stepper cannot exceed max steppers (" + MAXSTEPPERS + ")"
    );
  }

  // Convert an array of pins to the appropriate named pin
  if (Array.isArray(this.pins)) {
    if (this.pins.length === 2) {
      // Using an array of 2 pins requres a TYPE
      // to disambiguate DRIVER and TWO_WIRE
      if (!opts.type) {
        throw new Error(
          "Stepper requires a 'type' number value (DRIVER, TWO_WIRE)"
        );
      }
    }

    if (opts.type === Stepper.TYPE.DRIVER) {
      this.pins = {
        step: this.pins[0],
        dir: this.pins[1]
      };
    } else {
      this.pins = new MotorPins(this.pins);
    }
  }

  // Attempt to guess the type if none is provided
  if (!opts.type) {
    if (this.pins.dir) {
      opts.type = Stepper.TYPE.DRIVER;
    } else {
      if (this.pins.motor3) {
        opts.type = Stepper.TYPE.FOUR_WIRE;
      } else {
        opts.type = Stepper.TYPE.TWO_WIRE;
      }
    }
  }


  // Initial Stepper config params (same for all 3 types)
  params.push(this.id, opts.type, opts.stepsPerRev);


  if (opts.type === Stepper.TYPE.DRIVER) {
    if (typeof this.pins.dir === "undefined" ||
        typeof this.pins.step === "undefined") {
      throw new Error(
        "Stepper.TYPE.DRIVER expects: 'pins.dir', 'pins.step'"
      );
    }

    params.push(
      this.pins.dir, this.pins.step
    );
  }

  if (opts.type === Stepper.TYPE.TWO_WIRE) {
    if (typeof this.pins.motor1 === "undefined" ||
        typeof this.pins.motor2 === "undefined") {
      throw new Error(
        "Stepper.TYPE.TWO_WIRE expects: 'pins.motor1', 'pins.motor2'"
      );
    }

    params.push(
      this.pins.motor1, this.pins.motor2
    );
  }

  if (opts.type === Stepper.TYPE.FOUR_WIRE) {
    if (typeof this.pins.motor1 === "undefined" ||
        typeof this.pins.motor2 === "undefined" ||
        typeof this.pins.motor3 === "undefined" ||
        typeof this.pins.motor4 === "undefined") {
      throw new Error(
        "Stepper.TYPE.FOUR_WIRE expects: 'pins.motor1', 'pins.motor2', 'pins.motor3', 'pins.motor4'"
      );
    }

    params.push(
      this.pins.motor1, this.pins.motor2, this.pins.motor3, this.pins.motor4
    );
  }

  // Iterate the params and set each pin's mode to MODES.STEPPER
  // Params:
  // [deviceNum, type, stepsPerRev, dirOrMotor1Pin, stepOrMotor2Pin, motor3Pin, motor4Pin]
  // The first 3 are required, the remaining 2-4 will be pins
  params.slice(3).forEach(function(pin) {
    this.io.pinMode(pin, this.io.MODES.STEPPER);
  }, this);

  this.io.stepperConfig.apply(this.io, params);

  steppers.get(this.board).push(this);

  state = Step.PROPERTIES.reduce(function(state, key, i) {
    return (state[key] = typeof opts[key] !== "undefined" ? opts[key] : Step.DEFAULTS[i], state);
  }, {
    isRunning: false,
    type: opts.type,
    pins: this.pins
  });

  priv.set(this, state);

  Object.defineProperties(this, {
    type: {
      get: function() {
        return state.type;
      }
    },

    pins: {
      get: function() {
        return state.pins;
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Switch"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Switch (opts)](#apidoc.element.johnny-five.Switch)
- description and source-code
```javascript
function Switch(opts) {

  if (!(this instanceof Switch)) {
    return new Switch(opts);
  }

  // Create a 5 ms debounce boundary on event triggers
  // this avoids button events firing on
  // press noise and false positives
  var trigger = Fn.debounce(function(key) {
    aliases[key].forEach(function(type) {
      this.emit(type, null);
    }, this);
  }, 5);

  // Resolve the default type to Normally Open
  opts.type = opts.type || "NO";

  // Is this instance Normally Open?
  var isNormallyOpen = opts.type === "NO";
  var raw = null;
  var invert = typeof opts.invert !== "undefined" ?
    opts.invert : (isNormallyOpen || false);

  // Logical Defaults
  var closeValue = 1;
  var openValue = 0;

  if (invert) {
    closeValue ^= 1;
    openValue ^= 1;
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  this.io.pinMode(this.pin, this.io.MODES.INPUT);

  if (isNormallyOpen) {
    this.io.digitalWrite(this.pin, this.io.HIGH);
  }

  this.io.digitalRead(this.pin, function(data) {
    raw = data;

    trigger.call(this, this.isOpen ? "open" : "close");
  }.bind(this));

  Object.defineProperties(this, {
    value: {
      get: function() {
        return Number(this.isOpen);
      }
    },
    invert: {
      get: function() {
        return invert;
      },
      set: function(value) {
        invert = value;
        closeValue = invert ? 0 : 1;
        openValue = invert ? 1 : 0;
      }
    },
    closeValue: {
      get: function() {
        return closeValue;
      },
      set: function(value) {
        closeValue = value;
        openValue = value ^ 1;
      }
    },
    openValue: {
      get: function() {
        return openValue;
      },
      set: function(value) {
        openValue = value;
        closeValue = value ^ 1;
      }
    },
    isOpen: {
      get: function() {
        return raw === openValue;
      }
    },
    isClosed: {
      get: function() {
        return raw === closeValue;
      }
    },
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Switches"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Switches (numsOrObjects)](#apidoc.element.johnny-five.Switches)
- description and source-code
```javascript
function Switches(numsOrObjects) {
  if (!(this instanceof Switches)) {
    return new Switches(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Switch
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Temperature"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Temperature (opts)](#apidoc.element.johnny-five.Temperature)
- description and source-code
```javascript
function Thermometer(opts) {

  if (!(this instanceof Thermometer)) {
    return new Thermometer(opts);
  }

  var controller = null;
  var last = null;
  var raw = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var freq = opts.freq || 25;

  // Analog Reference Voltage (default to board.io.aref || 5)
  this.aref = opts.aref || this.io.aref || 5;

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.ANALOG;
  }

  priv.set(this, {});

  Board.Controller.call(this, controller, opts);

  if (!this.toCelsius) {
    this.toCelsius = opts.toCelsius || function(x) {
      return x;
    };
  }

  var descriptors = {
    celsius: {
      get: function() {
        return this.toCelsius(raw);
      }
    },
    fahrenheit: {
      get: function() {
        return toFixed((this.celsius * 9 / 5) + 32, 2);
      }
    },
    kelvin: {
      get: function() {
        return toFixed(this.celsius + CELSIUS_TO_KELVIN, 2);
      }
    }
  };
  // Convenience aliases
  descriptors.C = descriptors.celsius;
  descriptors.F = descriptors.fahrenheit;
  descriptors.K = descriptors.kelvin;

  Object.defineProperties(this, descriptors);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw == null) {
      return;
    }

    var data = {};
    data.C = data.celsius = this.celsius;
    data.F = data.fahrenheit = this.fahrenheit;
    data.K = data.kelvin = this.kelvin;

    this.emit("data", data);

    if (this.celsius !== last) {
      last = this.celsius;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Thermometer"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Thermometer (opts)](#apidoc.element.johnny-five.Thermometer)
- description and source-code
```javascript
function Thermometer(opts) {

  if (!(this instanceof Thermometer)) {
    return new Thermometer(opts);
  }

  var controller = null;
  var last = null;
  var raw = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var freq = opts.freq || 25;

  // Analog Reference Voltage (default to board.io.aref || 5)
  this.aref = opts.aref || this.io.aref || 5;

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.ANALOG;
  }

  priv.set(this, {});

  Board.Controller.call(this, controller, opts);

  if (!this.toCelsius) {
    this.toCelsius = opts.toCelsius || function(x) {
      return x;
    };
  }

  var descriptors = {
    celsius: {
      get: function() {
        return this.toCelsius(raw);
      }
    },
    fahrenheit: {
      get: function() {
        return toFixed((this.celsius * 9 / 5) + 32, 2);
      }
    },
    kelvin: {
      get: function() {
        return toFixed(this.celsius + CELSIUS_TO_KELVIN, 2);
      }
    }
  };
  // Convenience aliases
  descriptors.C = descriptors.celsius;
  descriptors.F = descriptors.fahrenheit;
  descriptors.K = descriptors.kelvin;

  Object.defineProperties(this, descriptors);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw == null) {
      return;
    }

    var data = {};
    data.C = data.celsius = this.celsius;
    data.F = data.fahrenheit = this.fahrenheit;
    data.K = data.kelvin = this.kelvin;

    this.emit("data", data);

    if (this.celsius !== last) {
      last = this.celsius;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Touchpad"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Touchpad (opts)](#apidoc.element.johnny-five.Touchpad)
- description and source-code
```javascript
function Keypad(opts) {

  if (!(this instanceof Keypad)) {
    return new Keypad(opts);
  }

  // Initialize a Device instance on a Board
  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var raw = null;
  var controller = null;
  var state = {
    touches: null,
    timeout: null,
    length: null,
    keys: null,
    mapping: null,
    holdtime: null,
  };

  var trigger = Fn.debounce(function(type, value) {
    var event = {
      type: type,
      which: value,
      timestamp: Date.now()
    };
    aliases[type].forEach(function(type) {
      this.emit(type, event);
    }, this);

    this.emit("change", Object.assign({}, event));
  }, 5);


  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.ANALOG;
  }

  Board.Controller.call(this, controller, opts);

  state.holdtime = opts.holdtime ? opts.holdtime : 500;

  priv.set(this, state);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {

      raw = data;

      var now = Date.now();
      var indices = this.toIndices(data);
      var kLength = state.length;

      var lists = {
        down: [],
        hold: [],
        up: [],
      };

      var target = null;
      var alias = null;

      for (var k = 0; k < kLength; k++) {
        alias = this.toAlias(k);

        if (indices.includes(k)) {
          if (state.touches[k].value === 0) {

            state.touches[k].timeout = now + state.holdtime;
            lists.down.push(alias);

          } else if (state.touches[k].value === 1) {
            if (state.touches[k].timeout !== null && now > state.touches[k].timeout) {
              state.touches[k].timeout = now + state.holdtime;
              lists.hold.push(alias);
            }
          }

          state.touches[k].value = 1;
        } else {
          if (state.touches[k].value === 1) {
            state.touches[k].timeout = null;
            lists.up.push(alias);
          }
          state.touches[k].value = 0;
        }
        target = null;
        alias = null;
      }

      Object.keys(lists).forEach(function(key) {
        var list = lists[key];

        if (list.length) {
          trigger.call(this, key, list);
        }
      }, this);
    }.bind(this));
  }

  Object.defineProperties(this, {
    isMultitouch: {
      get: function() {
        return state.isMultitouch;
      }
    },
    value: {
      get: function() {
        return raw;
      }
    },
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Wii"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Wii (opts)](#apidoc.element.johnny-five.Wii)
- description and source-code
```javascript
function Wii(opts) {

  if (!(this instanceof Wii)) {
    return new Wii(opts);
  }

  Board.Component.call(this, opts);

  // Derive device definition from Devices
  var device = Devices[opts.device];
  var address = device.address;
  var bytes = device.bytes;
  var delay = device.delay;
  var data = device.data.bind(this);
  var setup = device.setup;
  var preread = device.preread;

  // Wii controller instance properties
  this.freq = opts.freq || 100;

  // Button instance properties
  this.holdtime = opts.holdtime || 500;
  this.threshold = opts.threshold || 10;

  // Initialize components
  device.initialize.call(this);

  // Set initial "last data" byte array
  last.set(this, [0, 0, 0, 0, 0, 0, 0]);

  // Set up I2C data connection
  this.io.i2cConfig(opts);

  // Iterate and write each set of setup instructions
  setup.forEach(function(bytes) {
    this.io.i2cWrite(address, bytes);
  }, this);

  // Unthrottled i2c read request loop
  setInterval(function() {

    // Send this command to get all sensor data and store into
    // the 6-byte register within Wii controller.
    // This must be execute before reading data from the Wii.

    // Iterate and write each set of setup instructions
    preread.forEach(function(bytes) {
      this.io.i2cWrite(address, bytes);
    }, this);


    // Request six bytes of data from the controller
    this.io.i2cReadOnce(address, bytes, data);

    // Use the high-frequency data read loop as the change event
    // emitting loop. This drastically improves change event
    // frequency and sensitivity
    //
    // Emit change events if any delta is greater than
    // the threshold

    // RVL-005 does not have a read method at this time.
    if (typeof device.read !== "undefined") {
      device.read.call(this);
    }
  }.bind(this), delay || this.freq);

  // Throttled "read" event loop
  setInterval(function() {
    var event = new Board.Event({
      target: this
    });

    this.emit("data", event);

  }.bind(this), this.freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.evshield"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>evshield (options)](#apidoc.element.johnny-five.evshield)
- description and source-code
```javascript
function EVS(options) {
  if (shared) {
    return shared;
  }

  this.bank = {
    a: new Bank({
      address: EVS.BANK_A,
      io: options.io,
    }),
    b: new Bank({
      address: EVS.BANK_B,
      io: options.io,
    })
  };

  shared = this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.orientation"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>orientation (opts)](#apidoc.element.johnny-five.orientation)
- description and source-code
```javascript
function Orientation(opts) {

  if (!(this instanceof Orientation)) {
    return new Orientation(opts);
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var freq = opts.freq || 25;
  var controller = null;
  var raw = null;
  var state = {
    euler: {
      heading: 0,
      roll: 0,
      pitch: 0,
    },
    quarternion: {
      w: 0,
      x: 0,
      y: 0,
      z: 0,
    },
    calibration: 0,
  };

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller === null || typeof controller !== "object") {
    throw new Error("Missing valid Orientation controller");
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toScaledQuarternion) {
    this.toScaledQuarternion = opts.toScaledQuarternion || function(raw) {
      return raw;
    };
  }

  if (!this.toScaledEuler) {
    this.toScaledEuler = opts.toScaledEuler || function(raw) {
      return raw;
    };
  }

  priv.set(this, state);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw === null) {
      return;
    }
    var didOrientationChange = false;
    var didCalibrationChange = false;

    ["heading", "roll", "pitch"].forEach(function(el) {
      if (state.euler[el] !== raw.orientation.euler[el]) {
        didOrientationChange = true;
      }
      state.euler[el] = raw.orientation.euler[el];
    });

    ["w", "x", "y", "z"].forEach(function(el) {
      if (state.quarternion[el] !== raw.orientation.quarternion[el]) {
        didOrientationChange = true;
      }
      state.quarternion[el] = raw.orientation.quarternion[el];
    });

    //if we have a raw calibration state...
    // not sure if this is the best place... some devices may not have a calibration state...
    if (raw.calibration) {
      if (state.calibration !== raw.calibration) {
        didCalibrationChange = true;
      }
      state.calibration = raw.calibration;
    }

    var data = {
      euler: this.euler,
      quarternion: this.quarternion,
      calibration: this.calibration
    };

    this.emit("data", data);

    if (didOrientationChange) {
      this.emit("change", data);
    }

    //not sure how we can get this event into other drivers
    if (didCalibrationChange) {
      this.emit("calibration", this.calibration);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.reflectancearray"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>reflectancearray (opts)](#apidoc.element.johnny-five.reflectancearray)
- description and source-code
```javascript
function ReflectanceArray(opts) {

  if (!(this instanceof ReflectanceArray)) {
    return new ReflectanceArray(opts);
  }

  this.opts = Board.Options(opts);

  Board.Component.call(
    this, this.opts, {
      requestPin: false
    }
  );

  // Read event throttling
  this.freq = opts.freq || 25;

  // Make private data entry
  var state = {
    lastLine: 0,
    isOn: false,
    calibration: {
      min: [],
      max: []
    },
    autoCalibrate: opts.autoCalibrate || false
  };

  priv.set(this, state);

  initialize.call(this);

  Object.defineProperties(this, {
    isOn: {
      get: function() {
        return state.emitter.isOn;
      }
    },
    isCalibrated: {
      get: function() {
        return calibrationIsValid(this.calibration, this.sensors);
      }
    },
    isOnLine: {
      get: function() {
        var line = this.line;
        return line > CALIBRATED_MIN_VALUE && line < maxLineValue.call(this);
      }
    },
    sensors: {
      get: function() {
        return state.sensorStates.map(function(sensorState) {
          return sensorState.sensor;
        });
      }
    },
    calibration: {
      get: function() {
        return state.calibration;
      }
    },
    raw: {
      get: function() {
        return state.sensorStates.map(function(sensorState) {
          return sensorState.rawValue;
        });
      }
    },
    values: {
      get: function() {
        return this.isCalibrated ? calibratedValues.call(this) : this.raw;
      }
    },
    line: {
      get: function() {
        return this.isCalibrated ? getLine.call(this) : 0;
      }
    }
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Accelerometer"></a>[module johnny-five.Accelerometer](#apidoc.module.johnny-five.Accelerometer)

#### <a name="apidoc.element.johnny-five.Accelerometer.Accelerometer"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Accelerometer (opts)](#apidoc.element.johnny-five.Accelerometer.Accelerometer)
- description and source-code
```javascript
function Accelerometer(opts) {
  if (!(this instanceof Accelerometer)) {
    return new Accelerometer(opts);
  }

  var controller = null;

  var state = {
    enabled: true,
    x: {
      value: 0,
      previous: 0,
      stash: [],
      orientation: null,
      inclination: null,
      acceleration: null,
      calibration: []
    },
    y: {
      value: 0,
      previous: 0,
      stash: [],
      orientation: null,
      inclination: null,
      acceleration: null,
      calibration: []
    },
    z: {
      value: 0,
      previous: 0,
      stash: [],
      orientation: null,
      inclination: null,
      acceleration: null,
      calibration: []
    }
  };

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.ANALOG;
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toGravity) {
    this.toGravity = opts.toGravity || function(raw) {
      return raw;
    };
  }

  if (!this.enabledChanged) {
    this.enabledChanged = function() {};
  }

  priv.set(this, state);

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      var isChange = false;

      if (!state.enabled) {
        return;
      }

      Object.keys(data).forEach(function(axis) {
        var value = data[axis];
        var sensor = state[axis];

        if (opts.autoCalibrate && sensor.calibration.length < calibrationSize) {
          var axisIndex = axes.indexOf(axis);
          sensor.calibration.push(value);

          if (!Array.isArray(state.zeroV)) {
            state.zeroV = [];
          }

          state.zeroV[axisIndex] = sum(sensor.calibration) / sensor.calibration.length;
          if (axis === aZ) {
            state.zeroV[axisIndex] -= state.sensitivity;
          }
        }

        // The first run needs to prime the "stash"
        // of data values.
        if (sensor.stash.length === 0) {
          for (var i = 0; i < 5; i++) {
            sensor.stash[i] = value;
          }
        }

        sensor.previous = sensor.value;
        sensor.stash.shift();
        sensor.stash.push(value);

        sensor.value = (sum(sensor.stash) / 5) | 0;

        if (this.acceleration !== sensor.acceleration) {
          sensor.acceleration = this.acceleration;
          isChange = true;
          this.emit("acceleration", sensor.acceleration);
        }

        if (this.orientation !== sensor.orientation) {
          sensor.orientation = this.orientation;
          isChange = true;
          this.emit("orientation", sensor.orientation);
        }

        if (this.inclination !== sensor.inclination) {
          sensor.inclination = this.inclination;
          isChange = true;
          this.emit("inclination", sensor.inclination);
        }
      }, this);

      this.emit("data", {
        x: state.x.value,
        y: state.y.value,
        z: state.z.value
      });

      if (isChange) {
        this.emit("change", {
          x: this.x,
          y: this.y,
          z: this.z
        });
      }
    }.bind(this));
  }

  Object.defineProperties(this, {
    hasAxis: {
      writable: true,
      value: function(axis) {
        /* istanbul ignore next */
        return state[axis] ? state[axis].stash.length > 0 : false;
      }
    },
    enable: {
      value: function() {
        state.enabled = true;
        this.enabledChanged(true);
        return this;
      }
    },
    disable: {
      value: function() {
        state.enabled = false;
        this.enabledChanged(false);
        return this;
      }
    },
    zeroV: {
      get: function() {
        return state.zeroV;
      }
    },
    /**
     * [read-only] Calculated pitch value
     * @property pitch
     * @type Number
     */
    pitch: {
      get: function() {
        var x = this.x;
        var y = this.y;
        var z = this.z;
        var r ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Accelerometer.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Accelerometer.</span>super_ ()](#apidoc.element.johnny-five.Accelerometer.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Altimeter"></a>[module johnny-five.Altimeter](#apidoc.module.johnny-five.Altimeter)

#### <a name="apidoc.element.johnny-five.Altimeter.Altimeter"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Altimeter (opts)](#apidoc.element.johnny-five.Altimeter.Altimeter)
- description and source-code
```javascript
function Altimeter(opts) {
  if (!(this instanceof Altimeter)) {
    return new Altimeter(opts);
  }

  var controller = null;
  var freq;
  var last = null;
  var raw = null;
  var state = {};

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  freq = opts.freq || 25;


  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    throw new Error("Altimeter expects a valid controller");
  }

  priv.set(this, state);

  Board.Controller.call(this, controller, opts);

  if (!this.toMeters) {
    this.toMeters = opts.toMeters || function(x) {
      return x;
    };
  }

  var descriptors = {
    meters: {
      get: function() {
        return this.toMeters(raw);
      }
    },
    feet: {
      get: function() {
        return Fn.toFixed(this.meters * 3.28084, 2);
      }
    }
  };
  // Convenience aliases
  descriptors.m = descriptors.meters;
  descriptors.ft = descriptors.feet;

  Object.defineProperties(this, descriptors);


<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw == null) {
      return;
    }

    var data = {};
    data.m = data.meters = this.meters;
    data.ft = data.feet = this.feet;

    this.emit("data", data);

    /* istanbul ignore else */
    if (this.meters !== last) {
      last = this.meters;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Altimeter.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Altimeter.</span>super_ ()](#apidoc.element.johnny-five.Altimeter.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Animation"></a>[module johnny-five.Animation](#apidoc.module.johnny-five.Animation)

#### <a name="apidoc.element.johnny-five.Animation.Animation"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Animation (target)](#apidoc.element.johnny-five.Animation.Animation)
- description and source-code
```javascript
function Animation(target) {

  // Necessary to avoid loading temporal unless necessary
  if (!temporal) {
    temporal = require("temporal");
  }

  if (!(this instanceof Animation)) {
    return new Animation(target);
  }

  Animation.Segment.call(this);

  this.defaultTarget = target;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation.Segment"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.</span>Segment (options)](#apidoc.element.johnny-five.Animation.Segment)
- description and source-code
```javascript
Segment = function (options) {
  this.cuePoints = [0, 1];
  this.duration = 1000;
  this.easing = "linear";
  this.loop = false;
  this.loopback = 0;
  this.metronomic = false;
  this.currentSpeed = 1;
  this.progress = 0;
  this.fps = 60;
  this.rate = 1000 / 60;
  this.paused = false;
  this.segments = [];
  this.onstart = null;
  this.onpause = null;
  this.onstop = null;
  this.oncomplete = null;
  this.onloop = null;

  if (options) {
    Object.assign(this, options);

    if (options.segments) {
      this.segments = options.segments.slice();
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation.TemporalFallback"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.</span>TemporalFallback (animation)](#apidoc.element.johnny-five.Animation.TemporalFallback)
- description and source-code
```javascript
TemporalFallback = function (animation) {
  this.interval = setInterval(function() {
    animation.loopFunction({
      calledAt: Date.now()
    });
  }, animation.rate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.</span>super_ ()](#apidoc.element.johnny-five.Animation.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Animation.TemporalFallback"></a>[module johnny-five.Animation.TemporalFallback](#apidoc.module.johnny-five.Animation.TemporalFallback)

#### <a name="apidoc.element.johnny-five.Animation.TemporalFallback.TemporalFallback"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.</span>TemporalFallback (animation)](#apidoc.element.johnny-five.Animation.TemporalFallback.TemporalFallback)
- description and source-code
```javascript
TemporalFallback = function (animation) {
  this.interval = setInterval(function() {
    animation.loopFunction({
      calledAt: Date.now()
    });
  }, animation.rate);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Animation.TemporalFallback.prototype"></a>[module johnny-five.Animation.TemporalFallback.prototype](#apidoc.module.johnny-five.Animation.TemporalFallback.prototype)

#### <a name="apidoc.element.johnny-five.Animation.TemporalFallback.prototype.stop"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.TemporalFallback.prototype.</span>stop ()](#apidoc.element.johnny-five.Animation.TemporalFallback.prototype.stop)
- description and source-code
```javascript
stop = function () {
  if (this.interval) {
    clearInterval(this.interval);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Animation.prototype"></a>[module johnny-five.Animation.prototype](#apidoc.module.johnny-five.Animation.prototype)

#### <a name="apidoc.element.johnny-five.Animation.prototype.calculateProgress"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>calculateProgress (calledAt)](#apidoc.element.johnny-five.Animation.prototype.calculateProgress)
- description and source-code
```javascript
calculateProgress = function (calledAt) {

  var progress = (calledAt - this.startTime) / this.scaledDuration;

  if (progress > 1) {
    progress = 1;
  }

  this.progress = progress;

  if (this.reverse) {
    progress = 1 - progress;
  }

  // Ease the timeline
  // to do: When reverse replace inFoo with outFoo and vice versa. skip inOutFoo
  progress = ease[this.easing](progress);
  progress = Fn.constrain(progress, 0, 1);

  return progress;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation.prototype.enqueue"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>enqueue (opts)](#apidoc.element.johnny-five.Animation.prototype.enqueue)
- description and source-code
```javascript
enqueue = function (opts) {

  opts = opts || {};

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (typeof opts.target === "undefined") {
    opts.target = this.defaultTarget;
  }

  this.segments.push(new Animation.Segment(opts));


  /* istanbul ignore if */
  if (!this.paused) {
    this.next();
  }

  return this;

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation.prototype.findIndices"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>findIndices (progress)](#apidoc.element.johnny-five.Animation.prototype.findIndices)
- description and source-code
```javascript
findIndices = function (progress) {
  var indices = {
    left: null,
    right: null
  };

  // Find our current before and after cuePoints
  indices.right = this.cuePoints.findIndex(function(point) {
    return point >= progress;
  });

  indices.left = indices.right === 0 ? /* istanbul ignore next */ 0 : indices.right - 1;

  return indices;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation.prototype.loopFunction"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>loopFunction (loop)](#apidoc.element.johnny-five.Animation.prototype.loopFunction)
- description and source-code
```javascript
loopFunction = function (loop) {

  // Find the current timeline progress
  var progress = this.calculateProgress(loop.calledAt);


  // Find the left and right cuePoints/keyFrames;
  var indices = this.findIndices(progress);

  // call render function with tweened value
  this.target[Animation.render](this.tweenedValue(indices, progress));

<span class="apidocCodeCommentSpan">  /**
   * If this animation has been running in temporal for too long
   * fall back to using setInterval so we don't melt the user's CPU
   **/
</span>  if (loop.calledAt > this.fallBackTime) {
    this.fallBackTime = Infinity;
    if (this.playLoop) {
      this.playLoop.stop();
    }
    this.playLoop = new Animation.TemporalFallback(this);
  }

  // See if we have reached the end of the animation
  /* istanbul ignore else */
  if ((this.progress === 1 && !this.reverse) || (progress === this.loopback && this.reverse)) {

    if (this.loop || (this.metronomic && !this.reverse)) {

      if (this.onloop) {
        this.onloop();
      }

      if (this.metronomic) {
        this.reverse = this.reverse ? false : true;
      }

      this.normalizeKeyframes();
      this.progress = this.loopback;
      this.startTime = Date.now() - this.scaledDuration * this.progress;
      this.endTime = this.startTime + this.scaledDuration;
    } else {

      this.stop();

      if (this.oncomplete) {
        process.nextTick(this.oncomplete.bind(this));
      }

      if (this.segments.length > 0) {
        this.next();
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation.prototype.next"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>next ()](#apidoc.element.johnny-five.Animation.prototype.next)
- description and source-code
```javascript
next = function () {

  if (this.segments.length > 0) {

    Object.assign(this, this.segments.shift());

    this.paused = this.currentSpeed === 0 ? true : false;

    if (this.onstart) {
      this.onstart();
    }

    this.normalizeKeyframes();

    if (this.reverse) {
      this.currentSpeed *= -1;
    }

    if (this.currentSpeed !== 0) {
      this.play();
    } else {
      this.paused = true;
    }
  } else {
    this.playLoop.stop();
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation.prototype.normalizeKeyframes"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>normalizeKeyframes ()](#apidoc.element.johnny-five.Animation.prototype.normalizeKeyframes)
- description and source-code
```javascript
normalizeKeyframes = function () {

  var previousVal,
    keyFrameSet = Fn.cloneDeep(this.keyFrames),
    cuePoints = this.cuePoints;

  // Run through the target's normalization
  keyFrameSet = this.target[Animation.normalize](keyFrameSet);

  // keyFrames can be passed as a single dimensional array if
  // there is just one servo/device. If the first element is not an
  // array, nest keyFrameSet so we only have to deal with one format
  if (!Array.isArray(keyFrameSet[0])) {
    keyFrameSet = [keyFrameSet];
  }

  keyFrameSet.forEach(function(keyFrames) {

    // Pad the right side of keyFrames arrays with null
    for (var i = keyFrames.length; i < cuePoints.length; i++) {
      keyFrames.push(null);
    }

    keyFrames.forEach(function(keyFrame, i, source) {

      if (keyFrame !== null) {

        // keyFrames need to be converted to objects
        if (typeof keyFrame !== "object") {
          keyFrame = {
            step: keyFrame,
            easing: "linear"
          };
        }

        // Replace step values
        if (typeof keyFrame.step !== "undefined") {
          keyFrame.value = keyFrame.step === false ?
            previousVal : previousVal + keyFrame.step;
        }

        // Set a default easing function
        if (!keyFrame.easing) {
          keyFrame.easing = "linear";
        }

        // Copy value from another frame
<span class="apidocCodeCommentSpan">        /* istanbul ignore if */
</span>        if (typeof keyFrame.copyValue !== "undefined") {
          keyFrame.value = source[keyFrame.copyValue].value;
        }

        // Copy everything from another keyframe in this array
        /* istanbul ignore if */
        if (keyFrame.copyFrame) {
          keyFrame = source[keyFrame.copyFrame];
        }

        previousVal = keyFrame.value;

      } else {

        if (i === source.length - 1) {
          keyFrame = {
            value: previousVal,
            easing: "linear"
          };
        } else {
          keyFrame = null;
        }

      }
      source[i] = keyFrame;

    }, this);
  });

  this.normalizedKeyFrames = keyFrameSet;

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation.prototype.pause"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>pause ()](#apidoc.element.johnny-five.Animation.prototype.pause)
- description and source-code
```javascript
pause = function () {

  this.emit("animation:pause");

  if (this.playLoop) {
    this.playLoop.stop();
  }
  this.paused = true;

  if (this.onpause) {
    this.onpause();
  }

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation.prototype.play"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>play ()](#apidoc.element.johnny-five.Animation.prototype.play)
- description and source-code
```javascript
play = function () {
  var now = Date.now();

  if (this.playLoop) {
    this.playLoop.stop();
  }

  this.paused = false;

  // Find our timeline endpoints and refresh rate
  this.scaledDuration = this.duration / Math.abs(this.currentSpeed);
  this.startTime = now - this.scaledDuration * this.progress;
  this.endTime = this.startTime + this.scaledDuration;

  // If our animation runs for more than 5 seconds switch to setTimeout
  this.fallBackTime = now + temporalTTL;
  this.frameCount = 0;

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (this.fps) {
    this.rate = 1000 / this.fps;
  }

  this.rate = this.rate | 0;

  this.playLoop = temporal.loop(this.rate, this.loopFunction.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation.prototype.speed"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>speed (speed)](#apidoc.element.johnny-five.Animation.prototype.speed)
- description and source-code
```javascript
speed = function (speed) {

  if (typeof speed === "undefined") {
    return this.currentSpeed;
  } else {
    this.currentSpeed = speed;

    // Find our timeline endpoints and refresh rate
    this.scaledDuration = this.duration / Math.abs(this.currentSpeed);
    this.startTime = Date.now() - this.scaledDuration * this.progress;
    this.endTime = this.startTime + this.scaledDuration;

    if (!this.paused) {
      this.play();
    }
    return this;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation.prototype.stop"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>stop ()](#apidoc.element.johnny-five.Animation.prototype.stop)
- description and source-code
```javascript
stop = function () {

  this.emit("animation:stop");

  this.segments = [];
  if (this.playLoop) {
    this.playLoop.stop();
  }

  if (this.onstop) {
    this.onstop();
  }

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Animation.prototype.tweenedValue"></a>[function <span class="apidocSignatureSpan">johnny-five.Animation.prototype.</span>tweenedValue (indices, progress)](#apidoc.element.johnny-five.Animation.prototype.tweenedValue)
- description and source-code
```javascript
tweenedValue = function (indices, progress) {

  var tween = {
    duration: null,
    progress: null
  };

  var result = this.normalizedKeyFrames.map(function(keyFrame) {
    // Note: "this" is bound to the animation object

    var memberIndices = {
      left: null,
      right: null
    };

    // If the keyframe at indices.left is null, move left
    for (memberIndices.left = indices.left; memberIndices.left > -1; memberIndices.left--) {
<span class="apidocCodeCommentSpan">      /* istanbul ignore else */
</span>      if (keyFrame[memberIndices.left] !== null) {
        break;
      }
    }

    // If the keyframe at indices.right is null, move right
    memberIndices.right = keyFrame.findIndex(function(frame, index) {
      return index >= indices.right && frame !== null;
    });

    // Find our progress for the current tween
    tween.duration = this.cuePoints[memberIndices.right] - this.cuePoints[memberIndices.left];
    tween.progress = (progress - this.cuePoints[memberIndices.left]) / tween.duration;

    // Catch divide by zero
    if (!Number.isFinite(tween.progress)) {
      /* istanbul ignore next */
      tween.progress = this.reverse ? 0 : 1;
    }

    var left = keyFrame[memberIndices.left],
      right = keyFrame[memberIndices.right];

    // Apply tween easing to tween.progress
    // to do: When reverse replace inFoo with outFoo and vice versa. skip inOutFoo
    tween.progress = ease[right.easing](tween.progress);

    // Calculate this tween value
    var calcValue;

    if (right.position) {
      // This is a tuple
      calcValue = right.position.map(function(value, index) {
        return (value - left.position[index]) *
          tween.progress + left.position[index];
      });
    } else {
      if (typeof right.value === "number" && typeof left.value === "number") {
        calcValue = (right.value - left.value) * tween.progress + left.value;
      } else {
        calcValue = this.target[Animation.keys].reduce(function(accum, key) {
          accum[key] = (right.value[key] - left.value[key]) * tween.progress + left.value[key];
          return accum;
        }, {});
      }
    }

    return calcValue;
  }, this);

  return result;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Barometer"></a>[module johnny-five.Barometer](#apidoc.module.johnny-five.Barometer)

#### <a name="apidoc.element.johnny-five.Barometer.Barometer"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Barometer (opts)](#apidoc.element.johnny-five.Barometer.Barometer)
- description and source-code
```javascript
function Barometer(opts) {
  if (!(this instanceof Barometer)) {
    return new Barometer(opts);
  }

  var controller = null;
  var last = null;
  var raw = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var freq = opts.freq || 25;

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    // controller = Controllers["ANALOG"];
    throw new Error("Missing Barometer controller");
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toPressure) {
    this.toPressure = opts.toPressure || function(raw) {
      return raw;
    };
  }

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  Object.defineProperties(this, {
    pressure: {
      get: function() {
        return toFixed(this.toPressure(raw), 4);
      }
    }
  });

  setInterval(function() {
    if (raw === null) {
      return;
    }

    var data = {
      pressure: this.pressure
    };

    this.emit("data", data);

    if (this.pressure !== last) {
      last = this.pressure;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Barometer.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Barometer.</span>super_ ()](#apidoc.element.johnny-five.Barometer.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Board"></a>[module johnny-five.Board](#apidoc.module.johnny-five.Board)

#### <a name="apidoc.element.johnny-five.Board.Board"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Board (opts)](#apidoc.element.johnny-five.Board.Board)
- description and source-code
```javascript
function Board(opts) {

  if (!(this instanceof Board)) {
    return new Board(opts);
  }

  // Ensure opts is an object
  opts = opts || {};

  // Used to define the board instance's own
  // properties in the REPL's scope.
  var replContext = {};

  // It's feasible that an IO-Plugin may emit
  // "connect" and "ready" events out of order.
  // This is used to enforce the order, by
  // postponing the "ready" event if the IO-Plugin
  // hasn't emitted a "connect" event. Once
  // the "connect" event is emitted, the
  // postponement is lifted and the board may
  // proceed with emitting the events in the
  // correct order.
  var isPostponed = false;

  // Initialize this Board instance with
  // param specified properties.
  Object.assign(this, opts);

  this.timer = null;

  this.isConnected = false;

  // Easily track state of hardware
  this.isReady = false;

  // Initialize instance property to reference io board
  this.io = this.io || null;

  // Registry of components
  this.register = [];

  // Pins, Addr (alt Pin name), Addresses
  this.occupied = [];

  // Registry of drivers by address (i.e. I2C Controllers)
  this.Drivers = {};

  // Identify for connect hardware cache
  if (!this.id) {
    this.id = Fn.uid();
  }

  // If no debug flag, default to true
  if (typeof this.debug === UNDEFINED) {
    this.debug = true;
  }

  // If no repl flag, default to true
  if (typeof this.repl === UNDEFINED) {
    this.repl = true;
  }

  // If no sigint flag, default to true
  if (typeof this.sigint === UNDEFINED) {
    this.sigint = true;
  }

  // Specially processed pin capabilities object
  // assigned when physical board has reported
  // "ready" via Firmata or IO-Plugin.
  this.pins = null;

  // Create a Repl instance and store as
  // instance property of this io/board.
  // This will reduce the amount of boilerplate
  // code required to _always_ have a Repl
  // session available.
  //
  // If a sesssion exists, use it
  // (instead of creating a new session)
  //
<span class="apidocCodeCommentSpan">  /* istanbul ignore if */
</span>  if (this.repl) {
    /* istanbul ignore if */
    if (Repl.ref) {
      /* istanbul ignore next */
      replContext[this.id] = this;
      /* istanbul ignore next */
      Repl.ref.on("ready", function() {
        /* istanbul ignore next */
        Repl.ref.inject(replContext);
      });
      /* istanbul ignore next */
      this.repl = Repl.ref;
    } else {
      replContext[this.id] = replContext.board = this;
      this.repl = new Repl(replContext);
    }
  }

  if (opts.io) {
    // If you already have a connected io instance
    this.io = opts.io;
    this.isReady = opts.io.isReady;
    this.transport = this.io.transport || null;
    this.port = this.io.name;
    this.pins = Board.Pins(this);
  } else {

    if (this.port && opts.port) {
      Serial.connect.call(this, this.port, finalizeAndBroadcast);
    } else {
      Serial.detect.call(this, function(path) {
        Serial.connect.call(this, path, finalizeAndBroadcast);
      });
    }
  }

  // Either an IO instance was provided or isOnBoard is true
  if (!opts.port && this.io !== null) {
    /* istanbul ignore next */
    this.info("Device(s)", chalk.grey(this.io.name || "unknown"));

    ["connect", "ready"].forEach(function(type) {
      this.io.once(type, function() {
        // Since connection and readiness happen asynchronously,
        // it's actually possible for Johnny-Five to receive the
        // events out of order and that should be ok.
        if (type === "ready" && !this.isConnected) {
          isPostponed = true;
        } else {
          // Will emit the "connect" and "ready" events
          // if received in order. If out of order, this
          // will only emit the "connect" event. The
          // "ready" event will be handled in the next
          // condition's consequent.
          finalizeAndBroadcast.call(this, null, type, this.io);
        }

        if (type === "connect" && isPostponed) {
          finalizeAndBroadcast.call(this, null, "ready", this.io);
        }
      }.bind(this));

      if (this.io.isReady) { ...
```
- example usage
```shell
...

## Hello Johnny

The ubiquitous "Hello World" program of the microcontroller and SoC world is "blink an LED". The following code demonstrates how
 this is done using the Johnny-Five framework.

'''javascript
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
...
```

#### <a name="apidoc.element.johnny-five.Board.Array"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>Array (opts)](#apidoc.element.johnny-five.Board.Array)
- description and source-code
```javascript
function Boards(opts) {
  if (!(this instanceof Boards)) {
    return new Boards(opts);
  }

  var ports;

  // new Boards([ ...Array of board opts ])
  if (Array.isArray(opts)) {
    ports = opts.slice();
    opts = {
      ports: ports,
    };
  }

  // new Boards({ ports: [ ...Array of board opts ], .... })
<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (!Array.isArray(opts) && typeof opts === "object" && opts.ports !== undefined) {
    ports = opts.ports;
  }

  // new Boards(non-Array?)
  // new Boards({ ports: non-Array? })
  /* istanbul ignore if */
  if (!Array.isArray(ports)) {
    throw new Error("Expected ports to be an array");
  }

  if (typeof opts.debug === UNDEFINED) {
    opts.debug = true;
  }

  if (typeof opts.repl === UNDEFINED) {
    opts.repl = true;
  }

  var initialized = {};
  var noRepl = ports.some(function(port) { return port.repl === false; });
  var noDebug = ports.some(function(port) { return port.debug === false; });

  this.length = ports.length;
  this.debug = opts.debug;
  this.repl = opts.repl;

  // If any of the port definitions have
  // explicitly shut off debug output, bubble up
  // to the Boards instance
  /* istanbul ignore else */
  if (noDebug) {
    this.debug = false;
  }

  // If any of the port definitions have
  // explicitly shut off the repl, bubble up
  // to the Boards instance
  /* istanbul ignore else */
  if (noRepl) {
    this.repl = false;
  }

  var expecteds = ports.map(function(port, index) {
    var portOpts;

    if (typeof port === "string") {
      portOpts = {};

      // If the string matches a known valid port
      // name pattern, then assume this is what
      // the user code intended.
      if (rport.test(port)) {
        portOpts.port = port;
      } else {
        // Otherwise they expect Johnny-Five to figure
        // out what ports to use and intended this
        // value to be used an id
        portOpts.id = port;
      }
    } else {
      portOpts = port;
    }

    // Shut off per-board repl instance creation
    portOpts.repl = false;

    this[index] = initialized[portOpts.id] = new Board(portOpts);

    // "error" event is not async, register immediately
    this[index].on("error", function(error) {
      this.emit("error", error);
    }.bind(this));

    return new Promise(function(resolve) {
      this[index].on("ready", function() {
        resolve(initialized[portOpts.id]);
      });
    }.bind(this));
  }, this);

  Promise.all(expecteds).then(function(boards) {
    Object.assign(this, boards);

    this.each(function(board) {
      board.info("Board ID: ", chalk.green(board.id));
    });

    // If the Boards instance requires a REPL,
    // make sure it's created before calling "ready"
    if (this.repl) {
      this.repl = new Repl(
        Object.assign({}, initialized, {
          board: this
        })
      );
      this.repl.initialize(function() {
        this.emit("ready", initialized);
      }.bind(this));
    } else {
      // Otherwise, call ready immediately
      this.emit("ready", initialized);
    }
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>Collection (opts)](#apidoc.element.johnny-five.Board.Collection)
- description and source-code
```javascript
function Boards(opts) {
  if (!(this instanceof Boards)) {
    return new Boards(opts);
  }

  var ports;

  // new Boards([ ...Array of board opts ])
  if (Array.isArray(opts)) {
    ports = opts.slice();
    opts = {
      ports: ports,
    };
  }

  // new Boards({ ports: [ ...Array of board opts ], .... })
<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (!Array.isArray(opts) && typeof opts === "object" && opts.ports !== undefined) {
    ports = opts.ports;
  }

  // new Boards(non-Array?)
  // new Boards({ ports: non-Array? })
  /* istanbul ignore if */
  if (!Array.isArray(ports)) {
    throw new Error("Expected ports to be an array");
  }

  if (typeof opts.debug === UNDEFINED) {
    opts.debug = true;
  }

  if (typeof opts.repl === UNDEFINED) {
    opts.repl = true;
  }

  var initialized = {};
  var noRepl = ports.some(function(port) { return port.repl === false; });
  var noDebug = ports.some(function(port) { return port.debug === false; });

  this.length = ports.length;
  this.debug = opts.debug;
  this.repl = opts.repl;

  // If any of the port definitions have
  // explicitly shut off debug output, bubble up
  // to the Boards instance
  /* istanbul ignore else */
  if (noDebug) {
    this.debug = false;
  }

  // If any of the port definitions have
  // explicitly shut off the repl, bubble up
  // to the Boards instance
  /* istanbul ignore else */
  if (noRepl) {
    this.repl = false;
  }

  var expecteds = ports.map(function(port, index) {
    var portOpts;

    if (typeof port === "string") {
      portOpts = {};

      // If the string matches a known valid port
      // name pattern, then assume this is what
      // the user code intended.
      if (rport.test(port)) {
        portOpts.port = port;
      } else {
        // Otherwise they expect Johnny-Five to figure
        // out what ports to use and intended this
        // value to be used an id
        portOpts.id = port;
      }
    } else {
      portOpts = port;
    }

    // Shut off per-board repl instance creation
    portOpts.repl = false;

    this[index] = initialized[portOpts.id] = new Board(portOpts);

    // "error" event is not async, register immediately
    this[index].on("error", function(error) {
      this.emit("error", error);
    }.bind(this));

    return new Promise(function(resolve) {
      this[index].on("ready", function() {
        resolve(initialized[portOpts.id]);
      });
    }.bind(this));
  }, this);

  Promise.all(expecteds).then(function(boards) {
    Object.assign(this, boards);

    this.each(function(board) {
      board.info("Board ID: ", chalk.green(board.id));
    });

    // If the Boards instance requires a REPL,
    // make sure it's created before calling "ready"
    if (this.repl) {
      this.repl = new Repl(
        Object.assign({}, initialized, {
          board: this
        })
      );
      this.repl.initialize(function() {
        this.emit("ready", initialized);
      }.bind(this));
    } else {
      // Otherwise, call ready immediately
      this.emit("ready", initialized);
    }
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Component"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>Component (opts, componentOpts)](#apidoc.element.johnny-five.Board.Component)
- description and source-code
```javascript
Component = function (opts, componentOpts) {
  if (typeof opts === UNDEFINED) {
    opts = {};
  }

  if (typeof componentOpts === UNDEFINED) {
    componentOpts = {};
  }

  // Board specific properties
  this.board = Board.mount(opts);
  this.io = this.board.io;

  // Component/Module instance properties
  this.id = opts.id || Board.uid();
  this.custom = opts.custom || {};

  var originalPins;

  if (typeof opts.pin === "number" || typeof opts.pin === "string") {
    originalPins = [opts.pin];
  } else {
    if (Array.isArray(opts.pins)) {
      originalPins = opts.pins.slice();
    } else {
      if (typeof opts.pins === "object" && opts.pins !== null) {

        var pinset = opts.pins || opts.pin;

        originalPins = [];
        for (var p in pinset) {
          originalPins.push(pinset[p]);
        }
      }
    }
  }


  if (opts.controller) {

    if (typeof opts.controller === "string") {
      opts.controller = opts.controller.replace(/-/g, "");
    }

    if (!Expander) {
      Expander = require("./expander");
    }

    if (Expander.hasController(opts.controller)) {
      componentOpts = {
        normalizePin: false,
        requestPin: false,
      };
    }
  }

  componentOpts = Board.Component.initialization(componentOpts);

  if (componentOpts.normalizePin) {
    opts = Board.Pins.normalize(opts, this.board);
  }

  // var requesting = [];

  if (typeof opts.pins !== UNDEFINED) {
    this.pins = opts.pins || [];

    // if (Array.isArray(this.pins)) {
    //   requesting = requesting.concat(
    //     this.pins.map(function(pin) {
    //       return {
    //         value: pin,
    //         type: "pin"
    //       };
    //     })
    //   );
    // } else {
    //   requesting = requesting.concat(
    //     Object.keys(this.pins).map(function(key) {
    //       return {
    //         value: this.pins[key],
    //         type: "pin"
    //       };
    //     }, this)
    //   );
    // }
  }

  if (typeof opts.pin !== UNDEFINED) {
    this.pin = opts.pin;
    // requesting.push({
    //   value: this.pin,
    //   type: "pin"
    // });
  }

  // TODO: Figure out what is using this
<span class="apidocCodeCommentSpan">  /* istanbul ignore if */
</span>  if (typeof opts.emitter !== UNDEFINED) {
    /* istanbul ignore next */
    this.emitter = opts.emitter;
    // requesting.push({
    //   value: this.emitter,
    //   type: "emitter"
    // });
  }

  if (typeof opts.address !== UNDEFINED) {
    this.address = opts.address;
    // requesting.forEach(function(request) {
    //   request.address = this.address;
    // }, this);
  }

  if (typeof opts.controller !== UNDEFINED) {
    this.controller = opts.controller;
    // requesting.forEach(function(request) {
    //   request.controller = this.controller;
    // }, this);
  }

  // TODO: Figure out what is using this
  /* istanbul ignore if */
  if (typeof opts.bus !== UNDEFINED) {
    /* istanbul ignore next */
    this.bus = opts.bus;
    // requesting.forEach(function(request) {
    //   request.bus = this.bus;
    // }, this);
  }

  // if (componentOpts.requestPin) {
  //   // With the pins being requested for use by this component,
  //   // compare with the list of pins that are already known to be
  //   // in use by other components. If any are known to be in use,
  //   // produce a warning for the user.
  //   requesting.forEach(function(request, index) {
  //     var hasController = typeof request.controller !== UNDEFINED;
  //     var hasAddress = typeof request.address !== UNDEFINED;
  //     var isOccupied = false;
  //     var message = "";

  //     request.value = originalPins[index];

  //     if (this.board.occupied.length) {
  //       isOccupied = this.board.occupied.some(function(occupied) {
  //         var isPinOccupied = request.value === occupied.value && request.type === occupied.type;

  //         if (typeof occupied.controller !== UNDEFINED) {
  //           if (hasController) {
  //             return isPinOccupied && (request.controller === occupied.controller);
  //           }
  //           return false;
  //         }

  //         if (typeof occupied.addre ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Controller"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>Controller (controller, options)](#apidoc.element.johnny-five.Board.Controller)
- description and source-code
```javascript
Controller = function (controller, options) {
  var requirements = controller.requirements && controller.requirements.value;

  if (requirements) {
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (requirements.options) {
      Object.keys(requirements.options).forEach(function(key) {
        /*
        requirements: {
          value: {
            options: {
              parameterName: {
                throws: false,
                message: "...blah blah blah",
                typeof: "number",
              }
            }
          }
        },
        */
        if (typeof options[key] === UNDEFINED ||
          typeof options[key] !== requirements.options[key].typeof) {
          if (requirements.options[key].throws) {
            throw new Error(requirements.options[key].message);
          } else {
            this.board.warn(this.constructor.name, requirements.options[key].message);
          }
        }
      }, this);
    }
  }

  Object.defineProperties(this, controller);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Event"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>Event (event)](#apidoc.element.johnny-five.Board.Event)
- description and source-code
```javascript
Event = function (event) {

  if (typeof event === UNDEFINED) {
    throw new Error("Board.Event missing Event object");
  }

  // default event is read
  this.type = event.type || "data";

  // actual target instance
  this.target = event.target || null;

  // Initialize this Board instance with
  // param specified properties.
  Object.assign(this, event);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Options"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>Options (arg)](#apidoc.element.johnny-five.Board.Options)
- description and source-code
```javascript
function Options(arg) {
  if (!(this instanceof Options)) {
    return new Options(arg);
  }

  var opts = {};

  if (typeof arg === "number" ||
    typeof arg === "string") {
    opts.pin = arg;
  } else if (Array.isArray(arg)) {
    opts.pins = arg;
  } else {
    opts = arg;


    // @Nick, this is where you want to focus.
    // Anytime this path is taken, the constructor
    // received an object. If the object contains
    // a "pins" property that is ALSO an object, we need
    // to normalize the keys of that object, using the
    // "aliases" map defined above.
    //
    // This change will require renaming pin properties in
    // a few classes, but I'm ok with that, because if we do this
    // right, no existing code will break.
    //
  }

  Object.assign(this, opts);
}
```
- example usage
```shell
...
function Orientation(opts) {

if (!(this instanceof Orientation)) {
  return new Orientation(opts);
}

Board.Component.call(
  this, opts = Board.Options(opts)
);

var freq = opts.freq || 25;
var controller = null;
var raw = null;
var state = {
  euler: {
...
```

#### <a name="apidoc.element.johnny-five.Board.Pins"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>Pins (board)](#apidoc.element.johnny-five.Board.Pins)
- description and source-code
```javascript
function Pins(board) {
  if (!(this instanceof Pins)) {
    return new Pins(board);
  }

  var io = board.io;
  var pins = io.pins.slice();
  var length = pins.length;
  var type = pinsToType[length] || "OTHER";

  board.type = type;

  // Copy pin data to index
  for (var i = 0; i < length; i++) {
    this[i] = pins[i];
  }

  Object.defineProperties(this, {
    type: {
      value: type
    },
    length: {
      value: length
    }
  });

  // If an IO Plugin or Expander defines
  // these, override the default
  [
    "isInput",
    "isOutput",
    "isAnalog",
    "isPwm",
    "isServo",
  ].forEach(function(isType) {
    if (io[isType]) {
      this[isType] = io[isType];
    }
  }, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Virtual"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>Virtual (opts)](#apidoc.element.johnny-five.Board.Virtual)
- description and source-code
```javascript
Virtual = function (opts) {
  var temp;

  if (opts instanceof module.exports.Expander) {
    temp = {
      io: opts
    };
  } else {
    temp = opts;
  }

  return new module.exports.Board(
    Object.assign({}, {
      repl: false,
      debug: false,
      sigint: false
    }, temp)
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.constrain"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>constrain (value, lower, upper)](#apidoc.element.johnny-five.Board.constrain)
- description and source-code
```javascript
constrain = function (value, lower, upper) {
  return Math.min(upper, Math.max(lower, value));
}
```
- example usage
```shell
...

function calibratedValues() {
  return this.raw.map(function(value, i) {
    var max = this.calibration.max[i],
      min = this.calibration.min[i];

    var scaled = __.scale(value, min, max, CALIBRATED_MIN_VALUE, CALIBRATED_MAX_VALUE);
    return __.constrain(scaled, CALIBRATED_MIN_VALUE, CALIBRATED_MAX_VALUE);
  }, this);
}

function maxLineValue() {
  return (this.sensors.length - 1) * CALIBRATED_MAX_VALUE;
}
...
```

#### <a name="apidoc.element.johnny-five.Board.fmap"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>fmap (value, fromLow, fromHigh, toLow, toHigh)](#apidoc.element.johnny-five.Board.fmap)
- description and source-code
```javascript
fmap = function (value, fromLow, fromHigh, toLow, toHigh) {
  f32A[0] = (value - fromLow) * (toHigh - toLow) / (fromHigh - fromLow) + toLow;
  return f32A[0];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.map"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>map (value, fromLow, fromHigh, toLow, toHigh)](#apidoc.element.johnny-five.Board.map)
- description and source-code
```javascript
map = function (value, fromLow, fromHigh, toLow, toHigh) {
  return ((value - fromLow) * (toHigh - toLow) / (fromHigh - fromLow) + toLow) | 0;
}
```
- example usage
```shell
...
}

state.emitter = new Led({
  board: this.board,
  pin: this.opts.emitter
});

state.sensorStates = this.pins.map(function(pin) {
  var sensorState = {
    sensor: new Sensor({
      board: this.board,
      freq: this.freq,
      pin: pin
    }),
    rawValue: 0,
...
```

#### <a name="apidoc.element.johnny-five.Board.mount"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>mount (arg)](#apidoc.element.johnny-five.Board.mount)
- description and source-code
```javascript
mount = function (arg) {
  var index = typeof arg === "number" && arg,
    hardware;

  // board was explicitly provided
  if (arg && arg.board) {
    return arg.board;
  }

  // index specified, attempt to return
  // hardware instance. Return null if not
  // found or not available
  if (typeof index === "number") {
    hardware = boards[index];
    return hardware && hardware || null;
  }

  // If no arg specified and hardware instances
  // exist in the cache
  if (boards.length) {
    return boards[0];
  }

  // No mountable hardware
  return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.range"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>range (lower, upper, tick)](#apidoc.element.johnny-five.Board.range)
- description and source-code
```javascript
range = function (lower, upper, tick) {

  if (arguments.length === 1) {
    upper = lower - 1;
    lower = 0;
  }

  lower = lower || 0;
  upper = upper || 0;
  tick = tick || 1;

  var len = Math.max(Math.ceil((upper - lower) / tick), 0),
    idx = 0,
    range = [];

  while (idx <= len) {
    range[idx++] = lower;
    lower += tick;
  }

  return range;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>super_ ()](#apidoc.element.johnny-five.Board.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.uid"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>uid ()](#apidoc.element.johnny-five.Board.uid)
- description and source-code
```javascript
uid = function () {
  return "xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx".replace(/[xy]/g, function(chr) {
    var rnd = Math.random() * 16 | 0;
    return (chr === "x" ? rnd : (rnd & 0x3 | 0x8)).toString(16);
  }).toUpperCase();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Board.Component"></a>[module johnny-five.Board.Component](#apidoc.module.johnny-five.Board.Component)

#### <a name="apidoc.element.johnny-five.Board.Component.Component"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>Component (opts, componentOpts)](#apidoc.element.johnny-five.Board.Component.Component)
- description and source-code
```javascript
Component = function (opts, componentOpts) {
  if (typeof opts === UNDEFINED) {
    opts = {};
  }

  if (typeof componentOpts === UNDEFINED) {
    componentOpts = {};
  }

  // Board specific properties
  this.board = Board.mount(opts);
  this.io = this.board.io;

  // Component/Module instance properties
  this.id = opts.id || Board.uid();
  this.custom = opts.custom || {};

  var originalPins;

  if (typeof opts.pin === "number" || typeof opts.pin === "string") {
    originalPins = [opts.pin];
  } else {
    if (Array.isArray(opts.pins)) {
      originalPins = opts.pins.slice();
    } else {
      if (typeof opts.pins === "object" && opts.pins !== null) {

        var pinset = opts.pins || opts.pin;

        originalPins = [];
        for (var p in pinset) {
          originalPins.push(pinset[p]);
        }
      }
    }
  }


  if (opts.controller) {

    if (typeof opts.controller === "string") {
      opts.controller = opts.controller.replace(/-/g, "");
    }

    if (!Expander) {
      Expander = require("./expander");
    }

    if (Expander.hasController(opts.controller)) {
      componentOpts = {
        normalizePin: false,
        requestPin: false,
      };
    }
  }

  componentOpts = Board.Component.initialization(componentOpts);

  if (componentOpts.normalizePin) {
    opts = Board.Pins.normalize(opts, this.board);
  }

  // var requesting = [];

  if (typeof opts.pins !== UNDEFINED) {
    this.pins = opts.pins || [];

    // if (Array.isArray(this.pins)) {
    //   requesting = requesting.concat(
    //     this.pins.map(function(pin) {
    //       return {
    //         value: pin,
    //         type: "pin"
    //       };
    //     })
    //   );
    // } else {
    //   requesting = requesting.concat(
    //     Object.keys(this.pins).map(function(key) {
    //       return {
    //         value: this.pins[key],
    //         type: "pin"
    //       };
    //     }, this)
    //   );
    // }
  }

  if (typeof opts.pin !== UNDEFINED) {
    this.pin = opts.pin;
    // requesting.push({
    //   value: this.pin,
    //   type: "pin"
    // });
  }

  // TODO: Figure out what is using this
<span class="apidocCodeCommentSpan">  /* istanbul ignore if */
</span>  if (typeof opts.emitter !== UNDEFINED) {
    /* istanbul ignore next */
    this.emitter = opts.emitter;
    // requesting.push({
    //   value: this.emitter,
    //   type: "emitter"
    // });
  }

  if (typeof opts.address !== UNDEFINED) {
    this.address = opts.address;
    // requesting.forEach(function(request) {
    //   request.address = this.address;
    // }, this);
  }

  if (typeof opts.controller !== UNDEFINED) {
    this.controller = opts.controller;
    // requesting.forEach(function(request) {
    //   request.controller = this.controller;
    // }, this);
  }

  // TODO: Figure out what is using this
  /* istanbul ignore if */
  if (typeof opts.bus !== UNDEFINED) {
    /* istanbul ignore next */
    this.bus = opts.bus;
    // requesting.forEach(function(request) {
    //   request.bus = this.bus;
    // }, this);
  }

  // if (componentOpts.requestPin) {
  //   // With the pins being requested for use by this component,
  //   // compare with the list of pins that are already known to be
  //   // in use by other components. If any are known to be in use,
  //   // produce a warning for the user.
  //   requesting.forEach(function(request, index) {
  //     var hasController = typeof request.controller !== UNDEFINED;
  //     var hasAddress = typeof request.address !== UNDEFINED;
  //     var isOccupied = false;
  //     var message = "";

  //     request.value = originalPins[index];

  //     if (this.board.occupied.length) {
  //       isOccupied = this.board.occupied.some(function(occupied) {
  //         var isPinOccupied = request.value === occupied.value && request.type === occupied.type;

  //         if (typeof occupied.controller !== UNDEFINED) {
  //           if (hasController) {
  //             return isPinOccupied && (request.controller === occupied.controller);
  //           }
  //           return false;
  //         }

  //         if (typeof occupied.addre ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Component.initialization"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.Component.</span>initialization (opts)](#apidoc.element.johnny-five.Board.Component.initialization)
- description and source-code
```javascript
initialization = function (opts) {
  var defaults = {
    requestPin: true,
    normalizePin: true
  };

  return Object.assign({}, defaults, opts);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Board.Pins"></a>[module johnny-five.Board.Pins](#apidoc.module.johnny-five.Board.Pins)

#### <a name="apidoc.element.johnny-five.Board.Pins.Pins"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>Pins (board)](#apidoc.element.johnny-five.Board.Pins.Pins)
- description and source-code
```javascript
function Pins(board) {
  if (!(this instanceof Pins)) {
    return new Pins(board);
  }

  var io = board.io;
  var pins = io.pins.slice();
  var length = pins.length;
  var type = pinsToType[length] || "OTHER";

  board.type = type;

  // Copy pin data to index
  for (var i = 0; i < length; i++) {
    this[i] = pins[i];
  }

  Object.defineProperties(this, {
    type: {
      value: type
    },
    length: {
      value: length
    }
  });

  // If an IO Plugin or Expander defines
  // these, override the default
  [
    "isInput",
    "isOutput",
    "isAnalog",
    "isPwm",
    "isServo",
  ].forEach(function(isType) {
    if (io[isType]) {
      this[isType] = io[isType];
    }
  }, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Pins.Error"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.Pins.</span>Error (opts)](#apidoc.element.johnny-five.Board.Pins.Error)
- description and source-code
```javascript
Error = function (opts) {
  throw new Error(
    "Pin Error: " + opts.pin +
    " is not a valid " + opts.type +
    " pin (" + opts.via + ")"
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Pins.fromAnalog"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.Pins.</span>fromAnalog (pin)](#apidoc.element.johnny-five.Board.Pins.fromAnalog)
- description and source-code
```javascript
fromAnalog = function (pin) {
  if (typeof pin === "string" && pin[0] === "A") {
    return parseInt(pin.slice(1), 10);
  }
  return pin;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Pins.identity"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.Pins.</span>identity (pins, needle)](#apidoc.element.johnny-five.Board.Pins.identity)
- description and source-code
```javascript
identity = function (pins, needle) {
  return [].findIndex.call(pins, function(pin) {
    return pin.name === needle || pin.id === needle || pin.port === needle;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Pins.isFirmata"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.Pins.</span>isFirmata (board)](#apidoc.element.johnny-five.Board.Pins.isFirmata)
- description and source-code
```javascript
function isFirmata(board) {
  return board.io.name === "Firmata" || board.io.name === "Mock";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Pins.normalize"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.Pins.</span>normalize (opts, board)](#apidoc.element.johnny-five.Board.Pins.normalize)
- description and source-code
```javascript
normalize = function (opts, board) {
  var type = board.pins.type;
  var isArduino = isFirmata(board);
  var normalizer = normalizers.get(board);
  var isNormalizing;

  if (typeof opts === "string" ||
    typeof opts === "number" ||
    Array.isArray(opts)) {

    opts = new Options(opts);
  }

  if (!normalizer) {
    isNormalizing = board.io && typeof board.io.normalize === "function";

    normalizer = function(pin) {
      return isArduino ?
        Pins.fromAnalog(Pins.translate(pin, type)) :
        (isNormalizing ? board.io.normalize(pin) : pin);
    };

    normalizers.set(board, normalizer);
  }

  // Auto-normalize pin values, this reduces boilerplate code
  // inside module constructors
  if (hasPins(opts)) {

    // When an array of pins is present, attempt to
    // normalize them if necessary
    if (opts.pins) {
      opts.pins = opts.pins.map(normalizer);
    } else {
      opts.pin = normalizer(opts.pin);
    }
  }

  return opts;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Pins.translate"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.Pins.</span>translate (pin, type)](#apidoc.element.johnny-five.Board.Pins.translate)
- description and source-code
```javascript
translate = function (pin, type) {
  var translations = Pins.translations[type.toUpperCase()];

  if (!translations) {
    return pin;
  }

  return Object.keys(translations).reduce(function(pin, map) {
    return translations[map][pin] || pin;
  }, pin);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Board.Pins.prototype"></a>[module johnny-five.Board.Pins.prototype](#apidoc.module.johnny-five.Board.Pins.prototype)

#### <a name="apidoc.element.johnny-five.Board.Pins.prototype.isAnalog"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.Pins.prototype.</span>isAnalog (pin)](#apidoc.element.johnny-five.Board.Pins.prototype.isAnalog)
- description and source-code
```javascript
isAnalog = function (pin) {
  var attrs = this[pin] || this[Pins.identity(this, pin)];

  if (attrs && attrs.supportedModes.includes(MODES[key])) {
    return true;
  }
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Pins.prototype.isDigital"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.Pins.prototype.</span>isDigital (pin)](#apidoc.element.johnny-five.Board.Pins.prototype.isDigital)
- description and source-code
```javascript
isDigital = function (pin) {
  var attrs = this[pin] || this[Pins.identity(this, pin)];

  if (attrs && attrs.supportedModes.length) {
    return true;
  }
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Pins.prototype.isInput"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.Pins.prototype.</span>isInput (pin)](#apidoc.element.johnny-five.Board.Pins.prototype.isInput)
- description and source-code
```javascript
isInput = function (pin) {
  var attrs = this[pin] || this[Pins.identity(this, pin)];

  if (attrs && attrs.supportedModes.includes(MODES[key])) {
    return true;
  }
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Pins.prototype.isOutput"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.Pins.prototype.</span>isOutput (pin)](#apidoc.element.johnny-five.Board.Pins.prototype.isOutput)
- description and source-code
```javascript
isOutput = function (pin) {
  var attrs = this[pin] || this[Pins.identity(this, pin)];

  if (attrs && attrs.supportedModes.includes(MODES[key])) {
    return true;
  }
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Pins.prototype.isPwm"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.Pins.prototype.</span>isPwm (pin)](#apidoc.element.johnny-five.Board.Pins.prototype.isPwm)
- description and source-code
```javascript
isPwm = function (pin) {
  var attrs = this[pin] || this[Pins.identity(this, pin)];

  if (attrs && attrs.supportedModes.includes(MODES[key])) {
    return true;
  }
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.Pins.prototype.isServo"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.Pins.prototype.</span>isServo (pin)](#apidoc.element.johnny-five.Board.Pins.prototype.isServo)
- description and source-code
```javascript
isServo = function (pin) {
  var attrs = this[pin] || this[Pins.identity(this, pin)];

  if (attrs && attrs.supportedModes.includes(MODES[key])) {
    return true;
  }
  return false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Board.prototype"></a>[module johnny-five.Board.prototype](#apidoc.module.johnny-five.Board.prototype)

#### <a name="apidoc.element.johnny-five.Board.prototype.analogRead"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>analogRead ()](#apidoc.element.johnny-five.Board.prototype.analogRead)
- description and source-code
```javascript
analogRead = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.analogWrite"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>analogWrite ()](#apidoc.element.johnny-five.Board.prototype.analogWrite)
- description and source-code
```javascript
analogWrite = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.digitalRead"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>digitalRead ()](#apidoc.element.johnny-five.Board.prototype.digitalRead)
- description and source-code
```javascript
digitalRead = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.digitalWrite"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>digitalWrite ()](#apidoc.element.johnny-five.Board.prototype.digitalWrite)
- description and source-code
```javascript
digitalWrite = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.error"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>error ()](#apidoc.element.johnny-five.Board.prototype.error)
- description and source-code
```javascript
error = function () {
  var args = [].slice.call(arguments);
  args.unshift(type);

  this.log.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.fail"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>fail ()](#apidoc.element.johnny-five.Board.prototype.fail)
- description and source-code
```javascript
fail = function () {
  var args = [].slice.call(arguments);
  args.unshift(type);

  this.log.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.i2cConfig"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>i2cConfig ()](#apidoc.element.johnny-five.Board.prototype.i2cConfig)
- description and source-code
```javascript
i2cConfig = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
...
var Emitter = require("events").EventEmitter;
var util = require("util");
var shared;

function Bank(options) {
this.address = options.address;
this.io = options.io;
this.io.i2cConfig(options);
}

Bank.prototype.read = function(register, numBytes, callback) {
if (register) {
  this.io.i2cRead(this.address, register, numBytes, callback);
} else {
  this.io.i2cRead(this.address, numBytes, callback);
...
```

#### <a name="apidoc.element.johnny-five.Board.prototype.i2cRead"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>i2cRead ()](#apidoc.element.johnny-five.Board.prototype.i2cRead)
- description and source-code
```javascript
i2cRead = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
...
this.address = options.address;
this.io = options.io;
this.io.i2cConfig(options);
}

Bank.prototype.read = function(register, numBytes, callback) {
if (register) {
  this.io.i2cRead(this.address, register, numBytes, callback);
} else {
  this.io.i2cRead(this.address, numBytes, callback);
}
};

Bank.prototype.write = function(register, bytes) {
if (!Array.isArray(bytes)) {
...
```

#### <a name="apidoc.element.johnny-five.Board.prototype.i2cReadOnce"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>i2cReadOnce ()](#apidoc.element.johnny-five.Board.prototype.i2cReadOnce)
- description and source-code
```javascript
i2cReadOnce = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.i2cWrite"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>i2cWrite ()](#apidoc.element.johnny-five.Board.prototype.i2cWrite)
- description and source-code
```javascript
i2cWrite = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
...
}
};

Bank.prototype.write = function(register, bytes) {
if (!Array.isArray(bytes)) {
  bytes = [bytes];
}
this.io.i2cWrite(this.address, register, bytes);
};

// http://www.nr.edu/csc200/labs-ev3/ev3-user-guide-EN.pdf

function EVS(options) {
if (shared) {
  return shared;
...
```

#### <a name="apidoc.element.johnny-five.Board.prototype.i2cWriteReg"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>i2cWriteReg ()](#apidoc.element.johnny-five.Board.prototype.i2cWriteReg)
- description and source-code
```javascript
i2cWriteReg = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.info"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>info ()](#apidoc.element.johnny-five.Board.prototype.info)
- description and source-code
```javascript
info = function () {
  var args = [].slice.call(arguments);
  args.unshift(type);

  this.log.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.log"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>log ()](#apidoc.element.johnny-five.Board.prototype.log)
- description and source-code
```javascript
log = function () {
  var args = Array.from(arguments);

  // If this was a direct call to 'log(...)', make sure
  // there is a correct "type" to emit below.
  if (!logging.specials.includes(args[0])) {
    args.unshift("log");
  }

  var type = args.shift();
  var klass = args.shift();
  var message = args.shift();
  var color = logging.colors[type];
  var now = Date.now();
  var event = {
    type: type,
    timestamp: now,
    class: klass,
    message: "",
    data: null,
  };

  if (typeof args[args.length - 1] === "object") {
    event.data = args.pop();
  }

  message += " " + args.join(", ");
  event.message = message.trim();

<span class="apidocCodeCommentSpan">  /* istanbul ignore if */
</span>  if (this.debug) {
    /* istanbul ignore next */
    console.log([
      // Timestamp
      chalk.grey(now),
      // Module, color matches type of log
      chalk.magenta(klass),
      // Details
      chalk[color](message),
      // Miscellaneous args
      args.join(", ")
    ].join(" "));
  }

  this.emit(type, event);
  this.emit("message", event);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.loop"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>loop (time, callback)](#apidoc.element.johnny-five.Board.prototype.loop)
- description and source-code
```javascript
loop = function (time, callback) {
  var handler = function() {
    callback(function() {
      clearInterval(interval);
    });
  };
  var interval = setInterval(handler, time);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.pinMode"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>pinMode ()](#apidoc.element.johnny-five.Board.prototype.pinMode)
- description and source-code
```javascript
pinMode = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.pwmWrite"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>pwmWrite ()](#apidoc.element.johnny-five.Board.prototype.pwmWrite)
- description and source-code
```javascript
pwmWrite = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.queryPinState"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>queryPinState ()](#apidoc.element.johnny-five.Board.prototype.queryPinState)
- description and source-code
```javascript
queryPinState = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.samplingInterval"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>samplingInterval (ms)](#apidoc.element.johnny-five.Board.prototype.samplingInterval)
- description and source-code
```javascript
samplingInterval = function (ms) {

  if (this.io.setSamplingInterval) {
    this.io.setSamplingInterval(ms);
  } else {
    throw new Error("This IO plugin does not implement an interval adjustment method");
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.sendI2CConfig"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>sendI2CConfig ()](#apidoc.element.johnny-five.Board.prototype.sendI2CConfig)
- description and source-code
```javascript
sendI2CConfig = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.sendI2CReadRequest"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>sendI2CReadRequest ()](#apidoc.element.johnny-five.Board.prototype.sendI2CReadRequest)
- description and source-code
```javascript
sendI2CReadRequest = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.sendI2CWriteRequest"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>sendI2CWriteRequest ()](#apidoc.element.johnny-five.Board.prototype.sendI2CWriteRequest)
- description and source-code
```javascript
sendI2CWriteRequest = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.serialClose"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialClose ()](#apidoc.element.johnny-five.Board.prototype.serialClose)
- description and source-code
```javascript
serialClose = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.serialConfig"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialConfig ()](#apidoc.element.johnny-five.Board.prototype.serialConfig)
- description and source-code
```javascript
serialConfig = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.serialFlush"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialFlush ()](#apidoc.element.johnny-five.Board.prototype.serialFlush)
- description and source-code
```javascript
serialFlush = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.serialListen"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialListen ()](#apidoc.element.johnny-five.Board.prototype.serialListen)
- description and source-code
```javascript
serialListen = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.serialRead"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialRead ()](#apidoc.element.johnny-five.Board.prototype.serialRead)
- description and source-code
```javascript
serialRead = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.serialStop"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialStop ()](#apidoc.element.johnny-five.Board.prototype.serialStop)
- description and source-code
```javascript
serialStop = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.serialWrite"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialWrite ()](#apidoc.element.johnny-five.Board.prototype.serialWrite)
- description and source-code
```javascript
serialWrite = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.serialize"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>serialize (reducer)](#apidoc.element.johnny-five.Board.prototype.serialize)
- description and source-code
```javascript
serialize = function (reducer) {
  return JSON.stringify(this.snapshot(reducer));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.servoConfig"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>servoConfig ()](#apidoc.element.johnny-five.Board.prototype.servoConfig)
- description and source-code
```javascript
servoConfig = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.servoWrite"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>servoWrite ()](#apidoc.element.johnny-five.Board.prototype.servoWrite)
- description and source-code
```javascript
servoWrite = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.shiftOut"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>shiftOut (dataPin, clockPin, isBigEndian, value)](#apidoc.element.johnny-five.Board.prototype.shiftOut)
- description and source-code
```javascript
shiftOut = function (dataPin, clockPin, isBigEndian, value) {
  if (arguments.length === 3) {
    value = isBigEndian;
    isBigEndian = true;
  }

  for (var i = 0; i < 8; i++) {
    this.io.digitalWrite(clockPin, 0);
    if (isBigEndian) {
      this.io.digitalWrite(dataPin, !!(value & (1 << (7 - i))) | 0);
    } else {
      this.io.digitalWrite(dataPin, !!(value & (1 << i)) | 0);
    }
    this.io.digitalWrite(clockPin, 1);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.snapshot"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>snapshot (reducer)](#apidoc.element.johnny-five.Board.prototype.snapshot)
- description and source-code
```javascript
snapshot = function (reducer) {
  var blacklist = this.snapshot.blacklist;
  var special = this.snapshot.special;
  var hasReducer = typeof reducer === "function";

  return this.register.reduce(function(accum, component) {
    // Don't include collections or multi/imu wrappers
    if (typeof component.components === UNDEFINED) {
      accum.push(
        Object.getOwnPropertyNames(component).reduce(function(data, prop) {
          var value = component[prop];

          if (!blacklist.includes(prop) && typeof value !== "function") {

            if (hasReducer) {
              var result = reducer(prop, value, component);

              if (result !== undefined) {
                data[prop] = result;
              }
            } else {
              data[prop] = special[prop] ?
                special[prop](value) : value;
            }
          }
          return data;
        }, Object.create(null))
      );
    }

    return accum;
  }.bind(this), []);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.stepperConfig"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>stepperConfig ()](#apidoc.element.johnny-five.Board.prototype.stepperConfig)
- description and source-code
```javascript
stepperConfig = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.stepperStep"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>stepperStep ()](#apidoc.element.johnny-five.Board.prototype.stepperStep)
- description and source-code
```javascript
stepperStep = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.sysexCommand"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>sysexCommand ()](#apidoc.element.johnny-five.Board.prototype.sysexCommand)
- description and source-code
```javascript
sysexCommand = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.sysexResponse"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>sysexResponse ()](#apidoc.element.johnny-five.Board.prototype.sysexResponse)
- description and source-code
```javascript
sysexResponse = function () {
  this.io[method].apply(this.io, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.wait"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>wait (time, callback)](#apidoc.element.johnny-five.Board.prototype.wait)
- description and source-code
```javascript
wait = function (time, callback) {
  setTimeout(callback, time);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.prototype.warn"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.prototype.</span>warn ()](#apidoc.element.johnny-five.Board.prototype.warn)
- description and source-code
```javascript
warn = function () {
  var args = [].slice.call(arguments);
  args.unshift(type);

  this.log.apply(this, args);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Board.range"></a>[module johnny-five.Board.range](#apidoc.module.johnny-five.Board.range)

#### <a name="apidoc.element.johnny-five.Board.range.range"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.</span>range (lower, upper, tick)](#apidoc.element.johnny-five.Board.range.range)
- description and source-code
```javascript
range = function (lower, upper, tick) {

  if (arguments.length === 1) {
    upper = lower - 1;
    lower = 0;
  }

  lower = lower || 0;
  upper = upper || 0;
  tick = tick || 1;

  var len = Math.max(Math.ceil((upper - lower) / tick), 0),
    idx = 0,
    range = [];

  while (idx <= len) {
    range[idx++] = lower;
    lower += tick;
  }

  return range;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Board.range.prefixed"></a>[function <span class="apidocSignatureSpan">johnny-five.Board.range.</span>prefixed (prefix)](#apidoc.element.johnny-five.Board.range.prefixed)
- description and source-code
```javascript
prefixed = function (prefix) {
  return Fn.range.apply(null, [].slice.call(arguments, 1)).map(function(val) {
    return prefix + val;
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Boards"></a>[module johnny-five.Boards](#apidoc.module.johnny-five.Boards)

#### <a name="apidoc.element.johnny-five.Boards.Boards"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Boards (opts)](#apidoc.element.johnny-five.Boards.Boards)
- description and source-code
```javascript
function Boards(opts) {
  if (!(this instanceof Boards)) {
    return new Boards(opts);
  }

  var ports;

  // new Boards([ ...Array of board opts ])
  if (Array.isArray(opts)) {
    ports = opts.slice();
    opts = {
      ports: ports,
    };
  }

  // new Boards({ ports: [ ...Array of board opts ], .... })
<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (!Array.isArray(opts) && typeof opts === "object" && opts.ports !== undefined) {
    ports = opts.ports;
  }

  // new Boards(non-Array?)
  // new Boards({ ports: non-Array? })
  /* istanbul ignore if */
  if (!Array.isArray(ports)) {
    throw new Error("Expected ports to be an array");
  }

  if (typeof opts.debug === UNDEFINED) {
    opts.debug = true;
  }

  if (typeof opts.repl === UNDEFINED) {
    opts.repl = true;
  }

  var initialized = {};
  var noRepl = ports.some(function(port) { return port.repl === false; });
  var noDebug = ports.some(function(port) { return port.debug === false; });

  this.length = ports.length;
  this.debug = opts.debug;
  this.repl = opts.repl;

  // If any of the port definitions have
  // explicitly shut off debug output, bubble up
  // to the Boards instance
  /* istanbul ignore else */
  if (noDebug) {
    this.debug = false;
  }

  // If any of the port definitions have
  // explicitly shut off the repl, bubble up
  // to the Boards instance
  /* istanbul ignore else */
  if (noRepl) {
    this.repl = false;
  }

  var expecteds = ports.map(function(port, index) {
    var portOpts;

    if (typeof port === "string") {
      portOpts = {};

      // If the string matches a known valid port
      // name pattern, then assume this is what
      // the user code intended.
      if (rport.test(port)) {
        portOpts.port = port;
      } else {
        // Otherwise they expect Johnny-Five to figure
        // out what ports to use and intended this
        // value to be used an id
        portOpts.id = port;
      }
    } else {
      portOpts = port;
    }

    // Shut off per-board repl instance creation
    portOpts.repl = false;

    this[index] = initialized[portOpts.id] = new Board(portOpts);

    // "error" event is not async, register immediately
    this[index].on("error", function(error) {
      this.emit("error", error);
    }.bind(this));

    return new Promise(function(resolve) {
      this[index].on("ready", function() {
        resolve(initialized[portOpts.id]);
      });
    }.bind(this));
  }, this);

  Promise.all(expecteds).then(function(boards) {
    Object.assign(this, boards);

    this.each(function(board) {
      board.info("Board ID: ", chalk.green(board.id));
    });

    // If the Boards instance requires a REPL,
    // make sure it's created before calling "ready"
    if (this.repl) {
      this.repl = new Repl(
        Object.assign({}, initialized, {
          board: this
        })
      );
      this.repl.initialize(function() {
        this.emit("ready", initialized);
      }.bind(this));
    } else {
      // Otherwise, call ready immediately
      this.emit("ready", initialized);
    }
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Boards.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Boards.</span>super_ ()](#apidoc.element.johnny-five.Boards.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Boards.prototype"></a>[module johnny-five.Boards.prototype](#apidoc.module.johnny-five.Boards.prototype)

#### <a name="apidoc.element.johnny-five.Boards.prototype.add"></a>[function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>add ()](#apidoc.element.johnny-five.Boards.prototype.add)
- description and source-code
```javascript
add = function () {
  var length = this.length;
  var aLen = arguments.length;

  for (var i = 0; i < aLen; i++) {
    // When a Type exists, respect it!
    if (this.type) {
      if (arguments[i] instanceof this.type ||
          arguments[i] instanceof this.constructor) {
        this[length++] = arguments[i];
      }
    } else {
      // Otherwise allow user to directly instantiate
      // Collection or Collection.Emitter to create
      // a mixed collection
      this[length++] = arguments[i];
    }
  }

  return (this.length = length);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Boards.prototype.byId"></a>[function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>byId (id)](#apidoc.element.johnny-five.Boards.prototype.byId)
- description and source-code
```javascript
byId = function (id) {
  for (var i = 0; i < this.length; i++) {
    if (this[i].id === id) {
      return this[i];
    }
  }

  return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Boards.prototype.each"></a>[function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>each (callbackFn)](#apidoc.element.johnny-five.Boards.prototype.each)
- description and source-code
```javascript
each = function (callbackFn) {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    callbackFn.call(this[i], this[i], i);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Boards.prototype.error"></a>[function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>error ()](#apidoc.element.johnny-five.Boards.prototype.error)
- description and source-code
```javascript
error = function () {
  var args = [].slice.call(arguments);
  args.unshift(type);

  this.log.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Boards.prototype.fail"></a>[function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>fail ()](#apidoc.element.johnny-five.Boards.prototype.fail)
- description and source-code
```javascript
fail = function () {
  var args = [].slice.call(arguments);
  args.unshift(type);

  this.log.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Boards.prototype.forEach"></a>[function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>forEach ()](#apidoc.element.johnny-five.Boards.prototype.forEach)
- description and source-code
```javascript
forEach = function () {
  [].forEach.apply(this, arguments);
}
```
- example usage
```shell
...
  setInterval(function() {
if (raw === null) {
  return;
}
var didOrientationChange = false;
var didCalibrationChange = false;

["heading", "roll", "pitch"].forEach(function(el) {
  if (state.euler[el] !== raw.orientation.euler[el]) {
    didOrientationChange = true;
  }
  state.euler[el] = raw.orientation.euler[el];
});

["w", "x", "y", "z"].forEach(function(el) {
...
```

#### <a name="apidoc.element.johnny-five.Boards.prototype.includes"></a>[function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>includes ()](#apidoc.element.johnny-five.Boards.prototype.includes)
- description and source-code
```javascript
includes = function () {
  return [].includes.apply(this, arguments);
}
```
- example usage
```shell
...
address = EVS.BANK_A;
bank = "a";
  } else {
address = EVS.BANK_B;
bank = "b";
  }

  if (pin.includes("M")) {
motor = pin.endsWith("M1") ? EVS.S1 : EVS.S2;
  }

  if (pin.includes("S")) {
endsWithS1 = pin.endsWith("S1");

// Used for reading 2 byte integer values from raw sensors
...
```

#### <a name="apidoc.element.johnny-five.Boards.prototype.indexOf"></a>[function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>indexOf ()](#apidoc.element.johnny-five.Boards.prototype.indexOf)
- description and source-code
```javascript
indexOf = function () {
  return [].indexOf.apply(this, arguments);
}
```
- example usage
```shell
...





Object.defineProperty(Array.prototype, "includes", {
  value: function(entry) {
    return this.indexOf(entry) !== -1;
  },
  enumerable: false,
  configurable: false,
  writable: false
});
...
```

#### <a name="apidoc.element.johnny-five.Boards.prototype.info"></a>[function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>info ()](#apidoc.element.johnny-five.Boards.prototype.info)
- description and source-code
```javascript
info = function () {
  var args = [].slice.call(arguments);
  args.unshift(type);

  this.log.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Boards.prototype.log"></a>[function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>log ()](#apidoc.element.johnny-five.Boards.prototype.log)
- description and source-code
```javascript
log = function () {
  var args = Array.from(arguments);

  // If this was a direct call to 'log(...)', make sure
  // there is a correct "type" to emit below.
  if (!logging.specials.includes(args[0])) {
    args.unshift("log");
  }

  var type = args.shift();
  var klass = args.shift();
  var message = args.shift();
  var color = logging.colors[type];
  var now = Date.now();
  var event = {
    type: type,
    timestamp: now,
    class: klass,
    message: "",
    data: null,
  };

  if (typeof args[args.length - 1] === "object") {
    event.data = args.pop();
  }

  message += " " + args.join(", ");
  event.message = message.trim();

<span class="apidocCodeCommentSpan">  /* istanbul ignore if */
</span>  if (this.debug) {
    /* istanbul ignore next */
    console.log([
      // Timestamp
      chalk.grey(now),
      // Module, color matches type of log
      chalk.magenta(klass),
      // Details
      chalk[color](message),
      // Miscellaneous args
      args.join(", ")
    ].join(" "));
  }

  this.emit(type, event);
  this.emit("message", event);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Boards.prototype.map"></a>[function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>map ()](#apidoc.element.johnny-five.Boards.prototype.map)
- description and source-code
```javascript
map = function () {
  return [].map.apply(this, arguments);
}
```
- example usage
```shell
...
}

state.emitter = new Led({
  board: this.board,
  pin: this.opts.emitter
});

state.sensorStates = this.pins.map(function(pin) {
  var sensorState = {
    sensor: new Sensor({
      board: this.board,
      freq: this.freq,
      pin: pin
    }),
    rawValue: 0,
...
```

#### <a name="apidoc.element.johnny-five.Boards.prototype.slice"></a>[function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>slice ()](#apidoc.element.johnny-five.Boards.prototype.slice)
- description and source-code
```javascript
slice = function () {
  return new this.constructor([].slice.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Boards.prototype.warn"></a>[function <span class="apidocSignatureSpan">johnny-five.Boards.prototype.</span>warn ()](#apidoc.element.johnny-five.Boards.prototype.warn)
- description and source-code
```javascript
warn = function () {
  var args = [].slice.call(arguments);
  args.unshift(type);

  this.log.apply(this, args);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Button"></a>[module johnny-five.Button](#apidoc.module.johnny-five.Button)

#### <a name="apidoc.element.johnny-five.Button.Button"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Button (opts)](#apidoc.element.johnny-five.Button.Button)
- description and source-code
```javascript
function Button(opts) {
  if (!(this instanceof Button)) {
    return new Button(opts);
  }

  var pinValue;
  var raw;
  var invert = false;
  var downValue = 1;
  var upValue = 0;
  var controller = null;
  var state = {
    interval: null,
    last: null
  };

  // Create a debounce boundary on event triggers
  // this avoids button events firing on
  // press noise and false positives
  var trigger = Fn.debounce(function(key) {
    aliases[key].forEach(function(type) {
      this.emit(type);
    }, this);
  }, 7);

  pinValue = typeof opts === "object" ? opts.pin : opts;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  opts.pinValue = pinValue;

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.DEFAULT;
  }

  Board.Controller.call(this, controller, opts);

  // 'holdtime' is used by an interval to determine
  // if the button has been released within a specified
  // time frame, in milliseconds.
  this.holdtime = opts.holdtime || 500;

  // 'opts.isPullup' is included as part of an effort to
  // phase out "isFoo" options properties
  this.pullup = opts.pullup || opts.isPullup || false;

  this.pulldown = opts.pulldown || opts.isPulldown || false;

  // Turns out some button circuits will send
  // 0 for up and 1 for down, and some the inverse,
  // so we can invert our function with this option.
  // Default to invert in pullup mode, but use opts.invert
  // if explicitly defined (even if false)
  invert = typeof opts.invert !== "undefined" ?
    opts.invert : (this.pullup || false);

  if (invert) {
    downValue = downValue ^ 1;
    upValue = upValue ^ 1;
  }

  state.last = upValue;

  // Create a "state" entry for privately
  // storing the state of the button
  priv.set(this, state);

  Object.defineProperties(this, {
    value: {
      get: function() {
        return Number(this.isDown);
      }
    },
    invert: {
      get: function() {
        return invert;
      },
      set: function(value) {
        invert = value;
        downValue = invert ? 0 : 1;
        upValue = invert ? 1 : 0;

        state.last = upValue;
      }
    },
    downValue: {
      get: function() {
        return downValue;
      },
      set: function(value) {
        downValue = value;
        upValue = value ^ 1;
        invert = value ? true : false;

        state.last = upValue;
      }
    },
    upValue: {
      get: function() {
        return upValue;
      },
      set: function(value) {
        upValue = value;
        downValue = value ^ 1;
        invert = value ? true : false;

        state.last = downValue;
      }
    },
    isDown: {
      get: function() {
        return this.toBoolean(raw);
      }
    }
  });

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      // Update the raw data value, which
      // is used by isDown = toBoolean()
      raw = data;

      if (!this.isDown) {
        /* istanbul ignore else */
        if (state.interval) {
          clearInterval(state.interval);
        }
        trigger.call(this, "up");
      }

      if (this.isDown) {
        trigger.call(this, "down");

        state.interval = setInterval(function() {
          /* istanbul ignore else */
          if (this.isDown) {
            this.emit("hold");
          }
        }.bind(this), this.holdtime);
      }

      state.last = data;
    }.bind(this));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Button.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.Button.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Button.Collection)
- description and source-code
```javascript
function Buttons(numsOrObjects) {
  if (!(this instanceof Buttons)) {
    return new Buttons(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Button
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Button.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Button.</span>super_ ()](#apidoc.element.johnny-five.Button.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Buttons"></a>[module johnny-five.Buttons](#apidoc.module.johnny-five.Buttons)

#### <a name="apidoc.element.johnny-five.Buttons.Buttons"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Buttons (numsOrObjects)](#apidoc.element.johnny-five.Buttons.Buttons)
- description and source-code
```javascript
function Buttons(numsOrObjects) {
  if (!(this instanceof Buttons)) {
    return new Buttons(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Button
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Buttons.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Buttons.super_)
- description and source-code
```javascript
super_ = function (numsOrObjects) {

  // Create private state ahead of super call
  priv.set(this, {
    timing: {
      last: Date.now()
    }
  });

  Collection.call(this, numsOrObjects);

  // If the Collection.Emitter was created
  // with a Shared Properties object, then
  // we should abide by the freq or period
  // properties...
  var interval = null;
  var period = 5;

  if (!Array.isArray(numsOrObjects) &&
      (typeof numsOrObjects === "object" && numsOrObjects !== null))  {

    period = numsOrObjects.freq || numsOrObjects.period || period;

    // _However_, looking to the future, we
    // need to start thinking about replacing
    // the garbage named _freq_ (the value is
    // actually a period), with real _frequency_
    // in Hz.

    // If provided, convert frequency to period
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (numsOrObjects.frequency) {
      period = (1 / numsOrObjects.frequency) * 1000;
    }
  }

  Object.defineProperties(this, {
    period: {
      get: function() {
        return period;
      },
      set: function(value) {
        if (period !== value) {
          period = value;
        }

        if (interval) {
          clearInterval(interval);
        }

        interval = setInterval(function() {
          this.emit("data", this);
        }.bind(this), period);
      }
    },
  });

  this.period = period;

  this.on("newListener", function(event) {
    if (event === "change" || event === "data") {
      return;
    }

    this.forEach(function(input) {
      input.on(event, function(data) {
        this.emit(event, input, data);
      }.bind(this));
    }, this);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Buttons.super_"></a>[module johnny-five.Buttons.super_](#apidoc.module.johnny-five.Buttons.super_)

#### <a name="apidoc.element.johnny-five.Buttons.super_.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Buttons.super_.super_)
- description and source-code
```javascript
function Collection(numsOrObjects) {
  var Type = this.type;
  var initObjects = [];

  this.length = 0;

  if (Array.isArray(numsOrObjects)) {
    initObjects = numsOrObjects;
  } else {
    // Initialize with a Shared Properties object
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (Array.isArray(numsOrObjects.pins)) {
      var keys = Object.keys(numsOrObjects).filter(function(key) {
        return key !== "pins";
      });
      initObjects = numsOrObjects.pins.map(function(pin) {
        var obj = {};

        if (Array.isArray(pin)) {
          obj.pins = pin;
        } else {
          obj.pin = pin;
        }

        return keys.reduce(function(accum, key) {
          accum[key] = numsOrObjects[key];
          return accum;
        }, obj);
      });
    }
  }

  /* istanbul ignore else */
  if (initObjects.length) {
    while (initObjects.length) {
      var numOrObject = initObjects.shift();

      // When a Type exists, respect it!
      if (typeof Type === "function") {
        if (!(numOrObject instanceof Type || numOrObject instanceof this.constructor)) {
          numOrObject = new Type(numOrObject);
        }
      }

      this.add(numOrObject);
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Buttons.super_.prototype"></a>[module johnny-five.Buttons.super_.prototype](#apidoc.module.johnny-five.Buttons.super_.prototype)

#### <a name="apidoc.element.johnny-five.Buttons.super_.prototype.add"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>add ()](#apidoc.element.johnny-five.Buttons.super_.prototype.add)
- description and source-code
```javascript
add = function () {
  var inputs = Array.from(arguments);

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (inputs.length) {
    Collection.prototype.add.apply(this, inputs);

    inputs.forEach(function(input) {
      if (input) {
        input.on("change", function() {
          this.emit("change", input);
        }.bind(this));
      }
    }, this);
  }
  return this.length;
  // return (this.length = length);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Buttons.super_.prototype.addListener"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>addListener (type, listener)](#apidoc.element.johnny-five.Buttons.super_.prototype.addListener)
- description and source-code
```javascript
function addListener(type, listener) {
  return _addListener(this, type, listener, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Buttons.super_.prototype.emit"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>emit (type)](#apidoc.element.johnny-five.Buttons.super_.prototype.emit)
- description and source-code
```javascript
function emit(type) {
  var er, handler, len, args, i, events, domain;
  var needDomainExit = false;
  var doError = (type === 'error');

  events = this._events;
  if (events)
    doError = (doError && events.error == null);
  else if (!doError)
    return false;

  domain = this.domain;

  // If there is no 'error' event listener then throw.
  if (doError) {
    er = arguments[1];
    if (domain) {
      if (!er)
        er = new Error('Uncaught, unspecified "error" event');
      er.domainEmitter = this;
      er.domain = domain;
      er.domainThrown = false;
      domain.emit('error', er);
    } else if (er instanceof Error) {
      throw er; // Unhandled 'error' event
    } else {
      // At least give some kind of context to the user
      var err = new Error('Uncaught, unspecified "error" event. (' + er + ')');
      err.context = er;
      throw err;
    }
    return false;
  }

  handler = events[type];

  if (!handler)
    return false;

  if (domain && this !== process) {
    domain.enter();
    needDomainExit = true;
  }

  var isFn = typeof handler === 'function';
  len = arguments.length;
  switch (len) {
    // fast cases
    case 1:
      emitNone(handler, isFn, this);
      break;
    case 2:
      emitOne(handler, isFn, this, arguments[1]);
      break;
    case 3:
      emitTwo(handler, isFn, this, arguments[1], arguments[2]);
      break;
    case 4:
      emitThree(handler, isFn, this, arguments[1], arguments[2], arguments[3]);
      break;
    // slower
    default:
      args = new Array(len - 1);
      for (i = 1; i < len; i++)
        args[i - 1] = arguments[i];
      emitMany(handler, isFn, this, args);
  }

  if (needDomainExit)
    domain.exit();

  return true;
}
```
- example usage
```shell
...

var data = {
  euler: this.euler,
  quarternion: this.quarternion,
  calibration: this.calibration
};

this.emit("data", data);

if (didOrientationChange) {
  this.emit("change", data);
}

//not sure how we can get this event into other drivers
if (didCalibrationChange) {
...
```

#### <a name="apidoc.element.johnny-five.Buttons.super_.prototype.eventNames"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>eventNames ()](#apidoc.element.johnny-five.Buttons.super_.prototype.eventNames)
- description and source-code
```javascript
function eventNames() {
  return this._eventsCount > 0 ? Reflect.ownKeys(this._events) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Buttons.super_.prototype.getMaxListeners"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>getMaxListeners ()](#apidoc.element.johnny-five.Buttons.super_.prototype.getMaxListeners)
- description and source-code
```javascript
function getMaxListeners() {
  return $getMaxListeners(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Buttons.super_.prototype.listenerCount"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>listenerCount (type)](#apidoc.element.johnny-five.Buttons.super_.prototype.listenerCount)
- description and source-code
```javascript
function listenerCount(type) {
  const events = this._events;

  if (events) {
    const evlistener = events[type];

    if (typeof evlistener === 'function') {
      return 1;
    } else if (evlistener) {
      return evlistener.length;
    }
  }

  return 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Buttons.super_.prototype.listeners"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>listeners (type)](#apidoc.element.johnny-five.Buttons.super_.prototype.listeners)
- description and source-code
```javascript
function listeners(type) {
  var evlistener;
  var ret;
  var events = this._events;

  if (!events)
    ret = [];
  else {
    evlistener = events[type];
    if (!evlistener)
      ret = [];
    else if (typeof evlistener === 'function')
      ret = [evlistener];
    else
      ret = arrayClone(evlistener, evlistener.length);
  }

  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Buttons.super_.prototype.on"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>on (type, listener)](#apidoc.element.johnny-five.Buttons.super_.prototype.on)
- description and source-code
```javascript
function addListener(type, listener) {
  return _addListener(this, type, listener, false);
}
```
- example usage
```shell
...

The ubiquitous "Hello World" program of the microcontroller and SoC world is "blink an LED". The following code demonstrates how
 this is done using the Johnny-Five framework.

'''javascript
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''
...
```

#### <a name="apidoc.element.johnny-five.Buttons.super_.prototype.once"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>once (type, listener)](#apidoc.element.johnny-five.Buttons.super_.prototype.once)
- description and source-code
```javascript
function once(type, listener) {
  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');
  this.on(type, _onceWrap(this, type, listener));
  return this;
}
```
- example usage
```shell
...
// Calibrate will store the min/max values for this sensor array
// It should be called many times in order to get a lot of readings
// on light and dark areas.  See calibrateUntil for a convenience
// for looping until a condition is met.
ReflectanceArray.prototype.calibrate = function() {
  var state = priv.get(this);

  this.once("data", function(values) {
    setCalibration(state.calibration, values);

    this.emit("calibrated");
  });

  return this;
};
...
```

#### <a name="apidoc.element.johnny-five.Buttons.super_.prototype.prependListener"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>prependListener (type, listener)](#apidoc.element.johnny-five.Buttons.super_.prototype.prependListener)
- description and source-code
```javascript
function prependListener(type, listener) {
  return _addListener(this, type, listener, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Buttons.super_.prototype.prependOnceListener"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>prependOnceListener (type, listener)](#apidoc.element.johnny-five.Buttons.super_.prototype.prependOnceListener)
- description and source-code
```javascript
function prependOnceListener(type, listener) {
  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');
  this.prependListener(type, _onceWrap(this, type, listener));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Buttons.super_.prototype.removeAllListeners"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>removeAllListeners (type)](#apidoc.element.johnny-five.Buttons.super_.prototype.removeAllListeners)
- description and source-code
```javascript
function removeAllListeners(type) {
  var listeners, events;

  events = this._events;
  if (!events)
    return this;

  // not listening for removeListener, no need to emit
  if (!events.removeListener) {
    if (arguments.length === 0) {
      this._events = new EventHandlers();
      this._eventsCount = 0;
    } else if (events[type]) {
      if (--this._eventsCount === 0)
        this._events = new EventHandlers();
      else
        delete events[type];
    }
    return this;
  }

  // emit removeListener for all listeners on all events
  if (arguments.length === 0) {
    var keys = Object.keys(events);
    for (var i = 0, key; i < keys.length; ++i) {
      key = keys[i];
      if (key === 'removeListener') continue;
      this.removeAllListeners(key);
    }
    this.removeAllListeners('removeListener');
    this._events = new EventHandlers();
    this._eventsCount = 0;
    return this;
  }

  listeners = events[type];

  if (typeof listeners === 'function') {
    this.removeListener(type, listeners);
  } else if (listeners) {
    // LIFO order
    do {
      this.removeListener(type, listeners[listeners.length - 1]);
    } while (listeners[0]);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Buttons.super_.prototype.removeListener"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>removeListener (type, listener)](#apidoc.element.johnny-five.Buttons.super_.prototype.removeListener)
- description and source-code
```javascript
function removeListener(type, listener) {
  var list, events, position, i, originalListener;

  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');

  events = this._events;
  if (!events)
    return this;

  list = events[type];
  if (!list)
    return this;

  if (list === listener || list.listener === listener) {
    if (--this._eventsCount === 0)
      this._events = new EventHandlers();
    else {
      delete events[type];
      if (events.removeListener)
        this.emit('removeListener', type, list.listener || listener);
    }
  } else if (typeof list !== 'function') {
    position = -1;

    for (i = list.length; i-- > 0;) {
      if (list[i] === listener || list[i].listener === listener) {
        originalListener = list[i].listener;
        position = i;
        break;
      }
    }

    if (position < 0)
      return this;

    if (list.length === 1) {
      list[0] = undefined;
      if (--this._eventsCount === 0) {
        this._events = new EventHandlers();
        return this;
      } else {
        delete events[type];
      }
    } else {
      spliceOne(list, position);
    }

    if (events.removeListener)
      this.emit('removeListener', type, originalListener || listener);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Buttons.super_.prototype.setMaxListeners"></a>[function <span class="apidocSignatureSpan">johnny-five.Buttons.super_.prototype.</span>setMaxListeners (n)](#apidoc.element.johnny-five.Buttons.super_.prototype.setMaxListeners)
- description and source-code
```javascript
function setMaxListeners(n) {
  if (typeof n !== 'number' || n < 0 || isNaN(n))
    throw new TypeError('"n" argument must be a positive number');
  this._maxListeners = n;
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Collection"></a>[module johnny-five.Collection](#apidoc.module.johnny-five.Collection)

#### <a name="apidoc.element.johnny-five.Collection.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Collection.Collection)
- description and source-code
```javascript
function Collection(numsOrObjects) {
  var Type = this.type;
  var initObjects = [];

  this.length = 0;

  if (Array.isArray(numsOrObjects)) {
    initObjects = numsOrObjects;
  } else {
    // Initialize with a Shared Properties object
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (Array.isArray(numsOrObjects.pins)) {
      var keys = Object.keys(numsOrObjects).filter(function(key) {
        return key !== "pins";
      });
      initObjects = numsOrObjects.pins.map(function(pin) {
        var obj = {};

        if (Array.isArray(pin)) {
          obj.pins = pin;
        } else {
          obj.pin = pin;
        }

        return keys.reduce(function(accum, key) {
          accum[key] = numsOrObjects[key];
          return accum;
        }, obj);
      });
    }
  }

  /* istanbul ignore else */
  if (initObjects.length) {
    while (initObjects.length) {
      var numOrObject = initObjects.shift();

      // When a Type exists, respect it!
      if (typeof Type === "function") {
        if (!(numOrObject instanceof Type || numOrObject instanceof this.constructor)) {
          numOrObject = new Type(numOrObject);
        }
      }

      this.add(numOrObject);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Collection.Emitter"></a>[function <span class="apidocSignatureSpan">johnny-five.Collection.</span>Emitter (numsOrObjects)](#apidoc.element.johnny-five.Collection.Emitter)
- description and source-code
```javascript
Emitter = function (numsOrObjects) {

  // Create private state ahead of super call
  priv.set(this, {
    timing: {
      last: Date.now()
    }
  });

  Collection.call(this, numsOrObjects);

  // If the Collection.Emitter was created
  // with a Shared Properties object, then
  // we should abide by the freq or period
  // properties...
  var interval = null;
  var period = 5;

  if (!Array.isArray(numsOrObjects) &&
      (typeof numsOrObjects === "object" && numsOrObjects !== null))  {

    period = numsOrObjects.freq || numsOrObjects.period || period;

    // _However_, looking to the future, we
    // need to start thinking about replacing
    // the garbage named _freq_ (the value is
    // actually a period), with real _frequency_
    // in Hz.

    // If provided, convert frequency to period
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (numsOrObjects.frequency) {
      period = (1 / numsOrObjects.frequency) * 1000;
    }
  }

  Object.defineProperties(this, {
    period: {
      get: function() {
        return period;
      },
      set: function(value) {
        if (period !== value) {
          period = value;
        }

        if (interval) {
          clearInterval(interval);
        }

        interval = setInterval(function() {
          this.emit("data", this);
        }.bind(this), period);
      }
    },
  });

  this.period = period;

  this.on("newListener", function(event) {
    if (event === "change" || event === "data") {
      return;
    }

    this.forEach(function(input) {
      input.on(event, function(data) {
        this.emit(event, input, data);
      }.bind(this));
    }, this);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Collection.installMethodForwarding"></a>[function <span class="apidocSignatureSpan">johnny-five.Collection.</span>installMethodForwarding (target, source)](#apidoc.element.johnny-five.Collection.installMethodForwarding)
- description and source-code
```javascript
installMethodForwarding = function (target, source) {
  return Object.keys(source).reduce(function(accum, method) {
    // Create Inputs wrappers for each method listed.
    // This will allow us control over all Input instances
    // simultaneously.
    accum[method] = function() {
      var length = this.length;

      for (var i = 0; i < length; i++) {
        this[i][method].apply(this[i], arguments);
      }
      return this;
    };

    return accum;
  }, target);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Collection.prototype"></a>[module johnny-five.Collection.prototype](#apidoc.module.johnny-five.Collection.prototype)

#### <a name="apidoc.element.johnny-five.Collection.prototype.add"></a>[function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>add ()](#apidoc.element.johnny-five.Collection.prototype.add)
- description and source-code
```javascript
add = function () {
  var length = this.length;
  var aLen = arguments.length;

  for (var i = 0; i < aLen; i++) {
    // When a Type exists, respect it!
    if (this.type) {
      if (arguments[i] instanceof this.type ||
          arguments[i] instanceof this.constructor) {
        this[length++] = arguments[i];
      }
    } else {
      // Otherwise allow user to directly instantiate
      // Collection or Collection.Emitter to create
      // a mixed collection
      this[length++] = arguments[i];
    }
  }

  return (this.length = length);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Collection.prototype.byId"></a>[function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>byId (id)](#apidoc.element.johnny-five.Collection.prototype.byId)
- description and source-code
```javascript
byId = function (id) {
  return [].find.call(this, function(entry) {
    return entry.id !== undefined && entry.id === id;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Collection.prototype.each"></a>[function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>each (callbackFn)](#apidoc.element.johnny-five.Collection.prototype.each)
- description and source-code
```javascript
each = function (callbackFn) {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    callbackFn.call(this[i], this[i], i);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Collection.prototype.forEach"></a>[function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>forEach ()](#apidoc.element.johnny-five.Collection.prototype.forEach)
- description and source-code
```javascript
forEach = function () {
  [].forEach.apply(this, arguments);
}
```
- example usage
```shell
...
  setInterval(function() {
if (raw === null) {
  return;
}
var didOrientationChange = false;
var didCalibrationChange = false;

["heading", "roll", "pitch"].forEach(function(el) {
  if (state.euler[el] !== raw.orientation.euler[el]) {
    didOrientationChange = true;
  }
  state.euler[el] = raw.orientation.euler[el];
});

["w", "x", "y", "z"].forEach(function(el) {
...
```

#### <a name="apidoc.element.johnny-five.Collection.prototype.includes"></a>[function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>includes ()](#apidoc.element.johnny-five.Collection.prototype.includes)
- description and source-code
```javascript
includes = function () {
  return [].includes.apply(this, arguments);
}
```
- example usage
```shell
...
address = EVS.BANK_A;
bank = "a";
  } else {
address = EVS.BANK_B;
bank = "b";
  }

  if (pin.includes("M")) {
motor = pin.endsWith("M1") ? EVS.S1 : EVS.S2;
  }

  if (pin.includes("S")) {
endsWithS1 = pin.endsWith("S1");

// Used for reading 2 byte integer values from raw sensors
...
```

#### <a name="apidoc.element.johnny-five.Collection.prototype.indexOf"></a>[function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>indexOf ()](#apidoc.element.johnny-five.Collection.prototype.indexOf)
- description and source-code
```javascript
indexOf = function () {
  return [].indexOf.apply(this, arguments);
}
```
- example usage
```shell
...





Object.defineProperty(Array.prototype, "includes", {
  value: function(entry) {
    return this.indexOf(entry) !== -1;
  },
  enumerable: false,
  configurable: false,
  writable: false
});
...
```

#### <a name="apidoc.element.johnny-five.Collection.prototype.map"></a>[function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>map ()](#apidoc.element.johnny-five.Collection.prototype.map)
- description and source-code
```javascript
map = function () {
  return [].map.apply(this, arguments);
}
```
- example usage
```shell
...
}

state.emitter = new Led({
  board: this.board,
  pin: this.opts.emitter
});

state.sensorStates = this.pins.map(function(pin) {
  var sensorState = {
    sensor: new Sensor({
      board: this.board,
      freq: this.freq,
      pin: pin
    }),
    rawValue: 0,
...
```

#### <a name="apidoc.element.johnny-five.Collection.prototype.slice"></a>[function <span class="apidocSignatureSpan">johnny-five.Collection.prototype.</span>slice ()](#apidoc.element.johnny-five.Collection.prototype.slice)
- description and source-code
```javascript
slice = function () {
  return new this.constructor([].slice.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Color"></a>[module johnny-five.Color](#apidoc.module.johnny-five.Color)

#### <a name="apidoc.element.johnny-five.Color.Color"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Color (opts)](#apidoc.element.johnny-five.Color.Color)
- description and source-code
```javascript
function Color(opts) {

  if (!(this instanceof Color)) {
    return new Color(opts);
  }

  var controller = null;
  var state = {};
  var freq = opts.freq || 25;
  var raw = 0;
  var last = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (typeof opts.controller === "string") {
    controller = Controllers[opts.controller];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    throw new Error("Color expects a valid controller");
  }

  priv.set(this, state);

  Board.Controller.call(this, controller, opts);

  if (!this.toRGB) {
    this.toRGB = opts.toRGB || function(x) {
      return x;
    };
  }

  Object.defineProperties(this, {
    value: {
      get: function() {
        return raw;
      }
    },
    rgb: {
      get: function() {
        return this.toRGB(raw).reduce(function(accum, value, index) {
          accum[colorNames[index]] = value;
          return accum;
        }, {});
      }
    }
  });

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw === undefined) {
      return;
    }

    var data = {
      rgb: this.rgb,
    };

    this.emit("data", data);

    if (raw !== last) {
      last = raw;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Color.hexCode"></a>[function <span class="apidocSignatureSpan">johnny-five.Color.</span>hexCode (rgb)](#apidoc.element.johnny-five.Color.hexCode)
- description and source-code
```javascript
hexCode = function (rgb) {
  if (rgb.red === undefined || rgb.green === undefined || rgb.blue === undefined) {
    return null;
  }
  return rgb.length === 0 ? "unknown" : colorNames.reduce(function(accum, name) {
    return accum += pad(rgb[name].toString(16), 2);
  }, "");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Color.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Color.</span>super_ ()](#apidoc.element.johnny-five.Color.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Compass"></a>[module johnny-five.Compass](#apidoc.module.johnny-five.Compass)

#### <a name="apidoc.element.johnny-five.Compass.Compass"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Compass (opts)](#apidoc.element.johnny-five.Compass.Compass)
- description and source-code
```javascript
function Compass(opts) {

  if (!(this instanceof Compass)) {
    return new Compass(opts);
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var freq = opts.freq || 25;
  var controller = null;
  var raw = {
    x: null,
    y: null,
    z: null,
  };
  var state = {
    x: 0,
    y: 0,
    z: 0,
    scale: 0,
    register: 0,
    heading: 0
  };

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    throw new Error("Compass expects a valid controller");
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toScaledHeading) {
    this.toScaledHeading = opts.toScaledHeading || function(raw) {
      return raw;
    };
  }

  priv.set(this, state);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw.x === null) {
      return;
    }
    var isChange = false;

    state.x = raw.x;
    state.y = raw.y;
    state.z = raw.z;

    var heading = this.heading;

    if (heading !== state.heading) {
      state.heading = heading;
      isChange = true;
    }

    this.emit("data", {
      heading: state.heading
    });

    if (isChange) {
      this.emit("change", {
        heading: state.heading
      });
    }
  }.bind(this), freq);

  Object.defineProperties(this, {
<span class="apidocCodeCommentSpan">    /**
     * [read-only] Bearing information
     * @name bearing
     * @property
     * @type Object
     *
     *
        name
        abbr
        low
        mid
        high
        heading
     *
     */
</span>
    bearing: {
      get: function() {
        var length = Compass.Points.length;
        var heading = Math.floor(this.heading);
        var point;

        for (var i = 0; i < length; i++) {
          point = Compass.Points[i];

          if (point.range.includes(heading)) {
            // Specify fields to return to avoid returning the
            // range array (too much noisy data)
            return {
              name: point.name,
              abbr: point.abbr,
              low: point.low,
              high: point.high,
              heading: heading
            };
          }
        }
      }
    },

    /**
     * [read-only] Heading (azimuth)
     * @name heading
     * @property
     * @type number
     */
    heading: {
      get: function() {
        return this.toScaledHeading(raw);
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Compass.Scale"></a>[function <span class="apidocSignatureSpan">johnny-five.Compass.</span>Scale (gauss)](#apidoc.element.johnny-five.Compass.Scale)
- description and source-code
```javascript
Scale = function (gauss) {

  if (gauss === 0.88) {
    this.register = 0x00;
    this.scale = 0.73;
  } else if (gauss === 1.3) {
    this.register = 0x01;
    this.scale = 0.92;
  } else if (gauss === 1.9) {
    this.register = 0x02;
    this.scale = 1.22;
  } else if (gauss === 2.5) {
    this.register = 0x03;
    this.scale = 1.52;
  } else if (gauss === 4.0) {
    this.register = 0x04;
    this.scale = 2.27;
  } else if (gauss === 4.7) {
    this.register = 0x05;
    this.scale = 2.56;
  } else if (gauss === 5.6) {
    this.register = 0x06;
    this.scale = 3.03;
  } else if (gauss === 8.1) {
    this.register = 0x07;
    this.scale = 4.35;
  } else {
    this.register = 0x00;
    this.scale = 1;
  }

  // Setting is in the top 3 bits of the register.
  this.register = this.register << 5;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Compass.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Compass.</span>super_ ()](#apidoc.element.johnny-five.Compass.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.ESC"></a>[module johnny-five.ESC](#apidoc.module.johnny-five.ESC)

#### <a name="apidoc.element.johnny-five.ESC.ESC"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>ESC (opts)](#apidoc.element.johnny-five.ESC.ESC)
- description and source-code
```javascript
function ESC(opts) {
  if (!(this instanceof ESC)) {
    return new ESC(opts);
  }

  var controller = null;
  var pinValue;
  var device;
  var state = {
    // All speed history for this ESC
    // history = [
    //   {
    //     timestamp: Date.now(),
    //     speed: speed
    //   }
    // ];
    history: [],
    value: 0
  };

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  priv.set(this, state);

  this.startAt = typeof opts.startAt !== "undefined" ? opts.startAt : null;
  this.neutral = opts.neutral;
  this.range = opts.range || [0, 100];
  this.pwmRange = opts.pwmRange || [544, 2400];
  this.interval = null;

  // StandardFirmata on Arduino allows controlling
  // servos from analog pins.
  // If we're currently operating with an Arduino
  // and the user has provided an analog pin name
  // (eg. "A0", "A5" etc.), parse out the numeric
  // value and capture the fully qualified analog
  // pin number.
  if (typeof opts.controller === "undefined" && Pins.isFirmata(this)) {
    if (typeof pinValue === "string" && pinValue[0] === "A") {
      pinValue = this.io.analogPins[+pinValue.slice(1)];
    }

    pinValue = +pinValue;

    // If the board's default pin normalization
    // came up with something different, use the
    // the local value.
    if (!Number.isNaN(pinValue) && this.pin !== pinValue) {
      this.pin = pinValue;
    }
  }

  // Allow users to pass in custom device types
  device = typeof opts.device === "string" ?
    Devices[opts.device] : opts.device;

  if (!device) {
    device = Devices.FORWARD;
  }

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (!controller) {
    controller = Controllers.DEFAULT;
  }

  Object.defineProperties(this, Object.assign({}, device, controller, {
    value: {
      get: function() {
        return state.value;
      }
    },
    history: {
      get: function() {
        return state.history.slice(-5);
      }
    },
    last: {
      get: function() {
        return state.history[state.history.length - 1] || {
          last: null
        };
      }
    }
  }));

  this.initialize(opts);

  if (this.deviceName !== "FORWARD") {
    if (Number.isNaN(+this.neutral)) {
      throw new Error("Directional speed controllers require a neutral point from 0-100 (number)");
    }

    this.startAt = this.neutral;
  }

  // Match either null or undefined, but not 0
  if (this.startAt !== null && this.startAt !== undefined) {
    this.speed(this.startAt);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESC.Array"></a>[function <span class="apidocSignatureSpan">johnny-five.ESC.</span>Array (numsOrObjects)](#apidoc.element.johnny-five.ESC.Array)
- description and source-code
```javascript
function ESCs(numsOrObjects) {
  if (!(this instanceof ESCs)) {
    return new ESCs(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: ESC
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESC.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.ESC.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.ESC.Collection)
- description and source-code
```javascript
function ESCs(numsOrObjects) {
  if (!(this instanceof ESCs)) {
    return new ESCs(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: ESC
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESC.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.ESC.</span>super_ ()](#apidoc.element.johnny-five.ESC.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.ESC.prototype"></a>[module johnny-five.ESC.prototype](#apidoc.module.johnny-five.ESC.prototype)

#### <a name="apidoc.element.johnny-five.ESC.prototype.brake"></a>[function <span class="apidocSignatureSpan">johnny-five.ESC.prototype.</span>brake ()](#apidoc.element.johnny-five.ESC.prototype.brake)
- description and source-code
```javascript
brake = function () {
  var state = priv.get(this);
  var speed = this.neutral || 0;

  this.speed(speed);

  state.history.push({
    timestamp: Date.now(),
    speed: speed
  });

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESC.prototype.forward"></a>[function <span class="apidocSignatureSpan">johnny-five.ESC.prototype.</span>forward (speed)](#apidoc.element.johnny-five.ESC.prototype.forward)
- description and source-code
```javascript
forward = function (speed) {
  this.dir(speed, dir);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESC.prototype.fwd"></a>[function <span class="apidocSignatureSpan">johnny-five.ESC.prototype.</span>fwd (speed)](#apidoc.element.johnny-five.ESC.prototype.fwd)
- description and source-code
```javascript
fwd = function (speed) {
  this.dir(speed, dir);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESC.prototype.rev"></a>[function <span class="apidocSignatureSpan">johnny-five.ESC.prototype.</span>rev (speed)](#apidoc.element.johnny-five.ESC.prototype.rev)
- description and source-code
```javascript
rev = function (speed) {
  this.dir(speed, dir);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESC.prototype.reverse"></a>[function <span class="apidocSignatureSpan">johnny-five.ESC.prototype.</span>reverse (speed)](#apidoc.element.johnny-five.ESC.prototype.reverse)
- description and source-code
```javascript
reverse = function (speed) {
  this.dir(speed, dir);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESC.prototype.speed"></a>[function <span class="apidocSignatureSpan">johnny-five.ESC.prototype.</span>speed (speed)](#apidoc.element.johnny-five.ESC.prototype.speed)
- description and source-code
```javascript
speed = function (speed) {
  var state = priv.get(this);
  var history = state.history;
  var noInterval = false;
  var steps = 0;
  var lspeed, hspeed;

  speed = Fn.constrain(speed, this.range[0], this.range[1]);

  if (this.interval) {
    // Bail out if speed is the same as whatever was
    // last _provided_
    if (this.value === speed) {
      return this;
    } else {
      clearInterval(this.interval);
      this.interval = null;
    }
  }

  state.value = speed;

  // This is the very first speed command being received.
  // Safe to assume that the ESC and Brushless motor are
  // not yet moving.
  if (history.length === 0) {
    noInterval = true;
  }

  // Bail out if speed is the same as whatever was
  // last _written_

  if (this.last.speed === speed) {
    return this;
  }

  lspeed = this.last.speed;
  hspeed = speed;
  steps = Math.ceil(Math.abs(lspeed - hspeed));

  if (!steps || steps === 1) {
    noInterval = true;
  }

  if (noInterval) {
    this.write(this.pin, Fn.fscale(speed, 0, 100, 0, 180));

    history.push({
      timestamp: Date.now(),
      speed: speed
    });
    return this;
  }

  var throttle = lspeed;

  this.interval = setInterval(function() {

    if (hspeed > throttle) {
      throttle++;
    } else {
      throttle--;
    }

    this.write(this.pin, (throttle * 180 / 100));

    history.push({
      timestamp: Date.now(),
      speed: throttle
    });

    if (steps) {
      steps--;

      if (!steps) {
        clearInterval(this.interval);
        this.interval = null;
      }
    }
  }.bind(this), 1);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESC.prototype.stop"></a>[function <span class="apidocSignatureSpan">johnny-five.ESC.prototype.</span>stop ()](#apidoc.element.johnny-five.ESC.prototype.stop)
- description and source-code
```javascript
stop = function () {
  var state = priv.get(this);
  var history = state.history;
  var speed = this.type === "bidirectional" ? this.neutral : 0;

  this.write(this.pin, Fn.fscale(speed, 0, 100, 0, 180));

  history.push({
    timestamp: Date.now(),
    speed: speed
  });

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.ESCs"></a>[module johnny-five.ESCs](#apidoc.module.johnny-five.ESCs)

#### <a name="apidoc.element.johnny-five.ESCs.ESCs"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>ESCs (numsOrObjects)](#apidoc.element.johnny-five.ESCs.ESCs)
- description and source-code
```javascript
function ESCs(numsOrObjects) {
  if (!(this instanceof ESCs)) {
    return new ESCs(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: ESC
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESCs.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.ESCs.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.ESCs.super_)
- description and source-code
```javascript
function Collection(numsOrObjects) {
  var Type = this.type;
  var initObjects = [];

  this.length = 0;

  if (Array.isArray(numsOrObjects)) {
    initObjects = numsOrObjects;
  } else {
    // Initialize with a Shared Properties object
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (Array.isArray(numsOrObjects.pins)) {
      var keys = Object.keys(numsOrObjects).filter(function(key) {
        return key !== "pins";
      });
      initObjects = numsOrObjects.pins.map(function(pin) {
        var obj = {};

        if (Array.isArray(pin)) {
          obj.pins = pin;
        } else {
          obj.pin = pin;
        }

        return keys.reduce(function(accum, key) {
          accum[key] = numsOrObjects[key];
          return accum;
        }, obj);
      });
    }
  }

  /* istanbul ignore else */
  if (initObjects.length) {
    while (initObjects.length) {
      var numOrObject = initObjects.shift();

      // When a Type exists, respect it!
      if (typeof Type === "function") {
        if (!(numOrObject instanceof Type || numOrObject instanceof this.constructor)) {
          numOrObject = new Type(numOrObject);
        }
      }

      this.add(numOrObject);
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.ESCs.prototype"></a>[module johnny-five.ESCs.prototype](#apidoc.module.johnny-five.ESCs.prototype)

#### <a name="apidoc.element.johnny-five.ESCs.prototype.brake"></a>[function <span class="apidocSignatureSpan">johnny-five.ESCs.prototype.</span>brake ()](#apidoc.element.johnny-five.ESCs.prototype.brake)
- description and source-code
```javascript
brake = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESCs.prototype.forward"></a>[function <span class="apidocSignatureSpan">johnny-five.ESCs.prototype.</span>forward ()](#apidoc.element.johnny-five.ESCs.prototype.forward)
- description and source-code
```javascript
forward = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESCs.prototype.fwd"></a>[function <span class="apidocSignatureSpan">johnny-five.ESCs.prototype.</span>fwd ()](#apidoc.element.johnny-five.ESCs.prototype.fwd)
- description and source-code
```javascript
fwd = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESCs.prototype.rev"></a>[function <span class="apidocSignatureSpan">johnny-five.ESCs.prototype.</span>rev ()](#apidoc.element.johnny-five.ESCs.prototype.rev)
- description and source-code
```javascript
rev = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESCs.prototype.reverse"></a>[function <span class="apidocSignatureSpan">johnny-five.ESCs.prototype.</span>reverse ()](#apidoc.element.johnny-five.ESCs.prototype.reverse)
- description and source-code
```javascript
reverse = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESCs.prototype.speed"></a>[function <span class="apidocSignatureSpan">johnny-five.ESCs.prototype.</span>speed ()](#apidoc.element.johnny-five.ESCs.prototype.speed)
- description and source-code
```javascript
speed = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ESCs.prototype.stop"></a>[function <span class="apidocSignatureSpan">johnny-five.ESCs.prototype.</span>stop ()](#apidoc.element.johnny-five.ESCs.prototype.stop)
- description and source-code
```javascript
stop = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Expander"></a>[module johnny-five.Expander](#apidoc.module.johnny-five.Expander)

#### <a name="apidoc.element.johnny-five.Expander.Expander"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Expander (opts)](#apidoc.element.johnny-five.Expander.Expander)
- description and source-code
```javascript
function Expander(opts) {
  if (!(this instanceof Expander)) {
    return new Expander(opts);
  }

  Base.call(this);

  var expander = null;
  var addressError = "Expander cannot reuse an active address";
  var controller = null;
  var state = {};
  var controllerValue;

  if (typeof opts === "string") {
    controllerValue = opts;
  }

  Board.Component.call(
    this, opts = Board.Options(opts), {
      normalizePin: false,
      requestPin: false
    }
  );

  expander = active.get(this.address);

  if (expander) {
    if (this.bus && (expander.bus !== undefined && expander.bus === this.bus)) {
      addressError += " on this bus";
    }
    throw new Error(addressError);
  }

  if (typeof opts.controller === "undefined" && controllerValue) {
    opts.controller = controllerValue;
  }

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    throw new Error("Expander expects a valid controller");
  }

  Board.Controller.call(this, controller, opts);

  priv.set(this, state);

  if (typeof this.initialize === "function") {
    this.initialize(opts);
  }

  active.set(this.address, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Expander.byAddress"></a>[function <span class="apidocSignatureSpan">johnny-five.Expander.</span>byAddress (address)](#apidoc.element.johnny-five.Expander.byAddress)
- description and source-code
```javascript
byAddress = function (address) {
  return active.get(address);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Expander.byController"></a>[function <span class="apidocSignatureSpan">johnny-five.Expander.</span>byController (name)](#apidoc.element.johnny-five.Expander.byController)
- description and source-code
```javascript
byController = function (name) {
  var controller = null;

  active.forEach(function(value) {
    if (value.name === name.toUpperCase()) {
      controller = value;
    }
  });
  return controller;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Expander.get"></a>[function <span class="apidocSignatureSpan">johnny-five.Expander.</span>get (required)](#apidoc.element.johnny-five.Expander.get)
- description and source-code
```javascript
get = function (required) {

  if (!required.address || !required.controller) {
    throw new Error("Expander.get(...) requires an address and controller");
  }

  if (required.address !== undefined) {
    required.address = Number(required.address);
  }

  if (Number.isNaN(required.address)) {
    throw new Error("Expander.get(...) expects address to be a number");
  }

  if (typeof required.controller !== "string") {
    throw new Error("Expander.get(...) expects controller name to be a string");
  }

  // If no address was sent them assume the request wants
  // to re-use an active Expander, by controller name.
  // if (!required.address) {
  //   return Expander.byController(required.controller);
  // }

  var expander = active.get(required.address);

  if (expander && (expander.name === required.controller.toUpperCase())) {
    return expander;
  }

  return new Expander(required);
}
```
- example usage
```shell
...

var Controllers = {

  BNO055: {
initialize: {
  value: function(opts, dataHandler) {
    var IMU = require("./imu"),
      driver = IMU.Drivers.get(this.board, "BNO055", opts);

    driver.on("data", function(data) {
      dataHandler(data);
    });
  }
},
toScaledEuler: {
...
```

#### <a name="apidoc.element.johnny-five.Expander.hasController"></a>[function <span class="apidocSignatureSpan">johnny-five.Expander.</span>hasController (key)](#apidoc.element.johnny-five.Expander.hasController)
- description and source-code
```javascript
hasController = function (key) {
  return Controllers[key] !== undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Expander.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Expander.</span>super_ ()](#apidoc.element.johnny-five.Expander.super_)
- description and source-code
```javascript
function Base() {
  Emitter.call(this);

  this.HIGH = 1;
  this.LOW = 0;
  this.isReady = false;

  this.MODES = {};
  this.pins = [];
  this.analogPins = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Expander.super_"></a>[module johnny-five.Expander.super_](#apidoc.module.johnny-five.Expander.super_)

#### <a name="apidoc.element.johnny-five.Expander.super_.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Expander.</span>super_ ()](#apidoc.element.johnny-five.Expander.super_.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Fn"></a>[module johnny-five.Fn](#apidoc.module.johnny-five.Fn)

#### <a name="apidoc.element.johnny-five.Fn._BV"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>_BV (bit)](#apidoc.element.johnny-five.Fn._BV)
- description and source-code
```javascript
_BV = function (bit) {
  return 1 << bit;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.bitSize"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>bitSize (n)](#apidoc.element.johnny-five.Fn.bitSize)
- description and source-code
```javascript
bitSize = function (n) {
  return Math.round(Math.log2(n));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.bitValue"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>bitValue (bit)](#apidoc.element.johnny-five.Fn.bitValue)
- description and source-code
```javascript
bitValue = function (bit) {
  return 1 << bit;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.bv"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>bv (bit)](#apidoc.element.johnny-five.Fn.bv)
- description and source-code
```javascript
bv = function (bit) {
  return 1 << bit;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.cloneDeep"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>cloneDeep (value)](#apidoc.element.johnny-five.Fn.cloneDeep)
- description and source-code
```javascript
function cloneDeep(value) {
  return baseClone(value, true, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.constrain"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>constrain (value, lower, upper)](#apidoc.element.johnny-five.Fn.constrain)
- description and source-code
```javascript
constrain = function (value, lower, upper) {
  return Math.min(upper, Math.max(lower, value));
}
```
- example usage
```shell
...

function calibratedValues() {
  return this.raw.map(function(value, i) {
    var max = this.calibration.max[i],
      min = this.calibration.min[i];

    var scaled = __.scale(value, min, max, CALIBRATED_MIN_VALUE, CALIBRATED_MAX_VALUE);
    return __.constrain(scaled, CALIBRATED_MIN_VALUE, CALIBRATED_MAX_VALUE);
  }, this);
}

function maxLineValue() {
  return (this.sensors.length - 1) * CALIBRATED_MAX_VALUE;
}
...
```

#### <a name="apidoc.element.johnny-five.Fn.debounce"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>debounce (func, wait, options)](#apidoc.element.johnny-five.Fn.debounce)
- description and source-code
```javascript
function debounce(func, wait, options) {
  var lastArgs,
      lastThis,
      maxWait,
      result,
      timerId,
      lastCallTime,
      lastInvokeTime = 0,
      leading = false,
      maxing = false,
      trailing = true;

  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  wait = toNumber(wait) || 0;
  if (isObject(options)) {
    leading = !!options.leading;
    maxing = 'maxWait' in options;
    maxWait = maxing ? nativeMax(toNumber(options.maxWait) || 0, wait) : maxWait;
    trailing = 'trailing' in options ? !!options.trailing : trailing;
  }

  function invokeFunc(time) {
    var args = lastArgs,
        thisArg = lastThis;

    lastArgs = lastThis = undefined;
    lastInvokeTime = time;
    result = func.apply(thisArg, args);
    return result;
  }

  function leadingEdge(time) {
    // Reset any 'maxWait' timer.
    lastInvokeTime = time;
    // Start the timer for the trailing edge.
    timerId = setTimeout(timerExpired, wait);
    // Invoke the leading edge.
    return leading ? invokeFunc(time) : result;
  }

  function remainingWait(time) {
    var timeSinceLastCall = time - lastCallTime,
        timeSinceLastInvoke = time - lastInvokeTime,
        result = wait - timeSinceLastCall;

    return maxing ? nativeMin(result, maxWait - timeSinceLastInvoke) : result;
  }

  function shouldInvoke(time) {
    var timeSinceLastCall = time - lastCallTime,
        timeSinceLastInvoke = time - lastInvokeTime;

    // Either this is the first call, activity has stopped and we're at the
    // trailing edge, the system time has gone backwards and we're treating
    // it as the trailing edge, or we've hit the 'maxWait' limit.
    return (lastCallTime === undefined || (timeSinceLastCall >= wait) ||
      (timeSinceLastCall < 0) || (maxing && timeSinceLastInvoke >= maxWait));
  }

  function timerExpired() {
    var time = now();
    if (shouldInvoke(time)) {
      return trailingEdge(time);
    }
    // Restart the timer.
    timerId = setTimeout(timerExpired, remainingWait(time));
  }

  function trailingEdge(time) {
    timerId = undefined;

    // Only invoke if we have 'lastArgs' which means 'func' has been
    // debounced at least once.
    if (trailing && lastArgs) {
      return invokeFunc(time);
    }
    lastArgs = lastThis = undefined;
    return result;
  }

  function cancel() {
    if (timerId !== undefined) {
      clearTimeout(timerId);
    }
    lastInvokeTime = 0;
    lastArgs = lastCallTime = lastThis = timerId = undefined;
  }

  function flush() {
    return timerId === undefined ? result : trailingEdge(now());
  }

  function debounced() {
    var time = now(),
        isInvoking = shouldInvoke(time);

    lastArgs = arguments;
    lastThis = this;
    lastCallTime = time;

    if (isInvoking) {
      if (timerId === undefined) {
        return leadingEdge(lastCallTime);
      }
      if (maxing) {
        // Handle invocations in a tight loop.
        timerId = setTimeout(timerExpired, wait);
        return invokeFunc(lastCallTime);
      }
    }
    if (timerId === undefined) {
      timerId = setTimeout(timerExpired, wait);
    }
    return result;
  }
  debounced.cancel = cancel;
  debounced.flush = flush;
  return debounced;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.fma"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>fma (a, b, c)](#apidoc.element.johnny-five.Fn.fma)
- description and source-code
```javascript
fma = function (a, b, c) {
  var aHigh = 134217729 * a;
  var aLow;

  aHigh = aHigh + (a - aHigh);
  aLow = a - aHigh;

  var bHigh = 134217729 * b;
  var bLow;

  bHigh = bHigh + (b - bHigh);
  bLow = b - bHigh;

  var r1 = a * b;
  var r2 = -r1 + aHigh * bHigh + aHigh * bLow + aLow * bHigh + aLow * bLow;

  var s = r1 + c;
  var t = (r1 - (s - c)) + (c - (s - r1));

  return s + (t + r2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.fmap"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>fmap (value, fromLow, fromHigh, toLow, toHigh)](#apidoc.element.johnny-five.Fn.fmap)
- description and source-code
```javascript
fmap = function (value, fromLow, fromHigh, toLow, toHigh) {
  f32A[0] = (value - fromLow) * (toHigh - toLow) / (fromHigh - fromLow) + toLow;
  return f32A[0];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.fscale"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>fscale (value, fromLow, fromHigh, toLow, toHigh)](#apidoc.element.johnny-five.Fn.fscale)
- description and source-code
```javascript
fscale = function (value, fromLow, fromHigh, toLow, toHigh) {
  f32A[0] = (value - fromLow) * (toHigh - toLow) / (fromHigh - fromLow) + toLow;
  return f32A[0];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.inRange"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>inRange (value, lower, upper)](#apidoc.element.johnny-five.Fn.inRange)
- description and source-code
```javascript
inRange = function (value, lower, upper) {
  return value >= lower && value <= upper;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.int16"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>int16 (msb, lsb)](#apidoc.element.johnny-five.Fn.int16)
- description and source-code
```javascript
int16 = function (msb, lsb) {
  var result = (msb << 8) | lsb;

  // Check highest bit for sign. If on, value is negative
  return result >> 15 ? ((result ^ 0xFFFF) + 1) * -1 : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.int24"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>int24 (b16, b8, b0)](#apidoc.element.johnny-five.Fn.int24)
- description and source-code
```javascript
int24 = function (b16, b8, b0) {
  var result = (b16 << 16) | (b8 << 8) | b0;

  // Check highest bit for sign. If on, value is negative
  return result >> 23 ? ((result ^ 0xFFFFFF) + 1) * -1 : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.int32"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>int32 (b24, b16, b8, b0)](#apidoc.element.johnny-five.Fn.int32)
- description and source-code
```javascript
int32 = function (b24, b16, b8, b0) {
  var result = (b24 << 24) | (b16 << 16) | (b8 << 8) | b0;
  // Check highest bit for sign. If on, value is negative
  return result >> 31 ? ((result ^ 0xFFFFFFFF) + 1) * -1 : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.map"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>map (value, fromLow, fromHigh, toLow, toHigh)](#apidoc.element.johnny-five.Fn.map)
- description and source-code
```javascript
map = function (value, fromLow, fromHigh, toLow, toHigh) {
  return ((value - fromLow) * (toHigh - toLow) / (fromHigh - fromLow) + toLow) | 0;
}
```
- example usage
```shell
...
}

state.emitter = new Led({
  board: this.board,
  pin: this.opts.emitter
});

state.sensorStates = this.pins.map(function(pin) {
  var sensorState = {
    sensor: new Sensor({
      board: this.board,
      freq: this.freq,
      pin: pin
    }),
    rawValue: 0,
...
```

#### <a name="apidoc.element.johnny-five.Fn.range"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>range (lower, upper, tick)](#apidoc.element.johnny-five.Fn.range)
- description and source-code
```javascript
range = function (lower, upper, tick) {

  if (arguments.length === 1) {
    upper = lower - 1;
    lower = 0;
  }

  lower = lower || 0;
  upper = upper || 0;
  tick = tick || 1;

  var len = Math.max(Math.ceil((upper - lower) / tick), 0),
    idx = 0,
    range = [];

  while (idx <= len) {
    range[idx++] = lower;
    lower += tick;
  }

  return range;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.s10"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s10 (value)](#apidoc.element.johnny-five.Fn.s10)
- description and source-code
```javascript
s10 = function (value) {
  if (value > halfMinusOne) {
    value -= decimal;
  }
  return Fn.constrain(value, -half, halfMinusOne);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.s12"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s12 (value)](#apidoc.element.johnny-five.Fn.s12)
- description and source-code
```javascript
s12 = function (value) {
  if (value > halfMinusOne) {
    value -= decimal;
  }
  return Fn.constrain(value, -half, halfMinusOne);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.s16"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s16 (value)](#apidoc.element.johnny-five.Fn.s16)
- description and source-code
```javascript
s16 = function (value) {
  if (value > halfMinusOne) {
    value -= decimal;
  }
  return Fn.constrain(value, -half, halfMinusOne);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.s20"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s20 (value)](#apidoc.element.johnny-five.Fn.s20)
- description and source-code
```javascript
s20 = function (value) {
  if (value > halfMinusOne) {
    value -= decimal;
  }
  return Fn.constrain(value, -half, halfMinusOne);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.s24"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s24 (value)](#apidoc.element.johnny-five.Fn.s24)
- description and source-code
```javascript
s24 = function (value) {
  if (value > halfMinusOne) {
    value -= decimal;
  }
  return Fn.constrain(value, -half, halfMinusOne);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.s32"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s32 (value)](#apidoc.element.johnny-five.Fn.s32)
- description and source-code
```javascript
s32 = function (value) {
  if (value > halfMinusOne) {
    value -= decimal;
  }
  return Fn.constrain(value, -half, halfMinusOne);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.s4"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s4 (value)](#apidoc.element.johnny-five.Fn.s4)
- description and source-code
```javascript
s4 = function (value) {
  if (value > halfMinusOne) {
    value -= decimal;
  }
  return Fn.constrain(value, -half, halfMinusOne);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.s8"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>s8 (value)](#apidoc.element.johnny-five.Fn.s8)
- description and source-code
```javascript
s8 = function (value) {
  if (value > halfMinusOne) {
    value -= decimal;
  }
  return Fn.constrain(value, -half, halfMinusOne);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.scale"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>scale (value, fromLow, fromHigh, toLow, toHigh)](#apidoc.element.johnny-five.Fn.scale)
- description and source-code
```javascript
scale = function (value, fromLow, fromHigh, toLow, toHigh) {
  return ((value - fromLow) * (toHigh - toLow) / (fromHigh - fromLow) + toLow) | 0;
}
```
- example usage
```shell
...


function calibratedValues() {
  return this.raw.map(function(value, i) {
    var max = this.calibration.max[i],
      min = this.calibration.min[i];

    var scaled = __.scale(value, min, max, CALIBRATED_MIN_VALUE, CALIBRATED_MAX_VALUE);
    return __.constrain(scaled, CALIBRATED_MIN_VALUE, CALIBRATED_MAX_VALUE);
  }, this);
}

function maxLineValue() {
  return (this.sensors.length - 1) * CALIBRATED_MAX_VALUE;
}
...
```

#### <a name="apidoc.element.johnny-five.Fn.square"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>square (x)](#apidoc.element.johnny-five.Fn.square)
- description and source-code
```javascript
square = function (x) {
  return x * x;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.sum"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>sum (values)](#apidoc.element.johnny-five.Fn.sum)
- description and source-code
```javascript
function sum(values) {
  var vals;
  if (Array.isArray(values)) {
    vals = values;
  } else {
    vals = [].slice.call(arguments);
  }
  return vals.reduce(function(accum, value) {
    return accum + value;
  }, 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.toFixed"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>toFixed (number, digits)](#apidoc.element.johnny-five.Fn.toFixed)
- description and source-code
```javascript
toFixed = function (number, digits) {
  // Guard against error when number is null or undefined
  // Cast result as number
  return +(number || 0).toFixed(digits);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.u10"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u10 (value)](#apidoc.element.johnny-five.Fn.u10)
- description and source-code
```javascript
u10 = function (value) {
  if (value < 0) {
    value += decimal;
  }
  return Fn.constrain(value, 0, decimal - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.u12"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u12 (value)](#apidoc.element.johnny-five.Fn.u12)
- description and source-code
```javascript
u12 = function (value) {
  if (value < 0) {
    value += decimal;
  }
  return Fn.constrain(value, 0, decimal - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.u16"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u16 (value)](#apidoc.element.johnny-five.Fn.u16)
- description and source-code
```javascript
u16 = function (value) {
  if (value < 0) {
    value += decimal;
  }
  return Fn.constrain(value, 0, decimal - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.u20"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u20 (value)](#apidoc.element.johnny-five.Fn.u20)
- description and source-code
```javascript
u20 = function (value) {
  if (value < 0) {
    value += decimal;
  }
  return Fn.constrain(value, 0, decimal - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.u24"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u24 (value)](#apidoc.element.johnny-five.Fn.u24)
- description and source-code
```javascript
u24 = function (value) {
  if (value < 0) {
    value += decimal;
  }
  return Fn.constrain(value, 0, decimal - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.u32"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u32 (value)](#apidoc.element.johnny-five.Fn.u32)
- description and source-code
```javascript
u32 = function (value) {
  if (value < 0) {
    value += decimal;
  }
  return Fn.constrain(value, 0, decimal - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.u4"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u4 (value)](#apidoc.element.johnny-five.Fn.u4)
- description and source-code
```javascript
u4 = function (value) {
  if (value < 0) {
    value += decimal;
  }
  return Fn.constrain(value, 0, decimal - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.u8"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>u8 (value)](#apidoc.element.johnny-five.Fn.u8)
- description and source-code
```javascript
u8 = function (value) {
  if (value < 0) {
    value += decimal;
  }
  return Fn.constrain(value, 0, decimal - 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.uid"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>uid ()](#apidoc.element.johnny-five.Fn.uid)
- description and source-code
```javascript
uid = function () {
  return "xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx".replace(/[xy]/g, function(chr) {
    var rnd = Math.random() * 16 | 0;
    return (chr === "x" ? rnd : (rnd & 0x3 | 0x8)).toString(16);
  }).toUpperCase();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.uint16"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>uint16 (msb, lsb)](#apidoc.element.johnny-five.Fn.uint16)
- description and source-code
```javascript
uint16 = function (msb, lsb) {
  return (msb << 8) | lsb;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.uint24"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>uint24 (b16, b8, b0)](#apidoc.element.johnny-five.Fn.uint24)
- description and source-code
```javascript
uint24 = function (b16, b8, b0) {
  return (b16 << 16) | (b8 << 8) | b0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Fn.uint32"></a>[function <span class="apidocSignatureSpan">johnny-five.Fn.</span>uint32 (b24, b16, b8, b0)](#apidoc.element.johnny-five.Fn.uint32)
- description and source-code
```javascript
uint32 = function (b24, b16, b8, b0) {
  // Note: If you left-shift a byte by 24 in JS and that byte's
  // MSbit is 1, the resulting value will be negative because JS casts
  // bitwise operands (temporarily) to SIGNED 32-bit numbers. The
  // final >>> 0 causes the sign bit to be disregarded, making sure our
  // result is non-negative.
  return ((b24 << 24) | (b16 << 16) | (b8 << 8) | b0) >>> 0;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.GPS"></a>[module johnny-five.GPS](#apidoc.module.johnny-five.GPS)

#### <a name="apidoc.element.johnny-five.GPS.GPS"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>GPS (opts)](#apidoc.element.johnny-five.GPS.GPS)
- description and source-code
```javascript
function GPS(opts) {

  var breakout, receiver, chip, state;

  if (!(this instanceof GPS)) {
    return new GPS(opts);
  }

  // Allow users to pass in a 2 element array for rx and tx pins
  if (Array.isArray(opts)) {
    opts = {
      pins: {
        rx: opts[0],
        tx: opts[1],
        onOff: opts[2]
      }
    };
  }

  if (typeof opts.pins === "undefined") {
    opts.pins = {};
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );



  // Get user values for breakout, receiver and chip
  breakout = opts.breakout || {};
  receiver = opts.receiver;
  chip = opts.chip;

  // If a breakout is defined check for receiver and chip
  if (Breakouts[breakout]) {
    if (!receiver && Breakouts[breakout].receiver) {
      receiver = Breakouts[breakout].receiver.value;
    }

    if (!chip && Breakouts[breakout].chip) {
      chip = Breakouts[breakout].chip.value;
    }
  }

  // If a receiver was defined or derived but chip was not
  if (!chip) {
    if (receiver && Receivers[receiver].chip) {
      chip = Receivers[receiver].chip.value;
    } else {
      chip = "DEFAULT";
    }
  }

  // Allow users to pass in custom chip types
  chip = typeof chip === "string" ?
    Chips[chip] : opts.chip;

  // Allow users to pass in custom receiver types
  receiver = typeof receiver === "string" ?
    Receivers[receiver] : opts.receiver;

  // Chip decorates the instance
  Object.defineProperties(this, chip);

  // Receiver decorates this instance
  if (receiver) {
    Object.defineProperties(this, receiver);
  }

  // breakout decorates the instance
  if (opts.breakout) {
    breakout = typeof opts.breakout === "string" ?
      Breakouts[opts.breakout] : opts.breakout;

    Board.Controller.call(this, breakout, opts);
  }

  // If necessary set default property values
  this.fixed = opts.fixed || 6;
  this.baud = opts.baud || this.baud;

  // Create a "state" entry for privately
  // storing the state of the instance
  state = {
    sat: {},
    latitude: 0.0,
    longitude: 0.0,
    altitude: 0.0,
    speed: 0.0,
    course: 0.0,
    frequency: 1,
    lowPowerMode: false
  };

  priv.set(this, state);

  // Getters for private state values
  Object.defineProperties(this, {
    latitude: {
      get: function() {
        return state.latitude;
      }
    },
    longitude: {
      get: function() {
        return state.longitude;
      }
    },
    altitude: {
      get: function() {
        return state.altitude;
      }
    },
    sat: {
      get: function() {
        return state.sat;
      }
    },
    speed: {
      get: function() {
        return state.speed;
      }
    },
    course: {
      get: function() {
        return state.course;
      }
    },
    time: {
      get: function() {
        return state.time;
      }
    }
  });

  if (this.initialize) {
    this.initialize(opts);
  }

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.GPS.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.GPS.</span>super_ ()](#apidoc.element.johnny-five.GPS.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.GPS.prototype"></a>[module johnny-five.GPS.prototype](#apidoc.module.johnny-five.GPS.prototype)

#### <a name="apidoc.element.johnny-five.GPS.prototype.initialize"></a>[function <span class="apidocSignatureSpan">johnny-five.GPS.prototype.</span>initialize (opts)](#apidoc.element.johnny-five.GPS.prototype.initialize)
- description and source-code
```javascript
initialize = function (opts) {

  var state = priv.get(this);
  state.portId = opts.serialPort || opts.portId || opts.port || opts.bus || this.io.SERIAL_PORT_IDs.DEFAULT;

  // Set the pin modes
  ["tx", "rx"].forEach(function(pin) {
    if (this.pins[pin]) {
      this.io.pinMode(this.pins[pin], this.io.MODES.SERIAL);
    }
  }, this);

  if (this.pins.onOff) {
    this.io.pinMode(this.pins.onOff, this.io.MODES.OUTPUT);
    this.onOff = new Pin(this.pins.onOff);
  }

  this.io.serialConfig({
    portId: state.portId,
    baud: this.baud,
    rxPin: this.pins.rx,
    txPin: this.pins.tx
  });

  if (this.configure) {
    this.configure(function() {
      this.listen();
      if (opts.frequency) {
        this.frequency = opts.frequency;
      }
    }.bind(this));
  }

}
```
- example usage
```shell
...
    return raw;
  };
}

priv.set(this, state);

if (typeof this.initialize === "function") {
  this.initialize(opts, function(data) {
    raw = data;
  });
}

setInterval(function() {
  if (raw === null) {
    return;
...
```

#### <a name="apidoc.element.johnny-five.GPS.prototype.listen"></a>[function <span class="apidocSignatureSpan">johnny-five.GPS.prototype.</span>listen ()](#apidoc.element.johnny-five.GPS.prototype.listen)
- description and source-code
```javascript
listen = function () {

  var state = priv.get(this);
  var input = "";

  // Start the read loop
  this.io.serialRead(state.portId, function(data) {

    input += new Buffer(data).toString("ascii");
    var sentences = input.split("\r\n");

    if (sentences.length > 1) {
      for (var i = 0; i < sentences.length - 1; i++) {
        this.parseNmeaSentence(sentences[i]);
      }
      input = sentences[sentences.length - 1];
    }
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.GPS.prototype.parseNmeaSentence"></a>[function <span class="apidocSignatureSpan">johnny-five.GPS.prototype.</span>parseNmeaSentence (sentence)](#apidoc.element.johnny-five.GPS.prototype.parseNmeaSentence)
- description and source-code
```javascript
parseNmeaSentence = function (sentence) {

  var state = priv.get(this);
  var cksum = sentence.split("*");

  // Check for valid sentence
  if (cksum[1] !== getNmeaChecksum(cksum[0].substring(1))) {
    return;
  }

  this.emit("sentence", sentence);

  var segments = cksum[0].split(",");
  var last = {
    latitude: state.latitude,
    longitude: state.longitude,
    altitude: state.altitude,
    speed: state.speed,
    course: state.course
  };

  switch (segments[0]) {
    case "$GPGGA":
      // Time, position and fix related data
      state.time = segments[1];
      state.latitude = degToDec(segments[2], 2, segments[3], this.fixed);
      state.longitude = degToDec(segments[4], 3, segments[5], this.fixed);
      state.altitude = Number(segments[9]);
      break;

    case "$GPGSA":
      // Operating details
      state.sat.satellites = segments.slice(3, 15);
      state.sat.pdop = Number(segments[15]);
      state.sat.hdop = Number(segments[16]);
      state.sat.vdop = Number(segments[17]);
      this.emit("operations", sentence);
      break;

    case "$GPRMC":
      // GPS & Transit data
      state.time = segments[1];
      state.latitude = degToDec(segments[3], 2, segments[4], this.fixed);
      state.longitude = degToDec(segments[5], 3, segments[6], this.fixed);
      state.course = Number(segments[8]);
      state.speed = toFixed(segments[7] * 0.514444, this.fixed);
      break;

    case "$GPVTG":
      // Track Made Good and Ground Speed
      state.course = Number(segments[1]);
      state.speed = toFixed(segments[5] * 0.514444, this.fixed);
      break;

    case "$GPGSV":
      // Satellites in view
      break;

    case "$PGACK":
      // Acknowledge command
      this.emit("acknowledge", sentence);
      break;

    default:
      this.emit("unknown", sentence);
      break;
  }

  this.emit("data", {
    latitude: state.latitude,
    longitude: state.longitude,
    altitude: state.altitude,
    speed: state.speed,
    course: state.course,
    sat: state.sat,
    time: state.time
  });

  if (last.latitude !== state.latitude ||
    last.longitude !== state.longitude ||
    last.altitude !== state.altitude) {

    this.emit("change", {
      latitude: state.latitude,
      longitude: state.longitude,
      altitude: state.altitude
    });
  }

  if (last.speed !== state.speed ||
    last.course !== state.course) {

    this.emit("navigation", {
      speed: state.speed,
      course: state.course
    });
  }

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.GPS.prototype.sendCommand"></a>[function <span class="apidocSignatureSpan">johnny-five.GPS.prototype.</span>sendCommand (string)](#apidoc.element.johnny-five.GPS.prototype.sendCommand)
- description and source-code
```javascript
sendCommand = function (string) {

  var state = priv.get(this);
  var cc = [];

  // Convert the string to a charCode array
  for (var i = 0; i < string.length; ++i) {
    cc[i] = string.charCodeAt(i);
  }

  // Append *, checksum and cr/lf
  var hexsum = getNmeaChecksum(string.substring(1));
  cc.push(42, hexsum.charCodeAt(0), hexsum.charCodeAt(1), 13, 10);

  this.io.serialWrite(state.portId, cc);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Gripper"></a>[module johnny-five.Gripper](#apidoc.module.johnny-five.Gripper)

#### <a name="apidoc.element.johnny-five.Gripper.Gripper"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Gripper (opts)](#apidoc.element.johnny-five.Gripper.Gripper)
- description and source-code
```javascript
function Gripper(opts) {

  if (!(this instanceof Gripper)) {
    return new Gripper(opts);
  }

  // Default options mode, assume only when opts is a pin number
  if (typeof opts === "number") {
    opts = {
      servo: {
        pin: opts,
        range: [0, 180]
      },
      scale: [0, 10]
    };
  }

  // Default set() args to 0-10
  this.scale = opts.scale || [0, 10];

  // Setup servo
  // Allows pre-constructed servo or creating new servo.
  // Defaults for new Servo creation fall back to Servo defaults
  this.servo = opts.servo instanceof Servo ?
    opts.servo : new Servo(opts.servo);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Gripper.prototype"></a>[module johnny-five.Gripper.prototype](#apidoc.module.johnny-five.Gripper.prototype)

#### <a name="apidoc.element.johnny-five.Gripper.prototype.close"></a>[function <span class="apidocSignatureSpan">johnny-five.Gripper.prototype.</span>close ()](#apidoc.element.johnny-five.Gripper.prototype.close)
- description and source-code
```javascript
close = function () {
  return this.servo.to(
    api.args.apply(this, [].slice.call(arguments))
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Gripper.prototype.open"></a>[function <span class="apidocSignatureSpan">johnny-five.Gripper.prototype.</span>open ()](#apidoc.element.johnny-five.Gripper.prototype.open)
- description and source-code
```javascript
open = function () {
  return this.servo.to(
    api.args.apply(this, [].slice.call(arguments))
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Gripper.prototype.set"></a>[function <span class="apidocSignatureSpan">johnny-five.Gripper.prototype.</span>set ()](#apidoc.element.johnny-five.Gripper.prototype.set)
- description and source-code
```javascript
set = function () {
  return this.servo.to(
    api.args.apply(this, [].slice.call(arguments))
  );
}
```
- example usage
```shell
...

if (!this.toScaledEuler) {
  this.toScaledEuler = opts.toScaledEuler || function(raw) {
    return raw;
  };
}

priv.set(this, state);

if (typeof this.initialize === "function") {
  this.initialize(opts, function(data) {
    raw = data;
  });
}
...
```



# <a name="apidoc.module.johnny-five.Gyro"></a>[module johnny-five.Gyro](#apidoc.module.johnny-five.Gyro)

#### <a name="apidoc.element.johnny-five.Gyro.Gyro"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Gyro (opts)](#apidoc.element.johnny-five.Gyro.Gyro)
- description and source-code
```javascript
function Gyro(opts) {
  if (!(this instanceof Gyro)) {
    return new Gyro(opts);
  }

  var controller = null;
  var isCalibrated = false;
  var sampleSize = 100;

  var state = {
    x: {
      angle: 0,
      value: 0,
      previous: 0,
      calibration: [],
      stash: [0, 0, 0, 0, 0],
      center: 0,
      hasValue: false
    },
    y: {
      angle: 0,
      value: 0,
      previous: 0,
      calibration: [],
      stash: [0, 0, 0, 0, 0],
      center: 0,
      hasValue: false
    },
    z: {
      angle: 0,
      value: 0,
      previous: 0,
      calibration: [],
      stash: [0, 0, 0, 0, 0],
      center: 0,
      hasValue: false
    }
  };

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.ANALOG;
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toNormal) {
    this.toNormal = opts.toNormal || function(raw) {
      return raw;
    };
  }

  if (!this.toDegreesPerSecond) {
    this.toDegreesPerSecond = opts.toDegreesPerSecond || function(raw) {
      return raw;
    };
  }

  priv.set(this, state);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      var isChange = false;

      Object.keys(data).forEach(function(axis) {
        var value = data[axis];
        var sensor = state[axis];

        sensor.previous = sensor.value;
        sensor.stash.shift();
        sensor.stash.push(value);
        sensor.hasValue = true;
        sensor.value = (sum(sensor.stash) / 5) | 0;

        if (!isCalibrated &&
          (state.x.calibration.length === sampleSize &&
            state.y.calibration.length === sampleSize &&
            (this.z === undefined || state.z.calibration.length === sampleSize))) {

          isCalibrated = true;
          state.x.center = (sum(state.x.calibration) / sampleSize) | 0;
          state.y.center = (sum(state.y.calibration) / sampleSize) | 0;
          state.z.center = (sum(state.z.calibration) / sampleSize) | 0;

          state.x.calibration.length = 0;
          state.y.calibration.length = 0;
          state.z.calibration.length = 0;
        } else {
          if (sensor.calibration.length < sampleSize) {
            sensor.calibration.push(value);
          }
        }

        if (sensor.previous !== sensor.value) {
          isChange = true;
        }
      }, this);

      if (isCalibrated) {
        state.x.angle += this.rate.x / 100;
        state.y.angle += this.rate.y / 100;
        state.z.angle += this.rate.z / 100;

        this.emit("data", {
          x: this.x,
          y: this.y,
          z: this.z
        });

        if (isChange) {
          this.emit("change", {
            x: this.x,
            y: this.y,
            z: this.z
          });
        }
      }
    }.bind(this));
  }

  Object.defineProperties(this, {
    isCalibrated: {
      get: function() {
        return isCalibrated;
      },
      set: function(value) {
        if (typeof value === "boolean") {
          isCalibrated = value;
        }
      }
    },
    pitch: {
      get: function() {
        return {
          rate: toFixed(this.rate.y, 2),
          angle: toFixed(state.y.angle, 2)
        };
      }
    },
    roll: {
      get: function() {
        return {
          rate: toFixed(this.rate.x, 2),
          angle: toFixed(state.x.angle, 2)
        };
      }
    },
    yaw: {
      get: function() {
        return {
          rate: this.z !== undefined ? toFixed(this.rate.z, 2) : 0,
          angle: this.z !== undefined ? toFixed(state.z.angle, 2) : 0
        };
      }
    },
    x: {
      get: function() {
        return toFixed(this.toNormal(state.x.value), 4);
      }
    },
    y: {
      get: function() {
        return toFixed(this.toNormal(state.y.value), 4);
      }
    },
    z: {
      get: function() {
        return state.z.hasValue ? toFixed(this.toNormal(state. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Gyro.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Gyro.</span>super_ ()](#apidoc.element.johnny-five.Gyro.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Gyro.prototype"></a>[module johnny-five.Gyro.prototype](#apidoc.module.johnny-five.Gyro.prototype)

#### <a name="apidoc.element.johnny-five.Gyro.prototype.recalibrate"></a>[function <span class="apidocSignatureSpan">johnny-five.Gyro.prototype.</span>recalibrate ()](#apidoc.element.johnny-five.Gyro.prototype.recalibrate)
- description and source-code
```javascript
recalibrate = function () {
  this.isCalibrated = false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Hygrometer"></a>[module johnny-five.Hygrometer](#apidoc.module.johnny-five.Hygrometer)

#### <a name="apidoc.element.johnny-five.Hygrometer.Hygrometer"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Hygrometer (opts)](#apidoc.element.johnny-five.Hygrometer.Hygrometer)
- description and source-code
```javascript
function Hygrometer(opts) {
  if (!(this instanceof Hygrometer)) {
    return new Hygrometer(opts);
  }

  var controller = null;
  var last = null;
  var raw = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var freq = opts.freq || 25;

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    throw new Error("Missing Hygrometer controller");
  }

  priv.set(this, {});

  Board.Controller.call(this, controller, opts);

  if (!this.toRelativeHumidity) {
    this.toRelativeHumidity = opts.toRelativeHumidity || function(x) {
      return x;
    };
  }

  var propDescriptors = {
    relativeHumidity: {
      get: function() {
        return this.toRelativeHumidity(raw);
      }
    }
  };
  // Convenience aliases
  propDescriptors.RH = propDescriptors.relativeHumidity;

  Object.defineProperties(this, propDescriptors);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw == null) {
      return;
    }

    if (Number.isNaN(this.relativeHumidity)) {
      return;
    }

    var data = {};
    data.RH = data.relativeHumidity = this.relativeHumidity;

    this.emit("data", data);

    if (this.relativeHumidity !== last) {
      last = this.relativeHumidity;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Hygrometer.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Hygrometer.</span>super_ ()](#apidoc.element.johnny-five.Hygrometer.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.IMU"></a>[module johnny-five.IMU](#apidoc.module.johnny-five.IMU)

#### <a name="apidoc.element.johnny-five.IMU.IMU"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>IMU (opts)](#apidoc.element.johnny-five.IMU.IMU)
- description and source-code
```javascript
function IMU(opts) {

  if (!(this instanceof IMU)) {
    return new IMU(opts);
  }

  var controller, state;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    throw new Error("Missing IMU/Multi controller");
  }

  this.freq = opts.freq || 20;

  state = {};
  priv.set(this, state);

  Board.Controller.call(this, controller, opts);

  if (typeof this.initialize === "function") {
    this.initialize(opts);
  }

  // The IMU/Multi isn't considered "ready"
  // until one of the components has notified via
  // a change event.
  this.isReady = false;

  setInterval(function() {
    if (this.isReady) {
      this.emit("data", this);
    }
  }.bind(this), this.freq);

  var awaiting = this.components.slice();

  if (this.components && this.components.length > 0) {
    this.components.forEach(function(component) {
      if (!(this[component] instanceof Emitter)) {
        return;
      }

      this[component].on("change", function() {
        if (awaiting.length) {
          var index = awaiting.indexOf(component);

          if (index !== -1) {
            awaiting.splice(index, 1);
          }
        }

        if (!awaiting.length && !this.isReady) {
          this.isReady = true;
        }

        if (this.isReady) {
          this.emit("change", this, component);
        }
      }.bind(this));
    }, this);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.IMU.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.IMU.</span>super_ ()](#apidoc.element.johnny-five.IMU.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.IMU.Drivers"></a>[module johnny-five.IMU.Drivers](#apidoc.module.johnny-five.IMU.Drivers)

#### <a name="apidoc.element.johnny-five.IMU.Drivers.clear"></a>[function <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>clear ()](#apidoc.element.johnny-five.IMU.Drivers.clear)
- description and source-code
```javascript
clear = function () {
  activeDrivers.clear();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.IMU.Drivers.get"></a>[function <span class="apidocSignatureSpan">johnny-five.IMU.Drivers.</span>get (board, driverName, opts)](#apidoc.element.johnny-five.IMU.Drivers.get)
- description and source-code
```javascript
get = function (board, driverName, opts) {
  var drivers, driverKey, driver;

  if (!activeDrivers.has(board)) {
    activeDrivers.set(board, {});
  }

  opts = opts || {};

  drivers = activeDrivers.get(board);
  driverKey = Drivers[driverName].identifier.value(opts);

  if (!drivers[driverKey]) {
    driver = new Emitter();
    Object.defineProperties(driver, Drivers[driverName]);
    driver.initialize(board, opts);
    drivers[driverKey] = driver;
  }

  return drivers[driverKey];
}
```
- example usage
```shell
...

var Controllers = {

  BNO055: {
initialize: {
  value: function(opts, dataHandler) {
    var IMU = require("./imu"),
      driver = IMU.Drivers.get(this.board, "BNO055", opts);

    driver.on("data", function(data) {
      dataHandler(data);
    });
  }
},
toScaledEuler: {
...
```



# <a name="apidoc.module.johnny-five.IR"></a>[module johnny-five.IR](#apidoc.module.johnny-five.IR)

#### <a name="apidoc.element.johnny-five.IR.IR"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>IR ()](#apidoc.element.johnny-five.IR.IR)
- description and source-code
```javascript
IR = function () {
  throw new Error("IR has been removed. Use Motion or Proximity instead.");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.IR.Distance"></a>[function <span class="apidocSignatureSpan">johnny-five.IR.</span>Distance ()](#apidoc.element.johnny-five.IR.Distance)
- description and source-code
```javascript
Distance = function () {
  throw new Error("IR.Distance has been removed. Use Proximity instead.");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.IR.Motion"></a>[function <span class="apidocSignatureSpan">johnny-five.IR.</span>Motion ()](#apidoc.element.johnny-five.IR.Motion)
- description and source-code
```javascript
Motion = function () {
  throw new Error("IR.Motion has been removed. Use Motion instead.");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.IR.Proximity"></a>[function <span class="apidocSignatureSpan">johnny-five.IR.</span>Proximity ()](#apidoc.element.johnny-five.IR.Proximity)
- description and source-code
```javascript
Proximity = function () {
  throw new Error("IR.Proximity has been removed. Use Proximity instead.");
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.IR.Reflect"></a>[module johnny-five.IR.Reflect](#apidoc.module.johnny-five.IR.Reflect)

#### <a name="apidoc.element.johnny-five.IR.Reflect.Array"></a>[function <span class="apidocSignatureSpan">johnny-five.IR.Reflect.</span>Array (opts)](#apidoc.element.johnny-five.IR.Reflect.Array)
- description and source-code
```javascript
function ReflectanceArray(opts) {

  if (!(this instanceof ReflectanceArray)) {
    return new ReflectanceArray(opts);
  }

  this.opts = Board.Options(opts);

  Board.Component.call(
    this, this.opts, {
      requestPin: false
    }
  );

  // Read event throttling
  this.freq = opts.freq || 25;

  // Make private data entry
  var state = {
    lastLine: 0,
    isOn: false,
    calibration: {
      min: [],
      max: []
    },
    autoCalibrate: opts.autoCalibrate || false
  };

  priv.set(this, state);

  initialize.call(this);

  Object.defineProperties(this, {
    isOn: {
      get: function() {
        return state.emitter.isOn;
      }
    },
    isCalibrated: {
      get: function() {
        return calibrationIsValid(this.calibration, this.sensors);
      }
    },
    isOnLine: {
      get: function() {
        var line = this.line;
        return line > CALIBRATED_MIN_VALUE && line < maxLineValue.call(this);
      }
    },
    sensors: {
      get: function() {
        return state.sensorStates.map(function(sensorState) {
          return sensorState.sensor;
        });
      }
    },
    calibration: {
      get: function() {
        return state.calibration;
      }
    },
    raw: {
      get: function() {
        return state.sensorStates.map(function(sensorState) {
          return sensorState.rawValue;
        });
      }
    },
    values: {
      get: function() {
        return this.isCalibrated ? calibratedValues.call(this) : this.raw;
      }
    },
    line: {
      get: function() {
        return this.isCalibrated ? getLine.call(this) : 0;
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.IR.Reflect.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.IR.Reflect.</span>Collection (opts)](#apidoc.element.johnny-five.IR.Reflect.Collection)
- description and source-code
```javascript
function ReflectanceArray(opts) {

  if (!(this instanceof ReflectanceArray)) {
    return new ReflectanceArray(opts);
  }

  this.opts = Board.Options(opts);

  Board.Component.call(
    this, this.opts, {
      requestPin: false
    }
  );

  // Read event throttling
  this.freq = opts.freq || 25;

  // Make private data entry
  var state = {
    lastLine: 0,
    isOn: false,
    calibration: {
      min: [],
      max: []
    },
    autoCalibrate: opts.autoCalibrate || false
  };

  priv.set(this, state);

  initialize.call(this);

  Object.defineProperties(this, {
    isOn: {
      get: function() {
        return state.emitter.isOn;
      }
    },
    isCalibrated: {
      get: function() {
        return calibrationIsValid(this.calibration, this.sensors);
      }
    },
    isOnLine: {
      get: function() {
        var line = this.line;
        return line > CALIBRATED_MIN_VALUE && line < maxLineValue.call(this);
      }
    },
    sensors: {
      get: function() {
        return state.sensorStates.map(function(sensorState) {
          return sensorState.sensor;
        });
      }
    },
    calibration: {
      get: function() {
        return state.calibration;
      }
    },
    raw: {
      get: function() {
        return state.sensorStates.map(function(sensorState) {
          return sensorState.rawValue;
        });
      }
    },
    values: {
      get: function() {
        return this.isCalibrated ? calibratedValues.call(this) : this.raw;
      }
    },
    line: {
      get: function() {
        return this.isCalibrated ? getLine.call(this) : 0;
      }
    }
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.IR.Reflect.Array.prototype"></a>[module johnny-five.IR.Reflect.Array.prototype](#apidoc.module.johnny-five.IR.Reflect.Array.prototype)

#### <a name="apidoc.element.johnny-five.IR.Reflect.Array.prototype.calibrate"></a>[function <span class="apidocSignatureSpan">johnny-five.IR.Reflect.Array.prototype.</span>calibrate ()](#apidoc.element.johnny-five.IR.Reflect.Array.prototype.calibrate)
- description and source-code
```javascript
calibrate = function () {
  var state = priv.get(this);

  this.once("data", function(values) {
    setCalibration(state.calibration, values);

    this.emit("calibrated");
  });

  return this;
}
```
- example usage
```shell
...
};

// This will continue to calibrate until the predicate is true.
// Allows the user to calibrate n-times, or wait for user input,
// or base it on calibration heuristics.  However the user wants.
ReflectanceArray.prototype.calibrateUntil = function(predicate) {
var loop = function() {
  this.calibrate();
  this.once("calibrated", function() {
    if (!predicate()) {
      loop();
    }
  });
}.bind(this);
...
```

#### <a name="apidoc.element.johnny-five.IR.Reflect.Array.prototype.calibrateUntil"></a>[function <span class="apidocSignatureSpan">johnny-five.IR.Reflect.Array.prototype.</span>calibrateUntil (predicate)](#apidoc.element.johnny-five.IR.Reflect.Array.prototype.calibrateUntil)
- description and source-code
```javascript
calibrateUntil = function (predicate) {
  var loop = function() {
    this.calibrate();
    this.once("calibrated", function() {
      if (!predicate()) {
        loop();
      }
    });
  }.bind(this);

  loop();

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.IR.Reflect.Array.prototype.disable"></a>[function <span class="apidocSignatureSpan">johnny-five.IR.Reflect.Array.prototype.</span>disable ()](#apidoc.element.johnny-five.IR.Reflect.Array.prototype.disable)
- description and source-code
```javascript
disable = function () {
  var state = priv.get(this);

  state.emitter.off();

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.IR.Reflect.Array.prototype.enable"></a>[function <span class="apidocSignatureSpan">johnny-five.IR.Reflect.Array.prototype.</span>enable ()](#apidoc.element.johnny-five.IR.Reflect.Array.prototype.enable)
- description and source-code
```javascript
enable = function () {
  var state = priv.get(this);

  state.emitter.on();

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.IR.Reflect.Array.prototype.loadCalibration"></a>[function <span class="apidocSignatureSpan">johnny-five.IR.Reflect.Array.prototype.</span>loadCalibration (calibration)](#apidoc.element.johnny-five.IR.Reflect.Array.prototype.loadCalibration)
- description and source-code
```javascript
loadCalibration = function (calibration) {
  var state = priv.get(this);

  if (!calibrationIsValid(calibration, this.sensors)) {
    throw new Error("Calibration data not properly set: {min: [], max: []}");
  }

  state.calibration = calibration;

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Joystick"></a>[module johnny-five.Joystick](#apidoc.module.johnny-five.Joystick)

#### <a name="apidoc.element.johnny-five.Joystick.Joystick"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Joystick (opts)](#apidoc.element.johnny-five.Joystick.Joystick)
- description and source-code
```javascript
function Joystick(opts) {
  if (!(this instanceof Joystick)) {
    return new Joystick(opts);
  }

  var controller = null;

  var state = {
    x: {
      invert: false,
      value: 0,
      previous: 0,
      zeroV: 0,
      calibrated: false
    },
    y: {
      invert: false,
      value: 0,
      previous: 0,
      zeroV: 0,
      calibrated: false
    }
  };

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.ANALOG;
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toAxis) {
    this.toAxis = opts.toAxis || function(raw) {
      return raw;
    };
  }

  state.x.zeroV = opts.zeroV === undefined ? 0 : (opts.zeroV.x || 0);
  state.y.zeroV = opts.zeroV === undefined ? 0 : (opts.zeroV.y || 0);

  state.x.invert = opts.invertX || opts.invert || false;
  state.y.invert = opts.invertY || opts.invert || false;

  priv.set(this, state);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      var isChange = false;
      var computed = {
        x: null,
        y: null
      };

      Object.keys(data).forEach(function(axis) {
        var value = data[axis];
        var sensor = state[axis];

        // Set the internal ADC reading value...
        sensor.value = value;

        if (!state[axis].calibrated) {
          state[axis].calibrated = true;
          state[axis].zeroV = value;
          isChange = true;
        }

        // ... Get the computed axis value.
        computed[axis] = this[axis];

        var absAxis = Math.abs(computed[axis]);
        var absPAxis = Math.abs(sensor.previous);

        if ((absAxis < absPAxis) ||
          (absAxis > absPAxis)) {
          isChange = true;
        }

        sensor.previous = computed[axis];
      }, this);

      this.emit("data", {
        x: computed.x,
        y: computed.y
      });

      if (isChange) {
        this.emit("change", {
          x: computed.x,
          y: computed.y
        });
      }
    }.bind(this));
  }

  Object.defineProperties(this, {
    x: {
      get: function() {
        return this.toAxis(state.x.value, "x") * (state.x.invert ? -1 : 1);
      }
    },
    y: {
      get: function() {
        return this.toAxis(state.y.value, "y") * (state.y.invert ? -1 : 1);
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Joystick.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Joystick.</span>super_ ()](#apidoc.element.johnny-five.Joystick.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Keypad"></a>[module johnny-five.Keypad](#apidoc.module.johnny-five.Keypad)

#### <a name="apidoc.element.johnny-five.Keypad.Keypad"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Keypad (opts)](#apidoc.element.johnny-five.Keypad.Keypad)
- description and source-code
```javascript
function Keypad(opts) {

  if (!(this instanceof Keypad)) {
    return new Keypad(opts);
  }

  // Initialize a Device instance on a Board
  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var raw = null;
  var controller = null;
  var state = {
    touches: null,
    timeout: null,
    length: null,
    keys: null,
    mapping: null,
    holdtime: null,
  };

  var trigger = Fn.debounce(function(type, value) {
    var event = {
      type: type,
      which: value,
      timestamp: Date.now()
    };
    aliases[type].forEach(function(type) {
      this.emit(type, event);
    }, this);

    this.emit("change", Object.assign({}, event));
  }, 5);


  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.ANALOG;
  }

  Board.Controller.call(this, controller, opts);

  state.holdtime = opts.holdtime ? opts.holdtime : 500;

  priv.set(this, state);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {

      raw = data;

      var now = Date.now();
      var indices = this.toIndices(data);
      var kLength = state.length;

      var lists = {
        down: [],
        hold: [],
        up: [],
      };

      var target = null;
      var alias = null;

      for (var k = 0; k < kLength; k++) {
        alias = this.toAlias(k);

        if (indices.includes(k)) {
          if (state.touches[k].value === 0) {

            state.touches[k].timeout = now + state.holdtime;
            lists.down.push(alias);

          } else if (state.touches[k].value === 1) {
            if (state.touches[k].timeout !== null && now > state.touches[k].timeout) {
              state.touches[k].timeout = now + state.holdtime;
              lists.hold.push(alias);
            }
          }

          state.touches[k].value = 1;
        } else {
          if (state.touches[k].value === 1) {
            state.touches[k].timeout = null;
            lists.up.push(alias);
          }
          state.touches[k].value = 0;
        }
        target = null;
        alias = null;
      }

      Object.keys(lists).forEach(function(key) {
        var list = lists[key];

        if (list.length) {
          trigger.call(this, key, list);
        }
      }, this);
    }.bind(this));
  }

  Object.defineProperties(this, {
    isMultitouch: {
      get: function() {
        return state.isMultitouch;
      }
    },
    value: {
      get: function() {
        return raw;
      }
    },
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Keypad.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Keypad.</span>super_ ()](#apidoc.element.johnny-five.Keypad.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.LCD"></a>[module johnny-five.LCD](#apidoc.module.johnny-five.LCD)

#### <a name="apidoc.element.johnny-five.LCD.LCD"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>LCD (opts)](#apidoc.element.johnny-five.LCD.LCD)
- description and source-code
```javascript
function LCD(opts) {

  if (!(this instanceof LCD)) {
    return new LCD(opts);
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var controller = null;

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.PARALLEL;
  }

  Board.Controller.call(this, controller, opts);

  this.ctype = opts.controller;

  if (this.initialize) {
    this.initialize(opts);
  }

  Object.defineProperties(this, {
    characters: {
      get: function() {
        return Object.assign({}, priv.get(this).characters);
      },
    },
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.LCD.prototype"></a>[module johnny-five.LCD.prototype](#apidoc.module.johnny-five.LCD.prototype)

#### <a name="apidoc.element.johnny-five.LCD.prototype.autoscroll"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>autoscroll ()](#apidoc.element.johnny-five.LCD.prototype.autoscroll)
- description and source-code
```javascript
autoscroll = function () {
  var state = priv.get(this);

  state.display |= this.REGISTER.ENTRYSHIFTINCREMENT;
  this.command(this.REGISTER.ENTRY | state.display);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.backlight"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>backlight (highOrLow)](#apidoc.element.johnny-five.LCD.prototype.backlight)
- description and source-code
```javascript
backlight = function (highOrLow) {
  var state = priv.get(this);

  highOrLow = typeof highOrLow === "undefined" ? true : false;

  if (state.backlight.pin instanceof Pin) {
    if (highOrLow) {
      state.backlight.pin.high();
    } else {
      state.backlight.pin.low();
    }
  }

  if (highOrLow) {
    state.display |= this.REGISTER.DISPLAYON;
  } else {
    state.display &= ~this.REGISTER.DISPLAYON;
  }

  this.command(state.display);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.blink"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>blink ()](#apidoc.element.johnny-five.LCD.prototype.blink)
- description and source-code
```javascript
blink = function () {
  var state = priv.get(this);

  state.display |= this.REGISTER.BLINKON;
  this.command(state.display);

  return this;
}
```
- example usage
```shell
...
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''

<img src="https://github.com/rwaldron/johnny-five/raw/master/assets/led-blink.gif">

> Note: Node will crash if you try to run johnny-five in the node REPL, but board instances will create their own contextual REPL
. Put your script in a file.
...
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.clear"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>clear ()](#apidoc.element.johnny-five.LCD.prototype.clear)
- description and source-code
```javascript
clear = function () {
  this.command(this.REGISTER.CLEAR);
  sleep(2);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.command"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>command (mode, value)](#apidoc.element.johnny-five.LCD.prototype.command)
- description and source-code
```javascript
command = function (mode, value) {
  if (typeof value === "undefined") {
    value = mode;
    mode = 0x80;
  }

  if (this.bitMode === 4) {
    this.send(value >> 4);
  }

  this.send(value);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.createChar"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>createChar (name, charMap)](#apidoc.element.johnny-five.LCD.prototype.createChar)
- description and source-code
```javascript
createChar = function (name, charMap) {
  // Ensure location is never above 7
  var state = priv.get(this);
  var address;

  if (typeof name === "number") {
    address = name & 0x07;
  } else {
    address = state.index;
    state.index--;
    if (state.index === -1) {
      state.index = this.REGISTER.MEMORYLIMIT - 1;
    }
  }

  this.command(this.REGISTER.SETCGRAMADDR | (address << 3));

  this.hilo(function() {
    for (var i = 0; i < 8; i++) {
      this.command(this.REGISTER.DATA, charMap[i]);
    }
  });

  // Fill in address
  state.characters[name] = address;

  return address;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.cursor"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>cursor (row, col)](#apidoc.element.johnny-five.LCD.prototype.cursor)
- description and source-code
```javascript
cursor = function (row, col) {
  // When provided with col & row, cursor will behave like setCursor,
  // except that it has row and col in the order that most people
  // intuitively expect it to be in.
  if (typeof col !== "undefined" && typeof row !== "undefined") {
    return this.setCursor(col, row);
  }
  var state = priv.get(this);

  state.display |= this.REGISTER.CURSORON;
  this.command(state.display);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.hilo"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>hilo (callback)](#apidoc.element.johnny-five.LCD.prototype.hilo)
- description and source-code
```javascript
hilo = function (callback) {
  // RS High for write mode
  this.io.digitalWrite(this.pins.rs, this.io.HIGH);

  callback.call(this);

  // RS Low for command mode
  this.io.digitalWrite(this.pins.rs, this.io.LOW);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.home"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>home ()](#apidoc.element.johnny-five.LCD.prototype.home)
- description and source-code
```javascript
home = function () {
  this.command(this.REGISTER.HOME);
  sleep(2);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.noAutoscroll"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>noAutoscroll ()](#apidoc.element.johnny-five.LCD.prototype.noAutoscroll)
- description and source-code
```javascript
noAutoscroll = function () {
  var state = priv.get(this);

  state.display &= ~this.REGISTER.ENTRYSHIFTINCREMENT;
  this.command(this.REGISTER.ENTRY | state.display);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.noBacklight"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>noBacklight ()](#apidoc.element.johnny-five.LCD.prototype.noBacklight)
- description and source-code
```javascript
noBacklight = function () {
  var state = priv.get(this);

  if (state.backlight.pin instanceof Pin) {
    state.backlight.pin.high();
  }

  // if (highOrLow) {
  //   state.display |= this.REGISTER.DISPLAYON;
  // } else {
  //   state.display &= ~this.REGISTER.DISPLAYON;
  // }

  // this.command(state.display);

  return this.backlight(false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.noBlink"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>noBlink ()](#apidoc.element.johnny-five.LCD.prototype.noBlink)
- description and source-code
```javascript
noBlink = function () {
  var state = priv.get(this);

  state.display &= ~this.REGISTER.BLINKON;
  this.command(state.display);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.noCursor"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>noCursor ()](#apidoc.element.johnny-five.LCD.prototype.noCursor)
- description and source-code
```javascript
noCursor = function () {
  var state = priv.get(this);

  state.display &= ~this.REGISTER.CURSORON;
  this.command(state.display);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.off"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>off ()](#apidoc.element.johnny-five.LCD.prototype.off)
- description and source-code
```javascript
off = function () {
  var state = priv.get(this);

  state.display &= ~this.REGISTER.DISPLAYON;
  this.command(state.display);

  return this;
}
```
- example usage
```shell
...

  return this;
};

ReflectanceArray.prototype.disable = function() {
  var state = priv.get(this);

  state.emitter.off();

  return this;
};

// Calibrate will store the min/max values for this sensor array
// It should be called many times in order to get a lot of readings
// on light and dark areas.  See calibrateUntil for a convenience
...
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.on"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>on ()](#apidoc.element.johnny-five.LCD.prototype.on)
- description and source-code
```javascript
on = function () {
  var state = priv.get(this);

  state.display |= this.REGISTER.DISPLAYON;
  this.command(state.display);

  return this;
}
```
- example usage
```shell
...

The ubiquitous "Hello World" program of the microcontroller and SoC world is "blink an LED". The following code demonstrates how
 this is done using the Johnny-Five framework.

'''javascript
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''
...
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.print"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>print (message, opts)](#apidoc.element.johnny-five.LCD.prototype.print)
- description and source-code
```javascript
print = function (message, opts) {
  var state, dontProcessSpecials, hasCharacters, processed;

  message = message + "";
  opts = opts || {};

  state = priv.get(this);
  dontProcessSpecials = opts.dontProcessSpecials || false;
  hasCharacters = !dontProcessSpecials && RE_SPECIALS.test(message);

  if (message.length === 1) {
    this.hilo(function() {
      this.command(this.REGISTER.DATA, message.charCodeAt(0));
    });
  } else {

    if (hasCharacters) {
      processed = message.replace(RE_SPECIALS, function(match, name) {
        var address = state.characters[name];

        return typeof address === "number" ? String.fromCharCode(address) : match;
      });

      this.print(processed, {
        dontProcessSpecials: true
      });
    } else {
      this.hilo(function() {
        Array.from(message).forEach(function(character) {
          this.command(this.REGISTER.DATA, character.charCodeAt(0));
        }, this);
      });
    }
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.send"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>send (value)](#apidoc.element.johnny-five.LCD.prototype.send)
- description and source-code
```javascript
send = function (value) {
  var pin = 0;
  var mask = {
    4: 8,
    8: 128
  }[this.bitMode];

  for (; mask > 0; mask = mask >> 1) {
    this.io.digitalWrite(
      this.pins.data[pin],
      this.io[value & mask ? "HIGH" : "LOW"]
    );
    pin++;
  }

  ["LOW", "HIGH", "LOW"].forEach(function(val) {
    this.io.digitalWrite(this.pins.en, this.io[val]);
  }, this);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.setCursor"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>setCursor (col, row)](#apidoc.element.johnny-five.LCD.prototype.setCursor)
- description and source-code
```javascript
setCursor = function (col, row) {
  var rowOffsets = [0x00, 0x40, 0x14, 0x54];
  this.command(this.REGISTER.SETDDRAMADDR | (col + rowOffsets[row]));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.useChar"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>useChar (name)](#apidoc.element.johnny-five.LCD.prototype.useChar)
- description and source-code
```javascript
useChar = function (name) {
  var state = priv.get(this);

  if (typeof state.characters[name] === "undefined") {
    // Create the character in LCD memory and
    var newCharIndex = this.createChar(name, this.CHARS[name]);

    // If character's index already used, remove this character in current LCD character map
    // because it's not in LCD memory anymore.
    for (var oldName in state.characters) {
      if (name !== oldName && state.characters[oldName] === newCharIndex) {
        delete state.characters[oldName];
        break;
      }
    }

    // Add character to current LCD character map
    state.characters[name] = newCharIndex;
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LCD.prototype.write"></a>[function <span class="apidocSignatureSpan">johnny-five.LCD.prototype.</span>write (charCode)](#apidoc.element.johnny-five.LCD.prototype.write)
- description and source-code
```javascript
write = function (charCode) {
  this.hilo.call(this, function() {
    this.command(this.REGISTER.DATA, charCode);
  });

  return this;
}
```
- example usage
```shell
...
EVS.isRawSensor = function(port) {
return port.analog === EVS.S1_ANALOG || port.analog === EVS.S2_ANALOG;
};

util.inherits(EVS, Emitter);

EVS.prototype.setup = function(port, type) {
this.bank[port.bank].write(port.mode, [type]);
};

EVS.prototype.read = function(port, register, numBytes, callback) {

if (port.sensor && port.offset && !EVS.isRawSensor(port)) {
  register += port.offset;
}
...
```



# <a name="apidoc.module.johnny-five.Led"></a>[module johnny-five.Led](#apidoc.module.johnny-five.Led)

#### <a name="apidoc.element.johnny-five.Led.Led"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Led (opts)](#apidoc.element.johnny-five.Led.Led)
- description and source-code
```javascript
function Led(opts) {
  if (!(this instanceof Led)) {
    return new Led(opts);
  }

  var pinValue = typeof opts === "object" ? opts.pin : opts;
  var controller = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.DEFAULT;
  }

  Object.defineProperties(this, controller);

  var state = {
    isAnode: opts.isAnode,
    isOn: false,
    isRunning: false,
    value: null,
    direction: 1,
    mode: null,
    intensity: 0,
    interval: null
  };

  priv.set(this, state);

  Object.defineProperties(this, {
    value: {
      get: function() {
        return state.value;
      }
    },
    mode: {
      get: function() {
        return state.mode;
      }
    },
    isOn: {
      get: function() {
        return !!state.value;
      }
    },
    isRunning: {
      get: function() {
        return state.isRunning;
      }
    },
    animation: {
      get: function() {
        return state.animation;
      }
    }
  });

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (typeof this.initialize === "function") {
    this.initialize(opts, pinValue);
  }
}
```
- example usage
```shell
...

'''javascript
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''

<img src="https://github.com/rwaldron/johnny-five/raw/master/assets/led-blink.gif">
...
```

#### <a name="apidoc.element.johnny-five.Led.Array"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.</span>Array (numsOrObjects)](#apidoc.element.johnny-five.Led.Array)
- description and source-code
```javascript
function Leds(numsOrObjects) {
  if (!(this instanceof Leds)) {
    return new Leds(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Led
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Led.Collection)
- description and source-code
```javascript
function Leds(numsOrObjects) {
  if (!(this instanceof Leds)) {
    return new Leds(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Led
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.Digits"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.</span>Digits (opts)](#apidoc.element.johnny-five.Led.Digits)
- description and source-code
```javascript
function Digits(opts) {
  opts.isMatrix = false;
  return new LedControl(opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.Matrix"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.</span>Matrix (opts)](#apidoc.element.johnny-five.Led.Matrix)
- description and source-code
```javascript
function Matrix(opts) {
  opts.isMatrix = true;
  return new LedControl(opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGB"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.</span>RGB (opts)](#apidoc.element.johnny-five.Led.RGB)
- description and source-code
```javascript
function RGB(opts) {
  if (!(this instanceof RGB)) {
    return new RGB(opts);
  }

  var controller = null;

  if (Array.isArray(opts)) {
    // RGB([Byte, Byte, Byte]) shorthand
    // Convert to opts.pins array definition
    opts = {
      pins: opts
    };
    // If opts.pins is an object, convert to array
  } else if (typeof opts.pins === "object" && !Array.isArray(opts.pins)) {
    opts.pins = [opts.pins.red, opts.pins.green, opts.pins.blue];
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.DEFAULT;
  }


  // The default color is #ffffff, but the light will be off
  var state = {
    red: 255,
    green: 255,
    blue: 255,
    intensity: 100,
    isAnode: opts.isAnode || false,
    interval: null
  };

  // red, green, and blue store the raw color set via .color()
  // values takes state into account, such as on/off and intensity
  state.values = {
    red: state.red,
    green: state.green,
    blue: state.blue
  };

  priv.set(this, state);

  Board.Controller.call(this, controller, opts);

  Object.defineProperties(this, {
    isOn: {
      get: function() {
        return RGB.colors.some(function(color) {
          return state[color] > 0;
        });
      }
    },
    isRunning: {
      get: function() {
        return !!state.interval;
      }
    },
    isAnode: {
      get: function() {
        return state.isAnode;
      }
    },
    values: {
      get: function() {
        return Object.assign({}, state.values);
      }
    },
    update: {
      value: function(colors) {
        var state = priv.get(this);

        colors = colors || this.color();

        state.values = RGB.ToScaledRGB(state.intensity, colors);

        this.write(state.values);

        Object.assign(state, colors);
      }
    }
  });

  this.initialize(opts);
  this.off();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGBs"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.</span>RGBs (numsOrObjects)](#apidoc.element.johnny-five.Led.RGBs)
- description and source-code
```javascript
function RGBs(numsOrObjects) {
  if (!(this instanceof RGBs)) {
    return new RGBs(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: RGB
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Led.RGB"></a>[module johnny-five.Led.RGB](#apidoc.module.johnny-five.Led.RGB)

#### <a name="apidoc.element.johnny-five.Led.RGB.RGB"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.</span>RGB (opts)](#apidoc.element.johnny-five.Led.RGB.RGB)
- description and source-code
```javascript
function RGB(opts) {
  if (!(this instanceof RGB)) {
    return new RGB(opts);
  }

  var controller = null;

  if (Array.isArray(opts)) {
    // RGB([Byte, Byte, Byte]) shorthand
    // Convert to opts.pins array definition
    opts = {
      pins: opts
    };
    // If opts.pins is an object, convert to array
  } else if (typeof opts.pins === "object" && !Array.isArray(opts.pins)) {
    opts.pins = [opts.pins.red, opts.pins.green, opts.pins.blue];
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.DEFAULT;
  }


  // The default color is #ffffff, but the light will be off
  var state = {
    red: 255,
    green: 255,
    blue: 255,
    intensity: 100,
    isAnode: opts.isAnode || false,
    interval: null
  };

  // red, green, and blue store the raw color set via .color()
  // values takes state into account, such as on/off and intensity
  state.values = {
    red: state.red,
    green: state.green,
    blue: state.blue
  };

  priv.set(this, state);

  Board.Controller.call(this, controller, opts);

  Object.defineProperties(this, {
    isOn: {
      get: function() {
        return RGB.colors.some(function(color) {
          return state[color] > 0;
        });
      }
    },
    isRunning: {
      get: function() {
        return !!state.interval;
      }
    },
    isAnode: {
      get: function() {
        return state.isAnode;
      }
    },
    values: {
      get: function() {
        return Object.assign({}, state.values);
      }
    },
    update: {
      value: function(colors) {
        var state = priv.get(this);

        colors = colors || this.color();

        state.values = RGB.ToScaledRGB(state.intensity, colors);

        this.write(state.values);

        Object.assign(state, colors);
      }
    }
  });

  this.initialize(opts);
  this.off();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGB.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGB.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Led.RGB.Collection)
- description and source-code
```javascript
function RGBs(numsOrObjects) {
  if (!(this instanceof RGBs)) {
    return new RGBs(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: RGB
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGB.ToRGB"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGB.</span>ToRGB (red, green, blue)](#apidoc.element.johnny-five.Led.RGB.ToRGB)
- description and source-code
```javascript
ToRGB = function (red, green, blue) {
  var update = {};
  var flags = 0;
  var input;

  if (typeof red !== "undefined") {
    // 0b100
    flags |= 1 << 2;
  }

  if (typeof green !== "undefined") {
    // 0b010
    flags |= 1 << 1;
  }

  if (typeof blue !== "undefined") {
    // 0b001
    flags |= 1 << 0;
  }

  if ((flags | 0x04) === 0x04) {
    input = red;

    if (input == null) {
      throw new Error("Invalid color (" + input + ")");
    }

<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (Array.isArray(input)) {
      // color([Byte, Byte, Byte])
      update = {
        red: input[0],
        green: input[1],
        blue: input[2]
      };
    } else if (typeof input === "object") {
      // color({
      //   red: Byte,
      //   green: Byte,
      //   blue: Byte
      // });
      update = {
        red: input.red,
        green: input.green,
        blue: input.blue
      };
    } else if (typeof input === "string") {

      // color("#ffffff") or color("ffffff")
      if (input.match(/^#?[0-9A-Fa-f]{6}$/)) {

        // remove the leading # if there is one
        if (input.length === 7 && input[0] === "#") {
          input = input.slice(1);
        }

        update = {
          red: parseInt(input.slice(0, 2), 16),
          green: parseInt(input.slice(2, 4), 16),
          blue: parseInt(input.slice(4, 6), 16)
        };
      } else {
        // color name
        return RGB.ToRGB(converter.keyword.rgb(input.toLowerCase()));
      }
    }
  } else {
    // color(red, green, blue)
    update = {
      red: red,
      green: green,
      blue: blue
    };
  }

  return update;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGB.ToScaledRGB"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGB.</span>ToScaledRGB (intensity, colors)](#apidoc.element.johnny-five.Led.RGB.ToScaledRGB)
- description and source-code
```javascript
ToScaledRGB = function (intensity, colors) {
  var scale = intensity / 100;

  return RGB.colors.reduce(function(current, color) {
    return (current[color] = Math.round(colors[color] * scale), current);
  }, {});
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Led.RGB.prototype"></a>[module johnny-five.Led.RGB.prototype](#apidoc.module.johnny-five.Led.RGB.prototype)

#### <a name="apidoc.element.johnny-five.Led.RGB.prototype.blink"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>blink (duration, callback)](#apidoc.element.johnny-five.Led.RGB.prototype.blink)
- description and source-code
```javascript
blink = function (duration, callback) {
  var state = priv.get(this);

  // Avoid traffic jams
  this.stop();

  if (typeof duration === "function") {
    callback = duration;
    duration = null;
  }

  state.interval = setInterval(function() {
    this.toggle();
    if (typeof callback === "function") {
      callback();
    }
  }.bind(this), duration || 100);

  return this;
}
```
- example usage
```shell
...
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''

<img src="https://github.com/rwaldron/johnny-five/raw/master/assets/led-blink.gif">

> Note: Node will crash if you try to run johnny-five in the node REPL, but board instances will create their own contextual REPL
. Put your script in a file.
...
```

#### <a name="apidoc.element.johnny-five.Led.RGB.prototype.color"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>color (red, green, blue)](#apidoc.element.johnny-five.Led.RGB.prototype.color)
- description and source-code
```javascript
color = function (red, green, blue) {
  var state = priv.get(this);
  var colors;

  if (arguments.length === 0) {
    // Return a copy of the state values,
    // not a reference to the state object itself.
    colors = this.isOn ? state : state.prev;
    return RGB.colors.reduce(function(current, color) {
      return (current[color] = Math.round(colors[color]), current);
    }, {});
  }

  var update = RGB.ToRGB(red, green, blue);

  // Validate all color values before writing any values
  RGB.colors.forEach(function(color) {
    var value = update[color];

    if (value == null) {
      throw new Error("Led.RGB.color: invalid color ([" + [update.red, update.green, update.blue].join(",") + "])");
    }

    value = Fn.constrain(value, 0, 255);
    update[color] = value;
  }, this);

  this.update(update);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGB.prototype.intensity"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>intensity (intensity)](#apidoc.element.johnny-five.Led.RGB.prototype.intensity)
- description and source-code
```javascript
intensity = function (intensity) {
  var state = priv.get(this);

  if (arguments.length === 0) {
    return state.intensity;
  }

  state.intensity = Fn.constrain(intensity, 0, 100);

  this.update();

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGB.prototype.off"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>off ()](#apidoc.element.johnny-five.Led.RGB.prototype.off)
- description and source-code
```javascript
off = function () {
  var state = priv.get(this);

  // If it's already off, do nothing so the pervious state stays intact
<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (this.isOn) {
    state.prev = RGB.colors.reduce(function(current, color) {
      return (current[color] = state[color], current);
    }.bind(this), {});

    this.update({
      red: 0,
      green: 0,
      blue: 0
    });
  }

  return this;
}
```
- example usage
```shell
...

  return this;
};

ReflectanceArray.prototype.disable = function() {
  var state = priv.get(this);

  state.emitter.off();

  return this;
};

// Calibrate will store the min/max values for this sensor array
// It should be called many times in order to get a lot of readings
// on light and dark areas.  See calibrateUntil for a convenience
...
```

#### <a name="apidoc.element.johnny-five.Led.RGB.prototype.on"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>on ()](#apidoc.element.johnny-five.Led.RGB.prototype.on)
- description and source-code
```javascript
on = function () {
  var state = priv.get(this);
  var colors;

  // If it's not already on, we set them to the previous color
  if (!this.isOn) {
<span class="apidocCodeCommentSpan">    /* istanbul ignore next */
</span>    colors = state.prev || {
      red: 255,
      green: 255,
      blue: 255
    };

    state.prev = null;

    this.update(colors);
  }

  return this;
}
```
- example usage
```shell
...

The ubiquitous "Hello World" program of the microcontroller and SoC world is "blink an LED". The following code demonstrates how
 this is done using the Johnny-Five framework.

'''javascript
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''
...
```

#### <a name="apidoc.element.johnny-five.Led.RGB.prototype.stop"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>stop ()](#apidoc.element.johnny-five.Led.RGB.prototype.stop)
- description and source-code
```javascript
stop = function () {
  var state = priv.get(this);

  if (state.interval) {
    clearInterval(state.interval);
  }

<span class="apidocCodeCommentSpan">  /* istanbul ignore if */
</span>  if (state.animation) {
    state.animation.stop();
  }

  state.interval = null;

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGB.prototype.strobe"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>strobe (duration, callback)](#apidoc.element.johnny-five.Led.RGB.prototype.strobe)
- description and source-code
```javascript
strobe = function (duration, callback) {
  var state = priv.get(this);

  // Avoid traffic jams
  this.stop();

  if (typeof duration === "function") {
    callback = duration;
    duration = null;
  }

  state.interval = setInterval(function() {
    this.toggle();
    if (typeof callback === "function") {
      callback();
    }
  }.bind(this), duration || 100);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGB.prototype.toggle"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGB.prototype.</span>toggle ()](#apidoc.element.johnny-five.Led.RGB.prototype.toggle)
- description and source-code
```javascript
toggle = function () {
  return this[this.isOn ? "off" : "on"]();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Led.RGBs"></a>[module johnny-five.Led.RGBs](#apidoc.module.johnny-five.Led.RGBs)

#### <a name="apidoc.element.johnny-five.Led.RGBs.RGBs"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.</span>RGBs (numsOrObjects)](#apidoc.element.johnny-five.Led.RGBs.RGBs)
- description and source-code
```javascript
function RGBs(numsOrObjects) {
  if (!(this instanceof RGBs)) {
    return new RGBs(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: RGB
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGBs.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Led.RGBs.super_)
- description and source-code
```javascript
function Collection(numsOrObjects) {
  var Type = this.type;
  var initObjects = [];

  this.length = 0;

  if (Array.isArray(numsOrObjects)) {
    initObjects = numsOrObjects;
  } else {
    // Initialize with a Shared Properties object
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (Array.isArray(numsOrObjects.pins)) {
      var keys = Object.keys(numsOrObjects).filter(function(key) {
        return key !== "pins";
      });
      initObjects = numsOrObjects.pins.map(function(pin) {
        var obj = {};

        if (Array.isArray(pin)) {
          obj.pins = pin;
        } else {
          obj.pin = pin;
        }

        return keys.reduce(function(accum, key) {
          accum[key] = numsOrObjects[key];
          return accum;
        }, obj);
      });
    }
  }

  /* istanbul ignore else */
  if (initObjects.length) {
    while (initObjects.length) {
      var numOrObject = initObjects.shift();

      // When a Type exists, respect it!
      if (typeof Type === "function") {
        if (!(numOrObject instanceof Type || numOrObject instanceof this.constructor)) {
          numOrObject = new Type(numOrObject);
        }
      }

      this.add(numOrObject);
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Led.RGBs.prototype"></a>[module johnny-five.Led.RGBs.prototype](#apidoc.module.johnny-five.Led.RGBs.prototype)

#### <a name="apidoc.element.johnny-five.Led.RGBs.prototype.blink"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>blink (duration, callback)](#apidoc.element.johnny-five.Led.RGBs.prototype.blink)
- description and source-code
```javascript
blink = function (duration, callback) {
  var length = this.length;
  var signals = [];
  var led;

  if (typeof duration === "function") {
    callback = duration;
    duration = 1000;
  }

  if (typeof callback !== "function") {
    callback = noop;
  }

  for (var i = 0; i < length; i++) {
    led = this[i];
    signals.push(
<span class="apidocCodeCommentSpan">      /* jshint ignore:start */
</span>      new Promise(function(resolve) {
        led[method](duration, function() {
          resolve();
        });
      })
      /* jshint ignore:end */
    );
  }

  Promise.all(signals).then(callback);

  return this;
}
```
- example usage
```shell
...
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''

<img src="https://github.com/rwaldron/johnny-five/raw/master/assets/led-blink.gif">

> Note: Node will crash if you try to run johnny-five in the node REPL, but board instances will create their own contextual REPL
. Put your script in a file.
...
```

#### <a name="apidoc.element.johnny-five.Led.RGBs.prototype.color"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>color ()](#apidoc.element.johnny-five.Led.RGBs.prototype.color)
- description and source-code
```javascript
color = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGBs.prototype.intensity"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>intensity ()](#apidoc.element.johnny-five.Led.RGBs.prototype.intensity)
- description and source-code
```javascript
intensity = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGBs.prototype.off"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>off ()](#apidoc.element.johnny-five.Led.RGBs.prototype.off)
- description and source-code
```javascript
off = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
...

  return this;
};

ReflectanceArray.prototype.disable = function() {
  var state = priv.get(this);

  state.emitter.off();

  return this;
};

// Calibrate will store the min/max values for this sensor array
// It should be called many times in order to get a lot of readings
// on light and dark areas.  See calibrateUntil for a convenience
...
```

#### <a name="apidoc.element.johnny-five.Led.RGBs.prototype.on"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>on ()](#apidoc.element.johnny-five.Led.RGBs.prototype.on)
- description and source-code
```javascript
on = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
...

The ubiquitous "Hello World" program of the microcontroller and SoC world is "blink an LED". The following code demonstrates how
 this is done using the Johnny-Five framework.

'''javascript
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''
...
```

#### <a name="apidoc.element.johnny-five.Led.RGBs.prototype.stop"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>stop ()](#apidoc.element.johnny-five.Led.RGBs.prototype.stop)
- description and source-code
```javascript
stop = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGBs.prototype.strobe"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>strobe ()](#apidoc.element.johnny-five.Led.RGBs.prototype.strobe)
- description and source-code
```javascript
strobe = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.RGBs.prototype.toggle"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.RGBs.prototype.</span>toggle ()](#apidoc.element.johnny-five.Led.RGBs.prototype.toggle)
- description and source-code
```javascript
toggle = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Led.prototype"></a>[module johnny-five.Led.prototype](#apidoc.module.johnny-five.Led.prototype)

#### <a name="apidoc.element.johnny-five.Led.prototype.blink"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>blink (duration, callback)](#apidoc.element.johnny-five.Led.prototype.blink)
- description and source-code
```javascript
blink = function (duration, callback) {
  var state = priv.get(this);

  // Avoid traffic jams
  this.stop();

  if (typeof duration === "function") {
    callback = duration;
    duration = null;
  }

  state.isRunning = true;

  state.interval = setInterval(function() {
    this.toggle();
    if (typeof callback === "function") {
      callback();
    }
  }.bind(this), duration || 100);

  return this;
}
```
- example usage
```shell
...
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''

<img src="https://github.com/rwaldron/johnny-five/raw/master/assets/led-blink.gif">

> Note: Node will crash if you try to run johnny-five in the node REPL, but board instances will create their own contextual REPL
. Put your script in a file.
...
```

#### <a name="apidoc.element.johnny-five.Led.prototype.brightness"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>brightness (brightness)](#apidoc.element.johnny-five.Led.prototype.brightness)
- description and source-code
```javascript
brightness = function (brightness) {
  var state = priv.get(this);
  state.value = brightness;

  this.update();

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.prototype.fade"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>fade (val, duration, callback)](#apidoc.element.johnny-five.Led.prototype.fade)
- description and source-code
```javascript
fade = function (val, duration, callback) {

  var state = priv.get(this);

  this.stop();

  var options = {
    duration: typeof duration === "number" ? duration : 1000,
    keyFrames: [null, typeof val === "number" ? val : 0xff],
    easing: "outSine",
    oncomplete: function() {
      state.isRunning = false;
<span class="apidocCodeCommentSpan">      /* istanbul ignore else */
</span>      if (typeof callback === "function") {
        callback();
      }
    }
  };

  if (typeof val === "object") {
    Object.assign(options, val);
  }

  if (typeof val === "function") {
    callback = val;
  }

  if (typeof duration === "object") {
    Object.assign(options, duration);
  }

  if (typeof duration === "function") {
    callback = duration;
  }

  state.isRunning = true;

  state.animation = state.animation || new Animation(this);
  state.animation.enqueue(options);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.prototype.fadeIn"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>fadeIn (duration, callback)](#apidoc.element.johnny-five.Led.prototype.fadeIn)
- description and source-code
```javascript
fadeIn = function (duration, callback) {
  return this.fade(255, duration || 1000, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.prototype.fadeOut"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>fadeOut (duration, callback)](#apidoc.element.johnny-five.Led.prototype.fadeOut)
- description and source-code
```javascript
fadeOut = function (duration, callback) {
  return this.fade(0, duration || 1000, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.prototype.intensity"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>intensity (intensity)](#apidoc.element.johnny-five.Led.prototype.intensity)
- description and source-code
```javascript
intensity = function (intensity) {
  var state = priv.get(this);

  if (arguments.length === 0) {
    return state.intensity;
  }

  state.intensity = Fn.constrain(intensity, 0, 100);

  return this.brightness(Fn.scale(state.intensity, 0, 100, 0, 255));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.prototype.off"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>off ()](#apidoc.element.johnny-five.Led.prototype.off)
- description and source-code
```javascript
off = function () {
  var state = priv.get(this);

  state.value = 0;

  this.update();

  return this;
}
```
- example usage
```shell
...

  return this;
};

ReflectanceArray.prototype.disable = function() {
  var state = priv.get(this);

  state.emitter.off();

  return this;
};

// Calibrate will store the min/max values for this sensor array
// It should be called many times in order to get a lot of readings
// on light and dark areas.  See calibrateUntil for a convenience
...
```

#### <a name="apidoc.element.johnny-five.Led.prototype.on"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>on ()](#apidoc.element.johnny-five.Led.prototype.on)
- description and source-code
```javascript
on = function () {
  var state = priv.get(this);

  if (state.mode === this.io.MODES.OUTPUT) {
    state.value = this.io.HIGH;
  }

  if (state.mode === this.io.MODES.PWM) {
    // Assume we need to simply turn this all the way on, when:

    // ...state.value is null
    if (state.value === null) {
      state.value = 255;
    }

    // ...there is no active interval
    if (!state.interval) {
      state.value = 255;
    }

    // ...the last value was 0
    if (state.value === 0) {
      state.value = 255;
    }
  }

  this.update();

  return this;
}
```
- example usage
```shell
...

The ubiquitous "Hello World" program of the microcontroller and SoC world is "blink an LED". The following code demonstrates how
 this is done using the Johnny-Five framework.

'''javascript
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''
...
```

#### <a name="apidoc.element.johnny-five.Led.prototype.pulse"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>pulse (duration, callback)](#apidoc.element.johnny-five.Led.prototype.pulse)
- description and source-code
```javascript
pulse = function (duration, callback) {
  var state = priv.get(this);

  this.stop();

  var options = {
    duration: typeof duration === "number" ? duration : 1000,
    keyFrames: [0, 0xff],
    metronomic: true,
    loop: true,
    easing: "inOutSine",
    onloop: function() {
<span class="apidocCodeCommentSpan">      /* istanbul ignore else */
</span>      if (typeof callback === "function") {
        callback();
      }
    }
  };

  if (typeof duration === "object") {
    Object.assign(options, duration);
  }

  if (typeof duration === "function") {
    callback = duration;
  }

  state.isRunning = true;

  state.animation = state.animation || new Animation(this);
  state.animation.enqueue(options);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.prototype.stop"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>stop ()](#apidoc.element.johnny-five.Led.prototype.stop)
- description and source-code
```javascript
stop = function () {
  var state = priv.get(this);

  if (state.interval) {
    clearInterval(state.interval);
  }

  if (state.animation) {
    state.animation.stop();
  }

  state.interval = null;
  state.isRunning = false;

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.prototype.strobe"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>strobe (duration, callback)](#apidoc.element.johnny-five.Led.prototype.strobe)
- description and source-code
```javascript
strobe = function (duration, callback) {
  var state = priv.get(this);

  // Avoid traffic jams
  this.stop();

  if (typeof duration === "function") {
    callback = duration;
    duration = null;
  }

  state.isRunning = true;

  state.interval = setInterval(function() {
    this.toggle();
    if (typeof callback === "function") {
      callback();
    }
  }.bind(this), duration || 100);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Led.prototype.toggle"></a>[function <span class="apidocSignatureSpan">johnny-five.Led.prototype.</span>toggle ()](#apidoc.element.johnny-five.Led.prototype.toggle)
- description and source-code
```javascript
toggle = function () {
  return this[this.isOn ? "off" : "on"]();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.LedControl"></a>[module johnny-five.LedControl](#apidoc.module.johnny-five.LedControl)

#### <a name="apidoc.element.johnny-five.LedControl.LedControl"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>LedControl (opts)](#apidoc.element.johnny-five.LedControl.LedControl)
- description and source-code
```javascript
function LedControl(opts) {

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

<span class="apidocCodeCommentSpan">  /*
   device instance uses an interface from Controllers:
   either MAX 7219 (default) or HT16K33
   */
</span>  var controller = null;

  if (typeof opts.controller === "string") {
    controller = Controllers[opts.controller];
  } else {
    controller = opts.controller;
  }

  if (typeof controller === "undefined") {
    controller = Controllers.DEFAULT;
  }

  // functions from Controller interface

  this.clear = controller.clear;
  this.led = controller.led;
  this.row = controller.row;
  this.scanLimit = controller.scanLimit;
  this.send = controller.send;
  this.sendDigit = controller.sendDigit;
  this.initialize = controller.initialize;

  // controller specific op codes
  this.OP = controller.OP;

  // digit indexes may be ordered left to right (1) or reversed (-1)
  this.digitOrder = 1;

  // Does the device have a built-in colon?
  /* istanbul ignore else */
  if (!this.isMatrix) {
    this.colon = opts.colon || false;
  }

  // extra functions for HT16K33 devices only
  if (controller.writeDisplay) {
    this.writeDisplay = controller.writeDisplay;
  }
  if (controller.blink) {
    this.blink = controller.blink;
  }
  /*
    devices variable indicates number of connected LED devices
    Here's an example of multiple devices:
    http://tronixstuff.com/2013/10/11/tutorial-arduino-max7219-led-display-driver-ic/
   */
  var devices = opts.devices || (opts.addresses ? opts.addresses.length : 1);

  this.memory = Array(64).fill(0);

  opts.dims = opts.dims || LedControl.MATRIX_DIMENSIONS["8x8"];
  if (typeof opts.dims === "string") {
    opts.dims = LedControl.MATRIX_DIMENSIONS[opts.dims];
  }
  if (Array.isArray(opts.dims)) {
    opts.dims = {
      rows: opts.dims[0],
      columns: opts.dims[1],
    };
  }
  var state = {
    devices: devices,
    digits: opts.digits || 8,
    isMatrix: !!opts.isMatrix,
    isBicolor: !!opts.isBicolor,
    rows: opts.dims.rows,
    columns: opts.dims.columns
  };

  if (!(state.columns === 8 || state.columns === 16) || !(state.rows === 8 || state.rows === 16) || (state.columns + state.rows ===
32)) {
    throw new Error("Invalid matrix dimensions specified: must be 8x8, 16x8 or 8x16");
  }

  Object.defineProperties(this, {
    devices: {
      get: function() {
        return state.devices;
      }
    },
    digits: {
      get: function() {
        return state.digits;
      }
    },
    isMatrix: {
      get: function() {
        return state.isMatrix;
      }
    },
    isBicolor: {
      get: function() {
        return state.isBicolor;
      }
    },
    rows: {
      get: function() {
        return state.rows;
      }
    },
    columns: {
      get: function() {
        return state.columns;
      }
    }
  });

  priv.set(this, state);
  controller.initialize.call(this, opts);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.LedControl.prototype"></a>[module johnny-five.LedControl.prototype](#apidoc.module.johnny-five.LedControl.prototype)

#### <a name="apidoc.element.johnny-five.LedControl.prototype.brightness"></a>[function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>brightness (addr, val)](#apidoc.element.johnny-five.LedControl.prototype.brightness)
- description and source-code
```javascript
brightness = function (addr, val) {
  if (arguments.length === 1) {
    val = addr;
    this.each(function(device) {
      this.brightness(device, val);
    });
  } else {
    this.send(addr, this.OP.BRIGHTNESS || LedControl.OP.BRIGHTNESS, Board.map(val, 0, 100, 0, 15));
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LedControl.prototype.char"></a>[function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>char ()](#apidoc.element.johnny-five.LedControl.prototype.char)
- description and source-code
```javascript
function deprecated() {
  warned = exports.printDeprecationMessage(msg, warned, deprecated);
  if (new.target) {
    return Reflect.construct(fn, arguments, new.target);
  }
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LedControl.prototype.column"></a>[function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>column (addr, col, value)](#apidoc.element.johnny-five.LedControl.prototype.column)
- description and source-code
```javascript
column = function (addr, col, value) {
  var state;
  if (!this.isMatrix) {
    throw new Error("The 'column' method is only supported for Matrix devices");
  }
  if (arguments.length === 2) {
    value = col;
    col = addr;
    this.each(function(device) {
      this.column(device, col, value);
    });
  } else {
    for (var row = 0; row < this.rows; row++) {
      state = value >> ((this.rows - 1) - row);
      state = state & 0x01;
      this.led(addr, row, col, state);
    }
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LedControl.prototype.device"></a>[function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>device (addr)](#apidoc.element.johnny-five.LedControl.prototype.device)
- description and source-code
```javascript
device = function (addr) {
  var bound = {};

<span class="apidocCodeCommentSpan">  /* keys from prototype */
</span>  Object.keys(LedControl.prototype).forEach(function(key) {
    bound[key] = this[key].bind(this, addr);
  }, this);

  /* functions from interface */
  Object.getOwnPropertyNames(this).forEach(function(key) {
    if (this[key] && typeof this[key] === "function") {
      bound[key] = this[key].bind(this, addr);
    }
  }, this);
  return bound;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LedControl.prototype.digit"></a>[function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>digit (addr, position, chr)](#apidoc.element.johnny-five.LedControl.prototype.digit)
- description and source-code
```javascript
digit = function (addr, position, chr) {
  var args, offset, index, character, value;
  var hasDecimal = false;

  if (arguments.length < 3) {
    args = Array.from(arguments);
    this.each(function(device) {
      this.digit.apply(this, (args.unshift(device), args));
    });
    return this;
  }

  if (this.isMatrix) {
    // Not sure this is the best path, will check when segment
    // devices are available.
    this.draw.apply(this, arguments);
    return this;
  }

  offset = addr * this.digits;

  character = String(chr);
  position = Number(position);

  // If controller's indexes are ordered right to left, flip
  // the index around.
  index = position;
  if (this.digitOrder === -1) {
    index = this.digits - index - 1;
  }

  if (character.length === 2 && character[1] === ".") {
    hasDecimal = true;
    character = character[0];
  }

  value = LedControl.DIGIT_CHARS[character];

  if (!value) {
    value = Math.abs(Number(character));
  }

  if (hasDecimal) {
    value = value | LedControl.DIGIT_CHARS["."];
  }

  this.memory[offset + index] = value;
  this.sendDigit(addr, index, value);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LedControl.prototype.draw"></a>[function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>draw (addr, chr)](#apidoc.element.johnny-five.LedControl.prototype.draw)
- description and source-code
```javascript
draw = function (addr, chr) {
  // in matrix mode, this takes two arguments:
  // addr and the character to display
  var character;

  if (arguments.length === 1) {
    chr = addr;
    this.each(function(device) {
      this.draw(device, chr);
    });
  } else {

    if (this.isMatrix) {
      if (Array.isArray(chr)) {
        character = chr;
      } else {
        character = ledCharacters.MATRIX_CHARS[chr];
      }

<span class="apidocCodeCommentSpan">      /* istanbul ignore else */
</span>      if (character !== undefined) {
        if (character.length !== this.rows && character.length !== this.columns) {
          throw new Error("Invalid character: " + character);
        }
        // pad character to match number of rows suppported by device
        var charLength = character.length;

        for (var i = 0; i < (this.rows - charLength); i++) {
          /* istanbul ignore next */
          character.push(0);
        }

        character.forEach(function(rowData, idx) {
          this.row(addr, idx, rowData);
        }, this);
      }
    } else {

      // in seven-segment mode, this takes four arguments, which
      // are just passed through to digit
      this.digit.apply(this, arguments);
    }
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LedControl.prototype.each"></a>[function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>each (callbackfn)](#apidoc.element.johnny-five.LedControl.prototype.each)
- description and source-code
```javascript
each = function (callbackfn) {
  for (var i = 0; i < this.devices; i++) {
    callbackfn.call(this, i);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LedControl.prototype.off"></a>[function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>off (addr)](#apidoc.element.johnny-five.LedControl.prototype.off)
- description and source-code
```javascript
off = function (addr) {
  if (typeof addr === "undefined") {
    this.each(function(device) {
      this.off(device);
    });
  } else {
    this.send(addr, this.OP.SHUTDOWN || LedControl.OP.SHUTDOWN, 0);
  }
  return this;
}
```
- example usage
```shell
...

  return this;
};

ReflectanceArray.prototype.disable = function() {
  var state = priv.get(this);

  state.emitter.off();

  return this;
};

// Calibrate will store the min/max values for this sensor array
// It should be called many times in order to get a lot of readings
// on light and dark areas.  See calibrateUntil for a convenience
...
```

#### <a name="apidoc.element.johnny-five.LedControl.prototype.on"></a>[function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>on (addr)](#apidoc.element.johnny-five.LedControl.prototype.on)
- description and source-code
```javascript
on = function (addr) {
  if (typeof addr === "undefined") {
    this.each(function(device) {
      this.on(device);
    });
  } else {
    this.send(addr, this.OP.SHUTDOWN || LedControl.OP.SHUTDOWN, 1);
  }
  return this;
}
```
- example usage
```shell
...

The ubiquitous "Hello World" program of the microcontroller and SoC world is "blink an LED". The following code demonstrates how
 this is done using the Johnny-Five framework.

'''javascript
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''
...
```

#### <a name="apidoc.element.johnny-five.LedControl.prototype.print"></a>[function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>print (message, opts)](#apidoc.element.johnny-five.LedControl.prototype.print)
- description and source-code
```javascript
print = function (message, opts) {
  var rdigchars = /([0-9A-Za-z][.]|[0-9A-Za-z:]|[\s])/g;
  var characters;

  opts = opts || {
    device: 0
  };

  if (this.isMatrix) {
    // figure out what to do with Matrix displays
    throw new Error("Led.Matrix does not yet support the print method");
  }

  if (typeof message !== "string") {
    message = String(message);
  }

  characters = message.match(rdigchars);

  // When a device has a built-in colon, ie. "00:00",
  // then attempt to make it less awkward to print words across
  // the display by splicing in a " " placeholder, but only
  // when necessary.
  if (this.colon) {
    if (characters.length > 2 &&
      (characters[2] !== ":" && characters[2] !== " ")) {
      characters.splice(2, 0, " ");
    }
  }

<span class="apidocCodeCommentSpan">  /* istanbul ignore next */
</span>  (characters || []).forEach(function(character, position) {
    this.digit(opts.device, position, character);
  }, this);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.LedControl.prototype.setLed"></a>[function <span class="apidocSignatureSpan">johnny-five.LedControl.prototype.</span>setLed ()](#apidoc.element.johnny-five.LedControl.prototype.setLed)
- description and source-code
```javascript
function deprecated() {
  warned = exports.printDeprecationMessage(msg, warned, deprecated);
  if (new.target) {
    return Reflect.construct(fn, arguments, new.target);
  }
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Leds"></a>[module johnny-five.Leds](#apidoc.module.johnny-five.Leds)

#### <a name="apidoc.element.johnny-five.Leds.Leds"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Leds (numsOrObjects)](#apidoc.element.johnny-five.Leds.Leds)
- description and source-code
```javascript
function Leds(numsOrObjects) {
  if (!(this instanceof Leds)) {
    return new Leds(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Led
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Leds.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Leds.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Leds.super_)
- description and source-code
```javascript
function Collection(numsOrObjects) {
  var Type = this.type;
  var initObjects = [];

  this.length = 0;

  if (Array.isArray(numsOrObjects)) {
    initObjects = numsOrObjects;
  } else {
    // Initialize with a Shared Properties object
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (Array.isArray(numsOrObjects.pins)) {
      var keys = Object.keys(numsOrObjects).filter(function(key) {
        return key !== "pins";
      });
      initObjects = numsOrObjects.pins.map(function(pin) {
        var obj = {};

        if (Array.isArray(pin)) {
          obj.pins = pin;
        } else {
          obj.pin = pin;
        }

        return keys.reduce(function(accum, key) {
          accum[key] = numsOrObjects[key];
          return accum;
        }, obj);
      });
    }
  }

  /* istanbul ignore else */
  if (initObjects.length) {
    while (initObjects.length) {
      var numOrObject = initObjects.shift();

      // When a Type exists, respect it!
      if (typeof Type === "function") {
        if (!(numOrObject instanceof Type || numOrObject instanceof this.constructor)) {
          numOrObject = new Type(numOrObject);
        }
      }

      this.add(numOrObject);
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Leds.prototype"></a>[module johnny-five.Leds.prototype](#apidoc.module.johnny-five.Leds.prototype)

#### <a name="apidoc.element.johnny-five.Leds.prototype.blink"></a>[function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>blink (duration, callback)](#apidoc.element.johnny-five.Leds.prototype.blink)
- description and source-code
```javascript
blink = function (duration, callback) {
  var length = this.length;
  var signals = [];
  var led;

  if (typeof duration === "function") {
    callback = duration;
    duration = 1000;
  }

  if (typeof callback !== "function") {
    callback = noop;
  }

  for (var i = 0; i < length; i++) {
    led = this[i];
    signals.push(
<span class="apidocCodeCommentSpan">      /* jshint ignore:start */
</span>      new Promise(function(resolve) {
        led[method](duration, function() {
          resolve();
        });
      })
      /* jshint ignore:end */
    );
  }

  Promise.all(signals).then(callback);

  return this;
}
```
- example usage
```shell
...
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''

<img src="https://github.com/rwaldron/johnny-five/raw/master/assets/led-blink.gif">

> Note: Node will crash if you try to run johnny-five in the node REPL, but board instances will create their own contextual REPL
. Put your script in a file.
...
```

#### <a name="apidoc.element.johnny-five.Leds.prototype.brightness"></a>[function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>brightness ()](#apidoc.element.johnny-five.Leds.prototype.brightness)
- description and source-code
```javascript
brightness = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Leds.prototype.fade"></a>[function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>fade (duration, callback)](#apidoc.element.johnny-five.Leds.prototype.fade)
- description and source-code
```javascript
fade = function (duration, callback) {
  var length = this.length;
  var signals = [];
  var led;

  if (typeof duration === "function") {
    callback = duration;
    duration = 1000;
  }

  if (typeof callback !== "function") {
    callback = noop;
  }

  for (var i = 0; i < length; i++) {
    led = this[i];
    signals.push(
<span class="apidocCodeCommentSpan">      /* jshint ignore:start */
</span>      new Promise(function(resolve) {
        led[method](duration, function() {
          resolve();
        });
      })
      /* jshint ignore:end */
    );
  }

  Promise.all(signals).then(callback);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Leds.prototype.fadeIn"></a>[function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>fadeIn (duration, callback)](#apidoc.element.johnny-five.Leds.prototype.fadeIn)
- description and source-code
```javascript
fadeIn = function (duration, callback) {
  var length = this.length;
  var signals = [];
  var led;

  if (typeof duration === "function") {
    callback = duration;
    duration = 1000;
  }

  if (typeof callback !== "function") {
    callback = noop;
  }

  for (var i = 0; i < length; i++) {
    led = this[i];
    signals.push(
<span class="apidocCodeCommentSpan">      /* jshint ignore:start */
</span>      new Promise(function(resolve) {
        led[method](duration, function() {
          resolve();
        });
      })
      /* jshint ignore:end */
    );
  }

  Promise.all(signals).then(callback);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Leds.prototype.fadeOut"></a>[function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>fadeOut (duration, callback)](#apidoc.element.johnny-five.Leds.prototype.fadeOut)
- description and source-code
```javascript
fadeOut = function (duration, callback) {
  var length = this.length;
  var signals = [];
  var led;

  if (typeof duration === "function") {
    callback = duration;
    duration = 1000;
  }

  if (typeof callback !== "function") {
    callback = noop;
  }

  for (var i = 0; i < length; i++) {
    led = this[i];
    signals.push(
<span class="apidocCodeCommentSpan">      /* jshint ignore:start */
</span>      new Promise(function(resolve) {
        led[method](duration, function() {
          resolve();
        });
      })
      /* jshint ignore:end */
    );
  }

  Promise.all(signals).then(callback);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Leds.prototype.intensity"></a>[function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>intensity ()](#apidoc.element.johnny-five.Leds.prototype.intensity)
- description and source-code
```javascript
intensity = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Leds.prototype.off"></a>[function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>off ()](#apidoc.element.johnny-five.Leds.prototype.off)
- description and source-code
```javascript
off = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
...

  return this;
};

ReflectanceArray.prototype.disable = function() {
  var state = priv.get(this);

  state.emitter.off();

  return this;
};

// Calibrate will store the min/max values for this sensor array
// It should be called many times in order to get a lot of readings
// on light and dark areas.  See calibrateUntil for a convenience
...
```

#### <a name="apidoc.element.johnny-five.Leds.prototype.on"></a>[function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>on ()](#apidoc.element.johnny-five.Leds.prototype.on)
- description and source-code
```javascript
on = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
...

The ubiquitous "Hello World" program of the microcontroller and SoC world is "blink an LED". The following code demonstrates how
 this is done using the Johnny-Five framework.

'''javascript
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''
...
```

#### <a name="apidoc.element.johnny-five.Leds.prototype.pulse"></a>[function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>pulse (duration, callback)](#apidoc.element.johnny-five.Leds.prototype.pulse)
- description and source-code
```javascript
pulse = function (duration, callback) {
  var length = this.length;
  var signals = [];
  var led;

  if (typeof duration === "function") {
    callback = duration;
    duration = 1000;
  }

  if (typeof callback !== "function") {
    callback = noop;
  }

  for (var i = 0; i < length; i++) {
    led = this[i];
    signals.push(
<span class="apidocCodeCommentSpan">      /* jshint ignore:start */
</span>      new Promise(function(resolve) {
        led[method](duration, function() {
          resolve();
        });
      })
      /* jshint ignore:end */
    );
  }

  Promise.all(signals).then(callback);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Leds.prototype.stop"></a>[function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>stop ()](#apidoc.element.johnny-five.Leds.prototype.stop)
- description and source-code
```javascript
stop = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Leds.prototype.strobe"></a>[function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>strobe ()](#apidoc.element.johnny-five.Leds.prototype.strobe)
- description and source-code
```javascript
strobe = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Leds.prototype.toggle"></a>[function <span class="apidocSignatureSpan">johnny-five.Leds.prototype.</span>toggle ()](#apidoc.element.johnny-five.Leds.prototype.toggle)
- description and source-code
```javascript
toggle = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Light"></a>[module johnny-five.Light](#apidoc.module.johnny-five.Light)

#### <a name="apidoc.element.johnny-five.Light.Light"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Light (opts)](#apidoc.element.johnny-five.Light.Light)
- description and source-code
```javascript
function Light(opts) {

  if (!(this instanceof Light)) {
    return new Light(opts);
  }

  var controller = null;
  var state = {};
  var raw = 0;
  var last = 0;
  var freq = opts.freq || 25;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (typeof opts.controller === "string") {
    controller = Controllers[opts.controller];
  } else {
    controller = opts.controller || Controllers.DEFAULT;
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toIntensityLevel) {
    this.toIntensityLevel = opts.toIntensityLevel || function(x) {
      return x;
    };
  }

  if (!this.toLux) {
    this.toLux = opts.toLux || function(x) {
      return x;
    };
  }

  Object.defineProperties(this, {
    value: {
      get: function() {
        return raw;
      },
    },
    level: {
      get: function() {
        return this.toIntensityLevel(raw);
      },
    },
  });

  priv.set(this, state);

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  if (typeof this.lux === "undefined") {
    Object.defineProperty(this, "lux", {
      get: function() {
        return this.toLux(raw);
      },
    });
  }

  var data = {
    level: 0,
    lux: 0,
  };

  setInterval(function() {
    data.level = this.level;
    data.lux = this.lux;

    this.emit("data", data);

    if (raw !== last) {
      last = raw;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Light.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Light.</span>super_ ()](#apidoc.element.johnny-five.Light.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Light.prototype"></a>[module johnny-five.Light.prototype](#apidoc.module.johnny-five.Light.prototype)

#### <a name="apidoc.element.johnny-five.Light.prototype.within"></a>[function <span class="apidocSignatureSpan">johnny-five.Light.prototype.</span>within (range, unit, callback)](#apidoc.element.johnny-five.Light.prototype.within)
- description and source-code
```javascript
within = function (range, unit, callback) {
  var upper;

  if (typeof range === "number") {
    upper = range;
    range = [0, upper];
  }

  if (!Array.isArray(range)) {
    throw new Error("within expected a range array");
  }

  if (typeof unit === "function") {
    callback = unit;
    unit = "value";
  }

  if (typeof this[unit] === "undefined") {
    return this;
  }

  // Use the continuous read event for high resolution
  this.on("data", function() {
    var value = this[unit];
    if (value >= range[0] && value <= range[1]) {
      callback.call(this, null, value);
    }
  }.bind(this));

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Motion"></a>[module johnny-five.Motion](#apidoc.module.johnny-five.Motion)

#### <a name="apidoc.element.johnny-five.Motion.Motion"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Motion (opts)](#apidoc.element.johnny-five.Motion.Motion)
- description and source-code
```javascript
function Motion(opts) {

  if (!(this instanceof Motion)) {
    return new Motion(opts);
  }

  var freq = opts.freq || 25;
  var last = false;
  var controller;
  var state;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (typeof opts.controller === "string") {
    controller = Controllers[opts.controller];
  } else {
    controller = opts.controller || Controllers["PIR"];
  }

  Board.Controller.call(this, controller, opts);

  state = {
    value: false,
    isCalibrated: false
  };

  priv.set(this, state);

  Object.defineProperties(this, {
<span class="apidocCodeCommentSpan">    /**
     * [read-only] Current sensor state
     * @property detectedMotion
     * @type Boolean
     */
</span>    detectedMotion: {
      get: function() {
        return this.toBoolean(state.value);
      }
    },
    /**
     * [read-only] Sensor calibration status
     * @property isCalibrated
     * @type Boolean
     */
    isCalibrated: {
      get: function() {
        return state.isCalibrated;
      }
    },
  });

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      state.value = data;
    });
  }

  setInterval(function() {
    var isChange = false;
    var eventData = {
      timestamp: Date.now(),
      detectedMotion: this.detectedMotion,
      isCalibrated: state.isCalibrated
    };

    if (state.isCalibrated && this.detectedMotion && !last) {
      this.emit("motionstart", eventData);
    }

    if (state.isCalibrated && !this.detectedMotion && last) {
      this.emit("motionend", eventData);
    }

    if (last !== this.detectedMotion) {
      isChange = true;
    }

    this.emit("data", eventData);

    if (isChange) {
      this.emit("change", eventData);
    }

    last = this.detectedMotion;
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motion.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.Motion.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Motion.Collection)
- description and source-code
```javascript
Collection = function (numsOrObjects) {
  if (!(this instanceof Motion.Collection)) {
    return new Motion.Collection(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Motion
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motion.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Motion.</span>super_ ()](#apidoc.element.johnny-five.Motion.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Motion.Collection"></a>[module johnny-five.Motion.Collection](#apidoc.module.johnny-five.Motion.Collection)

#### <a name="apidoc.element.johnny-five.Motion.Collection.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.Motion.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Motion.Collection.Collection)
- description and source-code
```javascript
Collection = function (numsOrObjects) {
  if (!(this instanceof Motion.Collection)) {
    return new Motion.Collection(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Motion
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motion.Collection.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Motion.Collection.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Motion.Collection.super_)
- description and source-code
```javascript
super_ = function (numsOrObjects) {

  // Create private state ahead of super call
  priv.set(this, {
    timing: {
      last: Date.now()
    }
  });

  Collection.call(this, numsOrObjects);

  // If the Collection.Emitter was created
  // with a Shared Properties object, then
  // we should abide by the freq or period
  // properties...
  var interval = null;
  var period = 5;

  if (!Array.isArray(numsOrObjects) &&
      (typeof numsOrObjects === "object" && numsOrObjects !== null))  {

    period = numsOrObjects.freq || numsOrObjects.period || period;

    // _However_, looking to the future, we
    // need to start thinking about replacing
    // the garbage named _freq_ (the value is
    // actually a period), with real _frequency_
    // in Hz.

    // If provided, convert frequency to period
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (numsOrObjects.frequency) {
      period = (1 / numsOrObjects.frequency) * 1000;
    }
  }

  Object.defineProperties(this, {
    period: {
      get: function() {
        return period;
      },
      set: function(value) {
        if (period !== value) {
          period = value;
        }

        if (interval) {
          clearInterval(interval);
        }

        interval = setInterval(function() {
          this.emit("data", this);
        }.bind(this), period);
      }
    },
  });

  this.period = period;

  this.on("newListener", function(event) {
    if (event === "change" || event === "data") {
      return;
    }

    this.forEach(function(input) {
      input.on(event, function(data) {
        this.emit(event, input, data);
      }.bind(this));
    }, this);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Motor"></a>[module johnny-five.Motor](#apidoc.module.johnny-five.Motor)

#### <a name="apidoc.element.johnny-five.Motor.Motor"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Motor (opts)](#apidoc.element.johnny-five.Motor.Motor)
- description and source-code
```javascript
function Motor(opts) {

  var device, controller, state;

  if (!(this instanceof Motor)) {
    return new Motor(opts);
  }

  Board.Component.call(
    this, this.opts = Board.Options(opts)
  );

  controller = opts.controller || null;

  // Derive device based on pins passed
  if (typeof this.opts.device === "undefined") {

    this.opts.device = (typeof this.opts.pins === "undefined" && typeof this.opts.register !== "object") ?
      "NONDIRECTIONAL" : "DIRECTIONAL";

    if (this.opts.pins && (this.opts.pins.cdir || this.opts.pins.length > 2)) {
      this.opts.device = "CDIR";
    }

    if (typeof controller === "string" &&
      (controller.startsWith("EVS") || controller.startsWith("GROVE_I2C"))) {
      this.opts.device = "DIRECTIONAL";
    }
  }

  // Allow users to pass in custom device types
  device = typeof this.opts.device === "string" ?
    Devices[this.opts.device] : this.opts.device;

  this.threshold = typeof this.opts.threshold !== "undefined" ?
    this.opts.threshold : 30;

  this.invertPWM = typeof this.opts.invertPWM !== "undefined" ?
    this.opts.invertPWM : false;

  Object.defineProperties(this, device);

  if (this.opts.register) {
    this.opts.controller = "ShiftRegister";
  }

<span class="apidocCodeCommentSpan">  /**
   * Note: Controller decorates the device. Used for adding
   * special controllers (i.e. PCA9685)
   **/
</span>  if (this.opts.controller) {
    controller = typeof this.opts.controller === "string" ?
      Controllers[this.opts.controller] : this.opts.controller;

    Board.Controller.call(this, controller, opts);
  }

  // current just wraps a Sensor
  if (this.opts.current) {
    this.opts.current.board = this.board;
    this.current = new Sensor(this.opts.current);
  }

  // Create a "state" entry for privately
  // storing the state of the motor
  state = {
    isOn: false,
    currentSpeed: typeof this.opts.speed !== "undefined" ?
      this.opts.speed : 128,
    braking: false,
    enabled: true
  };

  priv.set(this, state);

  Object.defineProperties(this, {
    // Calculated, read-only motor on/off state
    // true|false
    isOn: {
      get: function() {
        return state.isOn;
      }
    },
    currentSpeed: {
      get: function() {
        return state.currentSpeed;
      }
    },
    braking: {
      get: function() {
        return state.braking;
      }
    },
    enabled: {
      get: function() {
        return state.enabled;
      }
    }
  });

  // We need to store and initialize the state of the dir pin(s)
  this.direction = {
    value: 1
  };

  if (this.initialize) {
    this.initialize(opts);
  }

  this.enable();
  this.dir(this.direction);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.Array"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.</span>Array (numsOrObjects)](#apidoc.element.johnny-five.Motor.Array)
- description and source-code
```javascript
function Motors(numsOrObjects) {
  if (!(this instanceof Motors)) {
    return new Motors(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Motor
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Motor.Collection)
- description and source-code
```javascript
function Motors(numsOrObjects) {
  if (!(this instanceof Motors)) {
    return new Motors(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Motor
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.</span>super_ ()](#apidoc.element.johnny-five.Motor.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Motor.prototype"></a>[module johnny-five.Motor.prototype](#apidoc.module.johnny-five.Motor.prototype)

#### <a name="apidoc.element.johnny-five.Motor.prototype.brake"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>brake (duration)](#apidoc.element.johnny-five.Motor.prototype.brake)
- description and source-code
```javascript
brake = function (duration) {
  if (typeof this.pins.brake === "undefined") {
    if (this.board.io.name !== "Mock") {
      console.log("Non-braking motor type");
    }
    this.stop();
  } else {
    this.setPin(this.pins.brake, 1);
    this.setPin(this.pins.dir, 1);
    this.speed({
      speed: 255,
      saveSpeed: false,
      braking: true
    });
    process.nextTick(this.emit.bind(this, "brake"));

    if (duration) {
      var motor = this;
      this.board.wait(duration, function() {
        motor.resume();
      });
    }
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.prototype.disable"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>disable ()](#apidoc.element.johnny-five.Motor.prototype.disable)
- description and source-code
```javascript
disable = function () {
  var state = priv.get(this);
  if (typeof this.pins.enable !== "undefined" && this.enabled) {
    this.setPin(this.pins.enable, 0);
    state.enabled = false;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.prototype.enable"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>enable ()](#apidoc.element.johnny-five.Motor.prototype.enable)
- description and source-code
```javascript
enable = function () {
  var state = priv.get(this);
  if (typeof this.pins.enable !== "undefined" && !this.enabled) {
    this.setPin(this.pins.enable, 1);
    state.enabled = true;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.prototype.forward"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>forward (speed)](#apidoc.element.johnny-five.Motor.prototype.forward)
- description and source-code
```javascript
forward = function (speed) {
  this.dir(dir);
  this.start(speed);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.prototype.fwd"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>fwd (speed)](#apidoc.element.johnny-five.Motor.prototype.fwd)
- description and source-code
```javascript
fwd = function (speed) {
  this.dir(dir);
  this.start(speed);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.prototype.initialize"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>initialize ()](#apidoc.element.johnny-five.Motor.prototype.initialize)
- description and source-code
```javascript
initialize = function () {
  this.io.pinMode(this.pins.pwm, this.io.MODES.PWM);

  ["dir", "cdir", "brake", "enable"].forEach(function(pin) {
    if (typeof this.pins[pin] !== "undefined") {
      this.io.pinMode(this.pins[pin], this.io.MODES.OUTPUT);
    }
  }, this);

}
```
- example usage
```shell
...
    return raw;
  };
}

priv.set(this, state);

if (typeof this.initialize === "function") {
  this.initialize(opts, function(data) {
    raw = data;
  });
}

setInterval(function() {
  if (raw === null) {
    return;
...
```

#### <a name="apidoc.element.johnny-five.Motor.prototype.release"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>release ()](#apidoc.element.johnny-five.Motor.prototype.release)
- description and source-code
```javascript
release = function () {
  this.resume();
  process.nextTick(this.emit.bind(this, "release"));

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.prototype.resume"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>resume ()](#apidoc.element.johnny-five.Motor.prototype.resume)
- description and source-code
```javascript
resume = function () {
  var speed = this.speed();
  this.dir(this.direction);
  this.start(speed);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.prototype.rev"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>rev (speed)](#apidoc.element.johnny-five.Motor.prototype.rev)
- description and source-code
```javascript
rev = function (speed) {
  this.dir(dir);
  this.start(speed);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.prototype.reverse"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>reverse (speed)](#apidoc.element.johnny-five.Motor.prototype.reverse)
- description and source-code
```javascript
reverse = function (speed) {
  this.dir(dir);
  this.start(speed);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.prototype.setPWM"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>setPWM (pin, value)](#apidoc.element.johnny-five.Motor.prototype.setPWM)
- description and source-code
```javascript
setPWM = function (pin, value) {
  this.io.analogWrite(pin, value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.prototype.setPin"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>setPin (pin, value)](#apidoc.element.johnny-five.Motor.prototype.setPin)
- description and source-code
```javascript
setPin = function (pin, value) {
  this.io.digitalWrite(pin, value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.prototype.speed"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>speed (opts)](#apidoc.element.johnny-five.Motor.prototype.speed)
- description and source-code
```javascript
speed = function (opts) {
  var state = priv.get(this);

  if (typeof opts === "undefined") {
    return state.currentSpeed;
  } else {

    if (typeof opts === "number") {
      opts = {
        speed: opts
      };
    }

    opts.speed = Board.constrain(opts.speed, 0, 255);

    opts.saveSpeed = typeof opts.saveSpeed !== "undefined" ?
      opts.saveSpeed : true;

    if (opts.speed < this.threshold) {
      opts.speed = 0;
    }

    state.isOn = opts.speed === 0 ? false : true;

    if (opts.saveSpeed) {
      state.currentSpeed = opts.speed;
    }

    if (opts.braking) {
      state.braking = true;
    }

    if (this.invertPWM && this.direction.value === 1) {
      opts.speed ^= 0xff;
    }

    this.setPWM(this.pins.pwm, opts.speed);

    return this;
  }

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.prototype.start"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>start (speed)](#apidoc.element.johnny-five.Motor.prototype.start)
- description and source-code
```javascript
start = function (speed) {
  // Send a signal to turn on the motor and run at given speed in whatever
  // direction is currently set.
  if (this.pins.brake && this.braking) {
    this.setPin(this.pins.brake, 0);
  }

  // get current speed if nothing provided.
  speed = typeof speed !== "undefined" ?
    speed : this.speed();

  this.speed({
    speed: speed,
    braking: false
  });

  // "start" event is fired when the motor is started
  if (speed > 0) {
    process.nextTick(this.emit.bind(this, "start"));
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motor.prototype.stop"></a>[function <span class="apidocSignatureSpan">johnny-five.Motor.prototype.</span>stop ()](#apidoc.element.johnny-five.Motor.prototype.stop)
- description and source-code
```javascript
stop = function () {
  this.speed({
    speed: 0,
    saveSpeed: false
  });
  process.nextTick(this.emit.bind(this, "stop"));

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Motors"></a>[module johnny-five.Motors](#apidoc.module.johnny-five.Motors)

#### <a name="apidoc.element.johnny-five.Motors.Motors"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Motors (numsOrObjects)](#apidoc.element.johnny-five.Motors.Motors)
- description and source-code
```javascript
function Motors(numsOrObjects) {
  if (!(this instanceof Motors)) {
    return new Motors(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Motor
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Motors.super_)
- description and source-code
```javascript
function Collection(numsOrObjects) {
  var Type = this.type;
  var initObjects = [];

  this.length = 0;

  if (Array.isArray(numsOrObjects)) {
    initObjects = numsOrObjects;
  } else {
    // Initialize with a Shared Properties object
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (Array.isArray(numsOrObjects.pins)) {
      var keys = Object.keys(numsOrObjects).filter(function(key) {
        return key !== "pins";
      });
      initObjects = numsOrObjects.pins.map(function(pin) {
        var obj = {};

        if (Array.isArray(pin)) {
          obj.pins = pin;
        } else {
          obj.pin = pin;
        }

        return keys.reduce(function(accum, key) {
          accum[key] = numsOrObjects[key];
          return accum;
        }, obj);
      });
    }
  }

  /* istanbul ignore else */
  if (initObjects.length) {
    while (initObjects.length) {
      var numOrObject = initObjects.shift();

      // When a Type exists, respect it!
      if (typeof Type === "function") {
        if (!(numOrObject instanceof Type || numOrObject instanceof this.constructor)) {
          numOrObject = new Type(numOrObject);
        }
      }

      this.add(numOrObject);
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Motors.prototype"></a>[module johnny-five.Motors.prototype](#apidoc.module.johnny-five.Motors.prototype)

#### <a name="apidoc.element.johnny-five.Motors.prototype.brake"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>brake ()](#apidoc.element.johnny-five.Motors.prototype.brake)
- description and source-code
```javascript
brake = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors.prototype.disable"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>disable ()](#apidoc.element.johnny-five.Motors.prototype.disable)
- description and source-code
```javascript
disable = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors.prototype.enable"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>enable ()](#apidoc.element.johnny-five.Motors.prototype.enable)
- description and source-code
```javascript
enable = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors.prototype.forward"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>forward ()](#apidoc.element.johnny-five.Motors.prototype.forward)
- description and source-code
```javascript
forward = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors.prototype.fwd"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>fwd ()](#apidoc.element.johnny-five.Motors.prototype.fwd)
- description and source-code
```javascript
fwd = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors.prototype.initialize"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>initialize ()](#apidoc.element.johnny-five.Motors.prototype.initialize)
- description and source-code
```javascript
initialize = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
...
    return raw;
  };
}

priv.set(this, state);

if (typeof this.initialize === "function") {
  this.initialize(opts, function(data) {
    raw = data;
  });
}

setInterval(function() {
  if (raw === null) {
    return;
...
```

#### <a name="apidoc.element.johnny-five.Motors.prototype.release"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>release ()](#apidoc.element.johnny-five.Motors.prototype.release)
- description and source-code
```javascript
release = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors.prototype.resume"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>resume ()](#apidoc.element.johnny-five.Motors.prototype.resume)
- description and source-code
```javascript
resume = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors.prototype.rev"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>rev ()](#apidoc.element.johnny-five.Motors.prototype.rev)
- description and source-code
```javascript
rev = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors.prototype.reverse"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>reverse ()](#apidoc.element.johnny-five.Motors.prototype.reverse)
- description and source-code
```javascript
reverse = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors.prototype.setPWM"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>setPWM ()](#apidoc.element.johnny-five.Motors.prototype.setPWM)
- description and source-code
```javascript
setPWM = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors.prototype.setPin"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>setPin ()](#apidoc.element.johnny-five.Motors.prototype.setPin)
- description and source-code
```javascript
setPin = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors.prototype.speed"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>speed ()](#apidoc.element.johnny-five.Motors.prototype.speed)
- description and source-code
```javascript
speed = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors.prototype.start"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>start ()](#apidoc.element.johnny-five.Motors.prototype.start)
- description and source-code
```javascript
start = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Motors.prototype.stop"></a>[function <span class="apidocSignatureSpan">johnny-five.Motors.prototype.</span>stop ()](#apidoc.element.johnny-five.Motors.prototype.stop)
- description and source-code
```javascript
stop = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Piezo"></a>[module johnny-five.Piezo](#apidoc.module.johnny-five.Piezo)

#### <a name="apidoc.element.johnny-five.Piezo.Piezo"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Piezo (opts)](#apidoc.element.johnny-five.Piezo.Piezo)
- description and source-code
```javascript
function Piezo(opts) {

  if (!(this instanceof Piezo)) {
    return new Piezo(opts);
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var controller = null;

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.DEFAULT;
  }

  Object.defineProperties(this, controller);

  Board.Controller.call(this, controller, opts);

  // Piezo instance properties
  var state = {
    isPlaying: false,
    timeout: null,
    address: null,
  };

  priv.set(this, state);

  Object.defineProperties(this, {
    isPlaying: {
      get: function() {
        return state.isPlaying;
      }
    }
  });

  if (typeof this.initialize === "function") {
    this.initialize(opts);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Piezo.ToFrequency"></a>[function <span class="apidocSignatureSpan">johnny-five.Piezo.</span>ToFrequency (tone)](#apidoc.element.johnny-five.Piezo.ToFrequency)
- description and source-code
```javascript
ToFrequency = function (tone) {
  var toneSeconds = tone / MICROSECONDS_PER_SECOND;
  var period = toneSeconds * 2;
  return Math.round(1 / period);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Piezo.ToSong"></a>[function <span class="apidocSignatureSpan">johnny-five.Piezo.</span>ToSong (stringSong, beats)](#apidoc.element.johnny-five.Piezo.ToSong)
- description and source-code
```javascript
ToSong = function (stringSong, beats) {
  beats = beats || 1;
  var notes = stringSong.split(" ");
  var song = [];
  var note, lastNote;
  while (notes.length) {
    note = notes.shift();
    if (/^[0-9]+$/.test(note)) {
      note = parseInt(note, 10);
    }
    lastNote = song[song.length - 1];
    if (lastNote && lastNote[0] === note) {
      lastNote[1] += beats;
    } else {
      song.push([note, beats]);
    }
  }
  return song;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Piezo.ToTone"></a>[function <span class="apidocSignatureSpan">johnny-five.Piezo.</span>ToTone (frequency)](#apidoc.element.johnny-five.Piezo.ToTone)
- description and source-code
```javascript
ToTone = function (frequency) {
  var period = 1 / frequency;
  var duty = period / 2;
  return Math.round(duty * MICROSECONDS_PER_SECOND);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Piezo.defaultOctave"></a>[function <span class="apidocSignatureSpan">johnny-five.Piezo.</span>defaultOctave (octave)](#apidoc.element.johnny-five.Piezo.defaultOctave)
- description and source-code
```javascript
defaultOctave = function (octave) {
  if (Piezo.isValidOctave(octave)) {
    defaultOctave = octave;
  }

  return defaultOctave;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Piezo.isValidOctave"></a>[function <span class="apidocSignatureSpan">johnny-five.Piezo.</span>isValidOctave (octave)](#apidoc.element.johnny-five.Piezo.isValidOctave)
- description and source-code
```javascript
isValidOctave = function (octave) {
  return typeof octave === "number" && (octave >= 0 && octave <= 8);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Piezo.Parsers"></a>[module johnny-five.Piezo.Parsers](#apidoc.module.johnny-five.Piezo.Parsers)

#### <a name="apidoc.element.johnny-five.Piezo.Parsers.beatFromNote"></a>[function <span class="apidocSignatureSpan">johnny-five.Piezo.Parsers.</span>beatFromNote (note)](#apidoc.element.johnny-five.Piezo.Parsers.beatFromNote)
- description and source-code
```javascript
beatFromNote = function (note) {
  var beat = 1;
  if (Array.isArray(note) && note[1] !== undefined) {
    // If extant, beat will be second element of note
    beat = note[1];
  }
  return beat;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Piezo.Parsers.hzFromInput"></a>[function <span class="apidocSignatureSpan">johnny-five.Piezo.Parsers.</span>hzFromInput (input)](#apidoc.element.johnny-five.Piezo.Parsers.hzFromInput)
- description and source-code
```javascript
hzFromInput = function (input) {
  var output = input;

  if (Array.isArray(input)) {
    output = input[0];
  }

  // Is it a valid frequency?
  if (typeof output === "number" &&
      Piezo.Frequencies[output]) {
    return output;
  }

  // See above: Piezo.Notes { ... }
  if (typeof output === "string") {
    output = output.toLowerCase().trim();

    // Example: c#, c
    if (output.endsWith("#") || output.length === 1) {
      output += defaultOctave;
    }

    // There will never be a 0 tone
    output = Piezo.Notes[output] || null;
  }

  // Normalize NaN, null & undefined to null
  if (isNaN(output)) {
    output = null;
  }

  return output;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Piezo.prototype"></a>[module johnny-five.Piezo.prototype](#apidoc.module.johnny-five.Piezo.prototype)

#### <a name="apidoc.element.johnny-five.Piezo.prototype.frequency"></a>[function <span class="apidocSignatureSpan">johnny-five.Piezo.prototype.</span>frequency (frequency, duration)](#apidoc.element.johnny-five.Piezo.prototype.frequency)
- description and source-code
```javascript
frequency = function (frequency, duration) {
  return this.tone(Piezo.ToTone(frequency), duration);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Piezo.prototype.note"></a>[function <span class="apidocSignatureSpan">johnny-five.Piezo.prototype.</span>note (note, duration)](#apidoc.element.johnny-five.Piezo.prototype.note)
- description and source-code
```javascript
note = function (note, duration) {
  var tone = Piezo.Parsers.hzFromInput(note);

  return this.tone(tone, duration);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Piezo.prototype.off"></a>[function <span class="apidocSignatureSpan">johnny-five.Piezo.prototype.</span>off ()](#apidoc.element.johnny-five.Piezo.prototype.off)
- description and source-code
```javascript
off = function () {
  return this.noTone();
}
```
- example usage
```shell
...

  return this;
};

ReflectanceArray.prototype.disable = function() {
  var state = priv.get(this);

  state.emitter.off();

  return this;
};

// Calibrate will store the min/max values for this sensor array
// It should be called many times in order to get a lot of readings
// on light and dark areas.  See calibrateUntil for a convenience
...
```

#### <a name="apidoc.element.johnny-five.Piezo.prototype.play"></a>[function <span class="apidocSignatureSpan">johnny-five.Piezo.prototype.</span>play (tune, callback)](#apidoc.element.johnny-five.Piezo.prototype.play)
- description and source-code
```javascript
play = function (tune, callback) {
  if (typeof tune !== "object") {
    tune = {
      song: tune
    };
  }

  if (typeof tune.song === "string") {
    tune.song = Piezo.ToSong(tune.song, tune.beats);
  }

  if (tune.song && !Array.isArray(tune.song)) {
<span class="apidocCodeCommentSpan">    /*
      If 'tune.song' was present and not falsy,
      but also is not a string (above), or an array
      (presently), then it is likely a Hz value, so
      normalize song to the appropriate array format:
     */
</span>    tune.song = [tune.song];
    /*
      Note: This path is taken for calls that look
      like this:

      piezo.play({
        song: 262,
      }, ...)

      Where 262 is a frequency in Hz
     */
  }

  var state = priv.get(this);
  var tempo = tune.tempo || 250;
  // Length for a single beat in ms
  var beatDuration = Math.round(60000 / tempo);
  var song = tune.song || [];
  var duration;
  var nextNoteIndex = 0;

  var next = function() {
    if (nextNoteIndex === song.length) {
      // No more notes in song:
      // Song is over
      state.isPlaying = false;
      if (typeof callback === "function") {
        callback(tune);
      }
      return;
    }

    var note = song[nextNoteIndex];
    var hz = Piezo.Parsers.hzFromInput(note);
    var beat = Piezo.Parsers.beatFromNote(note);

    duration = beat * beatDuration;
    nextNoteIndex++;

    if (hz === null) {
      this.noTone();
    } else {
      this.frequency(hz, duration);
    }

    state.timeout = setTimeout(next, duration);
  }.bind(this);

  // We are playing a song
  state.isPlaying = true;

  next();

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Piezo.prototype.stop"></a>[function <span class="apidocSignatureSpan">johnny-five.Piezo.prototype.</span>stop ()](#apidoc.element.johnny-five.Piezo.prototype.stop)
- description and source-code
```javascript
stop = function () {
  var state = priv.get(this);

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (state.timeout) {
    clearTimeout(state.timeout);
    state.timeout = null;
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Piezo.prototype.tone"></a>[function <span class="apidocSignatureSpan">johnny-five.Piezo.prototype.</span>tone (tone, duration)](#apidoc.element.johnny-five.Piezo.prototype.tone)
- description and source-code
```javascript
tone = function (tone, duration) {
  return this.frequency(Piezo.ToFrequency(tone), duration);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Pin"></a>[module johnny-five.Pin](#apidoc.module.johnny-five.Pin)

#### <a name="apidoc.element.johnny-five.Pin.Pin"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Pin (opts)](#apidoc.element.johnny-five.Pin.Pin)
- description and source-code
```javascript
function Pin(opts) {
  if (!(this instanceof Pin)) {
    return new Pin(opts);
  }
  if (opts === undefined || (typeof opts === "object" &&
      opts.addr === undefined && opts.pin === undefined)) {
    throw new Error("Pins must have a pin number");
  }

  var pinValue = typeof opts === "object" ? (opts.addr || opts.pin || 0) : opts;
  var isAnalogInput = Pin.isAnalog(opts);
  var isDTOA = false;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  opts.addr = opts.addr || opts.pin;

  if (this.io.analogPins.includes(pinValue)) {
    isAnalogInput = false;
    isDTOA = true;
  }

  var isPin = typeof opts !== "object";
  var addr = isDTOA ? pinValue : (isPin ? opts : opts.addr);
  var type = opts.type || (isAnalogInput ? "analog" : "digital");

  // Create a private side table
  var state = {
    mode: null,
    last: null,
    value: 0
  };

  priv.set(this, state);

  // Create read-only "addr(address)" property
  Object.defineProperties(this, {
    type: {
      get: function() {
        return type;
      }
    },
    addr: {
      get: function() {
        return addr;
      }
    },
    value: {
      get: function() {
        return state.value;
      }
    },
    mode: {
      set: function(mode) {
        var state = priv.get(this);
        state.mode = mode;
        this.io.pinMode(this.addr, mode);
      },
      get: function() {
        return priv.get(this).mode;
      }
    }
  });

  this.mode = typeof opts.as !== "undefined" ? opts.as :
    (typeof opts.mode !== "undefined" ? opts.mode : (isAnalogInput ? 0x02 : 0x01));

  this.freq = typeof opts.freq !== "undefined" ? opts.freq : 20;

  if (this.mode === 0 || this.mode === 2) {
    read(this);
  }

  if (type === "digital") {
    Object.defineProperties(this, {
      isHigh: {
        get: function() {
          return !!state.value;
        }
      },
      isLow: {
        get: function() {
          return !state.value;
        }
      },
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Pin.Array"></a>[function <span class="apidocSignatureSpan">johnny-five.Pin.</span>Array (numsOrObjects)](#apidoc.element.johnny-five.Pin.Array)
- description and source-code
```javascript
function Pins(numsOrObjects) {
  if (!(this instanceof Pins)) {
    return new Pins(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Pin
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Pin.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.Pin.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Pin.Collection)
- description and source-code
```javascript
function Pins(numsOrObjects) {
  if (!(this instanceof Pins)) {
    return new Pins(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Pin
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Pin.isAnalog"></a>[function <span class="apidocSignatureSpan">johnny-five.Pin.</span>isAnalog (opts)](#apidoc.element.johnny-five.Pin.isAnalog)
- description and source-code
```javascript
isAnalog = function (opts) {
  if (typeof opts === "string" && Pin.isPrefixed(opts, ["I", "A"])) {
    return true;
  }

  if (typeof opts === "object") {
    return Pin.isAnalog(
      typeof opts.addr !== "undefined" ? opts.addr : opts.pin
    );
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Pin.isPrefixed"></a>[function <span class="apidocSignatureSpan">johnny-five.Pin.</span>isPrefixed (value, prefixes)](#apidoc.element.johnny-five.Pin.isPrefixed)
- description and source-code
```javascript
isPrefixed = function (value, prefixes) {
  value = value[0];

  return prefixes.reduce(function(resolution, prefix) {
    if (!resolution) {
      return prefix === value;
    }
    return resolution;
  }, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Pin.read"></a>[function <span class="apidocSignatureSpan">johnny-five.Pin.</span>read (pin, callback)](#apidoc.element.johnny-five.Pin.read)
- description and source-code
```javascript
read = function (pin, callback) {
  // Set the correct mode (INPUT)
  // This will only set if it needs to be set, otherwise a no-op

  var isChanging = false;

  if (pin.type === "digital" && pin.mode !== 0) {
    isChanging = true;
    pin.mode = modes.INPUT;
  }

  if (pin.type === "analog" && pin.mode !== 2) {
    isChanging = true;
    pin.mode = modes.ANALOG;
  }

  if (isChanging) {
    read(pin);
  }

  pin.on("data", function() {
    callback.call(pin, null, pin.value);
  });
}
```
- example usage
```shell
...

EVS.prototype.read = function(port, register, numBytes, callback) {

  if (port.sensor && port.offset && !EVS.isRawSensor(port)) {
    register += port.offset;
  }

  this.bank[port.bank].read(register, numBytes, callback);
};

EVS.prototype.write = function(port, register, data) {
  this.bank[port.bank].write(register, data);
};

/*
...
```

#### <a name="apidoc.element.johnny-five.Pin.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Pin.</span>super_ ()](#apidoc.element.johnny-five.Pin.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Pin.write"></a>[function <span class="apidocSignatureSpan">johnny-five.Pin.</span>write (pin, val)](#apidoc.element.johnny-five.Pin.write)
- description and source-code
```javascript
write = function (pin, val) {
  var state = priv.get(pin);

  state.value = val;

  // Set the correct mode (OUTPUT)
  // This will only set if it needs to be set, otherwise a no-op
  pin.mode = modes.OUTPUT;

  // Create the correct type of write command
  pin.io[pin.type + "Write"](pin.addr, val);

  pin.emit("write", null, val);
}
```
- example usage
```shell
...
EVS.isRawSensor = function(port) {
return port.analog === EVS.S1_ANALOG || port.analog === EVS.S2_ANALOG;
};

util.inherits(EVS, Emitter);

EVS.prototype.setup = function(port, type) {
this.bank[port.bank].write(port.mode, [type]);
};

EVS.prototype.read = function(port, register, numBytes, callback) {

if (port.sensor && port.offset && !EVS.isRawSensor(port)) {
  register += port.offset;
}
...
```



# <a name="apidoc.module.johnny-five.Pin.prototype"></a>[module johnny-five.Pin.prototype](#apidoc.module.johnny-five.Pin.prototype)

#### <a name="apidoc.element.johnny-five.Pin.prototype.high"></a>[function <span class="apidocSignatureSpan">johnny-five.Pin.prototype.</span>high ()](#apidoc.element.johnny-five.Pin.prototype.high)
- description and source-code
```javascript
high = function () {
  var value = this.type === "analog" ? 255 : 1;
  Pin.write(this, value);
  this.emit("high");
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Pin.prototype.low"></a>[function <span class="apidocSignatureSpan">johnny-five.Pin.prototype.</span>low ()](#apidoc.element.johnny-five.Pin.prototype.low)
- description and source-code
```javascript
low = function () {
  Pin.write(this, 0);
  this.emit("low");
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Pin.prototype.query"></a>[function <span class="apidocSignatureSpan">johnny-five.Pin.prototype.</span>query (callback)](#apidoc.element.johnny-five.Pin.prototype.query)
- description and source-code
```javascript
query = function (callback) {
  var index = this.addr;

  if (this.type === "analog") {
    index = this.io.analogPins[this.addr];
  }

  function handler() {
    callback(this.io.pins[index]);
  }

  this.io.queryPinState(index, handler.bind(this));

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Pin.prototype.read"></a>[function <span class="apidocSignatureSpan">johnny-five.Pin.prototype.</span>read (valOrCallback)](#apidoc.element.johnny-five.Pin.prototype.read)
- description and source-code
```javascript
read = function (valOrCallback) {
  Pin[operation](this, valOrCallback);
  return this;
}
```
- example usage
```shell
...

EVS.prototype.read = function(port, register, numBytes, callback) {

  if (port.sensor && port.offset && !EVS.isRawSensor(port)) {
    register += port.offset;
  }

  this.bank[port.bank].read(register, numBytes, callback);
};

EVS.prototype.write = function(port, register, data) {
  this.bank[port.bank].write(register, data);
};

/*
...
```

#### <a name="apidoc.element.johnny-five.Pin.prototype.write"></a>[function <span class="apidocSignatureSpan">johnny-five.Pin.prototype.</span>write (valOrCallback)](#apidoc.element.johnny-five.Pin.prototype.write)
- description and source-code
```javascript
write = function (valOrCallback) {
  Pin[operation](this, valOrCallback);
  return this;
}
```
- example usage
```shell
...
EVS.isRawSensor = function(port) {
return port.analog === EVS.S1_ANALOG || port.analog === EVS.S2_ANALOG;
};

util.inherits(EVS, Emitter);

EVS.prototype.setup = function(port, type) {
this.bank[port.bank].write(port.mode, [type]);
};

EVS.prototype.read = function(port, register, numBytes, callback) {

if (port.sensor && port.offset && !EVS.isRawSensor(port)) {
  register += port.offset;
}
...
```



# <a name="apidoc.module.johnny-five.Ping"></a>[module johnny-five.Ping](#apidoc.module.johnny-five.Ping)

#### <a name="apidoc.element.johnny-five.Ping.Ping"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Ping (opts)](#apidoc.element.johnny-five.Ping.Ping)
- description and source-code
```javascript
function Ping(opts) {

  if (!(this instanceof Ping)) {
    return new Ping(opts);
  }

  var last = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  this.pin = opts && opts.pin || 7;
  this.freq = opts.freq || 20;
  // this.pulse = opts.pulse || 250;

  var state = {
    value: null
  };

  // Private settings object
  var settings = {
    pin: this.pin,
    value: this.io.HIGH,
    pulseOut: 5
  };

  this.io.setMaxListeners(100);

  // Interval for polling pulse duration as reported in microseconds
  setInterval(function() {
    this.io.pingRead(settings, function(microseconds) {
      state.value = microseconds;
    });
  }.bind(this), 225);

  // Interval for throttled event
  setInterval(function() {
    if (state.value === null) {
      return;
    }

    // The "read" event has been deprecated in
    // favor of a "data" event.
    this.emit("data", state.value);

    // If the state.value for this interval is not the same as the
    // state.value in the last interval, fire a "change" event.
    if (state.value !== last) {
      this.emit("change", state.value);
    }

    // Store state.value for comparison in next interval
    last = state.value;

    // Reset samples;
    // samples.length = 0;
  }.bind(this), this.freq);

  Object.defineProperties(this, {
    value: {
      get: function() {
        return state.value;
      }
    },
    // Based on the round trip travel time in microseconds,
    // Calculate the distance in inches and centimeters
    inches: {
      get: function() {
        return toFixed(state.value / 74 / 2, 2);
      }
    },
    in: {
      get: function() {
        return this.inches;
      }
    },
    cm: {
      get: function() {
        return toFixed(state.value / 29 / 2, 3);
      }
    }
  });

  priv.set(this, state);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Ping.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Ping.</span>super_ ()](#apidoc.element.johnny-five.Ping.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Ping.prototype"></a>[module johnny-five.Ping.prototype](#apidoc.module.johnny-five.Ping.prototype)

#### <a name="apidoc.element.johnny-five.Ping.prototype.within"></a>[function <span class="apidocSignatureSpan">johnny-five.Ping.prototype.</span>within (range, unit, callback)](#apidoc.element.johnny-five.Ping.prototype.within)
- description and source-code
```javascript
within = function (range, unit, callback) {
  var upper;

  if (typeof range === "number") {
    upper = range;
    range = [0, upper];
  }

  if (!Array.isArray(range)) {
    throw new Error("within expected a range array");
  }

  if (typeof unit === "function") {
    callback = unit;
    unit = "value";
  }

  if (typeof this[unit] === "undefined") {
    return this;
  }

  // Use the continuous read event for high resolution
  this.on("data", function() {
    var value = this[unit];
    if (value >= range[0] && value <= range[1]) {
      callback.call(this, null, value);
    }
  }.bind(this));

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Pins"></a>[module johnny-five.Pins](#apidoc.module.johnny-five.Pins)

#### <a name="apidoc.element.johnny-five.Pins.Pins"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Pins (numsOrObjects)](#apidoc.element.johnny-five.Pins.Pins)
- description and source-code
```javascript
function Pins(numsOrObjects) {
  if (!(this instanceof Pins)) {
    return new Pins(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Pin
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Pins.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Pins.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Pins.super_)
- description and source-code
```javascript
function Collection(numsOrObjects) {
  var Type = this.type;
  var initObjects = [];

  this.length = 0;

  if (Array.isArray(numsOrObjects)) {
    initObjects = numsOrObjects;
  } else {
    // Initialize with a Shared Properties object
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (Array.isArray(numsOrObjects.pins)) {
      var keys = Object.keys(numsOrObjects).filter(function(key) {
        return key !== "pins";
      });
      initObjects = numsOrObjects.pins.map(function(pin) {
        var obj = {};

        if (Array.isArray(pin)) {
          obj.pins = pin;
        } else {
          obj.pin = pin;
        }

        return keys.reduce(function(accum, key) {
          accum[key] = numsOrObjects[key];
          return accum;
        }, obj);
      });
    }
  }

  /* istanbul ignore else */
  if (initObjects.length) {
    while (initObjects.length) {
      var numOrObject = initObjects.shift();

      // When a Type exists, respect it!
      if (typeof Type === "function") {
        if (!(numOrObject instanceof Type || numOrObject instanceof this.constructor)) {
          numOrObject = new Type(numOrObject);
        }
      }

      this.add(numOrObject);
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Pins.prototype"></a>[module johnny-five.Pins.prototype](#apidoc.module.johnny-five.Pins.prototype)

#### <a name="apidoc.element.johnny-five.Pins.prototype.high"></a>[function <span class="apidocSignatureSpan">johnny-five.Pins.prototype.</span>high ()](#apidoc.element.johnny-five.Pins.prototype.high)
- description and source-code
```javascript
high = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Pins.prototype.low"></a>[function <span class="apidocSignatureSpan">johnny-five.Pins.prototype.</span>low ()](#apidoc.element.johnny-five.Pins.prototype.low)
- description and source-code
```javascript
low = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Pins.prototype.write"></a>[function <span class="apidocSignatureSpan">johnny-five.Pins.prototype.</span>write ()](#apidoc.element.johnny-five.Pins.prototype.write)
- description and source-code
```javascript
write = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
...
EVS.isRawSensor = function(port) {
return port.analog === EVS.S1_ANALOG || port.analog === EVS.S2_ANALOG;
};

util.inherits(EVS, Emitter);

EVS.prototype.setup = function(port, type) {
this.bank[port.bank].write(port.mode, [type]);
};

EVS.prototype.read = function(port, register, numBytes, callback) {

if (port.sensor && port.offset && !EVS.isRawSensor(port)) {
  register += port.offset;
}
...
```



# <a name="apidoc.module.johnny-five.Proximity"></a>[module johnny-five.Proximity](#apidoc.module.johnny-five.Proximity)

#### <a name="apidoc.element.johnny-five.Proximity.Proximity"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Proximity (opts)](#apidoc.element.johnny-five.Proximity.Proximity)
- description and source-code
```javascript
function Proximity(opts) {

  if (!(this instanceof Proximity)) {
    return new Proximity(opts);
  }

  var controller = null;
  var state = {};
  var raw = 0;
  var freq = opts.freq || 25;
  var last = 0;
  var pinValue = typeof opts === "object" ? opts.pin : opts;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (typeof opts.controller === "string") {
    controller = Controllers[opts.controller];
  } else {
    controller = opts.controller || Controllers["GP2Y0A21YK"];
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toCm) {
    this.toCm = opts.toCm || function(x) {
      return x;
    };
  }

  priv.set(this, state);

  Object.defineProperties(this, {
<span class="apidocCodeCommentSpan">    /**
     * [read-only] Calculated centimeter value
     * @property centimeters
     * @type Number
     */
</span>    centimeters: {
      get: function() {
        return this.toCm(raw);
      }
    },
    cm: {
      get: function() {
        return this.centimeters;
      }
    },
    /**
     * [read-only] Calculated inch value
     * @property inches
     * @type Number
     */
    inches: {
      get: function() {
        return toFixed(this.centimeters * 0.39, 2);
      }
    },
    in: {
      get: function() {
        return this.inches;
      }
    },
  });

  if (typeof this.initialize === "function") {
    opts.pinValue = pinValue;
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw === undefined) {
      return;
    }

    var data = {
      cm: this.cm,
      centimeters: this.centimeters,
      in: this.in,
      inches: this.inches
    };

    this.emit("data", data);

    if (raw !== last) {
      last = raw;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Proximity.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.Proximity.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Proximity.Collection)
- description and source-code
```javascript
Collection = function (numsOrObjects) {
  if (!(this instanceof Proximity.Collection)) {
    return new Proximity.Collection(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Proximity
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Proximity.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Proximity.</span>super_ ()](#apidoc.element.johnny-five.Proximity.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Proximity.Collection"></a>[module johnny-five.Proximity.Collection](#apidoc.module.johnny-five.Proximity.Collection)

#### <a name="apidoc.element.johnny-five.Proximity.Collection.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.Proximity.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Proximity.Collection.Collection)
- description and source-code
```javascript
Collection = function (numsOrObjects) {
  if (!(this instanceof Proximity.Collection)) {
    return new Proximity.Collection(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Proximity
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Proximity.Collection.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Proximity.Collection.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Proximity.Collection.super_)
- description and source-code
```javascript
super_ = function (numsOrObjects) {

  // Create private state ahead of super call
  priv.set(this, {
    timing: {
      last: Date.now()
    }
  });

  Collection.call(this, numsOrObjects);

  // If the Collection.Emitter was created
  // with a Shared Properties object, then
  // we should abide by the freq or period
  // properties...
  var interval = null;
  var period = 5;

  if (!Array.isArray(numsOrObjects) &&
      (typeof numsOrObjects === "object" && numsOrObjects !== null))  {

    period = numsOrObjects.freq || numsOrObjects.period || period;

    // _However_, looking to the future, we
    // need to start thinking about replacing
    // the garbage named _freq_ (the value is
    // actually a period), with real _frequency_
    // in Hz.

    // If provided, convert frequency to period
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (numsOrObjects.frequency) {
      period = (1 / numsOrObjects.frequency) * 1000;
    }
  }

  Object.defineProperties(this, {
    period: {
      get: function() {
        return period;
      },
      set: function(value) {
        if (period !== value) {
          period = value;
        }

        if (interval) {
          clearInterval(interval);
        }

        interval = setInterval(function() {
          this.emit("data", this);
        }.bind(this), period);
      }
    },
  });

  this.period = period;

  this.on("newListener", function(event) {
    if (event === "change" || event === "data") {
      return;
    }

    this.forEach(function(input) {
      input.on(event, function(data) {
        this.emit(event, input, data);
      }.bind(this));
    }, this);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Proximity.Collection.prototype"></a>[module johnny-five.Proximity.Collection.prototype](#apidoc.module.johnny-five.Proximity.Collection.prototype)

#### <a name="apidoc.element.johnny-five.Proximity.Collection.prototype.within"></a>[function <span class="apidocSignatureSpan">johnny-five.Proximity.Collection.prototype.</span>within ()](#apidoc.element.johnny-five.Proximity.Collection.prototype.within)
- description and source-code
```javascript
within = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Proximity.prototype"></a>[module johnny-five.Proximity.prototype](#apidoc.module.johnny-five.Proximity.prototype)

#### <a name="apidoc.element.johnny-five.Proximity.prototype.within"></a>[function <span class="apidocSignatureSpan">johnny-five.Proximity.prototype.</span>within (range, unit, callback)](#apidoc.element.johnny-five.Proximity.prototype.within)
- description and source-code
```javascript
within = function (range, unit, callback) {
  var upper;

  if (typeof range === "number") {
    upper = range;
    range = [0, upper];
  }

  if (!Array.isArray(range)) {
    throw new Error("within expected a range array");
  }

  if (typeof unit === "function") {
    callback = unit;
    unit = "value";
  }

  if (typeof this[unit] === "undefined") {
    return this;
  }

  // Use the continuous read event for high resolution
  this.on("data", function() {
    var value = this[unit];
    if (value >= range[0] && value <= range[1]) {
      callback.call(this, null, value);
    }
  }.bind(this));

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Relay"></a>[module johnny-five.Relay](#apidoc.module.johnny-five.Relay)

#### <a name="apidoc.element.johnny-five.Relay.Relay"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Relay (opts)](#apidoc.element.johnny-five.Relay.Relay)
- description and source-code
```javascript
function Relay(opts) {

  var state;

  if (!(this instanceof Relay)) {
    return new Relay(opts);
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  opts.type = opts.type || "NO";

  state = {
    isInverted: opts.type === "NC",
    isOn: false,
    value: null,
  };

  priv.set(this, state);

  Object.defineProperties(this, {
    value: {
      get: function() {
        return Number(this.isOn);
      }
    },
    type: {
      get: function() {
        return state.isInverted ? "NC" : "NO";
      }
    },
    isOn: {
      get: function() {
        return state.isOn;
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Relay.Array"></a>[function <span class="apidocSignatureSpan">johnny-five.Relay.</span>Array (numsOrObjects)](#apidoc.element.johnny-five.Relay.Array)
- description and source-code
```javascript
function Relays(numsOrObjects) {
  if (!(this instanceof Relays)) {
    return new Relays(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Relay
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Relay.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.Relay.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Relay.Collection)
- description and source-code
```javascript
function Relays(numsOrObjects) {
  if (!(this instanceof Relays)) {
    return new Relays(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Relay
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Relay.prototype"></a>[module johnny-five.Relay.prototype](#apidoc.module.johnny-five.Relay.prototype)

#### <a name="apidoc.element.johnny-five.Relay.prototype.close"></a>[function <span class="apidocSignatureSpan">johnny-five.Relay.prototype.</span>close ()](#apidoc.element.johnny-five.Relay.prototype.close)
- description and source-code
```javascript
close = function () {
  var state = priv.get(this);

  this.io.digitalWrite(
    this.pin, state.isInverted ? this.io.LOW : this.io.HIGH
  );
  state.isOn = true;

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Relay.prototype.off"></a>[function <span class="apidocSignatureSpan">johnny-five.Relay.prototype.</span>off ()](#apidoc.element.johnny-five.Relay.prototype.off)
- description and source-code
```javascript
off = function () {
  var state = priv.get(this);

  this.io.digitalWrite(
    this.pin, state.isInverted ? this.io.HIGH : this.io.LOW
  );
  state.isOn = false;

  return this;
}
```
- example usage
```shell
...

  return this;
};

ReflectanceArray.prototype.disable = function() {
  var state = priv.get(this);

  state.emitter.off();

  return this;
};

// Calibrate will store the min/max values for this sensor array
// It should be called many times in order to get a lot of readings
// on light and dark areas.  See calibrateUntil for a convenience
...
```

#### <a name="apidoc.element.johnny-five.Relay.prototype.on"></a>[function <span class="apidocSignatureSpan">johnny-five.Relay.prototype.</span>on ()](#apidoc.element.johnny-five.Relay.prototype.on)
- description and source-code
```javascript
on = function () {
  var state = priv.get(this);

  this.io.digitalWrite(
    this.pin, state.isInverted ? this.io.LOW : this.io.HIGH
  );
  state.isOn = true;

  return this;
}
```
- example usage
```shell
...

The ubiquitous "Hello World" program of the microcontroller and SoC world is "blink an LED". The following code demonstrates how
 this is done using the Johnny-Five framework.

'''javascript
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''
...
```

#### <a name="apidoc.element.johnny-five.Relay.prototype.open"></a>[function <span class="apidocSignatureSpan">johnny-five.Relay.prototype.</span>open ()](#apidoc.element.johnny-five.Relay.prototype.open)
- description and source-code
```javascript
open = function () {
  var state = priv.get(this);

  this.io.digitalWrite(
    this.pin, state.isInverted ? this.io.HIGH : this.io.LOW
  );
  state.isOn = false;

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Relay.prototype.toggle"></a>[function <span class="apidocSignatureSpan">johnny-five.Relay.prototype.</span>toggle ()](#apidoc.element.johnny-five.Relay.prototype.toggle)
- description and source-code
```javascript
toggle = function () {
  var state = priv.get(this);

  if (state.isOn) {
    this.off();
  } else {
    this.on();
  }

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Relays"></a>[module johnny-five.Relays](#apidoc.module.johnny-five.Relays)

#### <a name="apidoc.element.johnny-five.Relays.Relays"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Relays (numsOrObjects)](#apidoc.element.johnny-five.Relays.Relays)
- description and source-code
```javascript
function Relays(numsOrObjects) {
  if (!(this instanceof Relays)) {
    return new Relays(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Relay
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Relays.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Relays.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Relays.super_)
- description and source-code
```javascript
function Collection(numsOrObjects) {
  var Type = this.type;
  var initObjects = [];

  this.length = 0;

  if (Array.isArray(numsOrObjects)) {
    initObjects = numsOrObjects;
  } else {
    // Initialize with a Shared Properties object
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (Array.isArray(numsOrObjects.pins)) {
      var keys = Object.keys(numsOrObjects).filter(function(key) {
        return key !== "pins";
      });
      initObjects = numsOrObjects.pins.map(function(pin) {
        var obj = {};

        if (Array.isArray(pin)) {
          obj.pins = pin;
        } else {
          obj.pin = pin;
        }

        return keys.reduce(function(accum, key) {
          accum[key] = numsOrObjects[key];
          return accum;
        }, obj);
      });
    }
  }

  /* istanbul ignore else */
  if (initObjects.length) {
    while (initObjects.length) {
      var numOrObject = initObjects.shift();

      // When a Type exists, respect it!
      if (typeof Type === "function") {
        if (!(numOrObject instanceof Type || numOrObject instanceof this.constructor)) {
          numOrObject = new Type(numOrObject);
        }
      }

      this.add(numOrObject);
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Relays.prototype"></a>[module johnny-five.Relays.prototype](#apidoc.module.johnny-five.Relays.prototype)

#### <a name="apidoc.element.johnny-five.Relays.prototype.close"></a>[function <span class="apidocSignatureSpan">johnny-five.Relays.prototype.</span>close ()](#apidoc.element.johnny-five.Relays.prototype.close)
- description and source-code
```javascript
close = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Relays.prototype.off"></a>[function <span class="apidocSignatureSpan">johnny-five.Relays.prototype.</span>off ()](#apidoc.element.johnny-five.Relays.prototype.off)
- description and source-code
```javascript
off = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
...

  return this;
};

ReflectanceArray.prototype.disable = function() {
  var state = priv.get(this);

  state.emitter.off();

  return this;
};

// Calibrate will store the min/max values for this sensor array
// It should be called many times in order to get a lot of readings
// on light and dark areas.  See calibrateUntil for a convenience
...
```

#### <a name="apidoc.element.johnny-five.Relays.prototype.on"></a>[function <span class="apidocSignatureSpan">johnny-five.Relays.prototype.</span>on ()](#apidoc.element.johnny-five.Relays.prototype.on)
- description and source-code
```javascript
on = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
...

The ubiquitous "Hello World" program of the microcontroller and SoC world is "blink an LED". The following code demonstrates how
 this is done using the Johnny-Five framework.

'''javascript
var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  // Create an Led on pin 13
  var led = new five.Led(13);
  // Blink every half second
  led.blink(500);
});
'''
...
```

#### <a name="apidoc.element.johnny-five.Relays.prototype.open"></a>[function <span class="apidocSignatureSpan">johnny-five.Relays.prototype.</span>open ()](#apidoc.element.johnny-five.Relays.prototype.open)
- description and source-code
```javascript
open = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Relays.prototype.toggle"></a>[function <span class="apidocSignatureSpan">johnny-five.Relays.prototype.</span>toggle ()](#apidoc.element.johnny-five.Relays.prototype.toggle)
- description and source-code
```javascript
toggle = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Repl"></a>[module johnny-five.Repl](#apidoc.module.johnny-five.Repl)

#### <a name="apidoc.element.johnny-five.Repl.Repl"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Repl (opts)](#apidoc.element.johnny-five.Repl.Repl)
- description and source-code
```javascript
function Repl(opts) {
  if (!Repl.isActive) {
    Repl.isActive = true;

    if (!(this instanceof Repl)) {
      return new Repl(opts);
    }

    // Store context values in instance property
    // this will be used for managing scope when
    // injecting new values into an existing Repl
    // session.
    this.context = {};
    this.ready = false;

    var state = {
      opts: opts,
      board: opts.board,
    };

    priv.set(this, state);

    // Store an accessible copy of the Repl instance
    // on a static property. This is later used by the
    // Board constructor to automattically setup Repl
    // sessions for all programs, which reduces the
    // boilerplate requirement.
    Repl.ref = this;
  } else {
    return Repl.ref;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Repl.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Repl.</span>super_ ()](#apidoc.element.johnny-five.Repl.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Repl.prototype"></a>[module johnny-five.Repl.prototype](#apidoc.module.johnny-five.Repl.prototype)

#### <a name="apidoc.element.johnny-five.Repl.prototype.close"></a>[function <span class="apidocSignatureSpan">johnny-five.Repl.prototype.</span>close ()](#apidoc.element.johnny-five.Repl.prototype.close)
- description and source-code
```javascript
close = function () {
  this.cmd.emit("exit");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Repl.prototype.initialize"></a>[function <span class="apidocSignatureSpan">johnny-five.Repl.prototype.</span>initialize (callback)](#apidoc.element.johnny-five.Repl.prototype.initialize)
- description and source-code
```javascript
initialize = function (callback) {
  var state = priv.get(this);

  process.stdin.resume();
  process.stdin.setEncoding("utf8");

  var replDefaults = {
    prompt: ">> ",
    useGlobal: false
  };

  // Call this immediately before repl.start to
  // avoid crash on Intel Edison
  state.board.info("Repl", "Initialized");

  // Initialize the REPL session with the default
  // repl settings.
  // Assign the returned repl instance to "cmd"
  var cmd = repl.start(replDefaults);

  this.ready = true;

  // Assign a reference to the REPL's "content" object
  // This will be use later by the Repl.prototype.inject
  // method for allowing user programs to inject their
  // own explicit values and reference
  this.cmd = cmd;
  this.context = cmd.context;

  cmd.on("exit", function() {
    state.board.emit("exit");
    state.board.warn("Board", "Closing.");

    var interval = setInterval(function() {
<span class="apidocCodeCommentSpan">      /* istanbul ignore else */
</span>      if (!state.board.io.pending) {
        clearInterval(interval);
        process.nextTick(process.reallyExit);
      }
    }, 1);
  });

  this.inject(state.opts);

  /* istanbul ignore else */
  if (callback) {
    process.nextTick(callback);
  }
}
```
- example usage
```shell
...
    return raw;
  };
}

priv.set(this, state);

if (typeof this.initialize === "function") {
  this.initialize(opts, function(data) {
    raw = data;
  });
}

setInterval(function() {
  if (raw === null) {
    return;
...
```

#### <a name="apidoc.element.johnny-five.Repl.prototype.inject"></a>[function <span class="apidocSignatureSpan">johnny-five.Repl.prototype.</span>inject (obj)](#apidoc.element.johnny-five.Repl.prototype.inject)
- description and source-code
```javascript
inject = function (obj) {
  Object.keys(obj).forEach(function(key) {
    Object.defineProperty(
      this.context, key, Object.getOwnPropertyDescriptor(obj, key)
    );
  }, this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Sensor"></a>[module johnny-five.Sensor](#apidoc.module.johnny-five.Sensor)

#### <a name="apidoc.element.johnny-five.Sensor.Sensor"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Sensor (opts)](#apidoc.element.johnny-five.Sensor.Sensor)
- description and source-code
```javascript
function Sensor(opts) {

  if (!(this instanceof Sensor)) {
    return new Sensor(opts);
  }

  // Defaults to 10-bit resolution
  var resolution = 0x3FF;
  var raw = null;
  var last = -1;
  var samples = [];

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (!opts.type) {
    opts.type = "analog";
  }

  if (this.io.RESOLUTION &&
      (this.io.RESOLUTION.ADC &&
        (this.io.RESOLUTION.ADC !== resolution))) {
    resolution = this.io.RESOLUTION.ADC;
  }

  // Set the pin to ANALOG (INPUT) mode
  this.mode = opts.type === "digital" ?
    this.io.MODES.INPUT :
    this.io.MODES.ANALOG;

  this.io.pinMode(this.pin, this.mode);

  // Create a "state" entry for privately
  // storing the state of the sensor
  var state = {
    enabled: typeof opts.enabled === "undefined" ? true : opts.enabled,
    booleanBarrier: opts.type === "digital" ? 0 : null,
    intervalId: null,
    scale: null,
    value: 0,
    median: 0,
    freq: opts.freq || 25,
    previousFreq: opts.freq || 25,
  };
  // Put a reference where the prototype methods defined in this file have access
  priv.set(this, state);

  // Sensor instance properties
  this.range = opts.range || [0, resolution];
  this.limit = opts.limit || null;
  this.threshold = opts.threshold === undefined ? 1 : opts.threshold;
  this.isScaled = false;

  this.io[opts.type + "Read"](this.pin, function(data) {
    raw = data;

    // Only append to the samples when noise filtering can/will be used
    if (opts.type !== "digital") {
      samples.push(raw);
    }
  }.bind(this));

  // Throttle
  // TODO: The event (interval) processing function should be outside of the Sensor
  // constructor function (with appropriate passed (and bound?) arguments), to
  // avoid creating a separate copy (of the function) for each Sensor instance.
  var eventProcessing = function() {
    var err, boundary;

    err = null;

    // For digital sensors, skip the analog
    // noise filtering provided below.
    if (opts.type === "digital") {
      this.emit("data", raw);

<span class="apidocCodeCommentSpan">      /* istanbul ignore else */
</span>      if (last !== raw) {
        this.emit("change", raw);
        last = raw;
      }
      return;
    }

    // Keep the previous calculated value if there were no new readings
    if (samples.length > 0) {
      // Filter the accumulated sample values to reduce analog reading noise
      state.median = median(samples);
    }

    this.emit("data", state.median);

    // If the filtered (state.median) value for this interval is at least ± the
    // configured threshold from last, fire change events
    if (state.median <= (last - this.threshold) || state.median >= (last + this.threshold)) {
      this.emit("change", state.median);
      // Update the instance-local 'last' value (only) when a new change event
      // has been emitted.  For comparison in the next interval
      last = state.median;
    }

    if (this.limit) {
      if (state.median <= this.limit[0]) {
        boundary = "lower";
      }
      if (state.median >= this.limit[1]) {
        boundary = "upper";
      }

      if (boundary) {
        this.emit("limit", {
          boundary: boundary,
          value: state.median
        });
        this.emit("limit:" + boundary, state.median);
      }
    }

    // Reset samples
    samples.length = 0;
  }.bind(this); // ./function eventProcessing()


  Object.defineProperties(this, {
    raw: {
      get: function() {
        return raw;
      }
    },
    analog: {
      get: function() {
        if (opts.type === "digital") {
          return raw;
        }

        return raw === null ? 0 :
          Fn.map(this.raw, 0, resolution, 0, 255) | 0;
      },
    },
    constrained: {
      get: function() {
        if (opts.type === "digital") {
          return raw;
        }

        return raw === null ? 0 :
          Fn.constrain(this.raw, 0, 255);
      }
    },
    boolean: {
      get: function() {
        var state = priv.get(this);
        var booleanBarrier = state.booleanBarrier;
        var scale = state.scale || [0, resolution];

        if (boolean ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensor.Analog"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensor.</span>Analog (opts)](#apidoc.element.johnny-five.Sensor.Analog)
- description and source-code
```javascript
Analog = function (opts) {
  return new module.exports.Sensor(opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensor.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensor.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Sensor.Collection)
- description and source-code
```javascript
function Sensors(numsOrObjects) {
  if (!(this instanceof Sensors)) {
    return new Sensors(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Sensor
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensor.Digital"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensor.</span>Digital (opts)](#apidoc.element.johnny-five.Sensor.Digital)
- description and source-code
```javascript
Digital = function (opts) {
  var pin;

  if (typeof opts === "number" || typeof opts === "string") {
    pin = opts;
    opts = {
      type: "digital",
      pin: pin
    };
  } else {
    opts.type = opts.type || "digital";
  }

  return new module.exports.Sensor(opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensor.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensor.</span>super_ ()](#apidoc.element.johnny-five.Sensor.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Sensor.prototype"></a>[module johnny-five.Sensor.prototype](#apidoc.module.johnny-five.Sensor.prototype)

#### <a name="apidoc.element.johnny-five.Sensor.prototype.booleanAt"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensor.prototype.</span>booleanAt (barrier)](#apidoc.element.johnny-five.Sensor.prototype.booleanAt)
- description and source-code
```javascript
booleanAt = function (barrier) {
  priv.get(this).booleanBarrier = barrier;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensor.prototype.disable"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensor.prototype.</span>disable ()](#apidoc.element.johnny-five.Sensor.prototype.disable)
- description and source-code
```javascript
disable = function () {
  var state = priv.get(this);

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (state.enabled) {
    state.enabled = false;
    state.previousFreq = state.freq;
    this.freq = null;
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensor.prototype.enable"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensor.prototype.</span>enable ()](#apidoc.element.johnny-five.Sensor.prototype.enable)
- description and source-code
```javascript
enable = function () {
  var state = priv.get(this);

<span class="apidocCodeCommentSpan">  /* istanbul ignore else */
</span>  if (!state.enabled) {
    this.freq = state.freq || state.previousFreq;
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensor.prototype.fscaleTo"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensor.prototype.</span>fscaleTo (low, high)](#apidoc.element.johnny-five.Sensor.prototype.fscaleTo)
- description and source-code
```javascript
fscaleTo = function (low, high) {
  var scale = Array.isArray(low) ? low : [low, high];
  return Fn.fmap(this.raw, 0, this.resolution, scale[0], scale[1]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensor.prototype.scale"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensor.prototype.</span>scale (low, high)](#apidoc.element.johnny-five.Sensor.prototype.scale)
- description and source-code
```javascript
scale = function (low, high) {
  this.isScaled = true;

  priv.get(this).scale = Array.isArray(low) ?
    low : [low, high];

  return this;
}
```
- example usage
```shell
...


function calibratedValues() {
  return this.raw.map(function(value, i) {
    var max = this.calibration.max[i],
      min = this.calibration.min[i];

    var scaled = __.scale(value, min, max, CALIBRATED_MIN_VALUE, CALIBRATED_MAX_VALUE);
    return __.constrain(scaled, CALIBRATED_MIN_VALUE, CALIBRATED_MAX_VALUE);
  }, this);
}

function maxLineValue() {
  return (this.sensors.length - 1) * CALIBRATED_MAX_VALUE;
}
...
```

#### <a name="apidoc.element.johnny-five.Sensor.prototype.scaleTo"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensor.prototype.</span>scaleTo (low, high)](#apidoc.element.johnny-five.Sensor.prototype.scaleTo)
- description and source-code
```javascript
scaleTo = function (low, high) {
  var scale = Array.isArray(low) ? low : [low, high];
  return Fn.map(this.raw, 0, this.resolution, scale[0], scale[1]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensor.prototype.within"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensor.prototype.</span>within (range, unit, callback)](#apidoc.element.johnny-five.Sensor.prototype.within)
- description and source-code
```javascript
within = function (range, unit, callback) {
  var upper;

  if (typeof range === "number") {
    upper = range;
    range = [0, upper];
  }

  if (!Array.isArray(range)) {
    throw new Error("within expected a range array");
  }

  if (typeof unit === "function") {
    callback = unit;
    unit = "value";
  }

  if (typeof this[unit] === "undefined") {
    return this;
  }

  // Use the continuous read event for high resolution
  this.on("data", function() {
    var value = this[unit];
    if (value >= range[0] && value <= range[1]) {
      callback.call(this, null, value);
    }
  }.bind(this));

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Sensors"></a>[module johnny-five.Sensors](#apidoc.module.johnny-five.Sensors)

#### <a name="apidoc.element.johnny-five.Sensors.Sensors"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Sensors (numsOrObjects)](#apidoc.element.johnny-five.Sensors.Sensors)
- description and source-code
```javascript
function Sensors(numsOrObjects) {
  if (!(this instanceof Sensors)) {
    return new Sensors(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Sensor
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensors.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensors.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Sensors.super_)
- description and source-code
```javascript
super_ = function (numsOrObjects) {

  // Create private state ahead of super call
  priv.set(this, {
    timing: {
      last: Date.now()
    }
  });

  Collection.call(this, numsOrObjects);

  // If the Collection.Emitter was created
  // with a Shared Properties object, then
  // we should abide by the freq or period
  // properties...
  var interval = null;
  var period = 5;

  if (!Array.isArray(numsOrObjects) &&
      (typeof numsOrObjects === "object" && numsOrObjects !== null))  {

    period = numsOrObjects.freq || numsOrObjects.period || period;

    // _However_, looking to the future, we
    // need to start thinking about replacing
    // the garbage named _freq_ (the value is
    // actually a period), with real _frequency_
    // in Hz.

    // If provided, convert frequency to period
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (numsOrObjects.frequency) {
      period = (1 / numsOrObjects.frequency) * 1000;
    }
  }

  Object.defineProperties(this, {
    period: {
      get: function() {
        return period;
      },
      set: function(value) {
        if (period !== value) {
          period = value;
        }

        if (interval) {
          clearInterval(interval);
        }

        interval = setInterval(function() {
          this.emit("data", this);
        }.bind(this), period);
      }
    },
  });

  this.period = period;

  this.on("newListener", function(event) {
    if (event === "change" || event === "data") {
      return;
    }

    this.forEach(function(input) {
      input.on(event, function(data) {
        this.emit(event, input, data);
      }.bind(this));
    }, this);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Sensors.prototype"></a>[module johnny-five.Sensors.prototype](#apidoc.module.johnny-five.Sensors.prototype)

#### <a name="apidoc.element.johnny-five.Sensors.prototype.booleanAt"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensors.prototype.</span>booleanAt ()](#apidoc.element.johnny-five.Sensors.prototype.booleanAt)
- description and source-code
```javascript
booleanAt = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensors.prototype.disable"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensors.prototype.</span>disable ()](#apidoc.element.johnny-five.Sensors.prototype.disable)
- description and source-code
```javascript
disable = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensors.prototype.enable"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensors.prototype.</span>enable ()](#apidoc.element.johnny-five.Sensors.prototype.enable)
- description and source-code
```javascript
enable = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensors.prototype.fscaleTo"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensors.prototype.</span>fscaleTo ()](#apidoc.element.johnny-five.Sensors.prototype.fscaleTo)
- description and source-code
```javascript
fscaleTo = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensors.prototype.scale"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensors.prototype.</span>scale ()](#apidoc.element.johnny-five.Sensors.prototype.scale)
- description and source-code
```javascript
scale = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
...


function calibratedValues() {
  return this.raw.map(function(value, i) {
    var max = this.calibration.max[i],
      min = this.calibration.min[i];

    var scaled = __.scale(value, min, max, CALIBRATED_MIN_VALUE, CALIBRATED_MAX_VALUE);
    return __.constrain(scaled, CALIBRATED_MIN_VALUE, CALIBRATED_MAX_VALUE);
  }, this);
}

function maxLineValue() {
  return (this.sensors.length - 1) * CALIBRATED_MAX_VALUE;
}
...
```

#### <a name="apidoc.element.johnny-five.Sensors.prototype.scaleTo"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensors.prototype.</span>scaleTo ()](#apidoc.element.johnny-five.Sensors.prototype.scaleTo)
- description and source-code
```javascript
scaleTo = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sensors.prototype.within"></a>[function <span class="apidocSignatureSpan">johnny-five.Sensors.prototype.</span>within ()](#apidoc.element.johnny-five.Sensors.prototype.within)
- description and source-code
```javascript
within = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Servo"></a>[module johnny-five.Servo](#apidoc.module.johnny-five.Servo)

#### <a name="apidoc.element.johnny-five.Servo.Servo"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Servo (opts)](#apidoc.element.johnny-five.Servo.Servo)
- description and source-code
```javascript
function Servo(opts) {

  if (!(this instanceof Servo)) {
    return new Servo(opts);
  }

  var history = [];
  var pinValue = typeof opts === "object" ? opts.pin : opts;
  var controller = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  this.range = opts.range || [0, 180];
  this.deadband = opts.deadband || [90, 90];
  this.fps = opts.fps || 100;
  this.offset = opts.offset || 0;
  this.mode = this.io.MODES.SERVO;
  this.interval = null;
  this.value = null;

  // StandardFirmata on Arduino allows controlling
  // servos from analog pins.
  // If we're currently operating with an Arduino
  // and the user has provided an analog pin name
  // (eg. "A0", "A5" etc.), parse out the numeric
  // value and capture the fully qualified analog
  // pin number.
  if (typeof opts.controller === "undefined" && Pins.isFirmata(this)) {
    if (typeof pinValue === "string" && pinValue[0] === "A") {
      pinValue = this.io.analogPins[+pinValue.slice(1)];
    }

    pinValue = +pinValue;

    // If the board's default pin normalization
    // came up with something different, use the
    // the local value.
    if (!Number.isNaN(pinValue) && this.pin !== pinValue) {
      this.pin = pinValue;
    }
  }


  // The type of servo determines certain alternate
  // behaviours in the API
  this.type = opts.type || "standard";

  // Invert the value of all servoWrite operations
  // eg. 80 => 100, 90 => 90, 0 => 180
  if (opts.isInverted) {
    console.warn("The 'isInverted' property has been renamed 'invert'");
  }
  this.invert = opts.isInverted || opts.invert || false;

  // Allow "setup"instructions to come from
  // constructor options properties
  this.startAt = 90;

  // Collect all movement history for this servo
  // history = [
  //   {
  //     timestamp: Date.now(),
  //     degrees: degrees
  //   }
  // ];

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.Standard;
  }

  priv.set(this, {
    history: history
  });

  Board.Controller.call(this, controller, opts);

  Object.defineProperties(this, {
    history: {
      get: function() {
        return history.slice(-5);
      }
    },
    last: {
      get: function() {
        return history[history.length - 1];
      }
    },
    position: {
      get: function() {
        return history.length ? history[history.length - 1].degrees : -1;
      }
    }
  });

  this.initialize(opts);

  // If "startAt" is defined and center is falsy
  // set servo to min or max degrees
  if (opts.startAt !== undefined) {
    this.startAt = opts.startAt;
    this.to(opts.startAt);
  }

  // If "center" true set servo to 90deg
  if (opts.center) {
    this.center();
  }

  if (opts.type === "continuous") {
    this.stop();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.Array"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.</span>Array (numsOrObjects)](#apidoc.element.johnny-five.Servo.Array)
- description and source-code
```javascript
function Servos(numsOrObjects) {
  if (!(this instanceof Servos)) {
    return new Servos(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Servo
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Servo.Collection)
- description and source-code
```javascript
function Servos(numsOrObjects) {
  if (!(this instanceof Servos)) {
    return new Servos(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Servo
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.Continuous"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.</span>Continuous (pinOrOpts)](#apidoc.element.johnny-five.Servo.Continuous)
- description and source-code
```javascript
Continuous = function (pinOrOpts) {
  var opts = {};

  if (typeof pinOrOpts === "object") {
    Object.assign(opts, pinOrOpts);
  } else {
    opts.pin = pinOrOpts;
  }

  opts.type = "continuous";
  return new Servo(opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.</span>super_ ()](#apidoc.element.johnny-five.Servo.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Servo.prototype"></a>[module johnny-five.Servo.prototype](#apidoc.module.johnny-five.Servo.prototype)

#### <a name="apidoc.element.johnny-five.Servo.prototype.ccw"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>ccw (rate)](#apidoc.element.johnny-five.Servo.prototype.ccw)
- description and source-code
```javascript
ccw = function (rate) {
  var range;
  rate = rate === undefined ? 1 : rate;
<span class="apidocCodeCommentSpan">  /* istanbul ignore if */
</span>  if (this.type !== "continuous") {
    this.board.error(
      "Servo",
      "Servo.prototype." + api + " is only available for continuous servos"
    );
  }
  if (api === "cw" || api === "clockWise") {
    range = [rate, 0, 1, this.deadband[1] + 1, this.range[1]];
  } else {
    range = [rate, 0, 1, this.deadband[0] - 1, this.range[0]];
  }
  return this.to(Fn.scale.apply(null, range) | 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.prototype.center"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>center (time, rate)](#apidoc.element.johnny-five.Servo.prototype.center)
- description and source-code
```javascript
center = function (time, rate) {
  return this.to(Math.abs((this.range[0] + this.range[1]) / 2), time, rate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.prototype.clockWise"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>clockWise (rate)](#apidoc.element.johnny-five.Servo.prototype.clockWise)
- description and source-code
```javascript
clockWise = function (rate) {
  var range;
  rate = rate === undefined ? 1 : rate;
<span class="apidocCodeCommentSpan">  /* istanbul ignore if */
</span>  if (this.type !== "continuous") {
    this.board.error(
      "Servo",
      "Servo.prototype." + api + " is only available for continuous servos"
    );
  }
  if (api === "cw" || api === "clockWise") {
    range = [rate, 0, 1, this.deadband[1] + 1, this.range[1]];
  } else {
    range = [rate, 0, 1, this.deadband[0] - 1, this.range[0]];
  }
  return this.to(Fn.scale.apply(null, range) | 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.prototype.counterClockwise"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>counterClockwise (rate)](#apidoc.element.johnny-five.Servo.prototype.counterClockwise)
- description and source-code
```javascript
counterClockwise = function (rate) {
  var range;
  rate = rate === undefined ? 1 : rate;
<span class="apidocCodeCommentSpan">  /* istanbul ignore if */
</span>  if (this.type !== "continuous") {
    this.board.error(
      "Servo",
      "Servo.prototype." + api + " is only available for continuous servos"
    );
  }
  if (api === "cw" || api === "clockWise") {
    range = [rate, 0, 1, this.deadband[1] + 1, this.range[1]];
  } else {
    range = [rate, 0, 1, this.deadband[0] - 1, this.range[0]];
  }
  return this.to(Fn.scale.apply(null, range) | 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.prototype.cw"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>cw (rate)](#apidoc.element.johnny-five.Servo.prototype.cw)
- description and source-code
```javascript
cw = function (rate) {
  var range;
  rate = rate === undefined ? 1 : rate;
<span class="apidocCodeCommentSpan">  /* istanbul ignore if */
</span>  if (this.type !== "continuous") {
    this.board.error(
      "Servo",
      "Servo.prototype." + api + " is only available for continuous servos"
    );
  }
  if (api === "cw" || api === "clockWise") {
    range = [rate, 0, 1, this.deadband[1] + 1, this.range[1]];
  } else {
    range = [rate, 0, 1, this.deadband[0] - 1, this.range[0]];
  }
  return this.to(Fn.scale.apply(null, range) | 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.prototype.home"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>home ()](#apidoc.element.johnny-five.Servo.prototype.home)
- description and source-code
```javascript
home = function () {
  return this.to(this.startAt);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.prototype.max"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>max (time, rate)](#apidoc.element.johnny-five.Servo.prototype.max)
- description and source-code
```javascript
max = function (time, rate) {
  return this.to(this.range[1], time, rate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.prototype.min"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>min (time, rate)](#apidoc.element.johnny-five.Servo.prototype.min)
- description and source-code
```javascript
min = function (time, rate) {
  return this.to(this.range[0], time, rate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.prototype.move"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>move (degrees, time)](#apidoc.element.johnny-five.Servo.prototype.move)
- description and source-code
```javascript
move = function (degrees, time) {
  console.warn("Servo.prototype.move has been renamed to Servo.prototype.to");

  return this.to(degrees, time);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.prototype.step"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>step (degrees, time)](#apidoc.element.johnny-five.Servo.prototype.step)
- description and source-code
```javascript
step = function (degrees, time) {
  return this.to(this.last.target + degrees, time);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.prototype.stop"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>stop ()](#apidoc.element.johnny-five.Servo.prototype.stop)
- description and source-code
```javascript
stop = function () {
  var state = priv.get(this);

  if (state.animation) {
    state.animation.stop();
  }

  if (this.type === "continuous") {
    this.to(
      this.deadband.reduce(function(a, b) {
        return Math.round((a + b) / 2);
      })
    );
  } else {
    clearInterval(this.interval);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.prototype.sweep"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>sweep (opts)](#apidoc.element.johnny-five.Servo.prototype.sweep)
- description and source-code
```javascript
sweep = function (opts) {

  var options = {
    keyFrames: [{
      value: this.range[0]
    }, {
      value: this.range[1]
    }],
    metronomic: true,
    loop: true,
    easing: "inOutSine"
  };

  // If opts is an array, then assume a range was passed
  if (Array.isArray(opts)) {
    options.keyFrames = rangeToKeyFrames(opts);
  } else {
    if (typeof opts === "object" && opts !== null) {
      Object.assign(options, opts);
<span class="apidocCodeCommentSpan">      /* istanbul ignore else */
</span>      if (Array.isArray(options.range)) {
        options.keyFrames = rangeToKeyFrames(options.range);
      }
    }
  }

  return this.to(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.prototype.to"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>to (degrees, time, rate)](#apidoc.element.johnny-five.Servo.prototype.to)
- description and source-code
```javascript
to = function (degrees, time, rate) {

  var state = priv.get(this);
  var options = {};

  if (typeof degrees === "object") {

    Object.assign(options, degrees);

    options.duration = degrees.duration || degrees.interval || 1000;
    options.cuePoints = degrees.cuePoints || [0, 1.0];
    options.keyFrames = degrees.keyFrames || [
      null,
      {
        value: typeof degrees.degrees === "number" ? degrees.degrees : this.startAt
      }
    ];

    options.oncomplete = function() {
      // Enforce async execution for user "oncomplete"
      process.nextTick(function() {
        if (typeof degrees.oncomplete === "function") {
          degrees.oncomplete();
        }
        this.emit("move:complete");
      }.bind(this));
    }.bind(this);


    state.isRunning = true;
    state.animation = state.animation || new Animation(this);
    state.animation.enqueue(options);

  } else {

    var target = degrees;

    // Enforce limited range of motion
    degrees = Fn.constrain(degrees, this.range[0], this.range[1]);
    degrees += this.offset;

    this.value = degrees;

    if (this.invert) {
      degrees = Fn.map(
        degrees,
        0, 180,
        180, 0
      );
    }

    if (typeof time !== "undefined") {

      options.duration = time;
      options.keyFrames = [null, {
        degrees: degrees
      }];
      options.fps = rate || this.fps;

      this.to(options);

    } else {
      this.update(degrees);

      if (state.history.length > 5) {
        state.history.shift();
      }

      state.history.push({
        timestamp: Date.now(),
        degrees: degrees,
        target: target
      });
    }
  }

  // return this instance
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servo.prototype.write"></a>[function <span class="apidocSignatureSpan">johnny-five.Servo.prototype.</span>write (degrees, time)](#apidoc.element.johnny-five.Servo.prototype.write)
- description and source-code
```javascript
write = function (degrees, time) {
  console.warn("Servo.prototype.move has been renamed to Servo.prototype.to");

  return this.to(degrees, time);
}
```
- example usage
```shell
...
EVS.isRawSensor = function(port) {
return port.analog === EVS.S1_ANALOG || port.analog === EVS.S2_ANALOG;
};

util.inherits(EVS, Emitter);

EVS.prototype.setup = function(port, type) {
this.bank[port.bank].write(port.mode, [type]);
};

EVS.prototype.read = function(port, register, numBytes, callback) {

if (port.sensor && port.offset && !EVS.isRawSensor(port)) {
  register += port.offset;
}
...
```



# <a name="apidoc.module.johnny-five.Servos"></a>[module johnny-five.Servos](#apidoc.module.johnny-five.Servos)

#### <a name="apidoc.element.johnny-five.Servos.Servos"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Servos (numsOrObjects)](#apidoc.element.johnny-five.Servos.Servos)
- description and source-code
```javascript
function Servos(numsOrObjects) {
  if (!(this instanceof Servos)) {
    return new Servos(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Servo
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servos.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Servos.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Servos.super_)
- description and source-code
```javascript
function Collection(numsOrObjects) {
  var Type = this.type;
  var initObjects = [];

  this.length = 0;

  if (Array.isArray(numsOrObjects)) {
    initObjects = numsOrObjects;
  } else {
    // Initialize with a Shared Properties object
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (Array.isArray(numsOrObjects.pins)) {
      var keys = Object.keys(numsOrObjects).filter(function(key) {
        return key !== "pins";
      });
      initObjects = numsOrObjects.pins.map(function(pin) {
        var obj = {};

        if (Array.isArray(pin)) {
          obj.pins = pin;
        } else {
          obj.pin = pin;
        }

        return keys.reduce(function(accum, key) {
          accum[key] = numsOrObjects[key];
          return accum;
        }, obj);
      });
    }
  }

  /* istanbul ignore else */
  if (initObjects.length) {
    while (initObjects.length) {
      var numOrObject = initObjects.shift();

      // When a Type exists, respect it!
      if (typeof Type === "function") {
        if (!(numOrObject instanceof Type || numOrObject instanceof this.constructor)) {
          numOrObject = new Type(numOrObject);
        }
      }

      this.add(numOrObject);
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Servos.prototype"></a>[module johnny-five.Servos.prototype](#apidoc.module.johnny-five.Servos.prototype)

#### <a name="apidoc.element.johnny-five.Servos.prototype.ccw"></a>[function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>ccw ()](#apidoc.element.johnny-five.Servos.prototype.ccw)
- description and source-code
```javascript
ccw = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servos.prototype.center"></a>[function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>center ()](#apidoc.element.johnny-five.Servos.prototype.center)
- description and source-code
```javascript
center = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servos.prototype.clockWise"></a>[function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>clockWise ()](#apidoc.element.johnny-five.Servos.prototype.clockWise)
- description and source-code
```javascript
clockWise = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servos.prototype.counterClockwise"></a>[function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>counterClockwise ()](#apidoc.element.johnny-five.Servos.prototype.counterClockwise)
- description and source-code
```javascript
counterClockwise = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servos.prototype.cw"></a>[function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>cw ()](#apidoc.element.johnny-five.Servos.prototype.cw)
- description and source-code
```javascript
cw = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servos.prototype.home"></a>[function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>home ()](#apidoc.element.johnny-five.Servos.prototype.home)
- description and source-code
```javascript
home = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servos.prototype.max"></a>[function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>max ()](#apidoc.element.johnny-five.Servos.prototype.max)
- description and source-code
```javascript
max = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servos.prototype.min"></a>[function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>min ()](#apidoc.element.johnny-five.Servos.prototype.min)
- description and source-code
```javascript
min = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servos.prototype.move"></a>[function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>move ()](#apidoc.element.johnny-five.Servos.prototype.move)
- description and source-code
```javascript
move = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servos.prototype.step"></a>[function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>step ()](#apidoc.element.johnny-five.Servos.prototype.step)
- description and source-code
```javascript
step = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servos.prototype.stop"></a>[function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>stop ()](#apidoc.element.johnny-five.Servos.prototype.stop)
- description and source-code
```javascript
stop = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servos.prototype.sweep"></a>[function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>sweep ()](#apidoc.element.johnny-five.Servos.prototype.sweep)
- description and source-code
```javascript
sweep = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Servos.prototype.to"></a>[function <span class="apidocSignatureSpan">johnny-five.Servos.prototype.</span>to ()](#apidoc.element.johnny-five.Servos.prototype.to)
- description and source-code
```javascript
to = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.ShiftRegister"></a>[module johnny-five.ShiftRegister](#apidoc.module.johnny-five.ShiftRegister)

#### <a name="apidoc.element.johnny-five.ShiftRegister.ShiftRegister"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>ShiftRegister (opts)](#apidoc.element.johnny-five.ShiftRegister.ShiftRegister)
- description and source-code
```javascript
function ShiftRegister(opts) {
  if (!(this instanceof ShiftRegister)) {
    return new ShiftRegister(opts);
  }

  if (Array.isArray(opts)) {
    // [Data, Clock, Latch, Reset]
    opts = {
      pins: {
        data: opts[0],
        clock: opts[1],
        latch: opts[2],
        reset: opts.length === 4 ? opts[3] : null,
      }
    };
  } else if (typeof opts.pins === "object" && Array.isArray(opts.pins)) {
    opts.pins = {
      data: opts.pins[0],
      clock: opts.pins[1],
      latch: opts.pins[2],
      reset: opts.pins.length === 4 ? opts.pins[3] : null,
    };
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  this.size = opts.size || 1;
  this.pins.reset = typeof opts.pins.reset !== "undefined" ? opts.pins.reset : null;

  var isAnode = typeof opts.isAnode !== "undefined" ? opts.isAnode : false;
  var clear = isAnode ? 255 : 0;
  var state = {
    isAnode: isAnode,
    value: new Array(this.size).fill(clear),
    encoded: encoded[isAnode ? "anode" : "cathode"],
    clear: clear,
  };

  priv.set(this, state);

  Object.defineProperties(this, {
    isAnode: {
      get: function() {
        return isAnode;
      }
    },
    value: {
      get: function() {
        return state.value;
      }
    },
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ShiftRegister.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.ShiftRegister.Collection)
- description and source-code
```javascript
function ShiftRegisters(numsOrObjects) {
  if (!(this instanceof ShiftRegisters)) {
    return new ShiftRegisters(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: ShiftRegister
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.ShiftRegister.Collection"></a>[module johnny-five.ShiftRegister.Collection](#apidoc.module.johnny-five.ShiftRegister.Collection)

#### <a name="apidoc.element.johnny-five.ShiftRegister.Collection.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.ShiftRegister.Collection.Collection)
- description and source-code
```javascript
function ShiftRegisters(numsOrObjects) {
  if (!(this instanceof ShiftRegisters)) {
    return new ShiftRegisters(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: ShiftRegister
  });

  Collection.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ShiftRegister.Collection.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.Collection.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.ShiftRegister.Collection.super_)
- description and source-code
```javascript
function Collection(numsOrObjects) {
  var Type = this.type;
  var initObjects = [];

  this.length = 0;

  if (Array.isArray(numsOrObjects)) {
    initObjects = numsOrObjects;
  } else {
    // Initialize with a Shared Properties object
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (Array.isArray(numsOrObjects.pins)) {
      var keys = Object.keys(numsOrObjects).filter(function(key) {
        return key !== "pins";
      });
      initObjects = numsOrObjects.pins.map(function(pin) {
        var obj = {};

        if (Array.isArray(pin)) {
          obj.pins = pin;
        } else {
          obj.pin = pin;
        }

        return keys.reduce(function(accum, key) {
          accum[key] = numsOrObjects[key];
          return accum;
        }, obj);
      });
    }
  }

  /* istanbul ignore else */
  if (initObjects.length) {
    while (initObjects.length) {
      var numOrObject = initObjects.shift();

      // When a Type exists, respect it!
      if (typeof Type === "function") {
        if (!(numOrObject instanceof Type || numOrObject instanceof this.constructor)) {
          numOrObject = new Type(numOrObject);
        }
      }

      this.add(numOrObject);
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.ShiftRegister.Collection.prototype"></a>[module johnny-five.ShiftRegister.Collection.prototype](#apidoc.module.johnny-five.ShiftRegister.Collection.prototype)

#### <a name="apidoc.element.johnny-five.ShiftRegister.Collection.prototype.clear"></a>[function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.Collection.prototype.</span>clear ()](#apidoc.element.johnny-five.ShiftRegister.Collection.prototype.clear)
- description and source-code
```javascript
clear = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ShiftRegister.Collection.prototype.display"></a>[function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.Collection.prototype.</span>display ()](#apidoc.element.johnny-five.ShiftRegister.Collection.prototype.display)
- description and source-code
```javascript
display = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ShiftRegister.Collection.prototype.reset"></a>[function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.Collection.prototype.</span>reset ()](#apidoc.element.johnny-five.ShiftRegister.Collection.prototype.reset)
- description and source-code
```javascript
reset = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ShiftRegister.Collection.prototype.send"></a>[function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.Collection.prototype.</span>send ()](#apidoc.element.johnny-five.ShiftRegister.Collection.prototype.send)
- description and source-code
```javascript
send = function () {
  var length = this.length;

  for (var i = 0; i < length; i++) {
    this[i][method].apply(this[i], arguments);
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.ShiftRegister.prototype"></a>[module johnny-five.ShiftRegister.prototype](#apidoc.module.johnny-five.ShiftRegister.prototype)

#### <a name="apidoc.element.johnny-five.ShiftRegister.prototype.clear"></a>[function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.prototype.</span>clear ()](#apidoc.element.johnny-five.ShiftRegister.prototype.clear)
- description and source-code
```javascript
clear = function () {
  var state = priv.get(this);
  return this.send(Array(this.size).fill(state.clear));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ShiftRegister.prototype.display"></a>[function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.prototype.</span>display (value)](#apidoc.element.johnny-five.ShiftRegister.prototype.display)
- description and source-code
```javascript
display = function (value) {
  var state = priv.get(this);
  var chars;

  if (typeof value === "number") {
    // 1, 20, etc.
    return this.display(String(value));
  }

  if (typeof value === "string") {
    var matches = value.match(/([0-9]{1}\.*)/g);

    if (matches && matches.length) {
      chars = matches.map(function(char) {
        // "1"
        if (char.length === 1) {
          return state.encoded[char] | (1 << 7);
        }
        // "1.?.?"
        return state.encoded[char[0]];
      });
    }
  }

  this.send(chars);

  state.value = chars;

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ShiftRegister.prototype.reset"></a>[function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.prototype.</span>reset ()](#apidoc.element.johnny-five.ShiftRegister.prototype.reset)
- description and source-code
```javascript
reset = function () {
  if (this.pins.reset === null) {
    throw new Error("ShiftRegister was not initialized with a reset pin");
  }
  this.io.digitalWrite(this.pins.clock, this.io.LOW);
  this.io.digitalWrite(this.pins.reset, this.io.LOW);
  this.io.digitalWrite(this.pins.clock, this.io.HIGH);
  this.io.digitalWrite(this.pins.reset, this.io.HIGH);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.ShiftRegister.prototype.send"></a>[function <span class="apidocSignatureSpan">johnny-five.ShiftRegister.prototype.</span>send (value)](#apidoc.element.johnny-five.ShiftRegister.prototype.send)
- description and source-code
```javascript
send = function (value) {
  var state = priv.get(this);
  var args = Array.from(arguments);

  if (args.length === 1) {
    args = [value];
  }

  if (Array.isArray(value)) {
    args = value;
  }

  // open latch to fill register with data
  this.io.digitalWrite(this.pins.latch, this.io.LOW);

  args.forEach(function(arg) {
    if (typeof arg === "string") {
      arg = arg.charCodeAt(0);
    }
    if (this.isAnode &&
      (arg !== 255 && !state.encoded.includes(arg) && !state.encoded.includes(arg & ~(1 << 7)))) {

      var index = encoded.anode.findIndex(function(value) {
        return value === arg;
      });

      if (index !== -1) {
        arg = encoded.cathode[index];
      }
    }
    this.board.shiftOut(this.pins.data, this.pins.clock, true, arg);
  }, this);

  // close latch to commit bits into register.
  this.io.digitalWrite(this.pins.latch, this.io.HIGH);

  state.value = args;

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Sonar"></a>[module johnny-five.Sonar](#apidoc.module.johnny-five.Sonar)

#### <a name="apidoc.element.johnny-five.Sonar.Sonar"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Sonar (opts)](#apidoc.element.johnny-five.Sonar.Sonar)
- description and source-code
```javascript
function Sonar(opts) {

  if (!(this instanceof Sonar)) {
    return new Sonar(opts);
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var device, state;

  // Sonar instance properties
  this.freq = opts.freq || 100;
  this.value = null;

  state = {
    last: 0,
    median: 0,
    samples: []
  };

  priv.set(this, state);

  if (typeof opts.device === "string") {
    device = Devices[opts.device];
  } else {
    device = opts.device;
  }

  if (typeof device === "undefined") {
    device = Devices.DEFAULT;
  }

  device.initialize.call(this, opts);

  if (!device.descriptor.inches) {
    device.descriptor.inches = {
      get: function() {
        return +(this.cm * 0.39).toFixed(2);
      }
    };
  }

  device.descriptor.in = device.descriptor.inches;

  Object.defineProperties(this, device.descriptor);

  // Throttle
  setInterval(function() {
    // Nothing read since previous interval
    if (state.samples.length === 0) {
      return;
    }

    state.median = state.samples.sort()[Math.floor(state.samples.length / 2)];
    this.value = state.median;

    this.emit("data", state.median);

    // If the state.median value for this interval is not the same as the
    // state.median value in the last interval, fire a "change" event.
    //
    if (state.last && state.median &&
      (state.median.toFixed(1) !== state.last.toFixed(1))) {
      this.emit("change", state.median);
    }

    // Store this media value for comparison
    // in next interval
    state.last = state.median;

    // Reset state.samples;
    state.samples.length = 0;
  }.bind(this), this.freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Sonar.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Sonar.</span>super_ ()](#apidoc.element.johnny-five.Sonar.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Sonar.prototype"></a>[module johnny-five.Sonar.prototype](#apidoc.module.johnny-five.Sonar.prototype)

#### <a name="apidoc.element.johnny-five.Sonar.prototype.within"></a>[function <span class="apidocSignatureSpan">johnny-five.Sonar.prototype.</span>within (range, unit, callback)](#apidoc.element.johnny-five.Sonar.prototype.within)
- description and source-code
```javascript
within = function (range, unit, callback) {
  var upper;

  if (typeof range === "number") {
    upper = range;
    range = [0, upper];
  }

  if (!Array.isArray(range)) {
    throw new Error("within expected a range array");
  }

  if (typeof unit === "function") {
    callback = unit;
    unit = "value";
  }

  if (typeof this[unit] === "undefined") {
    return this;
  }

  // Use the continuous read event for high resolution
  this.on("data", function() {
    var value = this[unit];
    if (value >= range[0] && value <= range[1]) {
      callback.call(this, null, value);
    }
  }.bind(this));

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Stepper"></a>[module johnny-five.Stepper](#apidoc.module.johnny-five.Stepper)

#### <a name="apidoc.element.johnny-five.Stepper.Stepper"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Stepper (opts)](#apidoc.element.johnny-five.Stepper.Stepper)
- description and source-code
```javascript
function Stepper(opts) {
  var state, params = [];

  if (!(this instanceof Stepper)) {
    return new Stepper(opts);
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  if (!isSupported(this.io)) {
    throw new Error(
      "Stepper is not supported"
    );
  }

  if (!opts.pins) {
    throw new Error(
      "Stepper requires a 'pins' object or array"
    );
  }

  if (!opts.stepsPerRev) {
    throw new Error(
      "Stepper requires a 'stepsPerRev' number value"
    );
  }

  steppers.set(this.board, steppers.get(this.board) || []);
  this.id = steppers.get(this.board).length;

  if (this.id >= MAXSTEPPERS) {
    throw new Error(
      "Stepper cannot exceed max steppers (" + MAXSTEPPERS + ")"
    );
  }

  // Convert an array of pins to the appropriate named pin
  if (Array.isArray(this.pins)) {
    if (this.pins.length === 2) {
      // Using an array of 2 pins requres a TYPE
      // to disambiguate DRIVER and TWO_WIRE
      if (!opts.type) {
        throw new Error(
          "Stepper requires a 'type' number value (DRIVER, TWO_WIRE)"
        );
      }
    }

    if (opts.type === Stepper.TYPE.DRIVER) {
      this.pins = {
        step: this.pins[0],
        dir: this.pins[1]
      };
    } else {
      this.pins = new MotorPins(this.pins);
    }
  }

  // Attempt to guess the type if none is provided
  if (!opts.type) {
    if (this.pins.dir) {
      opts.type = Stepper.TYPE.DRIVER;
    } else {
      if (this.pins.motor3) {
        opts.type = Stepper.TYPE.FOUR_WIRE;
      } else {
        opts.type = Stepper.TYPE.TWO_WIRE;
      }
    }
  }


  // Initial Stepper config params (same for all 3 types)
  params.push(this.id, opts.type, opts.stepsPerRev);


  if (opts.type === Stepper.TYPE.DRIVER) {
    if (typeof this.pins.dir === "undefined" ||
        typeof this.pins.step === "undefined") {
      throw new Error(
        "Stepper.TYPE.DRIVER expects: 'pins.dir', 'pins.step'"
      );
    }

    params.push(
      this.pins.dir, this.pins.step
    );
  }

  if (opts.type === Stepper.TYPE.TWO_WIRE) {
    if (typeof this.pins.motor1 === "undefined" ||
        typeof this.pins.motor2 === "undefined") {
      throw new Error(
        "Stepper.TYPE.TWO_WIRE expects: 'pins.motor1', 'pins.motor2'"
      );
    }

    params.push(
      this.pins.motor1, this.pins.motor2
    );
  }

  if (opts.type === Stepper.TYPE.FOUR_WIRE) {
    if (typeof this.pins.motor1 === "undefined" ||
        typeof this.pins.motor2 === "undefined" ||
        typeof this.pins.motor3 === "undefined" ||
        typeof this.pins.motor4 === "undefined") {
      throw new Error(
        "Stepper.TYPE.FOUR_WIRE expects: 'pins.motor1', 'pins.motor2', 'pins.motor3', 'pins.motor4'"
      );
    }

    params.push(
      this.pins.motor1, this.pins.motor2, this.pins.motor3, this.pins.motor4
    );
  }

  // Iterate the params and set each pin's mode to MODES.STEPPER
  // Params:
  // [deviceNum, type, stepsPerRev, dirOrMotor1Pin, stepOrMotor2Pin, motor3Pin, motor4Pin]
  // The first 3 are required, the remaining 2-4 will be pins
  params.slice(3).forEach(function(pin) {
    this.io.pinMode(pin, this.io.MODES.STEPPER);
  }, this);

  this.io.stepperConfig.apply(this.io, params);

  steppers.get(this.board).push(this);

  state = Step.PROPERTIES.reduce(function(state, key, i) {
    return (state[key] = typeof opts[key] !== "undefined" ? opts[key] : Step.DEFAULTS[i], state);
  }, {
    isRunning: false,
    type: opts.type,
    pins: this.pins
  });

  priv.set(this, state);

  Object.defineProperties(this, {
    type: {
      get: function() {
        return state.type;
      }
    },

    pins: {
      get: function() {
        return state.pins;
      }
    }
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Stepper.prototype"></a>[module johnny-five.Stepper.prototype](#apidoc.module.johnny-five.Stepper.prototype)

#### <a name="apidoc.element.johnny-five.Stepper.prototype.accel"></a>[function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>accel (value)](#apidoc.element.johnny-five.Stepper.prototype.accel)
- description and source-code
```javascript
accel = function (value) {
  var state = priv.get(this);

  if (typeof value === "undefined") {
    return state[prop];
  }
  state[prop] = value;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Stepper.prototype.ccw"></a>[function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>ccw ()](#apidoc.element.johnny-five.Stepper.prototype.ccw)
- description and source-code
```javascript
ccw = function () {
  return this.direction(0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Stepper.prototype.cw"></a>[function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>cw ()](#apidoc.element.johnny-five.Stepper.prototype.cw)
- description and source-code
```javascript
cw = function () {
  return this.direction(1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Stepper.prototype.decel"></a>[function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>decel (value)](#apidoc.element.johnny-five.Stepper.prototype.decel)
- description and source-code
```javascript
decel = function (value) {
  var state = priv.get(this);

  if (typeof value === "undefined") {
    return state[prop];
  }
  state[prop] = value;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Stepper.prototype.direction"></a>[function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>direction (value)](#apidoc.element.johnny-five.Stepper.prototype.direction)
- description and source-code
```javascript
direction = function (value) {
  var state = priv.get(this);

  if (typeof value === "undefined") {
    return state[prop];
  }
  state[prop] = value;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Stepper.prototype.rpm"></a>[function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>rpm (rpm)](#apidoc.element.johnny-five.Stepper.prototype.rpm)
- description and source-code
```javascript
rpm = function (rpm) {
  var state = priv.get(this);

  if (typeof rpm === "undefined") {
    return state.rpm;
  }
  state.rpm = rpm;
  state.speed = Math.round(rpm * TAU * 100 / 60);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Stepper.prototype.speed"></a>[function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>speed (speed)](#apidoc.element.johnny-five.Stepper.prototype.speed)
- description and source-code
```javascript
speed = function (speed) {
  var state = priv.get(this);

  if (typeof speed === "undefined") {
    return state.speed;
  }
  state.speed = speed;
  state.rpm = Math.round(speed / TAU / 100 * 60);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Stepper.prototype.step"></a>[function <span class="apidocSignatureSpan">johnny-five.Stepper.prototype.</span>step (stepsOrOpts, callback)](#apidoc.element.johnny-five.Stepper.prototype.step)
- description and source-code
```javascript
step = function (stepsOrOpts, callback) {
  var steps, step, state, params, isValidStep;

  steps = typeof stepsOrOpts === "object" ?
    (stepsOrOpts.steps || 0) : Math.floor(stepsOrOpts);

  step = new Step(this);

  state = priv.get(this);

  params = [];

  isValidStep = true;

  function failback(error) {
    isValidStep = false;
    if (callback) {
      callback(error);
    }
  }

  params.push(steps);

  if (typeof stepsOrOpts === "object") {
    // If an object of property values has been provided,
    // call the correlating method with the value argument.
    Step.PROPERTIES.forEach(function(key) {
      if (typeof stepsOrOpts[key] !== "undefined") {
        this[key](stepsOrOpts[key]);
      }
    }, this);
  }

  if (!state.speed) {
    this.rpm(state.rpm);
    step.speed = this.speed();
  }


  // Ensure that the property params are set in the
  // correct order, but without rpm
  Step.PROPERTIES.slice(1).forEach(function(key) {
    params.push(step[key] = this[key]());
  }, this);


  if (steps === 0) {
    failback(
      new Error(
        "Must set a number of steps when calling 'step()'"
      )
    );
  }

  if (step.direction < 0) {
    failback(
      new Error(
        "Must set a direction before calling 'step()'"
      )
    );
  }

  if (isValidStep) {
    state.isRunning = true;

    params.push(function(complete) {
      state.isRunning = false;
      callback(null, complete);
    });

    step.move.apply(step, params);
  }

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Switch"></a>[module johnny-five.Switch](#apidoc.module.johnny-five.Switch)

#### <a name="apidoc.element.johnny-five.Switch.Switch"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Switch (opts)](#apidoc.element.johnny-five.Switch.Switch)
- description and source-code
```javascript
function Switch(opts) {

  if (!(this instanceof Switch)) {
    return new Switch(opts);
  }

  // Create a 5 ms debounce boundary on event triggers
  // this avoids button events firing on
  // press noise and false positives
  var trigger = Fn.debounce(function(key) {
    aliases[key].forEach(function(type) {
      this.emit(type, null);
    }, this);
  }, 5);

  // Resolve the default type to Normally Open
  opts.type = opts.type || "NO";

  // Is this instance Normally Open?
  var isNormallyOpen = opts.type === "NO";
  var raw = null;
  var invert = typeof opts.invert !== "undefined" ?
    opts.invert : (isNormallyOpen || false);

  // Logical Defaults
  var closeValue = 1;
  var openValue = 0;

  if (invert) {
    closeValue ^= 1;
    openValue ^= 1;
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  this.io.pinMode(this.pin, this.io.MODES.INPUT);

  if (isNormallyOpen) {
    this.io.digitalWrite(this.pin, this.io.HIGH);
  }

  this.io.digitalRead(this.pin, function(data) {
    raw = data;

    trigger.call(this, this.isOpen ? "open" : "close");
  }.bind(this));

  Object.defineProperties(this, {
    value: {
      get: function() {
        return Number(this.isOpen);
      }
    },
    invert: {
      get: function() {
        return invert;
      },
      set: function(value) {
        invert = value;
        closeValue = invert ? 0 : 1;
        openValue = invert ? 1 : 0;
      }
    },
    closeValue: {
      get: function() {
        return closeValue;
      },
      set: function(value) {
        closeValue = value;
        openValue = value ^ 1;
      }
    },
    openValue: {
      get: function() {
        return openValue;
      },
      set: function(value) {
        openValue = value;
        closeValue = value ^ 1;
      }
    },
    isOpen: {
      get: function() {
        return raw === openValue;
      }
    },
    isClosed: {
      get: function() {
        return raw === closeValue;
      }
    },
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Switch.Collection"></a>[function <span class="apidocSignatureSpan">johnny-five.Switch.</span>Collection (numsOrObjects)](#apidoc.element.johnny-five.Switch.Collection)
- description and source-code
```javascript
function Switches(numsOrObjects) {
  if (!(this instanceof Switches)) {
    return new Switches(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Switch
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Switch.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Switch.</span>super_ ()](#apidoc.element.johnny-five.Switch.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Switches"></a>[module johnny-five.Switches](#apidoc.module.johnny-five.Switches)

#### <a name="apidoc.element.johnny-five.Switches.Switches"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Switches (numsOrObjects)](#apidoc.element.johnny-five.Switches.Switches)
- description and source-code
```javascript
function Switches(numsOrObjects) {
  if (!(this instanceof Switches)) {
    return new Switches(numsOrObjects);
  }

  Object.defineProperty(this, "type", {
    value: Switch
  });

  Collection.Emitter.call(this, numsOrObjects);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Switches.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Switches.</span>super_ (numsOrObjects)](#apidoc.element.johnny-five.Switches.super_)
- description and source-code
```javascript
super_ = function (numsOrObjects) {

  // Create private state ahead of super call
  priv.set(this, {
    timing: {
      last: Date.now()
    }
  });

  Collection.call(this, numsOrObjects);

  // If the Collection.Emitter was created
  // with a Shared Properties object, then
  // we should abide by the freq or period
  // properties...
  var interval = null;
  var period = 5;

  if (!Array.isArray(numsOrObjects) &&
      (typeof numsOrObjects === "object" && numsOrObjects !== null))  {

    period = numsOrObjects.freq || numsOrObjects.period || period;

    // _However_, looking to the future, we
    // need to start thinking about replacing
    // the garbage named _freq_ (the value is
    // actually a period), with real _frequency_
    // in Hz.

    // If provided, convert frequency to period
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (numsOrObjects.frequency) {
      period = (1 / numsOrObjects.frequency) * 1000;
    }
  }

  Object.defineProperties(this, {
    period: {
      get: function() {
        return period;
      },
      set: function(value) {
        if (period !== value) {
          period = value;
        }

        if (interval) {
          clearInterval(interval);
        }

        interval = setInterval(function() {
          this.emit("data", this);
        }.bind(this), period);
      }
    },
  });

  this.period = period;

  this.on("newListener", function(event) {
    if (event === "change" || event === "data") {
      return;
    }

    this.forEach(function(input) {
      input.on(event, function(data) {
        this.emit(event, input, data);
      }.bind(this));
    }, this);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Thermometer"></a>[module johnny-five.Thermometer](#apidoc.module.johnny-five.Thermometer)

#### <a name="apidoc.element.johnny-five.Thermometer.Thermometer"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Thermometer (opts)](#apidoc.element.johnny-five.Thermometer.Thermometer)
- description and source-code
```javascript
function Thermometer(opts) {

  if (!(this instanceof Thermometer)) {
    return new Thermometer(opts);
  }

  var controller = null;
  var last = null;
  var raw = null;

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var freq = opts.freq || 25;

  // Analog Reference Voltage (default to board.io.aref || 5)
  this.aref = opts.aref || this.io.aref || 5;

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller == null) {
    controller = Controllers.ANALOG;
  }

  priv.set(this, {});

  Board.Controller.call(this, controller, opts);

  if (!this.toCelsius) {
    this.toCelsius = opts.toCelsius || function(x) {
      return x;
    };
  }

  var descriptors = {
    celsius: {
      get: function() {
        return this.toCelsius(raw);
      }
    },
    fahrenheit: {
      get: function() {
        return toFixed((this.celsius * 9 / 5) + 32, 2);
      }
    },
    kelvin: {
      get: function() {
        return toFixed(this.celsius + CELSIUS_TO_KELVIN, 2);
      }
    }
  };
  // Convenience aliases
  descriptors.C = descriptors.celsius;
  descriptors.F = descriptors.fahrenheit;
  descriptors.K = descriptors.kelvin;

  Object.defineProperties(this, descriptors);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw == null) {
      return;
    }

    var data = {};
    data.C = data.celsius = this.celsius;
    data.F = data.fahrenheit = this.fahrenheit;
    data.K = data.kelvin = this.kelvin;

    this.emit("data", data);

    if (this.celsius !== last) {
      last = this.celsius;
      this.emit("change", data);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Thermometer.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Thermometer.</span>super_ ()](#apidoc.element.johnny-five.Thermometer.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Thermometer.Drivers"></a>[module johnny-five.Thermometer.Drivers](#apidoc.module.johnny-five.Thermometer.Drivers)

#### <a name="apidoc.element.johnny-five.Thermometer.Drivers.clear"></a>[function <span class="apidocSignatureSpan">johnny-five.Thermometer.Drivers.</span>clear ()](#apidoc.element.johnny-five.Thermometer.Drivers.clear)
- description and source-code
```javascript
clear = function () {
  activeDrivers.clear();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Thermometer.Drivers.get"></a>[function <span class="apidocSignatureSpan">johnny-five.Thermometer.Drivers.</span>get (board, driverName, opts)](#apidoc.element.johnny-five.Thermometer.Drivers.get)
- description and source-code
```javascript
get = function (board, driverName, opts) {
  var drivers, driver;

  if (!activeDrivers.has(board)) {
    activeDrivers.set(board, {});
  }

  drivers = activeDrivers.get(board);

  if (!drivers[driverName]) {
    driver = new Emitter();
    Object.defineProperties(driver, Drivers[driverName]);
    driver.initialize(board, opts);
    drivers[driverName] = driver;
  }

  return drivers[driverName];
}
```
- example usage
```shell
...

var Controllers = {

  BNO055: {
initialize: {
  value: function(opts, dataHandler) {
    var IMU = require("./imu"),
      driver = IMU.Drivers.get(this.board, "BNO055", opts);

    driver.on("data", function(data) {
      dataHandler(data);
    });
  }
},
toScaledEuler: {
...
```



# <a name="apidoc.module.johnny-five.Wii"></a>[module johnny-five.Wii](#apidoc.module.johnny-five.Wii)

#### <a name="apidoc.element.johnny-five.Wii.Wii"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>Wii (opts)](#apidoc.element.johnny-five.Wii.Wii)
- description and source-code
```javascript
function Wii(opts) {

  if (!(this instanceof Wii)) {
    return new Wii(opts);
  }

  Board.Component.call(this, opts);

  // Derive device definition from Devices
  var device = Devices[opts.device];
  var address = device.address;
  var bytes = device.bytes;
  var delay = device.delay;
  var data = device.data.bind(this);
  var setup = device.setup;
  var preread = device.preread;

  // Wii controller instance properties
  this.freq = opts.freq || 100;

  // Button instance properties
  this.holdtime = opts.holdtime || 500;
  this.threshold = opts.threshold || 10;

  // Initialize components
  device.initialize.call(this);

  // Set initial "last data" byte array
  last.set(this, [0, 0, 0, 0, 0, 0, 0]);

  // Set up I2C data connection
  this.io.i2cConfig(opts);

  // Iterate and write each set of setup instructions
  setup.forEach(function(bytes) {
    this.io.i2cWrite(address, bytes);
  }, this);

  // Unthrottled i2c read request loop
  setInterval(function() {

    // Send this command to get all sensor data and store into
    // the 6-byte register within Wii controller.
    // This must be execute before reading data from the Wii.

    // Iterate and write each set of setup instructions
    preread.forEach(function(bytes) {
      this.io.i2cWrite(address, bytes);
    }, this);


    // Request six bytes of data from the controller
    this.io.i2cReadOnce(address, bytes, data);

    // Use the high-frequency data read loop as the change event
    // emitting loop. This drastically improves change event
    // frequency and sensitivity
    //
    // Emit change events if any delta is greater than
    // the threshold

    // RVL-005 does not have a read method at this time.
    if (typeof device.read !== "undefined") {
      device.read.call(this);
    }
  }.bind(this), delay || this.freq);

  // Throttled "read" event loop
  setInterval(function() {
    var event = new Board.Event({
      target: this
    });

    this.emit("data", event);

  }.bind(this), this.freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Wii.Classic"></a>[function <span class="apidocSignatureSpan">johnny-five.Wii.</span>Classic (opts)](#apidoc.element.johnny-five.Wii.Classic)
- description and source-code
```javascript
Classic = function (opts) {
  opts = opts || {};
  opts.device = "RVL-005";

  return new Wii(opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Wii.Nunchuk"></a>[function <span class="apidocSignatureSpan">johnny-five.Wii.</span>Nunchuk (opts)](#apidoc.element.johnny-five.Wii.Nunchuk)
- description and source-code
```javascript
Nunchuk = function (opts) {
  opts = opts || {};
  opts.device = "RVL-004";

  return new Wii(opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Wii.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.Wii.</span>super_ ()](#apidoc.element.johnny-five.Wii.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.Wii.Components"></a>[module johnny-five.Wii.Components](#apidoc.module.johnny-five.Wii.Components)

#### <a name="apidoc.element.johnny-five.Wii.Components.Accelerometer"></a>[function <span class="apidocSignatureSpan">johnny-five.Wii.Components.</span>Accelerometer (controller)](#apidoc.element.johnny-five.Wii.Components.Accelerometer)
- description and source-code
```javascript
Accelerometer = function (controller) {

  if (!(this instanceof Wii.Components.Accelerometer)) {
    return new Wii.Components.Accelerometer(controller);
  }

  this.controller = controller;

  var state, accessors;

  // Initialize empty state object
  state = {};

  // Initialize empty accessors object
  accessors = {};

  // Enumerate Joystick properties
  ["x", "y", "z", "dx", "dy", "dz"].forEach(function(key) {

    state[key] = 0;

    // Define accessors for each property in Joystick list
    accessors[key] = {
      get: function() {
        return state[key];
      }
    };
  }, this);

  // Store private state cache
  priv.set(this, state);

  // Register newly defined accessors
  Object.defineProperties(this, accessors);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Wii.Components.Button"></a>[function <span class="apidocSignatureSpan">johnny-five.Wii.Components.</span>Button (which, controller)](#apidoc.element.johnny-five.Wii.Components.Button)
- description and source-code
```javascript
Button = function (which, controller) {

  if (!(this instanceof Wii.Components.Button)) {
    return new Wii.Components.Button(which, controller);
  }

  // c or z.
  this.which = which;

  // reference to parent controller
  this.controller = controller;

  // Set initial values for state tracking
  var state = {
    isDown: false
  };
  priv.set(this, state);

  Object.defineProperties(this, {
    // is the button up (not pressed)?
    isUp: {
      get: function() {
        return !state.isDown;
      }
    },

    // is the button pressed?
    isDown: {
      get: function() {
        return state.isDown;
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.Wii.Components.Joystick"></a>[function <span class="apidocSignatureSpan">johnny-five.Wii.Components.</span>Joystick (controller)](#apidoc.element.johnny-five.Wii.Components.Joystick)
- description and source-code
```javascript
Joystick = function (controller) {

  if (!(this instanceof Wii.Components.Joystick)) {
    return new Wii.Components.Joystick(controller);
  }

  this.controller = controller;

  var state, accessors;

  // Initialize empty state object
  state = {};

  // Initialize empty accessors object
  accessors = {};

  // Enumerate Joystick properties
  ["x", "y", "dx", "dy"].forEach(function(key) {

    state[key] = 0;

    // Define accessors for each property in Joystick list
    accessors[key] = {
      get: function() {
        return state[key];
      }
    };
  }, this);

  // Store private state cache
  priv.set(this, state);

  // Register newly defined accessors
  Object.defineProperties(this, accessors);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.evshield"></a>[module johnny-five.evshield](#apidoc.module.johnny-five.evshield)

#### <a name="apidoc.element.johnny-five.evshield.evshield"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>evshield (options)](#apidoc.element.johnny-five.evshield.evshield)
- description and source-code
```javascript
function EVS(options) {
  if (shared) {
    return shared;
  }

  this.bank = {
    a: new Bank({
      address: EVS.BANK_A,
      io: options.io,
    }),
    b: new Bank({
      address: EVS.BANK_B,
      io: options.io,
    })
  };

  shared = this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.evshield.isRawSensor"></a>[function <span class="apidocSignatureSpan">johnny-five.evshield.</span>isRawSensor (port)](#apidoc.element.johnny-five.evshield.isRawSensor)
- description and source-code
```javascript
isRawSensor = function (port) {
  return port.analog === EVS.S1_ANALOG || port.analog === EVS.S2_ANALOG;
}
```
- example usage
```shell
...

EVS.prototype.setup = function(port, type) {
  this.bank[port.bank].write(port.mode, [type]);
};

EVS.prototype.read = function(port, register, numBytes, callback) {

  if (port.sensor && port.offset && !EVS.isRawSensor(port)) {
    register += port.offset;
  }

  this.bank[port.bank].read(register, numBytes, callback);
};

EVS.prototype.write = function(port, register, data) {
...
```

#### <a name="apidoc.element.johnny-five.evshield.shieldPort"></a>[function <span class="apidocSignatureSpan">johnny-five.evshield.</span>shieldPort (pin)](#apidoc.element.johnny-five.evshield.shieldPort)
- description and source-code
```javascript
shieldPort = function (pin) {
  var port = EVS[pin];

  if (port === undefined) {
    throw new Error("Invalid EVShield pin name");
  }

  var address, analog, bank, motor, mode, offset, sensor;
  var endsWithS1 = false;

  if (pin.startsWith("BA")) {
    address = EVS.BANK_A;
    bank = "a";
  } else {
    address = EVS.BANK_B;
    bank = "b";
  }

  if (pin.includes("M")) {
    motor = pin.endsWith("M1") ? EVS.S1 : EVS.S2;
  }

  if (pin.includes("S")) {
    endsWithS1 = pin.endsWith("S1");

    // Used for reading 2 byte integer values from raw sensors
    analog = endsWithS1 ? EVS.S1_ANALOG : EVS.S2_ANALOG;
    // Sensor Mode (1 or 2?)
    mode = endsWithS1 ? EVS.S1_MODE : EVS.S2_MODE;
    // Used for read registers
    offset = endsWithS1 ? EVS.S1_OFFSET : EVS.S2_OFFSET;
    // Used to address "sensor type"
    sensor = endsWithS1 ? EVS.S1 : EVS.S2;
  }

  return {
    address: address,
    analog: analog,
    bank: bank,
    mode: mode,
    motor: motor,
    offset: offset,
    port: port,
    sensor: sensor,
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.evshield.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.evshield.</span>super_ ()](#apidoc.element.johnny-five.evshield.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.evshield.prototype"></a>[module johnny-five.evshield.prototype](#apidoc.module.johnny-five.evshield.prototype)

#### <a name="apidoc.element.johnny-five.evshield.prototype.read"></a>[function <span class="apidocSignatureSpan">johnny-five.evshield.prototype.</span>read (port, register, numBytes, callback)](#apidoc.element.johnny-five.evshield.prototype.read)
- description and source-code
```javascript
read = function (port, register, numBytes, callback) {

  if (port.sensor && port.offset && !EVS.isRawSensor(port)) {
    register += port.offset;
  }

  this.bank[port.bank].read(register, numBytes, callback);
}
```
- example usage
```shell
...

EVS.prototype.read = function(port, register, numBytes, callback) {

  if (port.sensor && port.offset && !EVS.isRawSensor(port)) {
    register += port.offset;
  }

  this.bank[port.bank].read(register, numBytes, callback);
};

EVS.prototype.write = function(port, register, data) {
  this.bank[port.bank].write(register, data);
};

/*
...
```

#### <a name="apidoc.element.johnny-five.evshield.prototype.setup"></a>[function <span class="apidocSignatureSpan">johnny-five.evshield.prototype.</span>setup (port, type)](#apidoc.element.johnny-five.evshield.prototype.setup)
- description and source-code
```javascript
setup = function (port, type) {
  this.bank[port.bank].write(port.mode, [type]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.evshield.prototype.write"></a>[function <span class="apidocSignatureSpan">johnny-five.evshield.prototype.</span>write (port, register, data)](#apidoc.element.johnny-five.evshield.prototype.write)
- description and source-code
```javascript
write = function (port, register, data) {
  this.bank[port.bank].write(register, data);
}
```
- example usage
```shell
...
EVS.isRawSensor = function(port) {
return port.analog === EVS.S1_ANALOG || port.analog === EVS.S2_ANALOG;
};

util.inherits(EVS, Emitter);

EVS.prototype.setup = function(port, type) {
this.bank[port.bank].write(port.mode, [type]);
};

EVS.prototype.read = function(port, register, numBytes, callback) {

if (port.sensor && port.offset && !EVS.isRawSensor(port)) {
  register += port.offset;
}
...
```



# <a name="apidoc.module.johnny-five.orientation"></a>[module johnny-five.orientation](#apidoc.module.johnny-five.orientation)

#### <a name="apidoc.element.johnny-five.orientation.orientation"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>orientation (opts)](#apidoc.element.johnny-five.orientation.orientation)
- description and source-code
```javascript
function Orientation(opts) {

  if (!(this instanceof Orientation)) {
    return new Orientation(opts);
  }

  Board.Component.call(
    this, opts = Board.Options(opts)
  );

  var freq = opts.freq || 25;
  var controller = null;
  var raw = null;
  var state = {
    euler: {
      heading: 0,
      roll: 0,
      pitch: 0,
    },
    quarternion: {
      w: 0,
      x: 0,
      y: 0,
      z: 0,
    },
    calibration: 0,
  };

  if (opts.controller && typeof opts.controller === "string") {
    controller = Controllers[opts.controller.toUpperCase()];
  } else {
    controller = opts.controller;
  }

  if (controller === null || typeof controller !== "object") {
    throw new Error("Missing valid Orientation controller");
  }

  Board.Controller.call(this, controller, opts);

  if (!this.toScaledQuarternion) {
    this.toScaledQuarternion = opts.toScaledQuarternion || function(raw) {
      return raw;
    };
  }

  if (!this.toScaledEuler) {
    this.toScaledEuler = opts.toScaledEuler || function(raw) {
      return raw;
    };
  }

  priv.set(this, state);

  if (typeof this.initialize === "function") {
    this.initialize(opts, function(data) {
      raw = data;
    });
  }

  setInterval(function() {
    if (raw === null) {
      return;
    }
    var didOrientationChange = false;
    var didCalibrationChange = false;

    ["heading", "roll", "pitch"].forEach(function(el) {
      if (state.euler[el] !== raw.orientation.euler[el]) {
        didOrientationChange = true;
      }
      state.euler[el] = raw.orientation.euler[el];
    });

    ["w", "x", "y", "z"].forEach(function(el) {
      if (state.quarternion[el] !== raw.orientation.quarternion[el]) {
        didOrientationChange = true;
      }
      state.quarternion[el] = raw.orientation.quarternion[el];
    });

    //if we have a raw calibration state...
    // not sure if this is the best place... some devices may not have a calibration state...
    if (raw.calibration) {
      if (state.calibration !== raw.calibration) {
        didCalibrationChange = true;
      }
      state.calibration = raw.calibration;
    }

    var data = {
      euler: this.euler,
      quarternion: this.quarternion,
      calibration: this.calibration
    };

    this.emit("data", data);

    if (didOrientationChange) {
      this.emit("change", data);
    }

    //not sure how we can get this event into other drivers
    if (didCalibrationChange) {
      this.emit("calibration", this.calibration);
    }
  }.bind(this), freq);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.orientation.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.orientation.</span>super_ ()](#apidoc.element.johnny-five.orientation.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.reflectancearray"></a>[module johnny-five.reflectancearray](#apidoc.module.johnny-five.reflectancearray)

#### <a name="apidoc.element.johnny-five.reflectancearray.reflectancearray"></a>[function <span class="apidocSignatureSpan">johnny-five.</span>reflectancearray (opts)](#apidoc.element.johnny-five.reflectancearray.reflectancearray)
- description and source-code
```javascript
function ReflectanceArray(opts) {

  if (!(this instanceof ReflectanceArray)) {
    return new ReflectanceArray(opts);
  }

  this.opts = Board.Options(opts);

  Board.Component.call(
    this, this.opts, {
      requestPin: false
    }
  );

  // Read event throttling
  this.freq = opts.freq || 25;

  // Make private data entry
  var state = {
    lastLine: 0,
    isOn: false,
    calibration: {
      min: [],
      max: []
    },
    autoCalibrate: opts.autoCalibrate || false
  };

  priv.set(this, state);

  initialize.call(this);

  Object.defineProperties(this, {
    isOn: {
      get: function() {
        return state.emitter.isOn;
      }
    },
    isCalibrated: {
      get: function() {
        return calibrationIsValid(this.calibration, this.sensors);
      }
    },
    isOnLine: {
      get: function() {
        var line = this.line;
        return line > CALIBRATED_MIN_VALUE && line < maxLineValue.call(this);
      }
    },
    sensors: {
      get: function() {
        return state.sensorStates.map(function(sensorState) {
          return sensorState.sensor;
        });
      }
    },
    calibration: {
      get: function() {
        return state.calibration;
      }
    },
    raw: {
      get: function() {
        return state.sensorStates.map(function(sensorState) {
          return sensorState.rawValue;
        });
      }
    },
    values: {
      get: function() {
        return this.isCalibrated ? calibratedValues.call(this) : this.raw;
      }
    },
    line: {
      get: function() {
        return this.isCalibrated ? getLine.call(this) : 0;
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.johnny-five.reflectancearray.super_"></a>[function <span class="apidocSignatureSpan">johnny-five.reflectancearray.</span>super_ ()](#apidoc.element.johnny-five.reflectancearray.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.johnny-five.sleep"></a>[module johnny-five.sleep](#apidoc.module.johnny-five.sleep)

#### <a name="apidoc.element.johnny-five.sleep.nano"></a>[function <span class="apidocSignatureSpan">johnny-five.sleep.</span>nano (ns)](#apidoc.element.johnny-five.sleep.nano)
- description and source-code
```javascript
nano = function (ns) {
  var start = process.hrtime();
  while (process.hrtime() < start + ns) {}
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
