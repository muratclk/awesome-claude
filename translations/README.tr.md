# Awesome Claude [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Anthropic'in Claude'u için en iyi kaynakların derlenmiş listesi - modeller, uygulamalar, Claude Code, Model Context Protocol, SDK'lar, araçlar ve öğrenme materyalleri.

Claude, Anthropic tarafından geliştirilen; yardımsever, dürüst ve zararsız olacak şekilde tasarlanmış bir yapay zeka modelleri ve ürünleri ailesidir. Bu liste, Claude'u *kullanmak* ve onunla *geliştirme yapmak* için yüksek değerli kaynakları bir araya getirir. Her şey elle seçilmiştir ve her bağlantı kontrol edilmiştir - ölü bağlantı yok, dolgu yok.

**Diğer dillerde oku:** [English](../README.md) · **Türkçe** · [kendi dilini ekle »](../.github/CONTRIBUTING.md#translations)

## İçindekiler

- [Resmi](#resmi)
- [Claude Code](#claude-code)
- [Skills](#skills)
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
- [Claude Opus 5 Tanıtımı](https://www.anthropic.com/news/claude-opus-5) - Anthropic'in 1M token bağlam penceresi ve uyarlanabilir düşünmeye sahip Temmuz 2026 Opus sürümü.
- [Claude Fable 5 ve Mythos 5 Tanıtımı](https://platform.claude.com/docs/en/about-claude/models/introducing-claude-fable-5-and-claude-mythos-5) - Anthropic'in Mythos sınıfı sınır modellerine dair lansman detayları.
- [Claude Sonnet 5 Tanıtımı](https://www.anthropic.com/news/claude-sonnet-5) - Anthropic'in en agentic Sonnet katmanı modelinin duyurusu.
- [Claude Opus 4.5 Tanıtımı](https://www.anthropic.com/news/claude-opus-4-5) - Claude 4.5 ailesini tamamlayan, kodlama ve agent'lar için ayarlanmış modelin Kasım 2025 lansmanı.
- [Fiyatlandırma dokümanları](https://platform.claude.com/docs/en/about-claude/pricing) - Toplu iş indirimleri ve prompt önbellekleme oranları dâhil tam API fiyatlandırması.
- [Sürüm notları](https://platform.claude.com/docs/en/release-notes/overview) - Claude API, SDK'lar ve Console için değişiklik günlüğü.
- [Model kullanımdan kaldırmaları](https://platform.claude.com/docs/en/about-claude/model-deprecations) - Eski modeller için emeklilik takvimi ve geçiş rehberi.
- [Şeffaflık Merkezi](https://www.anthropic.com/transparency) - Model ve sistem kartları, bilgi kesim tarihleri ve güvenlik raporlaması.

### Uygulamalar ve Ürünler

- [Artifacts](https://www.anthropic.com/news/claude-powered-artifacts) - Doğrudan Claude içinde etkileşimli yapay zeka destekli uygulamalar oluştur, barındır ve paylaş.
- [Claude'a bellek geliyor](https://claude.com/blog/memory) - Claude'un projelerinizi, tercihlerinizi ve bağlamınızı sohbetler arası hatırlamasını sağlayan opsiyonel bellek.
- [Web'de Claude Code](https://claude.com/blog/claude-code-on-the-web) - Kodlama görevlerini tarayıcıdan veya mobil uygulamadan, Anthropic'in yönettiği bulut sandbox'larında paralel çalıştırarak devret.
- [Claude Cowork](https://claude.com/blog/cowork-research-preview) - Yerel dosyaları okuyup yazan ve Slack, Google Drive gibi bağlı uygulamalarda çalışan agentic bilgi-işi arkadaşı.
- [Claude Enterprise](https://www.anthropic.com/product/enterprise) - SSO, SCIM, denetim günlükleri ve genişletilmiş bağlam ile yönetim kontrolleri içeren kurumsal plan.
- [Claude for Chrome](https://claude.com/claude-for-chrome) - Claude'un siteleri okumasını, tıklamasını ve gezinmesini sağlayan resmi tarayıcı uzantısı.
- [Microsoft 365 için Claude](https://claude.com/claude-for-excel) - Excel, PowerPoint, Word ve Outlook içinde dosyaları düzenleyen ve bağlamı bu uygulamalar arasında taşıyan yerel Claude entegrasyonu.
- [Claude'u İndir](https://claude.com/download) - Masaüstü (macOS/Windows/Linux) ve mobil (iOS/Android) uygulama indirmeleri.
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
- [subinium/awesome-claude-code](https://github.com/subinium/awesome-claude-code) - Yüksek dahil edilme çıtası olan, Claude Code için araç, skill, eklenti ve MCP sunucusu listesi.

### Subagent'lar ve Eklentiler

- [wshobson/agents](https://github.com/wshobson/agents) - Claude Code için üretime hazır subagent, skill ve komut pazaryeri.
- [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) - Geliştirme kategorileri genelinde uzmanlaşmış Claude Code subagent derlemesi.
- [0xfurai/claude-code-subagents](https://github.com/0xfurai/claude-code-subagents) - Markdown dosyaları hâlinde üretime hazır geliştirme subagent'larının kapsamlı derlemesi.

### Hook'lar, Komutlar ve Yapılandırmalar

- [disler/claude-code-hooks-mastery](https://github.com/disler/claude-code-hooks-mastery) - Her Claude Code hook yaşam döngüsü olayını ileri düzey desenlerle gösteren referans proje.
- [wshobson/commands](https://github.com/wshobson/commands) - Claude Code için üretime hazır slash komutları (iş akışları ve tek amaçlı araçlar) derlemesi.
- [qdhenry/Claude-Command-Suite](https://github.com/qdhenry/Claude-Command-Suite) - Yapılandırılmış yazılım geliştirme iş akışları için slash komutları, agent ve skill takımı.
- [sirmalloc/ccstatusline](https://github.com/sirmalloc/ccstatusline) - Powerline desteği, temalar ve kullanım widget'ları olan yüksek düzeyde özelleştirilebilir Claude Code statusline'ı.
- [ryoppippi/ccusage](https://github.com/ryoppippi/ccusage) - Yerel JSONL günlüklerinden Claude Code kullanımını ve maliyetini analiz eden, statusline entegrasyonlu CLI.
- [Haleclipse/CCometixLine](https://github.com/Haleclipse/CCometixLine) - Git entegrasyonu, kullanım takibi ve TUI yapılandırması olan, Rust'ta yazılmış yüksek performanslı Claude Code statusline'ı.
- [Maciek-roboblog/Claude-Code-Usage-Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) - Token ve maliyet takibi, tükenme hızı tahminleri ve limit uyarıları olan gerçek zamanlı terminal kullanım monitörü.

### Araçlar ve Eklentiler

- [dagger/container-use](https://github.com/dagger/container-use) - Her kodlama agent'ına kendi Git dalında taze bir konteyner vererek birden çok agent'ın paralel çalışmasını sağlayan MCP sunucusu.
- [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) - Agent, komut, hook ve MCP yapılandırmaları kataloğuyla Claude Code'u yapılandırıp izleyen CLI.
- [musistudio/claude-code-router](https://github.com/musistudio/claude-code-router) - Claude Code isteklerini kural tabanlı yönlendirmeyle farklı model ve sağlayıcılara yönlendiren yerel proxy.
- [slopus/happy](https://github.com/slopus/happy) - Gerçek zamanlı ses, uçtan uca şifreleme ve telefondan uzaktan kontrol sunan Claude Code mobil ve web istemcisi.
- [smtg-ai/claude-squad](https://github.com/smtg-ai/claude-squad) - Birden çok Claude Code agent'ını, her biri kendi Git worktree ve tmux oturumunda paralel çalıştıran terminal yöneticisi.
- [SuperClaude-Org/SuperClaude_Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) - Claude Code'u özel slash komutları, personalar ve metodolojilerle genişleten yapılandırma çerçevesi.
- [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) - Her oturumu sıkıştırıp ilgili bağlamı gelecekteki Claude Code oturumlarına enjekte eden kalıcı bellek eklentisi.

### IDE ve Editör Entegrasyonları

- [VS Code'da Claude Code](https://code.claude.com/docs/en/vs-code) - Yerleşik sohbet paneli, checkpoint'ler, @-etiketleme ve diff görüntüleme sunan resmi VS Code uzantısı.
- [JetBrains için Claude Code](https://plugins.jetbrains.com/plugin/27310-claude-code-beta-) - IntelliJ, PyCharm, WebStorm ve diğerleri için resmi JetBrains eklentisi.
- [coder/claudecode.nvim](https://github.com/coder/claudecode.nvim) - Resmi Claude Code IDE entegrasyonlarıyla protokol uyumlu, saf Lua Neovim uzantısı.

## Skills

Agent Skills, Claude'un talep üzerine yüklediği talimat, betik ve kaynakları paketleyen `SKILL.md` dosyalı klasörlerdir - Claude uygulamaları, Claude Code, API ve Agent SDK genelinde çalışır.

### Resmi ve Dokümanlar

- [Agent Skills Tanıtımı](https://claude.com/blog/skills) - Anthropic'in Agent Skills lansman duyurusu.
- [Equipping agents for the real world with Agent Skills](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) - Agent Skills'in nasıl çalıştığına ve nasıl tasarlanacağına dair Anthropic mühendislik incelemesi.
- [Agent Skills genel bakışı](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview) - Agent Skills'in ne olduğuna ve SKILL.md biçimine dair resmi dokümantasyon.
- [Skill yazma en iyi uygulamaları](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/best-practices) - Claude'un keşfedip kullanabileceği etkili SKILL.md dosyaları yazmaya dair resmi rehber.
- [Agent Skills'i API ile kullanma](https://platform.claude.com/docs/en/build-with-claude/skills-guide) - Skills'i Claude API üzerinden yükleme ve çağırmaya dair resmi rehber.
- [Claude Code'da Skills](https://code.claude.com/docs/en/skills) - Skill oluşturma, yönetme ve çağırma için resmi Claude Code dokümanları.
- [Agent Skills'e Giriş](https://anthropic.skilljar.com/introduction-to-agent-skills) - Skill oluşturma ve paylaşma üzerine ücretsiz resmi Anthropic Academy kursu.
- [The Complete Guide to Building Skills for Claude](https://resources.anthropic.com/hubfs/The-Complete-Guide-to-Building-Skill-for-Claude.pdf) - Skill tasarlama ve yazma üzerine Anthropic'in indirilebilir el kitabı.
- [Agent Skills açık standardı](https://agentskills.io) - Anthropic tarafından başlatılan SKILL.md biçiminin açık spesifikasyonu.

### Derlemeler ve Pazaryerleri

- [anthropics/skills](https://github.com/anthropics/skills) - Anthropic'in açık kaynak örnek Skill'lerin resmi deposu.
- [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) - Popüler, derlenmiş Claude Skills, kaynak ve araç listesi.
- [karanb192/awesome-claude-skills](https://github.com/karanb192/awesome-claude-skills) - Claude Code, claude.ai ve API için doğrulanmış Skill'lerin topluluk derlemesi.
- [Claude Code Marketplaces](https://claudemarketplaces.com/) - Claude Code Skill'leri, eklentileri ve MCP sunucularının aranabilir dizini.
- [nvidia/skills](https://github.com/nvidia/skills) - Robotik, simülasyon, CUDA ve RAG'i kapsayan, Claude Code ve diğer agent'lar için resmi NVIDIA Agent Skills.
- [obra/superpowers](https://github.com/obra/superpowers) - Claude Code eklenti pazaryerinden kurulabilen, birleştirilebilir Agent Skills çerçevesi ve yazılım geliştirme metodolojisi.

### Skill Geliştirme Araçları

- [skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator) - Yeni Skill'ler oluşturma ve geliştirmede yol gösteren Anthropic meta-Skill'i.
- [claudelint Skills doğrulayıcı](https://claudelint.com/validators/skills) - SKILL.md dosyalarını doğruluk, güvenlik ve kalite açısından denetleyen linter.
- [agent-ecosystem/skill-validator](https://github.com/agent-ecosystem/skill-validator) - Agent Skill paketlerini doğrulayıp puanlayan CLI.

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
- [Smithery](https://smithery.ai) - CLI kurulumu ve uzak uç noktalarla binlerce MCP sunucusunu indeksleyen kayıt defteri ve barındırma platformu.
- [Docker MCP Catalog](https://hub.docker.com/mcp) - Docker Hub ve Desktop ile entegre, doğrulanmış konteynerli MCP sunucularının Docker kataloğu.
- [awesome-mcp-gateways](https://github.com/e2b-dev/awesome-mcp-gateways) - Açık kaynak ve ticari MCP ağ geçidi ürünlerinin derlenmiş listesi.

### Popüler Sunucular

- [Referans sunucular](https://github.com/modelcontextprotocol/servers) - Anthropic'in sürdürdüğü referans sunucular: Filesystem, Fetch, Git, Memory, Sequential Thinking, Time ve daha fazlası.
- [GitHub MCP Server](https://github.com/github/github-mcp-server) - GitHub'ın depolar, issue'lar, PR'lar ve iş akışları için resmi MCP sunucusu.
- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) - Erişilebilirlik anlık görüntüleriyle tarayıcı otomasyonu için Microsoft'un Playwright MCP sunucusu.
- [upstash/context7](https://github.com/upstash/context7) - LLM'lere güncel kütüphane dokümantasyonu sunan MCP sunucusu.
- [awslabs/mcp](https://github.com/awslabs/mcp) - AWS hizmetleri için resmi MCP sunucuları derlemesi.
- [microsoft/mcp](https://github.com/microsoft/mcp) - Resmi Microsoft MCP sunucu uygulamalarının kataloğu.
- [Apify MCP](https://github.com/apify/apify-mcp-server) - Web scraping ve otomasyon için binlerce Actor sunan resmi Apify MCP sunucusu.
- [Atlassian Rovo MCP](https://www.atlassian.com/platform/remote-mcp-server) - Jira, Confluence ve Compass'ı bağlayan resmi Atlassian uzak MCP sunucusu.
- [Chrome DevTools MCP](https://github.com/ChromeDevTools/chrome-devtools-mcp) - Canlı bir Chrome tarayıcısını kontrol edip inceleyen resmi Chrome DevTools MCP sunucusu.
- [Cloudflare MCP](https://github.com/cloudflare/mcp-server-cloudflare) - Workers, KV, R2, D1 ve gözlemlenebilirlik için resmi Cloudflare MCP sunucuları.
- [Firecrawl MCP](https://github.com/firecrawl/firecrawl-mcp-server) - LLM istemcilerine web scraping ve arama ekleyen resmi Firecrawl MCP sunucusu.
- [Grafana MCP](https://github.com/grafana/mcp-grafana) - Panolar, veri kaynakları, uyarılar ve olaylar için resmi Grafana MCP sunucusu.
- [Hugging Face MCP](https://github.com/huggingface/hf-mcp-server) - Model, veri seti, Space ve doküman aramak için resmi Hugging Face MCP sunucusu.
- [Linear MCP](https://linear.app/docs/mcp) - Issue, proje ve ürün iş akışları için resmi barındırılan Linear MCP sunucusu.
- [Neon MCP](https://github.com/neondatabase/mcp-server-neon) - Neon Yönetim API'si ve sunucusuz PostgreSQL için resmi Neon MCP sunucusu.
- [Notion MCP](https://github.com/makenotion/notion-mcp-server) - Notion çalışma alanlarını okuma, yazma ve arama için resmi Notion MCP sunucusu.
- [Sentry MCP](https://github.com/getsentry/sentry-mcp) - Issue, hata ve performans verilerini LLM'ler üzerinden sorgulamak için resmi Sentry MCP sunucusu.
- [Stripe MCP](https://github.com/stripe/ai) - Ödemeler, faturalama ve müşteri verileri için Stripe'ın resmi AI araç seti ve barındırılan MCP sunucusu.
- [Supabase MCP](https://github.com/supabase/mcp) - PostgreSQL veritabanlarını ve projeleri yönetip sorgulayan resmi Supabase MCP sunucusu.

### İstemciler ve Araçlar

- [MCP İstemcileri (resmi liste)](https://modelcontextprotocol.io/clients) - Anthropic'in MCP destekleyen uygulamalar listesi.
- [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) - MCP sunucuları için resmi görsel test ve hata ayıklama aracı.
- [FastMCP](https://github.com/jlowin/fastmcp) - MCP sunucu ve istemcileri geliştirmek için popüler, Pythonic bir çerçeve.
- [mcp-use](https://github.com/mcp-use/mcp-use) - MCP uygulamaları oluşturmak ve LLM'leri herhangi bir MCP sunucusuna bağlamak için açık kaynak çerçeve.
- [MetaMCP](https://github.com/metatool-ai/metamcp) - Tek, kendi kendine barındırılabilir uygulamada MCP toplayıcı, orkestratör, ara katman ve ağ geçidi.
- [mcpo](https://github.com/open-webui/mcpo) - Herhangi bir MCP sunucusunu OpenAPI uyumlu bir HTTP uç noktası olarak sunan proxy.
- [OpenAPI-MCP](https://github.com/gujord/OpenAPI-MCP) - OpenAPI spesifikasyonlarını MCP araçlarına, kaynaklarına ve prompt'larına çeviren proxy.
- [MCP-Scan](https://github.com/invariantlabs-ai/mcp-scan) - MCP sunucularında prompt injection, araç zehirleme ve rug pull tespiti yapan güvenlik tarayıcısı.

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
- [Deep Agents](https://github.com/langchain-ai/deepagents) - Planlama, alt-agent'lar ve sanal dosya sistemi olan LangChain'in Claude Code tarzı agent harness'ı.
- [Google ADK](https://github.com/google/adk-python) - Google'ın açık kaynak Agent Development Kit'i; Claude'u Anthropic entegrasyonu veya LiteLLM üzerinden çalıştırır.
- [Inngest AgentKit](https://github.com/inngest/agent-kit) - Deterministik yönlendirme ve yerleşik Anthropic sağlayıcısı olan, çok-agent ağları için TypeScript çerçevesi.
- [Letta](https://github.com/letta-ai/letta) - Uzun süreli belleğe sahip durumlu agent çerçevesi (eski adıyla MemGPT); Claude'a sağlayıcı olarak bağlanır.
- [LiveKit Agents](https://github.com/livekit/agents) - Özel Anthropic Claude LLM eklentisi olan gerçek zamanlı sesli yapay zeka agent çerçevesi.
- [Rivet](https://github.com/Ironclad/rivet) - Anthropic eklentisi olan, Ironclad'ın yapay zeka agent'ları için açık kaynak görsel programlama ortamı.
- [Strands Agents](https://github.com/strands-agents/sdk-python) - Birinci sınıf Anthropic Claude desteği olan, AWS yapımı açık kaynak Python ve TypeScript agent SDK'sı.
- [VoltAgent](https://github.com/VoltAgent/voltagent) - Gözlemlenebilirlik öncelikli TypeScript agent çerçevesi; yapılandırmayla Anthropic Claude'a geçin.

### Topluluk Kütüphaneleri

- [llm-anthropic](https://github.com/simonw/llm-anthropic) - Simon Willison'ın `llm` CLI ve Python kütüphanesi için Anthropic/Claude eklentisi.
- [anthropix](https://github.com/lebrunel/anthropix) - Araç kullanımı dâhil, Anthropic API için resmi olmayan Elixir istemcisi.
- [misanthropy](https://github.com/cortesi/misanthropy) - Anthropic API'ye idiyomatik Rust bağlamaları (akış, araçlar, görüntüler, uzun düşünme).
- [clust](https://github.com/mochi-neko/clust) - Anthropic/Claude API için resmi olmayan Rust istemcisi.
- [Anthropic.SDK](https://github.com/tghamm/Anthropic.SDK) - Özellik açısından zengin topluluk .NET/C# kütüphanesi (akış, araçlar, toplu işleme, Semantic Kernel entegrasyonu).
- [BAML](https://github.com/BoundaryML/baml) - Garantili yapılandırılmış çıktılarla tipli, test edilebilir LLM fonksiyonları için DSL; sağlayıcı olarak Claude'u destekler.
- [Cognee](https://github.com/topoteretes/cognee) - Claude Code ve MCP entegrasyonlarıyla kendi kendine barındırılan bilgi grafikleri kuran açık kaynak yapay zeka bellek platformu.
- [Graphiti](https://github.com/getzep/graphiti) - Agent'lar için zamansal bilgi grafiği belleği (Zep'in açık kaynak çekirdeği); Anthropic Claude ile çalışır.
- [Mem0](https://github.com/mem0ai/mem0) - Anthropic desteği ve Claude Agent SDK entegrasyonu olan, yapay zeka agent'ları için evrensel bellek katmanı.

### Ağ Geçitleri ve Gözlemlenebilirlik

- [LiteLLM](https://github.com/BerriAI/litellm) - Anthropic dâhil 100+ sağlayıcıya OpenAI uyumlu arayüz sunan açık kaynak SDK/proxy.
- [OpenRouter](https://openrouter.ai) - Claude ailesi dâhil yüzlerce modele tek uç noktadan yönlendiren birleşik API ağ geçidi.
- [Portkey Gateway](https://github.com/Portkey-AI/gateway) - Claude dâhil birçok LLM'ye koruma ve yönlendirme sunan hızlı açık kaynak yapay zeka ağ geçidi.
- [Langfuse](https://github.com/langfuse/langfuse) - Anthropic/Claude destekli açık kaynak LLM gözlemlenebilirlik, izleme ve değerlendirme aracı.
- [Helicone](https://github.com/Helicone/helicone) - Anthropic API'yi destekleyen açık kaynak LLM gözlemlenebilirlik ve izleme proxy'si.
- [Instructor](https://github.com/567-labs/instructor) - Anthropic/Claude dâhil sağlayıcılar genelinde yapılandırılmış (Pydantic) çıktılar.
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) - OpenTelemetry üzerine kurulu, Anthropic ve Claude Agent SDK enstrümantasyonu olan açık kaynak LLM izleme ve değerlendirme.
- [Bifrost](https://github.com/maximhq/bifrost) - Anthropic SDK'larının doğrudan yerine geçen, yüksek performanslı açık kaynak LLM ağ geçidi (Maxim AI'dan).
- [Braintrust](https://www.braintrust.dev) - Akış, önbellekleme ve araç kullanımı dâhil Anthropic Claude'u çağırıp izleyen değerlendirme ve gözlemlenebilirlik platformu.
- [Cloudflare AI Gateway](https://developers.cloudflare.com/ai-gateway/) - Anthropic dâhil sağlayıcıların önüne önbellekleme, hız sınırlama, analitik ve günlükleme ekleyen edge yapay zeka ağ geçidi.
- [OpenLLMetry](https://github.com/traceloop/openllmetry) - Özel bir Anthropic enstrümantasyon paketi sunan, OpenTelemetry tabanlı LLM gözlemlenebilirliği (Traceloop'tan).
- [Opik](https://github.com/comet-ml/opik) - Tek satırlık Anthropic entegrasyonu olan açık kaynak LLM gözlemlenebilirlik ve değerlendirme platformu (Comet'ten).
- [Promptfoo](https://github.com/promptfoo/promptfoo) - Anthropic Claude'un desteklenen sağlayıcılar arasında olduğu, LLM uygulamalarını test etme, değerlendirme ve red-teaming açık kaynak aracı.

## Yapay Zeka Kodlama Araçları

- [Aider](https://aider.chat) - Otomatik Git commit'leriyle terminal tabanlı yapay zeka eşli programcı; Claude modelleri en iyi altyapıları arasında.
- [Amp](https://ampcode.com) - Sourcegraph'ın terminal ve editörler için, Claude dâhil sınır modellerle çalışan agentic kodlama aracı.
- [Augment Code](https://www.augmentcode.com) - Orkestre edilen agent'ları Claude Sonnet ve Opus'ta çalışan agentic yazılım geliştirme platformu.
- [Cline](https://cline.bot) - VS Code ve JetBrains için birinci sınıf Claude destekli açık kaynak otonom kodlama agent'ı.
- [Codebuff](https://www.codebuff.com) - Claude ve diğer modelleri OpenRouter üzerinden çalıştıran açık kaynak çok-agent'lı kodlama agent'ı.
- [Continue](https://continue.dev) - Anthropic Claude ile yapılandırılabilen, VS Code ve JetBrains için açık kaynak yapay zeka asistanı ve agent'ı.
- [Crush](https://github.com/charmbracelet/crush) - Anthropic Claude ve diğer sağlayıcıları destekleyen Charm'ın terminal kodlama agent'ı.
- [Cursor](https://cursor.com) - Claude Opus ve Sonnet'i seçilebilir model altyapısı olarak sunan yapay zeka odaklı kod editörü.
- [Goose](https://github.com/block/goose) - 15+ sağlayıcı arasında Claude'u destekleyen, Block'un kodlama ve iş akışları için açık kaynak yapay zeka agent'ı.
- [Kilo Code](https://github.com/Kilo-Org/kilocode) - Claude Opus/Sonnet destekli açık kaynak agentic kodlama uzantısı (VS Code, JetBrains, CLI).
- [Kiro](https://kiro.dev) - Anthropic Claude modelleriyle çalışan AWS'nin spesifikasyon odaklı agentic IDE, CLI ve web uygulaması.
- [OpenCode](https://opencode.ai) - Birinci sınıf Claude desteği olan, terminal için açık kaynak, sağlayıcıdan bağımsız yapay zeka kodlama agent'ı.
- [Plandex](https://github.com/plandex-ai/plandex) - Büyük, gerçek dünya projeleri için, Anthropic Claude destekli açık kaynak terminal yapay zeka kodlama agent'ı.
- [Warp](https://www.warp.dev) - Claude çalıştıran ve Claude Code ile eşleşen agentic geliştirme ortamı ve terminali.
- [Windsurf](https://windsurf.com) - Çok adımlı kodlama görevlerini Claude ve diğer modellerde çalıştıran agentic yapay zeka IDE'si.
- [Zed](https://zed.dev) - Claude'u destekleyen yerleşik agentic özelliklere sahip yüksek performanslı açık kaynak editör.

## Sohbet Arayüzleri ve Uygulamalar

- [AnythingLLM](https://anythingllm.com) - Anthropic Claude'u destekleyen, RAG ve agent'lı hepsi-bir-arada masaüstü ve Docker yapay zeka uygulaması.
- [big-AGI](https://big-agi.com) - Claude Opus/Sonnet için doğrudan Anthropic entegrasyonlu çok-modelli uzman yapay zeka çalışma alanı.
- [Cherry Studio](https://github.com/CherryHQ/cherry-studio) - Anthropic Claude dâhil 300+ modeli birleştiren açık kaynak masaüstü yapay zeka çalışma istasyonu.
- [Chatbox](https://chatboxai.app) - Anthropic Claude modellerini destekleyen çapraz platform yapay zeka istemcisi (açık kaynak topluluk sürümü).
- [ChatWise](https://chatwise.app) - Claude ve Claude Pro/Max aboneliklerini destekleyen hızlı, gizlilik dostu masaüstü yapay zeka sohbet istemcisi.
- [Jan](https://jan.ai) - Anthropic API üzerinden Claude'a bağlanan açık kaynak, çevrimdışı öncelikli masaüstü ChatGPT alternatifi.
- [LibreChat](https://librechat.ai) - Yerel Claude desteğinin yanı sıra agent, MCP ve artifact'lar sunan açık kaynak çok-sağlayıcılı sohbet platformu.
- [Lobe Chat](https://github.com/lobehub/lobe-chat) - Birçok sağlayıcı arasında Anthropic Claude'u destekleyen açık kaynak modern sohbet çerçevesi.
- [Msty](https://msty.ai) - Anthropic Claude dâhil yerel ve bulut modelleri için gizlilik odaklı masaüstü yapay zeka sohbet uygulaması.
- [Open WebUI](https://openwebui.com) - Anthropic ve OpenAI uyumlu API'ler üzerinden Claude'a bağlanan, kendi kendine barındırılan genişletilebilir sohbet arayüzü.
- [TypingMind](https://www.typingmind.com) - Claude ve diğer LLM'ler için kendi anahtarını getir tarzı sohbet arayüzü.

## Dikkate Değer Açık Kaynak Projeler

- [opcode](https://github.com/winfunc/opcode) - Claude Code oturumlarını ve özel agent'ları yönetmek için masaüstü GUI ve araç seti (eski adıyla Claudia).
- [OpenHands](https://github.com/OpenHands/OpenHands) - Claude (ve diğer) modellerde çalışan açık kaynak otonom yazılım mühendisliği agent platformu.
- [STORM](https://github.com/stanford-oval/storm) - Kaynaklı, Wikipedia tarzı raporlar yazan Stanford LLM bilgi düzenleme sistemi; Claude ile LiteLLM üzerinden çalışır.
- [SWE-agent](https://github.com/SWE-agent/SWE-agent) - Claude modelleriyle güçlü SWE-bench sonuçlarına ulaşan, GitHub issue'larını otomatik düzelten Princeton/Stanford agent'ı.
- [Task Master](https://github.com/eyaltoledano/claude-task-master) - Claude Code, Cursor ve diğer agent'lara entegre olan yapay zeka destekli görev yönetim sistemi.

## Öğrenme ve Prompt

### Rehberler

- [Claude Code en iyi uygulamaları](https://code.claude.com/docs/en/best-practices) - Agentic kodlama iş akışları, CLAUDE.md, bağlam yönetimi ve araç kurulumu için Anthropic'in resmi rehberi.
- [Claude Agent SDK ile agent geliştirme](https://claude.com/blog/building-agents-with-the-claude-agent-sdk) - Agent SDK üzerine kurulu bağlam-topla, uygula ve doğrula agent döngüsüne dair Anthropic rehberi.
- [Code execution with MCP](https://www.anthropic.com/engineering/code-execution-with-mcp) - Agent'ların MCP araçlarını çağırmak için kod yazmasıyla token kullanımını azaltmaya dair Anthropic mühendislik yazısı.
- [Bağlam pencereleri](https://platform.claude.com/docs/en/build-with-claude/context-windows) - Bağlam penceresinin, uzun düşünmenin ve araç kullanımının token'ları nasıl tükettiğine dair resmi referans.
- [Agent'lar için etkili bağlam mühendisliği](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents) - Agent'larda bağlam çürümesine karşı bağlam penceresini düzenlemeye dair Anthropic mühendislik rehberi.
- [Uzun süre çalışan agent'lar için etkili harness'lar](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) - Agent ilerlemesini birçok bağlam penceresi ve oturum boyunca sürdürmeye dair Anthropic mühendislik rehberi.
- [Prompt önbellekleme](https://platform.claude.com/docs/en/build-with-claude/prompt-caching) - Tekrarlanan bağlamda gecikmeyi ve maliyeti azaltmak için prompt öneklerini önbelleğe almaya dair resmi rehber.
- [Agent'lar için etkili araçlar yazma](https://www.anthropic.com/engineering/writing-tools-for-agents) - Agent'ların çağırdığı araçları tasarlama, değerlendirme ve optimize etmeye dair Anthropic mühendislik rehberi.

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
- [Claude Code: A Highly Agentic Coding Assistant](https://www.deeplearning.ai/courses/claude-code-a-highly-agentic-coding-assistant) - Anthropic'ten Elie Schoppik ile gerçek dünya Claude Code iş akışları üzerine DeepLearning.AI kısa kursu.
- [Agent Skills with Anthropic](https://www.deeplearning.ai/courses/agent-skills-with-anthropic) - Anthropic ile geliştirilen, Agent Skills yazma ve dağıtma üzerine DeepLearning.AI kısa kursu.
- [MCP: Build Rich-Context AI Apps with Anthropic](https://www.deeplearning.ai/courses/mcp-build-rich-context-ai-apps-with-anthropic) - MCP sunucu ve istemcileri oluşturma, bağlama ve dağıtma üzerine DeepLearning.AI kısa kursu.

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
- [IndyDevDan](https://www.youtube.com/@indydevdan) - Fikir odaklı, spesifikasyon güdümlü Claude Code ve agentic mühendislik anlatımları olan popüler YouTube kanalı.
- [Chain of Thought (Every)](https://every.to/chain-of-thought) - Dan Shipper'ın, Claude ve Anthropic'i sık işleyen, yapay zekayla geliştirme üzerine köşesi ve AI & I podcast'i.

### Topluluklar

- [Claude Community](https://claude.com/community) - Discord, Reddit ve elçi programlarını birbirine bağlayan Anthropic'in resmi topluluk merkezi.
- [r/ClaudeAI](https://www.reddit.com/r/ClaudeAI/) - Claude tartışmaları, ipuçları ve karşılaştırmaları için büyük topluluk subreddit'i.
- [r/ClaudeCode](https://www.reddit.com/r/ClaudeCode/) - Claude Code iş akışları, ipuçları, araçlar ve sorun gidermeye odaklı aktif subreddit.

## Kıyaslamalar ve Liderlik Tabloları

- [SWE-bench](https://www.swebench.com/) - Gerçek GitHub issue çözümünü ölçen, Claude modellerinin en iyiler arasında yer aldığı kıyaslama.
- [Aider Polyglot Leaderboard](https://aider.chat/docs/leaderboards/) - Claude modellerini sıralayan çok dilli kod düzenleme kıyaslaması.
- [Terminal-Bench](https://www.tbench.ai/leaderboard) - Claude modellerini değerlendiren, gerçek terminal görevlerinde agent kıyaslaması.
- [Arena (eski adıyla LMArena / Chatbot Arena)](https://arena.ai) - Claude modellerini içeren insan tercihi LLM liderlik tablosu.
- [GAIA Leaderboard](https://huggingface.co/spaces/gaia-benchmark/leaderboard) - Claude tabanlı agent'ların değerlendirildiği genel yapay zeka asistanı kıyaslaması.
- [Artificial Analysis](https://artificialanalysis.ai) - Claude'u kalite, hız ve fiyat açısından izleyen bağımsız LLM kıyaslama sitesi.
- [ARC-AGI (ARC Prize)](https://arcprize.org) - Genel liderlik tablosu Claude modellerini içeren soyut akıl yürütme kıyaslaması ve ödülü.
- [Design Arena](https://www.designarena.ai) - Claude modellerinin yarıştığı, yapay zeka üretimi tasarım ve arayüz için kitle kaynaklı liderlik tablosu.
- [LiveBench](https://livebench.ai) - Claude modellerinin sıralandığı, aylık değişen sorularla kontaminasyona dirençli LLM kıyaslaması.
- [LiveCodeBench](https://livecodebench.github.io) - Kesim tarihi sonrası problemlerle Claude ve diğer modelleri değerlendiren, kontaminasyonsuz kodlama kıyaslaması.
- [tau-bench](https://github.com/sierra-research/tau-bench) - Claude'un değerlendirilen modeller arasında olduğu, gerçek dünya alanlarında araç-agent-kullanıcı etkileşimi için Sierra kıyaslaması.
- [tau2-bench](https://github.com/sierra-research/tau2-bench) - Gerçek dünya araç kullanımı için Claude modellerini değerlendiren Sierra'nın çift kontrollü agent kıyaslaması.
- [WebArena](https://webarena.dev) - Claude'un değerlendirilen modeller arasında olduğu, otonom agent'lar için gerçekçi, tekrarlanabilir web ortamı kıyaslaması.

## Katkıda Bulunma

Katkılar memnuniyetle karşılanır - tek bir güzel bağlantı bile gayet iyi bir pull request'tir. Lütfen önce [katkı rehberini](../.github/CONTRIBUTING.md) okuyun. Kısaca: girdileri Claude'la ilgili, yüksek kaliteli, tekrarsız tutun ve `- [Ad](https://url) - kısa, olgusal açıklama.` biçiminde yazın. Çeviriler `translations/` klasöründe yer alır.
