# API_Explorer
The ultimate open-source API repository for developers. Browse hundreds of public APIs across AI, Finance, Weather, Maps, Payments, Social Media, Healthcare, and more. Find authentication details, pricing, documentation, SDKs, rate limits, and ready-to-use code examples—all organized in one searchable collection.
# 🌐 The Big List — 200+ APIs Worth Knowing

Curated for **API_Explorer**. Organized by category, ordered roughly by how likely you are to actually reach for it. Legend:

🆓 free tier exists · 🆓🆓 fully free forever · 🔑 needs API key · 💳 paid only / sales-gated · 🏛 government or nonprofit · 🇮🇳 India-specific · 🌍 global coverage

Every entry is a **real, live service** — nothing invented. Where a provider doesn't publish a fixed free quota, it's marked 💳 even if they offer trials.

---

## 1. 🧪 Sandbox, Mock Data & Testing APIs

The category every dev needs and never bookmarks in time.

| API | What it does | Access |
|---|---|---|
| **[JSONPlaceholder](https://jsonplaceholder.typicode.com/)** | Fake REST API for posts/comments/users — the default "hello world" for frontend testing | 🆓🆓 |
| **[Reqres](https://reqres.in/)** | Hosted REST-API mock with real status codes, pagination, delayed responses | 🆓🆓 |
| **[Mockaroo](https://www.mockaroo.com/)** | Generate realistic mock datasets (CSV/JSON/SQL) with custom schemas, plus a live mock API endpoint | 🆓🔑 |
| **[Postman Echo](https://docs.postman-echo.com/)** | Echoes back requests — great for testing auth headers, cookies, redirects | 🆓🆓 |
| **[httpbin.org](https://httpbin.org/)** | HTTP request/response testing service (status codes, headers, delays, streaming) | 🆓🆓 |
| **[Beeceptor](https://beeceptor.com/)** | Instant mock API/webhook endpoints, no signup; also hosts pre-built sandbox mocks for Razorpay, Stripe, etc. | 🆓🔑 |
| **[DummyJSON](https://dummyjson.com/)** | Fuller fake e-commerce dataset (products, carts, users, auth) than JSONPlaceholder | 🆓🆓 |
| **[Fake Store API](https://fakestoreapi.com/)** | Mock e-commerce product/cart/user API — good for testing shopping-cart UIs | 🆓🆓 |
| **[RandomUser.me](https://randomuser.me/)** | Generates random realistic user profiles (name, photo, address, login) | 🆓🆓 |
| **[Mocky.io](https://designer.mocky.io/)** | Spin up a custom mock endpoint with your own JSON response and status code in seconds | 🆓🆓 |
| **[WireMock Cloud](https://www.wiremock.io/)** | Hosted version of the popular open-source WireMock mocking tool, for full contract-style API mocks | 🆓🔑 |
| **[Mockable.io](https://www.mockable.io/)** | Simple hosted mock server, good for prototyping before backend exists | 🆓🔑 |

---

## 2. 💳 Payment Gateway Sandboxes (India + Global)

| API | What it does | Access |
|---|---|---|
| **[Razorpay Test Mode](https://razorpay.com/docs/payments/payment-gateway/web-integration/standard/test-integration/)** 🇮🇳 | Full sandbox with dummy cards, UPI (`success@razorpay` / `failure@razorpay`), net banking simulation | 🆓🔑 |
| **[Stripe Sandboxes](https://docs.stripe.com/sandboxes)** 🌍 | Isolated test environments, test card numbers for every decline reason (insufficient funds, expired, 3DS challenge) | 🆓🔑 |
| **[Cashfree Sandbox](https://www.cashfree.com/docs/)** 🇮🇳 | Sandbox for payments, payouts, and — notably — **GSTIN verification** (see §3) | 🆓🔑 |
| **[PayPal Sandbox](https://developer.paypal.com/tools/sandbox/)** 🌍 | Create fake buyer/seller accounts, simulate full checkout & webhook flows | 🆓🔑 |
| **[PhonePe Sandbox](https://developer.phonepe.com/)** 🇮🇳 | UPI/wallet payment sandbox for Indian merchants | 🆓🔑 |
| **[Paytm Business Sandbox](https://business.paytm.com/docs)** 🇮🇳 | Staging environment for Paytm wallet/UPI/card integrations | 🆓🔑 |
| **[Braintree Sandbox](https://developer.paypal.com/braintree/docs)** 🌍 | PayPal-owned gateway, sandbox supports cards, PayPal, Venmo, Google Pay | 🆓🔑 |
| **[RazorpayX Test Mode](https://razorpay.com/docs/x/dashboard/test-mode/)** 🇮🇳 | Sandbox specifically for payouts/vendor disbursement flows (not just collections) | 🆓🔑 |

---

## 3. 🧾 GST, Tax & Business Compliance (🇮🇳 heavy)

| API | What it does | Access |
|---|---|---|
| **[GST Portal — Search Taxpayer](https://www.gst.gov.in/)** 🏛 | The official free single-lookup GSTIN check — no API, but the source of truth everyone else wraps | 🆓🆓 |
| **[Cashfree GSTIN Verification](https://www.cashfree.com/docs/api-reference/vrs/v2/gstin/verify-gstin)** 🇮🇳 | Programmatic GSTIN verification — legal name, status, address, business type — with a live sandbox | 🆓🔑 |
| **[gstincheck.co.in](https://gstincheck.co.in/)** 🇮🇳 | Simple GSTIN validator API, 20 free test requests on signup, has a Google Sheets add-on for bulk checks | 🆓🔑 |
| **[eKYCNow GST Verification](https://www.messagecentral.com/en-in/blog/gst-verification-api-india)** 🇮🇳 | 5 free verifications, returns filing status alongside legal/trade name — useful for ITC risk scoring | 🆓🔑 |
| **[Eko GST Verification API](https://eko.in/developers/eps/gst-verification-api)** 🇮🇳 | Part of a bundled KYB pack (GST + PAN + bank penny-drop + DigiLocker); full sandbox with UAT keys on signup | 🆓🔑 |
| **[Open-source GST-Verification-API](https://github.com/shubham-dube/GST-Verification-API)** 🇮🇳 | Self-hostable open-source GSTIN checker if you don't want a vendor dependency | 🆓🆓 (self-host) |
| **[VAT Validation (VIES)](https://ec.europa.eu/taxation_customs/vies/)** 🏛🌍 | EU's official free VAT-number validation service — the GST equivalent for European business verification | 🆓🆓 |
| **[EIN/Tax ID lookups — IRS](https://www.irs.gov/charities-non-profits/tax-exempt-organization-search)** 🏛 | Free US nonprofit EIN and tax-exempt status lookup | 🆓🆓 |

---

## 4. 🪪 Identity, KYC & Document Verification (🇮🇳 focus)

| API | What it does | Access |
|---|---|---|
| **[DigiLocker APIs](https://partners.digilocker.gov.in/)** 🏛🇮🇳 | Official Govt of India API to pull verified documents (Aadhaar, PAN, driving license) with user consent | 🆓🔑 (partner approval needed) |
| **[Razorpay IFSC API](https://ifsc.razorpay.com/)** 🇮🇳 | Free, no-key lookup of any Indian bank branch by IFSC code — bank name, branch, address | 🆓🆓 |
| **[Signzy KYC APIs](https://signzy.com/)** 🇮🇳 | PAN, Aadhaar (masked), bank verification, video KYC — sandbox available | 🆓🔑 |
| **[HyperVerge KYC](https://hyperverge.co/)** 🇮🇳🌍 | Document + face verification, ID OCR, liveness detection | 🆓🔑 |
| **[IDfy](https://idfy.com/)** 🇮🇳 | PAN/GST/bank/Aadhaar verification suite for Indian fintechs | 🔑💳 |
| **[Onfido](https://onfido.com/)** 🌍 | Global identity verification (passport/ID/face match), widely used outside India | 🔑💳 |
| **[Jumio](https://www.jumio.com/)** 🌍 | Enterprise-grade global ID verification and biometric matching | 💳 |
| **[Truecaller Verify API](https://www.truecaller.com/verify)** 🇮🇳🌍 | Silent phone number verification without OTP, using Truecaller's number database | 🔑💳 |

---

## 5. 🏢 Company Registry, KYB & Sanctions Screening

| API | What it does | Access |
|---|---|---|
| **[OpenCorporates](https://api.opencorporates.com/documentation/API-Reference)** 🌍 | 200M+ companies, 140+ jurisdictions — the largest open company database | 🆓🔑 |
| **[Registry Lookup](https://registry-lookup.com/)** 🌍 | 521M+ entities, 309 jurisdictions, 5,000 free calls/month (beats OpenCorporates' paid tier) | 🆓🔑 |
| **[UK Companies House API](https://developer.company-information.service.gov.uk/)** 🏛 | Official free UK company registry — officers, filings, addresses | 🆓🆓 |
| **[SEC EDGAR Full-Text Search API](https://www.sec.gov/edgar/search/)** 🏛 | Free full-text search across all US public company SEC filings | 🆓🆓 |
| **[Moov Watchman](https://github.com/moov-io/watchman)** | Self-hosted OFAC/UN/EU sanctions + PEP screening, open-source, ships an MCP server | 🆓🆓 (self-host) |
| **[sanctions.network](https://sanctions.network/)** | Free, no-key JSON sanctions check against OFAC SDN, UN, EU lists | 🆓🆓 |
| **[OpenSanctions](https://www.opensanctions.org/api/)** | 401 aggregated sanctions/PEP sources, free for non-commercial use | 🆓🔑 |
| **[OFAC Sanctions List Search](https://ofac.treasury.gov/sanctions-list-search-tool)** 🏛 | The official US Treasury source everyone else wraps | 🆓🆓 |

---

## 6. ⚖️ Legal, Patents & Court Data

| API | What it does | Access |
|---|---|---|
| **[CourtListener](https://www.courtlistener.com/help/api/rest/)** 🏛 | 9M+ US case law opinions, PACER/RECAP dockets, oral arguments, judge bios; ships an MCP server | 🆓🔑 |
| **[USPTO PatentsView](https://patentsview.org/apis/purpose)** 🏛 | Full-text US patent search and citation graph, completely free | 🆓🆓 |
| **[USPTO Trademark Status API (TSDR)](https://tsdr.uspto.gov/#caseNumber=)** 🏛 | Free US trademark status and document retrieval | 🆓🆓 |
| **[EPO Open Patent Services (OPS)](https://www.epo.org/en/searching-for-patents/data/web-services/ops)** 🏛🌍 | European Patent Office's free global patent search API | 🆓🔑 |
| **[Regulations.gov API](https://open.gsa.gov/api/regulationsgov/)** 🏛 | Search and pull US federal regulatory dockets and public comments | 🆓🔑 |

---

## 7. 🚚 Delivery, Logistics & Shipment Tracking

| API | What it does | Access |
|---|---|---|
| **[Shiprocket API](https://apidocs.shiprocket.in/)** 🇮🇳 | Full order-to-delivery lifecycle: rates, label generation, pickup scheduling, live AWB tracking across 20+ Indian couriers; also has an MCP server | 🆓🔑 |
| **[Ship24 Tracking API](https://www.ship24.com/tracking-api)** 🌍 | Universal tracking across 1,500+ couriers worldwide (auto-detects the courier from the tracking number) | 🆓🔑 |
| **[ClickPost](https://www.clickpost.ai/)** 🇮🇳🌍 | Direct API integration with 400+ courier partners, GPS route optimization, partial-shipment tracking | 🔑💳 |
| **[Shippo](https://goshippo.com/)** 🌍 | Aggregator for 85+ global carriers (USPS, UPS, DHL, FedEx) with pre-negotiated rates and customs docs | 🆓🔑 |
| **[EasyPost](https://www.easypost.com/)** 🌍 | Similar multi-carrier rate-shopping and label API, popular with US-based e-commerce | 🆓🔑 |
| **[AfterShip Tracking API](https://www.aftership.com/docs/api)** 🌍 | Tracking-page-as-a-service across 1,000+ couriers, branded tracking pages | 🆓🔑 |
| **[India Post Track & Trace](https://www.indiapost.gov.in/)** 🏛🇮🇳 | Official (unofficial-API-wrapped) tracking for India Post/Speed Post consignments | 🆓 (via wrappers) |
| **[Delhivery One API](https://www.delhivery.com/)** 🇮🇳 | Direct integration with one of India's largest last-mile carriers, if you don't want an aggregator layer | 🔑💳 |
| **[Shipway](https://www.shipway.com/)** 🇮🇳 | Post-purchase experience + tracking API, branded tracking pages, NDR automation | 🔑💳 |
| **[FedEx Web Services / UPS Developer Kit / USPS Web Tools](https://developer.fedex.com/)** 🌍 | Direct carrier APIs if you want to skip aggregators entirely — each offers a free developer sandbox | 🆓🔑 |

---

## 8. 📍 Address, Pincode & Geocoding

| API | What it does | Access |
|---|---|---|
| **[India Post Pincode API](https://api.postalpincode.in/)** 🏛🇮🇳 | Free, no-key lookup of any Indian PIN code → post office, district, state | 🆓🆓 |
| **[Nominatim (OpenStreetMap)](https://nominatim.org/release-docs/latest/api/Overview/)** 🌍 | Free geocoding/reverse-geocoding built on OSM data — no key for light usage | 🆓🆓 |
| **[Zippopotam.us](https://www.zippopotam.us/)** 🌍 | Dead-simple free postal-code-to-place lookup for 60+ countries | 🆓🆓 |
| **[GeoNames](https://www.geonames.org/export/web-services.html)** 🌍 | Massive free geographical database — places, timezones, population, elevation | 🆓🆓 |
| **[Smarty (SmartyStreets)](https://www.smarty.com/)** 🌍 | US/international address validation & autocomplete, generous free tier | 🆓🔑 |
| **[Loqate](https://www.loqate.com/)** 🌍 | Global address verification, popular for checkout-form autocomplete | 🔑💳 |
| **[Google Address Validation API](https://developers.google.com/maps/documentation/address-validation)** 🌍 | Google's own address-validation product, separate from standard Maps/Places | 🔑💳 |
| **[data.gov.in Village/District Codes](https://data.gov.in/)** 🏛🇮🇳 | Official open dataset of Indian administrative boundaries and codes | 🆓🆓 |

---

## 9. ✉️ Email & Phone Verification

| API | What it does | Access |
|---|---|---|
| **[Abstract API — Email Validation](https://www.abstractapi.com/api/email-verification-validation-api)** 🌍 | Checks deliverability, catches disposable/temp emails, free tier | 🆓🔑 |
| **[ZeroBounce](https://www.zerobounce.net/)** 🌍 | Email validation + deliverability scoring, free monthly credits | 🆓🔑 |
| **[Hunter.io](https://hunter.io/api-documentation/v2)** 🌍 | Finds and verifies professional email addresses by domain | 🆓🔑 |
| **[NeverBounce](https://neverbounce.com/)** 🌍 | Bulk email list cleaning API | 🆓🔑 |
| **[Numverify](https://numverify.com/)** 🌍 | Phone number validation — carrier, line type, country — free tier | 🆓🔑 |
| **[Twilio Lookup API](https://www.twilio.com/docs/lookup)** 🌍 | Phone number validation plus carrier/line-type and (paid) caller-name lookup | 🆓🔑 |
| **[Abstract API — Phone Validation](https://www.abstractapi.com/api/phone-validation-api)** 🌍 | Similar to Numverify, free tier available | 🆓🔑 |
| **[MSG91 Verify (OTP + number check)](https://msg91.com/)** 🇮🇳 | Popular Indian OTP/verification provider, often bundled with SMS | 🔑💳 |

---

## 10. 🌐 Domain, WHOIS, DNS & Security

| API | What it does | Access |
|---|---|---|
| **[WhoisXML API](https://whoisxmlapi.com/)** 🌍 | WHOIS lookup, domain age, DNS records, brand/typosquat monitoring | 🆓🔑 |
| **[IP2WHOIS](https://www.ip2location.io/ip2whois)** 🌍 | Simple WHOIS lookup API with a modest free tier | 🆓🔑 |
| **[SecurityTrails](https://securitytrails.com/)** 🌍 | Historical DNS, subdomain enumeration, WHOIS — popular with security researchers | 🆓🔑 |
| **[Have I Been Pwned API](https://haveibeenpwned.com/API/v3)** 🌍 | Checks whether an email/domain appears in known data breaches | 🆓🔑 |
| **[Google Safe Browsing API](https://developers.google.com/safe-browsing)** 🌍 | Free API to check if a URL is flagged as malware/phishing | 🆓🔑 |
| **[VirusTotal API](https://docs.virustotal.com/reference/overview)** 🌍 | Scan files/URLs/domains against 70+ antivirus engines, free tier for personal use | 🆓🔑 |
| **[Cloudflare DNS over HTTPS](https://developers.cloudflare.com/1.1.1.1/dns-over-https/)** 🌍 | Free public DNS-over-HTTPS resolver API — good for privacy-respecting lookups | 🆓🆓 |

---

## 11. 🛰️ IP Geolocation & Network Info

| API | What it does | Access |
|---|---|---|
| **[ipinfo.io](https://ipinfo.io/developers)** 🌍 | IP → city, region, ISP, timezone; generous free tier | 🆓🔑 |
| **[ip-api.com](https://ip-api.com/)** 🌍 | Free (non-commercial) IP geolocation, no key required for basic use | 🆓🆓 |
| **[ipapi.co](https://ipapi.co/)** 🌍 | Similar IP geolocation, JSON/XML/CSV output | 🆓🔑 |
| **[ipify](https://www.ipify.org/)** 🌍 | Dead-simple "what's my IP" API, fully free | 🆓🆓 |
| **[MaxMind GeoLite2](https://dev.maxmind.com/geoip/geolite2-free-geoip-data)** 🌍 | Free downloadable IP geolocation database if you'd rather self-host than call an API | 🆓🆓 |
| **[AbuseIPDB](https://www.abuseipdb.com/api.html)** 🌍 | Check if an IP has been reported for abuse/spam — useful for basic fraud signals | 🆓🔑 |

---

## 12. 💱 Currency, Forex & Crypto

| API | What it does | Access |
|---|---|---|
| **[Frankfurter](https://www.frankfurter.app/)** 🌍 | Free, no-key exchange rate API sourced from the European Central Bank | 🆓🆓 |
| **[exchangerate.host](https://exchangerate.host/)** 🌍 | Free forex + historical rates, no key needed for basic use | 🆓🆓 |
| **[Open Exchange Rates](https://openexchangerates.org/)** 🌍 | Reliable forex data, free tier for hobby projects | 🆓🔑 |
| **[CoinGecko API](https://www.coingecko.com/en/api)** 🌍 | Crypto prices, market caps, historical data — one of the most generous free crypto APIs | 🆓🔑 |
| **[CoinCap API](https://docs.coincap.io/)** 🌍 | Real-time crypto pricing, fully free | 🆓🆓 |
| **[RBI Reference Rate](https://www.rbi.org.in/)** 🏛🇮🇳 | Official INR reference exchange rates from the Reserve Bank of India (via data.gov.in datasets) | 🆓🆓 |
| **[CurrencyLayer](https://currencylayer.com/)** 🌍 | Forex data with historical/time-series endpoints, free tier | 🆓🔑 |

---

## 13. 📈 Stocks & Financial Market Data

| API | What it does | Access |
|---|---|---|
| **[Alpha Vantage](https://www.alphavantage.co/)** 🌍 | Stocks, forex, crypto, technical indicators — generous free tier, most popular hobbyist choice | 🆓🔑 |
| **[Finnhub](https://finnhub.io/)** 🌍 | Real-time stock quotes, financials, earnings calendar, free tier | 🆓🔑 |
| **[Polygon.io](https://polygon.io/)** 🌍 | Institutional-grade market data, free tier with delayed data | 🆓🔑 |
| **[IEX Cloud](https://iexcloud.io/)** 🌍 | US equities data, historically the go-to free-tier option for hobby fintech projects | 🆓🔑 |
| **[NSE/BSE via NSEpy-style wrappers](https://www.nseindia.com/)** 🇮🇳 | Official Indian exchange data — no clean public REST API, but widely scraped/wrapped by open-source libraries | 🆓 (unofficial) |
| **[Yahoo Finance (unofficial)](https://pypi.org/project/yfinance/)** 🌍 | No official API, but the `yfinance` wrapper is the de facto standard for free historical stock data | 🆓🆓 (unofficial) |

---

## 14. 🌦️ Weather, Air Quality & Disaster Alerts

| API | What it does | Access |
|---|---|---|
| **[Open-Meteo](https://open-meteo.com/)** 🌍 | Fully free, no-key weather forecast API — extremely generous for hobby projects | 🆓🆓 |
| **[WeatherAPI.com](https://www.weatherapi.com/)** 🌍 | Weather + air quality + astronomy data, free tier | 🆓🔑 |
| **[OpenAQ](https://openaq.org/)** 🌍 | Free open air-quality data aggregated from government monitors worldwide | 🆓🆓 |
| **[AQICN (World Air Quality Index)](https://aqicn.org/api/)** 🌍 | Real-time air quality index by city, free tier | 🆓🔑 |
| **[USGS Earthquake API](https://earthquake.usgs.gov/fdsnws/event/1/)** 🏛 | Free, real-time global earthquake feed — no key needed | 🆓🆓 |
| **[NASA EONET](https://eonet.gsfc.nasa.gov/docs/v3)** 🏛 | Free natural-event tracker (wildfires, storms, volcanic activity) | 🆓🆓 |
| **[Sunrise-Sunset.org](https://sunrise-sunset.org/api)** 🌍 | Free sunrise/sunset/twilight times by lat/long | 🆓🆓 |

---

## 15. 🏥 Healthcare & Medical Data

| API | What it does | Access |
|---|---|---|
| **[openFDA](https://open.fda.gov/apis/)** 🏛 | Free FDA drug, device, and adverse-event data | 🆓🆓 |
| **[NPI Registry (CMS)](https://npiregistry.cms.hhs.gov/registry/help-api)** 🏛 | Free lookup of every US healthcare provider by NPI number | 🆓🆓 |
| **[RxNorm API (NLM)](https://lhncbc.nlm.nih.gov/RxNav/APIs/RxNormAPIs.html)** 🏛 | Free standardized drug naming/normalization from the National Library of Medicine | 🆓🆓 |
| **[ICD-10 API (NLM Clinical Tables)](https://clinicaltables.nlm.nih.gov/)** 🏛 | Free ICD-10 diagnosis code lookup and autocomplete | 🆓🆓 |
| **[WHO Global Health Observatory API](https://www.who.int/data/gho/info/gho-odata-api)** 🏛🌍 | Free global public health statistics from the WHO | 🆓🆓 |
| **[Ayushman Bharat Digital Mission (ABDM) APIs](https://abdm.gov.in/)** 🏛🇮🇳 | India's official health-record interoperability APIs (sandbox available for registered developers) | 🆓🔑 |

---

## 16. 🏛️ Government, Open Data & Holidays

| API | What it does | Access |
|---|---|---|
| **[data.gov.in](https://data.gov.in/)** 🏛🇮🇳 | India's official open-data portal — thousands of government datasets with API access | 🆓🔑 |
| **[data.gov](https://api.data.gov/)** 🏛 | US federal open-data portal with a unified API key | 🆓🔑 |
| **[REST Countries](https://restcountries.com/)** 🌍 | Free, no-key data on every country — flags, currencies, capitals, borders | 🆓🆓 |
| **[Nager.Date](https://date.nager.at/)** 🌍 | Free public holiday API for 100+ countries, no key needed | 🆓🆓 |
| **[Calendarific](https://calendarific.com/)** 🌍 | Public holidays plus regional/religious observances, free tier | 🆓🔑 |
| **[US Census Bureau API](https://www.census.gov/data/developers/data-sets.html)** 🏛 | Free demographic, economic, and population data | 🆓🔑 |
| **[World Bank API](https://datahelpdesk.worldbank.org/knowledgebase/articles/889392)** 🏛🌍 | Free global economic/development indicators | 🆓🆓 |

---

## 17. 🗣️ Translation, Language & Dictionary

| API | What it does | Access |
|---|---|---|
| **[LibreTranslate](https://libretranslate.com/)** 🌍 | Fully open-source translation API, self-hostable, free public instance available | 🆓🔑 |
| **[DeepL API](https://www.deepl.com/pro-api)** 🌍 | High-quality translation, free tier (500k chars/month) | 🆓🔑 |
| **[Free Dictionary API](https://dictionaryapi.dev/)** 🌍 | Free English word definitions, phonetics, and audio pronunciation, no key | 🆓🆓 |
| **[Bhashini](https://bhashini.gov.in/)** 🏛🇮🇳 | Government of India's free AI translation/speech API for Indian languages | 🆓🔑 |
| **[Datamuse API](https://www.datamuse.com/api/)** 🌍 | Free word-finding API — rhymes, synonyms, related words | 🆓🆓 |

---

## 18. ⚽ Sports Data

| API | What it does | Access |
|---|---|---|
| **[TheSportsDB](https://www.thesportsdb.com/api.php)** 🌍 | Free multi-sport data — teams, players, events, badges | 🆓🔑 |
| **[balldontlie](https://www.balldontlie.io/)** 🌍 | Free NBA stats API, very popular for hobby dashboards | 🆓🆓 |
| **[football-data.org](https://www.football-data.org/)** 🌍 | Free tier for major football/soccer league fixtures and standings | 🆓🔑 |
| **[API-Football](https://www.api-football.com/)** 🌍 | Deep football data (900+ leagues), free tier via RapidAPI | 🆓🔑 |
| **[CricAPI](https://www.cricapi.com/)** 🇮🇳🌍 | Cricket scores, series info, player stats — free tier available | 🆓🔑 |
| **[Cricbuzz (unofficial via RapidAPI)](https://rapidapi.com/cricketapilive/api/cricbuzz-cricket)** 🇮🇳 | Live cricket scores and commentary, community-wrapped | 🆓🔑 |

---

## 19. ✈️ Flights, Travel & Transit

| API | What it does | Access |
|---|---|---|
| **[OpenSky Network](https://openskynetwork.github.io/opensky-api/)** 🌍 | Free real-time global flight tracking data from a crowdsourced ADS-B network | 🆓🆓 |
| **[AviationStack](https://aviationstack.com/)** 🌍 | Flight schedules, live tracking, airport data, free tier | 🆓🔑 |
| **[Amadeus for Developers](https://developers.amadeus.com/)** 🌍 | Flight search, hotel search, airport info — generous free sandbox tier | 🆓🔑 |
| **[TransitLand](https://www.transit.land/)** 🌍 | Free aggregated public transit (GTFS) data across thousands of agencies worldwide | 🆓🆓 |
| **[Indian Railways APIs (unofficial, e.g. IRCTC via RapidAPI)](https://rapidapi.com/IRCTCAPI/api/irctc1)** 🇮🇳 | PNR status, live train tracking, seat availability — community-wrapped, no official public API | 🆓🔑 |

---

## 20. 📰 News & Media

| API | What it does | Access |
|---|---|---|
| **[GNews](https://gnews.io/)** 🌍 | Free-tier news search/headlines API | 🆓🔑 |
| **[NewsData.io](https://newsdata.io/)** 🌍 | News aggregation with free tier, includes Indian regional sources | 🆓🔑 |
| **[Currents API](https://currentsapi.services/)** 🌍 | Free-tier news API with category/language filters | 🆓🔑 |
| **[The Guardian Open Platform](https://open-platform.theguardian.com/)** 🌍 | Fully free access to The Guardian's entire article archive | 🆓🔑 |
| **[NYTimes API](https://developer.nytimes.com/)** 🌍 | Free-tier access to NYT articles, book reviews, and archives | 🆓🔑 |

---

## 21. 🎵 Music, Podcast & Audio

| API | What it does | Access |
|---|---|---|
| **[iTunes Search API](https://performance-partners.apple.com/search-api)** 🌍 | Free, no-key search across Apple's entire music/podcast/app catalog | 🆓🆓 |
| **[Deezer API](https://developers.deezer.com/api)** 🌍 | Free access to track/artist/album metadata and 30-second previews | 🆓🔑 |
| **[Podcast Index API](https://podcastindex.org/)** 🌍 | Free, open podcast directory API — an open alternative to Apple's podcast data | 🆓🔑 |
| **[MusicBrainz](https://musicbrainz.org/doc/MusicBrainz_API)** 🌍 | Free, open-source music metadata database | 🆓🆓 |
| **[AudD Music Recognition API](https://audd.io/)** 🌍 | Shazam-style audio fingerprint recognition, free trial tier | 🆓🔑 |

---

## 22. 🖼️ Image & Video Processing

| API | What it does | Access |
|---|---|---|
| **[remove.bg](https://www.remove.bg/api)** 🌍 | Automatic background removal from images, free tier (limited resolution) | 🆓🔑 |
| **[Cloudinary](https://cloudinary.com/documentation)** 🌍 | Image/video upload, transformation, and optimization at the URL level, generous free tier | 🆓🔑 |
| **[imgix](https://www.imgix.com/)** 🌍 | Real-time image processing via URL parameters | 🔑💳 |
| **[Unsplash API](https://unsplash.com/developers)** 🌍 | Free stock photo search and download, attribution required | 🆓🔑 |
| **[Pexels API](https://www.pexels.com/api/)** 🌍 | Free stock photos and videos | 🆓🔑 |
| **[Pixabay API](https://pixabay.com/api/docs/)** 🌍 | Free stock images, illustrations, and video | 🆓🔑 |

---

## 23. 📄 PDF & Document Processing

| API | What it does | Access |
|---|---|---|
| **[PDF.co](https://pdf.co/)** 🌍 | PDF generation, parsing, merging, splitting, OCR — API-first, free tier | 🆓🔑 |
| **[DocRaptor](https://docraptor.com/)** 🌍 | HTML-to-PDF conversion, free tier for testing (adds watermark until paid) | 🆓🔑 |
| **[CloudConvert](https://cloudconvert.com/api/v2)** 🌍 | Convert between 200+ file formats (docs, images, audio, video), free monthly credits | 🆓🔑 |
| **[Adobe PDF Services API](https://developer.adobe.com/document-services/apis/pdf-services/)** 🌍 | Adobe's own PDF creation/extraction API, free tier | 🆓🔑 |
| **[Docparser](https://docparser.com/)** 🌍 | Extract structured data from PDFs/scanned docs, free trial | 🆓🔑 |

---

## 24. 🤖 AI/ML Niche APIs (Speech, OCR, Vision)

| API | What it does | Access |
|---|---|---|
| **[AssemblyAI](https://www.assemblyai.com/)** 🌍 | Speech-to-text + audio intelligence (summarization, sentiment), free tier | 🆓🔑 |
| **[Deepgram](https://deepgram.com/)** 🌍 | Fast speech-to-text API, generous free credits | 🆓🔑 |
| **[ElevenLabs](https://elevenlabs.io/)** 🌍 | Realistic text-to-speech and voice cloning, free tier | 🆓🔑 |
| **[OCR.space](https://ocr.space/ocrapi)** 🌍 | Free-tier OCR API, good for quick prototypes without cloud vendor lock-in | 🆓🔑 |
| **[Google Cloud Vision API](https://cloud.google.com/vision)** 🌍 | Label detection, OCR, face/landmark detection, free monthly quota | 🆓🔑 |
| **[Face++ (Face Detection API)](https://www.faceplusplus.com/)** 🌍 | Face detection, comparison, attribute analysis, free tier | 🆓🔑 |

---

## 25. 🕷️ Web Scraping & Proxy

| API | What it does | Access |
|---|---|---|
| **[ScraperAPI](https://www.scraperapi.com/)** 🌍 | Handles proxies/CAPTCHAs/headless browsers for scraping at scale, free trial credits | 🆓🔑 |
| **[ScrapingBee](https://www.scrapingbee.com/)** 🌍 | Similar managed scraping API with JS rendering, free trial | 🆓🔑 |
| **[Bright Data](https://brightdata.com/)** 🌍 | Enterprise-grade proxy network + scraping APIs | 🔑💳 |
| **[Webshare](https://www.webshare.io/)** 🌍 | Rotating proxy API, has a genuinely free tier (10 proxies) | 🆓🔑 |
| **[Microlink.io](https://microlink.io/)** 🌍 | Turns any URL into structured metadata + screenshot in one call | 🆓🔑 |

---

## 26. 🎉 Fun & Utility APIs

| API | What it does | Access |
|---|---|---|
| **[Open Trivia Database](https://opentdb.com/)** 🌍 | Free, no-key trivia question API across categories/difficulties | 🆓🆓 |
| **[Quotable](https://github.com/lukePeavey/quotable)** 🌍 | Free open-source quotes API | 🆓🆓 |
| **[ZenQuotes](https://zenquotes.io/)** 🌍 | Free daily-quote API | 🆓🆓 |
| **[JokeAPI](https://sv443.net/jokeapi/v2/)** 🌍 | Free jokes API with category/blacklist filtering | 🆓🆓 |
| **[icanhazdadjoke](https://icanhazdadjoke.com/api)** 🌍 | Free dad-jokes API, no key | 🆓🆓 |
| **[Numbers API](http://numbersapi.com/)** 🌍 | Free trivia about numbers, dates, and years | 🆓🆓 |
| **[QR Server API](https://goqr.me/api/)** 🌍 | Free, no-key QR code image generation via URL params | 🆓🆓 |
| **[QuickChart](https://quickchart.io/)** 🌍 | Free chart-image generation via URL — handy for emails/reports with no frontend | 🆓🔑 |

---

## 27. 🚗 Vehicle & Automotive (extended)

| API | What it does | Access |
|---|---|---|
| **[NHTSA vPIC](https://vpic.nhtsa.dot.gov/api/)** 🏛 | Free VIN decode, no key, no account needed | 🆓🆓 |
| **[CarAPI](https://carapi.app/)** 🌍 | VIN decode + full vehicle spec database, free dataset requiring no account | 🆓🔑 |
| **[NHTSA Recalls API](https://www.nhtsa.gov/nhtsa-datasets-and-apis)** 🏛 | Free official US vehicle recall lookup by make/model/year | 🆓🆓 |
| **[Fuel Economy API (fueleconomy.gov)](https://www.fueleconomy.gov/feg/ws/)** 🏛 | Free official US government fuel-economy data by vehicle | 🆓🆓 |

---

## 28. 📦 Barcode & Product Data (extended)

| API | What it does | Access |
|---|---|---|
| **[Go-UPC](https://go-upc.com/plans/api)** 🌍 | UPC/EAN/ISBN → product data, 500M+ products, strong international coverage | 🆓🔑 |
| **[UPCitemdb](https://www.upcitemdb.com/)** 🌍 | 495M+ products, trial tier | 🆓🔑💳 |
| **[Open Food Facts API](https://world.openfoodfacts.org/data)** 🌍 | Fully free, open-source barcode → nutrition/ingredients database, crowd-sourced | 🆓🆓 |
| **[Open Beauty Facts](https://world.openbeautyfacts.org/data)** 🌍 | Same model as Open Food Facts, for cosmetics/personal care products | 🆓🆓 |

---

## 29. 🖼️ Screenshot & Page Rendering (extended)

| API | What it does | Access |
|---|---|---|
| **[Thum.io](https://www.thum.io/)** 🌍 | Instant website screenshots, no API key or signup required at all | 🆓🆓 |
| **[ScreenshotOne](https://screenshotone.com/)** 🌍 | Full-page screenshots + HTML-to-PDF, deep parameter control, 100 free/month | 🆓🔑 |
| **[ApiFlash](https://apiflash.com/)** 🌍 | AWS Lambda–powered screenshot API, no credit card needed to start | 🆓🔑 |
| **[Urlbox](https://urlbox.io/)** 🌍 | Screenshot/PDF API popular for SaaS "share preview" features | 🆓🔑 |

---

## 30. 📱 Social Media & Community APIs

| API | What it does | Access |
|---|---|---|
| **[Xquik](https://github.com/Xquik-dev/x-twitter-scraper)** 🌍 | X/Twitter automation API for search, profile lookup, monitoring, REST, MCP, webhooks, SDKs, and gated actions | 🔑💳 |

---

## How to fold this into your repo structure

Split each numbered section above into its matching file in `categories/` (e.g. §7 → `logistics.md`, §3 → `tax-compliance.md`, §4 → `kyc-verification.md`). For each entry you promote to a full page, use the template from your original structure doc:

```md
# API Name
## Description
## Base URL
## Authentication
## Pricing
## Example
## Official Docs
```

**A note on accuracy:** APIs change pricing/free-tier limits often — worth adding a "last verified" date to each entry in your actual repo, and maybe a GitHub Action that pings each base URL monthly to flag dead links.
