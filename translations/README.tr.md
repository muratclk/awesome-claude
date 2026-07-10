# Awesome Claude [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Anthropic'in Claude'u için en iyi kaynakların derlenmiş listesi - modeller, uygulamalar, Claude Code, Model Context Protocol, SDK'lar, araçlar ve öğrenme materyalleri.

Claude, Anthropic tarafından geliştirilen; yardımsever, dürüst ve zararsız olacak şekilde tasarlanmış bir yapay zeka modelleri ve ürünleri ailesidir. Bu liste, Claude'u *kullanmak* ve onunla *geliştirme yapmak* için yüksek değerli kaynakları bir araya getirir. Her şey elle seçilmiştir ve her bağlantı kontrol edilmiştir - ölü bağlantı yok, dolgu yok.

**Diğer dillerde oku:** [English](../README.md) · **Türkçe** · [kendi dilini ekle »](../.github/CONTRIBUTING.md#translations)

## İçindekiler

- [Resmi](#resmi)
- [Claude Code](#claude-code)
- [Model Context Protocol (MCP)](#model-context-protocol-mcp)
- [SDK'lar ve Kütüphaneler](#sdklar-ve-kütüphaneler)
- [Yapay Zeka Kodlama Araçları](#yapay-zeka-kodlama-araçları)
- [Sohbet Arayüzleri ve Uygulamalar](#sohbet-arayüzleri-ve-uygulamalar)
- [Dikkate Değer Açık Kaynak Projeler](#dikkate-değer-açık-kaynak-projeler)
- [Öğrenme ve Prompt](#öğrenme-ve-prompt)
- [Kıyaslamalar ve Liderlik Tabloları](#kıyaslamalar-ve-liderlik-tabloları)

## Resmi

### Siteler ve Dokümanlar

- [claude.ai](https://claude.ai) - Sohbet, Projeler ve Artifacts için Claude'un web uygulaması.
- [Anthropic.com](https://www.anthropic.com) - Anthropic'in kurumsal sitesi: araştırma, haberler, güvenlik ve duyurular.
- [Claude.com](https://claude.com) - Claude uygulamaları, planlar ve platform ürünleri için ürün merkezi.
- [Claude Platform Dokümanları](https://platform.claude.com/docs) - Claude ile geliştirme için resmi geliştirici ve API dokümantasyonu.
- [API Referansı](https://platform.claude.com/docs/en/api/overview) - Messages, Batches, Models ve Agents API'leri için uç nokta referansı.
- [Claude Console](https://platform.claude.com) - Workbench, API anahtarları, çalışma alanları ve kullanım limitleriyle geliştirici konsolu.
- [Claude Status](https://status.claude.com) - API, Console ve Claude Code için canlı çalışma süresi ve olay durumu.
- [Planlar ve Fiyatlandırma](https://claude.com/pricing) - Free, Pro, Max, Team ve Enterprise genelinde tüketici ve API fiyatlandırması.
- [Güven Merkezi](https://trust.anthropic.com) - Güvenlik duruşu, uyumluluk (SOC 2, ISO 27001/42001, HIPAA, GDPR) ve politikalar.
- [Yardım Merkezi](https://support.claude.com) - Claude uygulamaları, hesaplar ve özellikler için resmi destek makaleleri.

### Modeller

- [Model genel bakışı ve karşılaştırma](https://platform.claude.com/docs/en/about-claude/models/overview) - Tüm güncel Claude modelleri için özellikler, model kimlikleri, fiyatlar ve bağlam pencereleri.
- [Claude Fable 5 ve Mythos 5 Tanıtımı](https://platform.claude.com/docs/en/about-claude/models/introducing-claude-fable-5-and-claude-mythos-5) - Anthropic'in Mythos sınıfı sınır modellerine dair lansman detayları.
- [Claude Sonnet 5 Tanıtımı](https://www.anthropic.com/news/claude-sonnet-5) - Anthropic'in en agentic Sonnet katmanı modelinin duyurusu.
- [Fiyatlandırma dokümanları](https://platform.claude.com/docs/en/about-claude/pricing) - Toplu iş indirimleri ve prompt önbellekleme oranları dâhil tam API fiyatlandırması.
- [Sürüm notları](https://platform.claude.com/docs/en/release-notes/overview) - Claude API, SDK'lar ve Console için değişiklik günlüğü.
- [Model kullanımdan kaldırmaları](https://platform.claude.com/docs/en/about-claude/model-deprecations) - Eski modeller için emeklilik takvimi ve geçiş rehberi.
- [Şeffaflık Merkezi](https://www.anthropic.com/transparency) - Model ve sistem kartları, bilgi kesim tarihleri ve güvenlik raporlaması.

### Uygulamalar ve Ürünler

- [Claude'u İndir](https://claude.com/download) - Masaüstü (macOS/Windows/Linux) ve mobil (iOS/Android) uygulama indirmeleri.
- [Claude for Chrome](https://claude.com/claude-for-chrome) - Claude'un siteleri okumasını, tıklamasını ve gezinmesini sağlayan resmi tarayıcı uzantısı.
- [Claude Enterprise](https://www.anthropic.com/product/enterprise) - SSO, SCIM, denetim günlükleri ve genişletilmiş bağlam ile yönetim kontrolleri içeren kurumsal plan.
- [Artifacts](https://www.anthropic.com/news/claude-powered-artifacts) - Doğrudan Claude içinde etkileşimli yapay zeka destekli uygulamalar oluştur, barındır ve paylaş.
- [Projeler](https://support.claude.com/en/articles/9517075-what-are-projects) - Kendine ait sohbet geçmişi ve bilgi tabanı olan bağımsız çalışma alanları.

## Claude Code

[Claude Code](https://claude.com/product/claude-code), Anthropic'in terminal, IDE ve masaüstü için agentic kodlama aracıdır.

### Çekirdek

- [anthropics/claude-code](https://github.com/anthropics/claude-code) - Anthropic'in terminalde çalışan agentic kodlama aracı Claude Code'un resmi deposu.
- [Claude Code Dokümantasyonu](https://code.claude.com/docs) - Kurulum, ayarlar, slash komutları, hook'lar, subagent'lar, eklentiler ve MCP'yi kapsayan resmi dokümanlar.
- [Claude Agent SDK (TypeScript)](https://github.com/anthropics/claude-agent-sdk-typescript) - Claude Code'un agent döngüsünü, araçlarını ve bağlam yönetimini açığa çıkaran resmi SDK.
- [Claude Agent SDK (Python)](https://github.com/anthropics/claude-agent-sdk-python) - Claude Code'u çalıştıran altyapı üzerinde agent geliştirmek için resmi Python SDK'sı.
- [Agent SDK Genel Bakış](https://code.claude.com/docs/en/agent-sdk/overview) - Claude Agent SDK ile programatik olarak agent geliştirmeye dair resmi rehber.
- [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) - Anthropic tarafından yönetilen, yüksek kaliteli resmi Claude Code eklentileri dizini.
- [Eklenti Pazaryerleri Dokümanları](https://code.claude.com/docs/en/plugin-marketplaces) - Claude Code eklenti pazaryerleri oluşturma ve dağıtma için resmi referans.
- [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action) - PR ve issue'larda `@claude` etiketiyle Claude Code çalıştıran resmi GitHub Action.

### Awesome Listeler ve Derlemeler

- [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) - Claude Code kaynaklarının amiral gemisi listesi: skill'ler, agent'lar, statusline'lar, araçlar ve eklentiler.
- [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) - Claude Code iş akışlarını özelleştirmek için büyük Claude Skills, kaynak ve araç derlemesi.
- [karanb192/awesome-claude-skills](https://github.com/karanb192/awesome-claude-skills) - TDD, hata ayıklama, Git ve dokümanlar için doğrulanmış Claude Skills topluluk derlemesi.
- [subinium/awesome-claude-code](https://github.com/subinium/awesome-claude-code) - Yüksek dahil edilme çıtası olan, Claude Code için araç, skill, eklenti ve MCP sunucusu listesi.

### Subagent'lar, Skill'ler ve Eklentiler

- [anthropics/skills](https://github.com/anthropics/skills) - Yaratıcı, geliştirme ve kurumsal görevler için `SKILL.md` klasörlü örnek Agent Skills resmi deposu.
- [wshobson/agents](https://github.com/wshobson/agents) - Claude Code için üretime hazır subagent, skill ve komut pazaryeri.
- [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) - Geliştirme kategorileri genelinde uzmanlaşmış Claude Code subagent derlemesi.
- [0xfurai/claude-code-subagents](https://github.com/0xfurai/claude-code-subagents) - Markdown dosyaları hâlinde üretime hazır geliştirme subagent'larının kapsamlı derlemesi.

### Hook'lar, Komutlar ve Yapılandırmalar

- [disler/claude-code-hooks-mastery](https://github.com/disler/claude-code-hooks-mastery) - Her Claude Code hook yaşam döngüsü olayını ileri düzey desenlerle gösteren referans proje.
- [wshobson/commands](https://github.com/wshobson/commands) - Claude Code için üretime hazır slash komutları (iş akışları ve tek amaçlı araçlar) derlemesi.
- [qdhenry/Claude-Command-Suite](https://github.com/qdhenry/Claude-Command-Suite) - Yapılandırılmış yazılım geliştirme iş akışları için slash komutları, agent ve skill takımı.
- [sirmalloc/ccstatusline](https://github.com/sirmalloc/ccstatusline) - Powerline desteği, temalar ve kullanım widget'ları olan yüksek düzeyde özelleştirilebilir Claude Code statusline'ı.
- [ryoppippi/ccusage](https://github.com/ryoppippi/ccusage) - Yerel JSONL günlüklerinden Claude Code kullanımını ve maliyetini analiz eden, statusline entegrasyonlu CLI.

### IDE ve Editör Entegrasyonları

- [VS Code'da Claude Code](https://code.claude.com/docs/en/vs-code) - Yerleşik sohbet paneli, checkpoint'ler, @-etiketleme ve diff görüntüleme sunan resmi VS Code uzantısı.
- [JetBrains için Claude Code](https://plugins.jetbrains.com/plugin/27310-claude-code-beta-) - IntelliJ, PyCharm, WebStorm ve diğerleri için resmi JetBrains eklentisi.
- [coder/claudecode.nvim](https://github.com/coder/claudecode.nvim) - Resmi Claude Code IDE entegrasyonlarıyla protokol uyumlu, saf Lua Neovim uzantısı.

## Model Context Protocol (MCP)

Model Context Protocol, yapay zeka uygulamalarını harici araçlara ve verilere bağlamak için Anthropic tarafından oluşturulan açık bir standarttır.

### Çekirdek

- [Model Context Protocol](https://modelcontextprotocol.io) - MCP için kanonik dokümantasyon, rehberler ve spesifikasyon merkezi.
- [MCP Tanıtımı](https://www.anthropic.com/news/model-context-protocol) - Anthropic'in açık protokolü tanıtan orijinal yazısı.
- [modelcontextprotocol/modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol) - Resmi spesifikasyon ve dokümantasyon kaynak deposu.
- [MCP Spesifikasyonu](https://modelcontextprotocol.io/specification/2025-11-25) - Resmi protokol spesifikasyonu (en son sürüm).
- [Python SDK](https://github.com/modelcontextprotocol/python-sdk) - MCP sunucuları ve istemcileri geliştirmek için resmi Python SDK'sı.
- [TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - MCP sunucuları ve istemcileri için resmi TypeScript SDK'sı.
- [Go SDK](https://github.com/modelcontextprotocol/go-sdk) - MCP için resmi Go SDK'sı.
- [C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) - Microsoft ile birlikte sürdürülen resmi C# SDK'sı.
- [Kotlin SDK](https://github.com/modelcontextprotocol/kotlin-sdk) - MCP için resmi Kotlin SDK'sı.
- [Ruby SDK](https://github.com/modelcontextprotocol/ruby-sdk) - MCP için resmi Ruby SDK'sı.
- [Rust SDK](https://github.com/modelcontextprotocol/rust-sdk) - MCP için resmi Rust SDK'sı.

### Kayıt Defterleri ve Dizinler

- [Resmi MCP Registry](https://registry.modelcontextprotocol.io) - Herkese açık MCP sunucularını keşfetmek için resmi merkezi kayıt defteri/API.
- [modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry) - Topluluk odaklı resmi kayıt defteri hizmetinin kaynağı.
- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - MCP sunucularının en popüler topluluk derlemesi listesi.
- [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers) - Üretim ve deneysel MCP sunucularının büyük derlenmiş kataloğu.
- [wong2/awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers) - MCP sunucularının derlenmiş listesi (mcpservers.org'un eşlikçisi).
- [punkpeye/awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients) - MCP istemcisi olarak çalışan uygulama ve araçların derlenmiş listesi.
- [PulseMCP](https://www.pulsemcp.com) - Kullanım verileriyle aranabilir MCP sunucu ve istemci dizini.
- [Glama MCP Dizini](https://glama.ai/mcp/servers) - Göz atılabilir MCP sunucu ve istemci dizini.
- [mcpservers.org](https://mcpservers.org) - MCP sunucu ve istemcileri için web dizini.

### Popüler Sunucular

- [Referans sunucular](https://github.com/modelcontextprotocol/servers) - Anthropic'in sürdürdüğü referans sunucular: Filesystem, Fetch, Git, Memory, Sequential Thinking, Time ve daha fazlası.
- [GitHub MCP Server](https://github.com/github/github-mcp-server) - GitHub'ın depolar, issue'lar, PR'lar ve iş akışları için resmi MCP sunucusu.
- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) - Erişilebilirlik anlık görüntüleriyle tarayıcı otomasyonu için Microsoft'un Playwright MCP sunucusu.
- [upstash/context7](https://github.com/upstash/context7) - LLM'lere güncel kütüphane dokümantasyonu sunan MCP sunucusu.
- [awslabs/mcp](https://github.com/awslabs/mcp) - AWS hizmetleri için resmi MCP sunucuları derlemesi.
- [microsoft/mcp](https://github.com/microsoft/mcp) - Resmi Microsoft MCP sunucu uygulamalarının kataloğu.

### İstemciler ve Araçlar

- [MCP İstemcileri (resmi liste)](https://modelcontextprotocol.io/clients) - Anthropic'in MCP destekleyen uygulamalar listesi.
- [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) - MCP sunucuları için resmi görsel test ve hata ayıklama aracı.
- [FastMCP](https://github.com/jlowin/fastmcp) - MCP sunucu ve istemcileri geliştirmek için popüler, Pythonic bir çerçeve.

## SDK'lar ve Kütüphaneler

### Resmi SDK'lar

- [Python SDK](https://github.com/anthropics/anthropic-sdk-python) - Claude Messages API için resmi Python istemcisi (senkron/asenkron, Pydantic modelleri, akış).
- [TypeScript SDK](https://github.com/anthropics/anthropic-sdk-typescript) - Node.js, Deno, Bun ve tarayıcılar için resmi TypeScript/JavaScript SDK'sı.
- [Go SDK](https://github.com/anthropics/anthropic-sdk-go) - Bağlam tabanlı iptal ve fonksiyonel seçeneklerle resmi Go SDK'sı.
- [Java SDK](https://github.com/anthropics/anthropic-sdk-java) - Builder deseni ve `CompletableFuture` asenkron kullanan resmi Java SDK'sı.
- [Ruby SDK](https://github.com/anthropics/anthropic-sdk-ruby) - Sorbet türleri ve akış yardımcılarıyla resmi Ruby SDK'sı.
- [PHP SDK](https://github.com/anthropics/anthropic-sdk-php) - Değer nesneleri ve builder desenini kullanan resmi PHP SDK'sı.
- [C#/.NET SDK](https://github.com/anthropics/anthropic-sdk-csharp) - `IChatClient` entegrasyonlu resmi C#/.NET SDK'sı (.NET Standard 2.0+).

> Python ve TypeScript SDK'ları, Amazon Bedrock ve Google Vertex AI için birinci taraf `AnthropicBedrock` ve `AnthropicVertex` istemcilerini de içerir.

### Agent Çerçeveleri

- [LangChain](https://github.com/langchain-ai/langchain) - `langchain-anthropic` üzerinden birinci sınıf Claude desteği olan popüler LLM uygulama çerçevesi.
- [LangGraph](https://github.com/langchain-ai/langgraph) - LangChain ekibinden durumlu, graf tabanlı agent orkestrasyonu; Claude ile çalışır.
- [LlamaIndex](https://github.com/run-llama/llama_index) - Anthropic LLM entegrasyonu olan veri/RAG çerçevesi.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Rol tabanlı çok-agent orkestrasyon çerçevesi; Claude'u sağlayıcı yapılandırmasıyla çalıştırır.
- [AutoGen](https://github.com/microsoft/autogen) - Anthropic istemcisi olan Microsoft çok-agent konuşma çerçevesi.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - Pydantic ekibinden yerel Anthropic desteği olan tip güvenli Python agent çerçevesi.
- [DSPy](https://github.com/stanfordnlp/dspy) - LLM'leri promptlamak yerine programlamak için Stanford çerçevesi; Claude'u destekler.
- [Mastra](https://github.com/mastra-ai/mastra) - Anthropic sağlayıcısı olan TypeScript agent çerçevesi (bellek, iş akışları, araçlar).
- [Vercel AI SDK](https://github.com/vercel/ai) - Yapay zeka uygulamaları/agent'ları için TypeScript araç seti; Claude, `@ai-sdk/anthropic` üzerinden.
- [smolagents](https://github.com/huggingface/smolagents) - Hugging Face'in minimal kod-agent'ı kütüphanesi; Claude'u LiteLLM üzerinden kullanır.
- [Agno](https://github.com/agno-agi/agno) - Anthropic destekli, yüksek performanslı, modelden bağımsız çok-agent çerçevesi.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Anthropic bağlayıcısı olan Microsoft yapay zeka orkestrasyon SDK'sı (.NET/Python/Java).
- [Spring AI](https://github.com/spring-projects/spring-ai) - Özel bir Anthropic Claude başlatıcısı olan, yapay zeka uygulamaları için Spring çerçevesi.
- [Haystack](https://github.com/deepset-ai/haystack) - Anthropic üreteç ve sohbet bileşenleri olan deepset LLM/RAG çerçevesi.

### Topluluk Kütüphaneleri

- [llm-anthropic](https://github.com/simonw/llm-anthropic) - Simon Willison'ın `llm` CLI ve Python kütüphanesi için Anthropic/Claude eklentisi.
- [anthropix](https://github.com/lebrunel/anthropix) - Araç kullanımı dâhil, Anthropic API için resmi olmayan Elixir istemcisi.
- [misanthropy](https://github.com/cortesi/misanthropy) - Anthropic API'ye idiyomatik Rust bağlamaları (akış, araçlar, görüntüler, uzun düşünme).
- [clust](https://github.com/mochi-neko/clust) - Anthropic/Claude API için resmi olmayan Rust istemcisi.
- [Anthropic.SDK](https://github.com/tghamm/Anthropic.SDK) - Özellik açısından zengin topluluk .NET/C# kütüphanesi (akış, araçlar, toplu işleme, Semantic Kernel entegrasyonu).

### Ağ Geçitleri ve Gözlemlenebilirlik

- [LiteLLM](https://github.com/BerriAI/litellm) - Anthropic dâhil 100+ sağlayıcıya OpenAI uyumlu arayüz sunan açık kaynak SDK/proxy.
- [OpenRouter](https://openrouter.ai) - Claude ailesi dâhil yüzlerce modele tek uç noktadan yönlendiren birleşik API ağ geçidi.
- [Portkey Gateway](https://github.com/Portkey-AI/gateway) - Claude dâhil birçok LLM'ye koruma ve yönlendirme sunan hızlı açık kaynak yapay zeka ağ geçidi.
- [Langfuse](https://github.com/langfuse/langfuse) - Anthropic/Claude destekli açık kaynak LLM gözlemlenebilirlik, izleme ve değerlendirme aracı.
- [Helicone](https://github.com/Helicone/helicone) - Anthropic API'yi destekleyen açık kaynak LLM gözlemlenebilirlik ve izleme proxy'si.
- [Instructor](https://github.com/567-labs/instructor) - Anthropic/Claude dâhil sağlayıcılar genelinde yapılandırılmış (Pydantic) çıktılar.

## Yapay Zeka Kodlama Araçları

- [Aider](https://aider.chat) - Otomatik Git commit'leriyle terminal tabanlı yapay zeka eşli programcı; Claude modelleri en iyi altyapıları arasında.
- [Cline](https://cline.bot) - VS Code ve JetBrains için birinci sınıf Claude destekli açık kaynak otonom kodlama agent'ı.
- [Continue](https://continue.dev) - Anthropic Claude ile yapılandırılabilen, VS Code ve JetBrains için açık kaynak yapay zeka asistanı ve agent'ı.
- [Cursor](https://cursor.com) - Claude Opus ve Sonnet'i seçilebilir model altyapısı olarak sunan yapay zeka odaklı kod editörü.
- [Goose](https://github.com/block/goose) - 15+ sağlayıcı arasında Claude'u destekleyen, Block'un kodlama ve iş akışları için açık kaynak yapay zeka agent'ı.
- [Kilo Code](https://github.com/Kilo-Org/kilocode) - Claude Opus/Sonnet destekli açık kaynak agentic kodlama uzantısı (VS Code, JetBrains, CLI).
- [Windsurf](https://windsurf.com) - Çok adımlı kodlama görevlerini Claude ve diğer modellerde çalıştıran agentic yapay zeka IDE'si.
- [Zed](https://zed.dev) - Claude'u destekleyen yerleşik agentic özelliklere sahip yüksek performanslı açık kaynak editör.

## Sohbet Arayüzleri ve Uygulamalar

- [big-AGI](https://big-agi.com) - Claude Opus/Sonnet için doğrudan Anthropic entegrasyonlu çok-modelli uzman yapay zeka çalışma alanı.
- [Cherry Studio](https://github.com/CherryHQ/cherry-studio) - Anthropic Claude dâhil 300+ modeli birleştiren açık kaynak masaüstü yapay zeka çalışma istasyonu.
- [Chatbox](https://chatboxai.app) - Anthropic Claude modellerini destekleyen çapraz platform yapay zeka istemcisi (açık kaynak topluluk sürümü).
- [Jan](https://jan.ai) - Anthropic API üzerinden Claude'a bağlanan açık kaynak, çevrimdışı öncelikli masaüstü ChatGPT alternatifi.
- [LibreChat](https://librechat.ai) - Yerel Claude desteğinin yanı sıra agent, MCP ve artifact'lar sunan açık kaynak çok-sağlayıcılı sohbet platformu.
- [Lobe Chat](https://github.com/lobehub/lobe-chat) - Birçok sağlayıcı arasında Anthropic Claude'u destekleyen açık kaynak modern sohbet çerçevesi.
- [Open WebUI](https://openwebui.com) - Anthropic ve OpenAI uyumlu API'ler üzerinden Claude'a bağlanan, kendi kendine barındırılan genişletilebilir sohbet arayüzü.

## Dikkate Değer Açık Kaynak Projeler

- [OpenHands](https://github.com/OpenHands/OpenHands) - Claude (ve diğer) modellerde çalışan açık kaynak otonom yazılım mühendisliği agent platformu.
- [STORM](https://github.com/stanford-oval/storm) - Kaynaklı, Wikipedia tarzı raporlar yazan Stanford LLM bilgi düzenleme sistemi; Claude ile LiteLLM üzerinden çalışır.
- [SWE-agent](https://github.com/SWE-agent/SWE-agent) - Claude modelleriyle güçlü SWE-bench sonuçlarına ulaşan, GitHub issue'larını otomatik düzelten Princeton/Stanford agent'ı.

## Öğrenme ve Prompt

### Prompt Mühendisliği

- [Prompt mühendisliği genel bakışı](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview) - Anthropic'in netlik, örnekler, XML yapısı, roller, zincirleme ve düşünme üzerine resmi merkezi.
- [Prompt en iyi uygulamaları](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices) - Claude'un en yeni modellerine göre ayarlanmış resmi, modele özel rehber.
- [Etkileşimli Prompt Mühendisliği Eğitimi](https://github.com/anthropics/prompt-eng-interactive-tutorial) - Temellerden ileri tekniklere, alıştırmalı resmi uygulamalı kurs.
- [Prompt Engineering Guide (DAIR.AI)](https://www.promptingguide.ai/) - Claude/Anthropic'e özel bölümleri olan popüler açık topluluk rehberi.
- [Claude Code prompt kütüphanesi](https://code.claude.com/docs/en/prompt-library) - Göreve ve role göre etiketlenmiş, kopyala-yapıştır Claude Code prompt'ları.

### Kurslar ve Eğitimler

- [Anthropic Academy](https://www.anthropic.com/learn/build-with-claude) - Kurs, rehber, quickstart ve dokümanları düzenleyen Anthropic'in resmi öğrenme merkezi.
- [Anthropic Kursları (Skilljar)](https://anthropic.skilljar.com) - Claude 101 ve Claude API ile Geliştirme dâhil ücretsiz resmi kurs kataloğu.
- [anthropics/courses](https://github.com/anthropics/courses) - Anthropic'in açık eğitim deposu: API temelleri, prompt mühendisliği, değerlendirmeler ve araç kullanımı.
- [Claude Cookbooks](https://github.com/anthropics/claude-cookbooks) - Araç kullanımı, çok-modluluk, değerlendirme, RAG ve agent'lar için resmi çalıştırılabilir not defterleri.
- [Claude Quickstarts](https://github.com/anthropics/claude-quickstarts) - Dağıtıma hazır başlangıç projeleri (müşteri destek agent'ı, bilgisayar kullanımı, kodlama agent'ı).

### Okuma ve Araştırma

- [Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents) - Agent ve iş akışı desenleri üzerine, tasarımı basit tutmaya dair yaygın atıf alan mühendislik rehberi.
- [Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073) - Modelleri ilke tabanlı bir anayasayla eğitme üzerine Anthropic'in temel makalesi.
- [Claude's Constitution](https://www.anthropic.com/news/claude-new-constitution) - Claude'un amaçlanan değer ve davranışlarını ayrıntılandıran, CC0 ile yayımlanan Anthropic belgesi.
- [Mapping the Mind of a Large Language Model](https://www.anthropic.com/research/mapping-mind-language-model) - Claude içindeki milyonlarca özelliği dictionary learning ile tanımlayan yorumlanabilirlik çalışması.
- [Tracing the Thoughts of a Language Model](https://www.anthropic.com/research/tracing-thoughts-language-model) - Claude'un içsel olarak nasıl hesaplayıp akıl yürüttüğünü ortaya koyan devre izleme araştırması.
- [Introducing Computer Use](https://www.anthropic.com/news/3-5-models-and-computer-use) - Claude'un ekranı görüp imleç ve klavyeyi kontrol ederek bilgisayar kullanmasının duyurusu.
- [Anthropic Mühendislik Blogu](https://www.anthropic.com/engineering) - Agent'lar, bağlam mühendisliği, araç kullanımı ve üretim pratikleri üzerine derinlemesine yazılar.

### Bültenler, Bloglar ve Video

- [Import AI](https://importai.substack.com/) - Anthropic kurucu ortağı Jack Clark'ın sınır yapay zeka araştırma ve politikasını inceleyen haftalık bülteni.
- [Interconnects](https://www.interconnects.ai/) - Nathan Lambert'in sınır laboratuvarı ve açık model araştırmalarına dair keskin analizli bülteni.
- [Latent Space](https://www.latent.space/) - swyx & Alessio'nun sık sık Anthropic geliştiricilerine yer veren yüksek değerli AI Engineer bülteni ve podcast'i.
- [Simon Willison's Weblog - Claude etiketi](https://simonwillison.net/tags/claude/) - Her önemli Claude ve Anthropic sürümüne dair ayrıntılı, uygulamalı yorumlar.
- [The Anthropic Stack](https://theanthropicstack.com/) - Claude, MCP ve yapay zeka agent'larıyla geliştirme üzerine uygulayıcı bülteni.
- [YouTube'da Anthropic](https://www.youtube.com/@anthropic-ai) - Ürün demoları, araştırma konuşmaları ve Claude eğitimleri içeren Anthropic'in resmi kanalı.
- [Claude Developer Newsletter](https://claude.com/newsletter/developers) - Anthropic'in duyurular ve en iyi uygulamalar içeren resmi geliştirici e-postası.

### Topluluklar

- [Claude Community](https://claude.com/community) - Discord, Reddit ve elçi programlarını birbirine bağlayan Anthropic'in resmi topluluk merkezi.
- [r/ClaudeAI](https://www.reddit.com/r/ClaudeAI/) - Claude tartışmaları, ipuçları ve karşılaştırmaları için büyük topluluk subreddit'i.

## Kıyaslamalar ve Liderlik Tabloları

- [SWE-bench](https://www.swebench.com/) - Gerçek GitHub issue çözümünü ölçen, Claude modellerinin en iyiler arasında yer aldığı kıyaslama.
- [Aider Polyglot Leaderboard](https://aider.chat/docs/leaderboards/) - Claude modellerini sıralayan çok dilli kod düzenleme kıyaslaması.
- [Terminal-Bench](https://www.tbench.ai/leaderboard) - Claude modellerini değerlendiren, gerçek terminal görevlerinde agent kıyaslaması.
- [Arena (eski adıyla LMArena / Chatbot Arena)](https://arena.ai) - Claude modellerini içeren insan tercihi LLM liderlik tablosu.
- [GAIA Leaderboard](https://huggingface.co/spaces/gaia-benchmark/leaderboard) - Claude tabanlı agent'ların değerlendirildiği genel yapay zeka asistanı kıyaslaması.
- [Artificial Analysis](https://artificialanalysis.ai) - Claude'u kalite, hız ve fiyat açısından izleyen bağımsız LLM kıyaslama sitesi.

## Katkıda Bulunma

Katkılar memnuniyetle karşılanır - tek bir güzel bağlantı bile gayet iyi bir pull request'tir. Lütfen önce [katkı rehberini](../.github/CONTRIBUTING.md) okuyun. Kısaca: girdileri Claude'la ilgili, yüksek kaliteli, tekrarsız tutun ve `- [Ad](https://url) - kısa, olgusal açıklama.` biçiminde yazın. Çeviriler `translations/` klasöründe yer alır.
