# Watchpoint

> [!WARNING]
> Currently, this project is alpha.
> This is a work in progress project. It is not yet ready for production use.

This is a [Plasmo extension](https://docs.plasmo.com/) project bootstrapped with [`plasmo init`](https://www.npmjs.com/package/plasmo).

## Development

First, run the development server:

```bash
pnpm dev
```

### Making production build

Run the following:

```bash
pnpm build
```

This should create a production bundle for your extension, ready to be zipped and published to the stores.

#### Components

- [x] Card component (for all data)
- [ ] Card component (for each data)
- [ ] Table component (for all data)
- [ ] Table component (for each data)
- [ ] Tabs component
- [ ] Datalization component
- [ ] Plus button component
- [ ] Settings component
- [ ] Admin info component
- [ ] QA component
- [ ] About component
- [ ] Request & Bug Report Form component
- [ ] User Guide component
- [ ] Privacy Policy component
- [ ] Terms of Service component
- [ ] License component
- [ ] Resources component

#### get json data

<!--
- [Social Media Tools](#social-media-tools)
  - [Twitter](#-twitter)
  - [Facebook](#-facebook)
  - [Instagram](#-instagram)
  - [Pinterest](#-pinterest)
  - [Reddit](#-reddit)
  - [VKontakte](#-vkontakte)
  - [Tumblr](#-tumblr)
  - [LinkedIn](#-linkedin)
  - [Telegram](#-telegram)
- [Blog Search](#-blog-search)
- [Forums and Discussion Boards Search](#-forums-and-discussion-boards-search)
- [Username Check](#-username-check)
- [People Investigations](#-people-investigations)
- [E-mail Search / E-mail Check](#-e-mail-search--e-mail-check)
- [Phone Number Research](#-phone-number-research)
- [Expert Search](#-expert-search)
- [Company Research](#-company-research)
- [Job Search Resources](#-job-search-resources)
- [Q&A Sites](#-qa-sites)
- [Domain and IP Research](#-domain-and-ip-research)
- [Keywords Discovery and Research](#-keywords-discovery-and-research)
- [Web History and Website Capture](#-web-history-and-website-capture)
- [Language Tools](#-language-tools)
- [Image Search](#-image-search)
- [Image Analysis](#-image-analysis)
- [Video Search and Other Video Tools](#-video-search-and-other-video-tools)
- [Academic Resources and Grey Literature](#-academic-resources-and-grey-literature)
- [Geospatial Research and Mapping Tools](#-geospatial-research-and-mapping-tools)
- [News](#-news)
- [News Digest and Discovery Tools](#-news-digest-and-discovery-tools)
- [Fact Checking](#-fact-checking)
- [Data and Statistics](#-data-and-statistics)
- [Web Monitoring](#-web-monitoring)
- [Browsers](#-browsers)
- [Offline Browsing](#-offline-browsing)
- [VPN Services](#-vpn-services)
- [Infographics and Data Visualization](#-infographics-and-data-visualization)
- [Social Network Analysis](#-social-network-analysis)
- [Privacy and Encryption Tools](#-privacy-and-encryption-tools)
- [DNS](#-dns)
- [Maritime](#-maritime)
- [Other Tools](#-other-tools)
- [Threat Intelligence](#-threat-intelligence)
- [OSINT Videos](#-osint-videos)
- [OSINT Blogs](#-osint-blogs)
- [Other Resources](#-other-resources)
- [Related Awesome Lists](#-related-awesome-lists) -->

- [x] getAllLinks
- [ ] Social Media Tools
  - [ ] getFacebook
  - [ ] getInstagram
  - [ ] getLinkedin
  - [ ] getPinterest
  - [ ] getReddit
  - [ ] getTelegram
  - [ ] getTumblr
  - [ ] getTwitter
  - [ ] getVKontakte
- [ ] getBlogSearch
- [ ] getForumsAndDiscussionBoardsSearch
- [ ] getUsernameCheck
- [ ] getPeopleInvestigations
- [ ] getEmailSearch
- [ ] getPhoneResearch
- [ ] getExpertSearch
- [ ] getCompanyResearch
- [ ] getJobSearchResources
- [ ] getQASites
- [ ] getDomainAndIPResearch
- [ ] getKeywordsDiscoveryAndResearch
- [ ] getWebHistoryAndWebsiteCapture
- [ ] getLanguageTools
- [ ] getImageSearch
- [ ] getImageAnalysis
- [ ] getVideoSearchAndOtherVideoTools
- [ ] getAcademicResourcesAndGreyLiterature
- [ ] getGeospatialResearchAndMappingTools
- [ ] getNews
- [ ] getNewsDigestAndDiscoveryTools
- [ ] getFactChecking
- [ ] getDataAndStatistics
- [ ] getWebMonitoring
- [ ] getBrowsers
- [ ] getOfflineBrowsing
- [ ] getVPNServices
- [ ] getInfographicsAndDataVisualization
- [ ] getSocialNetworkAnalysis
- [ ] getPrivacyAndEncryptionTools
- [ ] getDNS
- [ ] getMaritime
- [ ] getOtherTools
- [ ] getThreatIntelligence
- [ ] getOSINTVideos
- [ ] getOSINTBlogs
- [ ] getOtherResources
- [ ] getRelatedAwesomeLists
- [ ] getAdmin

### Submit to the webstores

The easiest way to deploy your Plasmo extension is to use the built-in [bpp](https://bpp.browser.market) GitHub action. Prior to using this action however, make sure to build your extension and upload the first version to the store to establish the basic credentials. Then, simply follow [this setup instruction](https://docs.plasmo.com/framework/workflows/submit) and you should be on your way for automated submission!

## Resources

- https://github.com/jivoi/awesome-osint/blob/master/README.md
  - for categorization
