<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "b96f2864e0bcb6fae9b4926813c3feb1",
  "translation_date": "2025-06-26T13:52:05+00:00",
  "source_file": "05-AdvancedTopics/README.md",
  "language_code": "ne"
}
-->
# MCP मा उन्नत विषयहरू

यो अध्याय Model Context Protocol (MCP) कार्यान्वयनमा उन्नत विषयहरू समेट्नको लागि तयार गरिएको हो, जसमा बहु-मोडल एकीकरण, स्केलेबिलिटी, सुरक्षा उत्तम अभ्यासहरू, र एन्त्रप्राइज एकीकरण समावेश छन्। यी विषयहरू आधुनिक AI प्रणालीहरूको माग पूरा गर्न सक्षम, बलियो र उत्पादन-तयार MCP अनुप्रयोगहरू निर्माण गर्न अत्यावश्यक छन्।

## अवलोकन

यो पाठले Model Context Protocol कार्यान्वयनमा उन्नत अवधारणाहरूको अन्वेषण गर्छ, विशेष गरी बहु-मोडल एकीकरण, स्केलेबिलिटी, सुरक्षा उत्तम अभ्यासहरू, र एन्त्रप्राइज एकीकरणमा केन्द्रित। यी विषयहरू जटिल आवश्यकताहरूलाई सम्हाल्न सक्ने उत्पादन-स्तरका MCP अनुप्रयोगहरू निर्माण गर्न आवश्यक छन्।

## सिकाइ उद्देश्यहरू

यस पाठको अन्त्यसम्म, तपाईं सक्षम हुनुहुनेछ:

- MCP फ्रेमवर्कहरूमा बहु-मोडल क्षमताहरू कार्यान्वयन गर्न
- उच्च मागका परिदृश्यहरूका लागि स्केलेबल MCP वास्तुकला डिजाइन गर्न
- MCP को सुरक्षा सिद्धान्तहरूसँग मेल खाने सुरक्षा उत्तम अभ्यासहरू लागू गर्न
- MCP लाई एन्त्रप्राइज AI प्रणालीहरू र फ्रेमवर्कहरूसँग एकीकृत गर्न
- उत्पादन वातावरणहरूमा प्रदर्शन र विश्वसनीयता अनुकूलन गर्न

## पाठहरू र नमूना परियोजनाहरू

| लिंक | शीर्षक | विवरण |
|------|-------|-------------|
| [5.1 Integration with Azure](./mcp-integration/README.md) | Azure सँग एकीकरण | Azure मा तपाईंको MCP Server कसरी एकीकृत गर्ने जान्नुहोस् |
| [5.2 Multi modal sample](./mcp-multi-modality/README.md) | MCP बहु-मोडल नमूनाहरू | अडियो, छवि र बहु-मोडल प्रतिक्रियाका नमूनाहरू |
| [5.3 MCP OAuth2 sample](../../../05-AdvancedTopics/mcp-oauth2-demo) | MCP OAuth2 डेमो | OAuth2 सँग MCP को न्यूनतम Spring Boot एप, जसले Authorization र Resource Server दुवैको रूपमा काम गर्छ। सुरक्षित टोकन जारी गर्ने, संरक्षित endpoints, Azure Container Apps मा डिप्लोयमेन्ट, र API व्यवस्थापन एकीकरण देखाउँछ। |
| [5.4 Root Contexts](./mcp-root-contexts/README.md) | Root contexts | Root context बारे थप जान्नुहोस् र तिनीहरू कसरी कार्यान्वयन गर्ने |
| [5.5 Routing](./mcp-routing/README.md) | Routing | विभिन्न प्रकारका routing सिक्नुहोस् |
| [5.6 Sampling](./mcp-sampling/README.md) | Sampling | Sampling कसरी काम गर्ने जान्नुहोस् |
| [5.7 Scaling](./mcp-scaling/README.md) | Scaling | Scaling बारे जान्नुहोस् |
| [5.8 Security](./mcp-security/README.md) | Security | तपाईंको MCP Server लाई सुरक्षित बनाउनुहोस् |
| [5.9 Web Search sample](./web-search-mcp/README.md) | Web Search MCP | Python MCP server र client जसले SerpAPI सँग एकीकृत गरेर वास्तविक-समय वेब, समाचार, उत्पादन खोज, र Q&A प्रदान गर्छ। बहु-उपकरण समन्वय, बाह्य API एकीकरण, र बलियो त्रुटि ह्यान्डलिंग देखाउँछ। |
| [5.10 Realtime Streaming](./mcp-realtimestreaming/README.md) | Streaming | वास्तविक-समय डाटा स्ट्रिमिङ आजको डाटा-चालित संसारमा अत्यावश्यक भएको छ, जहाँ व्यवसाय र अनुप्रयोगहरूले तत्काल जानकारीको पहुँच चाहिन्छ छिटो निर्णय लिन। |
| [5.11 Realtime Web Search](./mcp-realtimesearch/README.md) | Web Search | वास्तविक-समय वेब खोज कसरी MCP ले AI मोडेलहरू, खोज इन्जिनहरू, र अनुप्रयोगहरूमा सन्दर्भ व्यवस्थापनको लागि मानकीकृत दृष्टिकोण प्रदान गरेर वेब खोजलाई रूपान्तरण गर्छ। |
| [5.12  Entra ID Authentication for Model Context Protocol Servers](./mcp-security-entra/README.md) | Entra ID Authentication | Microsoft Entra ID एक बलियो क्लाउड-आधारित पहिचान र पहुँच व्यवस्थापन समाधान हो, जसले सुनिश्चित गर्छ कि केवल अधिकृत प्रयोगकर्ता र अनुप्रयोगहरूले तपाईंको MCP server सँग अन्तरक्रिया गर्न सक्छन्। |

## थप सन्दर्भहरू

उन्नत MCP विषयहरूमा सबैभन्दा नयाँ जानकारीका लागि, हेर्नुहोस्:
- [MCP Documentation](https://modelcontextprotocol.io/)
- [MCP Specification](https://spec.modelcontextprotocol.io/)
- [GitHub Repository](https://github.com/modelcontextprotocol)

## मुख्य सिकाइ बुँदाहरू

- बहु-मोडल MCP कार्यान्वयनहरूले AI क्षमताहरूलाई पाठ प्रशोधनभन्दा बाहिर विस्तार गर्छन्
- स्केलेबिलिटी एन्त्रप्राइज डिप्लोयमेन्टका लागि आवश्यक छ र यसलाई तेर्सो र उर्ध्वाधर स्केलिङ मार्फत सम्बोधन गर्न सकिन्छ
- व्यापक सुरक्षा उपायहरूले डाटा सुरक्षित राख्छन् र उचित पहुँच नियन्त्रण सुनिश्चित गर्छन्
- Azure OpenAI र Microsoft AI Foundry जस्ता प्लेटफर्महरूसँग एन्त्रप्राइज एकीकरणले MCP क्षमताहरूलाई बढावा दिन्छ
- उन्नत MCP कार्यान्वयनहरूले अनुकूलित वास्तुकला र सावधानीपूर्वक स्रोत व्यवस्थापनबाट लाभ उठाउँछन्

## अभ्यास

विशिष्ट प्रयोग केसका लागि एन्त्रप्राइज-स्तरको MCP कार्यान्वयन डिजाइन गर्नुहोस्:

1. तपाईंको प्रयोग केसका लागि बहु-मोडल आवश्यकताहरू पहिचान गर्नुहोस्
2. संवेदनशील डाटा संरक्षणका लागि आवश्यक सुरक्षा नियन्त्रणहरूको रूपरेखा बनाउनुहोस्
3. फरक-फरक लोड सम्हाल्न सक्ने स्केलेबल वास्तुकला डिजाइन गर्नुहोस्
4. एन्त्रप्राइज AI प्रणालीहरूसँग एकीकरणका बिन्दुहरूको योजना बनाउनुहोस्
5. सम्भावित प्रदर्शन अवरोधहरू र समाधान रणनीतिहरू दस्तावेज गर्नुहोस्

## थप स्रोतहरू

- [Azure OpenAI Documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/)
- [Microsoft AI Foundry Documentation](https://learn.microsoft.com/en-us/ai-services/)

---

## अब के

- [5.1 MCP Integration](./mcp-integration/README.md)

**अस्वीकरण**:  
यो दस्तावेज AI अनुवाद सेवा [Co-op Translator](https://github.com/Azure/co-op-translator) प्रयोग गरी अनुवाद गरिएको हो। हामी शुद्धताको प्रयास गर्छौं, तर कृपया ध्यान दिनुहोस् कि स्वचालित अनुवादमा त्रुटि वा अशुद्धता हुनसक्छ। मूल दस्तावेज यसको मूल भाषामा आधिकारिक स्रोत मानिनुपर्छ। महत्वपूर्ण जानकारीको लागि व्यावसायिक मानव अनुवाद सिफारिस गरिन्छ। यस अनुवादको प्रयोगबाट उत्पन्न हुने कुनै पनि गलतफहमी वा गलत व्याख्याको लागि हामी जिम्मेवार छैनौं।