<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-TF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>群組規範互動閱覽器</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', 'Noto Sans TC', sans-serif; /* Added Noto Sans TC for better Chinese character rendering */
        }
        .tab-button {
            padding: 0.75rem 1.5rem;
            cursor: pointer;
            border-bottom: 2px solid transparent;
            transition: all 0.3s ease;
            font-weight: 500;
        }
        .tab-button.active {
            border-bottom-color: #0284c7; /* sky-600 */
            color: #0284c7; /* sky-600 */
            font-weight: 600;
        }
        .tab-button:hover {
            background-color: #f0f9ff; /* sky-50 */
        }
        .content-section {
            display: none;
        }
        .content-section.active {
            display: block;
        }
        .article-item {
            padding: 0.75rem;
            border: 1px solid #e5e7eb; /* gray-200 */
            border-radius: 0.375rem; /* rounded-md */
            margin-bottom: 0.75rem;
            background-color: #ffffff; /* white */
        }
        .article-item.highlight {
            background-color: #ecfccb; /* lime-100, for highlighting search results */
            border-left: 4px solid #4d7c0f; /* lime-700 */
        }
        .chapter-title-main {
            font-size: 1.5rem; /* text-2xl */
            font-weight: 600;
            color: #1f2937; /* gray-800 */
            margin-top: 1.5rem;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 1px solid #d1d5db; /* gray-300 */
        }
         .article-title {
            font-weight: bold;
            color: #374151; /* gray-700 */
        }
        .search-input {
            width: 100%;
            padding: 0.75rem 1rem;
            border: 1px solid #d1d5db; /* gray-300 */
            border-radius: 0.375rem; /* rounded-md */
            margin-bottom: 1.5rem;
            box-shadow: inset 0 1px 2px 0 rgb(0 0 0 / 0.05);
        }
        .intro-paragraph {
            margin-bottom: 1.5rem;
            color: #4b5563; /* gray-600 */
            line-height: 1.75;
        }
        .section-container {
            max-height: 70vh;
            overflow-y: auto;
            padding-right: 1rem; /* For scrollbar */
        }
        /* Custom scrollbar for webkit browsers */
        .section-container::-webkit-scrollbar {
            width: 8px;
        }
        .section-container::-webkit-scrollbar-track {
            background: #f1f5f9; /* slate-100 */
            border-radius: 10px;
        }
        .section-container::-webkit-scrollbar-thumb {
            background: #94a3b8; /* slate-400 */
            border-radius: 10px;
        }
        .section-container::-webkit-scrollbar-thumb:hover {
            background: #64748b; /* slate-500 */
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800 min-h-screen">
    <div class="container mx-auto px-4 py-8 max-w-6xl">
        <header class="text-center mb-8">
            <h1 class="text-4xl font-bold text-sky-700">群組規範互動閱覽器</h1>
        </header>

        <nav class="flex justify-center border-b border-gray-300 mb-6 bg-white shadow-sm rounded-t-lg">
            <button class="tab-button active" data-tab-target="#content-constitution">群組憲法</button>
            <button class="tab-button" data-tab-target="#content-penal">群組刑法</button>
            <button class="tab-button" data-tab-target="#content-civil">群組民法</button>
        </nav>

        <main>
            <div id="content-constitution" class="content-section active bg-white p-6 rounded-b-lg shadow">
                <p class="intro-paragraph">
                    本節詳細介紹「群組憲法」的各項條文。群組憲法是本社群運作的最高準則，確立了群組的宗旨、目標、成員的基本權利與義務，以及組織架構和重要修改原則。您可以透過下方的章節導覽或使用搜尋功能來查找特定內容，以充分理解本社群的治理框架。
                </p>
                <input type="text" id="search-constitution" class="search-input" placeholder="搜尋憲法條文內容...">
                <div class="section-container">
                    <div class="chapter-group">
                        <h2 class="chapter-title-main">第一章：總綱</h2>
                        <div class="article-item" data-searchable-content="第一條： 本群組之正式名稱經核定為「ＸＸ群組」（此處應填入群組之專屬名稱）。"><span class="article-title">第一條：</span> 本群組之正式名稱經核定為「ＸＸ群組」（此處應填入群組之專屬名稱）。</div>
                        <div class="article-item" data-searchable-content="第二條： 本群組之設立宗旨，旨在（此處應簡要闡述群組之成立目的與目標，例如：提供成員間之交流平台、促進資訊之分享、組織各類活動等）。"><span class="article-title">第二條：</span> 本群組之設立宗旨，旨在（此處應簡要闡述群組之成立目的與目標，例如：提供成員間之交流平台、促進資訊之分享、組織各類活動等）。</div>
                        <div class="article-item" data-searchable-content="第三條： 本群組之性質界定為（社團/討論群組/或其他具體性質），其成員組成主要由（學生/特定同好/或其他特定群體）構成。"><span class="article-title">第三條：</span> 本群組之性質界定為（社團/討論群組/或其他具體性質），其成員組成主要由（學生/特定同好/或其他特定群體）構成。</div>
                        <div class="article-item" data-searchable-content="第四條： 本群組之具體目標為：（此處應詳述群組之特定目標，例如：促進成員間之深度交流、共同學習與成長）。"><span class="article-title">第四條：</span> 本群組之具體目標為：（此處應詳述群組之特定目標，例如：促進成員間之深度交流、共同學習與成長）。</div>
                        <div class="article-item" data-searchable-content="第五條： 本群組成員應享有以下權利： 發言權： 自由發表言論之權利應受保障，惟其內容不得牴觸本憲法及其他相關群組規定。 參與權： 參與群組所舉辦之各項活動，並對群組事務提出建議之權利應予確立。 平等權： 於群組內部，所有成員應享有平等地位，任何形式之歧視，無論基於性別、性傾向、宗教、種族、社經地位或其他因素，均應被嚴格禁止。 隱私權： 個人資料及隱私應受嚴密保護，未經當事人明確同意，任何資訊均不得公開揭露。 知情權： 對於群組之運作模式、財務狀況（如適用）及其他相關資訊，成員應擁有充分之知悉權利。 選舉權與被選舉權： 如設有相關制度，成員應擁有參與管理員選舉之權利，並具備被推選為管理員之資格。"><span class="article-title">第五條：</span> 本群組成員應享有以下權利：<ul class="list-disc list-inside ml-4 mt-2"><li><strong>發言權：</strong> 自由發表言論之權利應受保障，惟其內容不得牴觸本憲法及其他相關群組規定。</li><li><strong>參與權：</strong> 參與群組所舉辦之各項活動，並對群組事務提出建議之權利應予確立。</li><li><strong>平等權：</strong> 於群組內部，所有成員應享有平等地位，任何形式之歧視，無論基於性別、性傾向、宗教、種族、社經地位或其他因素，均應被嚴格禁止。</li><li><strong>隱私權：</strong> 個人資料及隱私應受嚴密保護，未經當事人明確同意，任何資訊均不得公開揭露。</li><li><strong>知情權：</strong> 對於群組之運作模式、財務狀況（如適用）及其他相關資訊，成員應擁有充分之知悉權利。</li><li><strong>選舉權與被選舉權：</strong> 如設有相關制度，成員應擁有參與管理員選舉之權利，並具備被推選為管理員之資格。</li></ul></div>
                        <div class="article-item" data-searchable-content="第六條： 本群組成員應履行以下義務： 本憲法及其他群組規定應被嚴格遵守。 對其他成員之尊重應被維護，群組內部和諧之氛圍應被共同營造。 積極參與群組活動，共同促進群組之發展應被視為義務。 對群組事務之積極參與及建議之提出應被鼓勵。 協助推廣群組宗旨，擴大群組影響力之行動應被支持。"><span class="article-title">第六條：</span> 本群組成員應履行以下義務：<ul class="list-disc list-inside ml-4 mt-2"><li>本憲法及其他群組規定應被嚴格遵守。</li><li>對其他成員之尊重應被維護，群組內部和諧之氛圍應被共同營造。</li><li>積極參與群組活動，共同促進群組之發展應被視為義務。</li><li>對群組事務之積極參與及建議之提出應被鼓勵。</li><li>協助推廣群組宗旨，擴大群組影響力之行動應被支持。</li></ul></div>
                        <div class="article-item" data-searchable-content="第七條： 管理員之產生，應由創辦管理員或經群組成員推選而確立，其職責在於執行本憲法及其他群組規定，並負責群組之日常事務管理。管理員之行為應對群組成員負責，並接受成員之監督。"><span class="article-title">第七條：</span> 管理員之產生，應由創辦管理員或經群組成員推選而確立，其職責在於執行本憲法及其他群組規定，並負責群組之日常事務管理。管理員之行為應對群組成員負責，並接受成員之監督。</div>
                        <div class="article-item" data-searchable-content="第八條： 本憲法之修正，須經憲法修改法務部三分之二以上人員之同意方可生效。憲法修改法務部之組成方式、成員資格及議事規則等細節，將另行訂定。"><span class="article-title">第八條：</span> 本憲法之修正，須經憲法修改法務部三分之二以上人員之同意方可生效。憲法修改法務部之組成方式、成員資格及議事規則等細節，將另行訂定。</div>
                    </div>
                    <div class="chapter-group">
                        <h2 class="chapter-title-main">第二章：基本權利與義務</h2>
                        <div class="article-item" data-searchable-content="第九條： 成員之言論自由應受保障，惟以下類型之言論發表應被嚴格禁止： 煽動暴力、仇恨或歧視之言論。 涉及色情、猥褻或人身攻擊性質之言論。 侵犯他人智慧財產權之言論。 可能對群組聲譽造成負面影響之言論。"><span class="article-title">第九條：</span> 成員之言論自由應受保障，惟以下類型之言論發表應被嚴格禁止：<ul class="list-disc list-inside ml-4 mt-2"><li>煽動暴力、仇恨或歧視之言論。</li><li>涉及色情、猥褻或人身攻擊性質之言論。</li><li>侵犯他人智慧財產權之言論。</li><li>可能對群組聲譽造成負面影響之言論。</li></ul></div>
                        <div class="article-item" data-searchable-content="第九條之一： 群組內部之所有資訊傳遞及言論發表，均應以事實為基礎，力求真實性與準確性。任何刻意散布非事實事件或言論之行為，均應被嚴格禁止。"><span class="article-title">第九條之一：</span> 群組內部之所有資訊傳遞及言論發表，均應以事實為基礎，力求真實性與準確性。任何刻意散布非事實事件或言論之行為，均應被嚴格禁止。</div>
                        <div class="article-item" data-searchable-content="第九條之二： 對於群組相關之任何文書或電子文件，其製作與使用應秉持誠信原則。任何形式之偽造、變造或不實記載之行為，均應被嚴格禁止。"><span class="article-title">第九條之二：</span> 對於群組相關之任何文書或電子文件，其製作與使用應秉持誠信原則。任何形式之偽造、變造或不實記載之行為，均應被嚴格禁止。</div>
                        <div class="article-item" data-searchable-content="第十條： 成員參與群組活動之權利應受保障，並允許其對活動內容及形式提出建議。"><span class="article-title">第十條：</span> 成員參與群組活動之權利應受保障，並允許其對活動內容及形式提出建議。</div>
                        <div class="article-item" data-searchable-content="第十一條： 成員間之意見交流應基於相互尊重及理性討論之原則，任何形式之人身攻擊或謾罵行為均應被禁止。"><span class="article-title">第十一條：</span> 成員間之意見交流應基於相互尊重及理性討論之原則，任何形式之人身攻擊或謾罵行為均應被禁止。</div>
                        <div class="article-item" data-searchable-content="第十二條： 群組秩序之維護應為所有成員之共同責任，洗版或惡意灌水等行為應被嚴格禁止。"><span class="article-title">第十二條：</span> 群組秩序之維護應為所有成員之共同責任，洗版或惡意灌水等行為應被嚴格禁止。</div>
                        <div class="article-item" data-searchable-content="第十三條： 成員應被賦予參與群組事務討論及提出建議之權利。對於群組之決策，成員應享有表達意見之權利。"><span class="article-title">第十三條：</span> 成員應被賦予參與群組事務討論及提出建議之權利。對於群組之決策，成員應享有表達意見之權利。</div>
                        <div class="article-item" data-searchable-content="第十四條： 成員對群組之財務狀況（如適用）及管理運作應具備知情權，管理員應定期公開相關資訊，並接受成員之監督。"><span class="article-title">第十四條：</span> 成員對群組之財務狀況（如適用）及管理運作應具備知情權，管理員應定期公開相關資訊，並接受成員之監督。</div>
                    </div>
                    <div class="chapter-group">
                        <h2 class="chapter-title-main">第三章：群組組織</h2>
                        <div class="article-item" data-searchable-content="第十五條： 本群組應設置若干名管理員，負責群組之日常管理職務。其產生方式及任期等細節，應於群組章程中予以明確規定。"><span class="article-title">第十五條：</span> 本群組應設置若干名管理員，負責群組之日常管理職務。其產生方式及任期等細節，應於群組章程中予以明確規定。</div>
                        <div class="article-item" data-searchable-content="第十六條： 管理員之職責範疇應包含以下項目： 執行群組憲法及相關規定。 審核成員之發言內容，並處理違規行為。 組織群組活動，以促進成員間之交流。 召開群組會議，並聽取成員之意見。 代表群組對外發言（如情況需要）。 其他應盡之職責。"><span class="article-title">第十六條：</span> 管理員之職責範疇應包含以下項目：<ul class="list-disc list-inside ml-4 mt-2"><li>執行群組憲法及相關規定。</li><li>審核成員之發言內容，並處理違規行為。</li><li>組織群組活動，以促進成員間之交流。</li><li>召開群組會議，並聽取成員之意見。</li><li>代表群組對外發言（如情況需要）。</li><li>其他應盡之職責。</li></ul></div>
                        <div class="article-item" data-searchable-content="第十七條： 群組會議之召集應由管理員負責，所有成員均有權參與。群組會議可區分為不定期會議及臨時會議。"><span class="article-title">第十七條：</span> 群組會議之召集應由管理員負責，所有成員均有權參與。群組會議可區分為不定期會議及臨時會議。</div>
                        <div class="article-item" data-searchable-content="第十八條： 群組會議之決議，除憲法修正案外，應經出席成員過半數之同意方可通過。對於重要事項之決議，得採特別多數決之方式。"><span class="article-title">第十八條：</span> 群組會議之決議，除憲法修正案外，應經出席成員過半數之同意方可通過。對於重要事項之決議，得採特別多數決之方式。</div>
                        <div class="article-item" data-searchable-content="第十九條： 群組之更新應被作成更新紀錄，並於群組內部公開。"><span class="article-title">第十九條：</span> 群組之更新應被作成更新紀錄，並於群組內部公開。</div>
                        <div class="article-item" data-searchable-content="第二十條： 本群組應設立監察機制，其職責在於監督管理員之運作，並受理成員之申訴。監察機制之組成及職權等細節，應於群組章程中予以明確規定。"><span class="article-title">第二十條：</span> 本群組應設立監察機制，其職責在於監督管理員之運作，並受理成員之申訴。監察機制之組成及職權等細節，應於群組章程中予以明確規定。</div>
                    </div>
                    <div class="chapter-group">
                        <h2 class="chapter-title-main">修改說明</h2>
                        <div class="article-item" data-searchable-content="修改說明： 關於群組性質、目標與成員組成之明確化，以利群組定位之確立： 透過對群組性質（例如：學術交流社群、興趣同好會、專業討論區等）及主要成員構成（例如：特定專業人士、學生族群、某領域愛好者等）進行精確界定，可有效吸引目標受眾，避免群組內容之發散，並確保成員間具備共同之基礎與交流範疇。此種清晰之定位對於群組文化之塑形、成員發言方向之引導，以及未來活動規劃之明確指引，均具有關鍵意義。例如，一個以「程式設計學習」為核心目標之群組，其內容與活動自將圍繞程式語言、專案實作、技術分享等相關議題，而非其他不相干之主題。 關於成員權利之擴充，尤其納入知情權、選舉權與被選舉權，以強化成員權益之保障： 賦予成員更為全面之權利，乃建立公平透明群組環境之基石。 知情權之確立，旨在確保成員能夠充分了解群組之運作狀況、重要決策程序，乃至於財務收支（如適用）等資訊。此舉有助於提升成員對管理團隊之信任感，並能及時發現潛在問題。例如，管理員應定期發布群組公告，詳述近期活動、重要決議或資源使用情況。 選舉權與被選舉權之引入，則進一步強化了成員之參與感與歸屬感，使成員有機會透過民主程序推選或擔任群組之管理者，直接影響群組之發展方向。此不僅有助於選出更具代表性之管理團隊，亦能促進管理員與成員間之良性互動與溝通。 關於成員義務之強化，尤其增訂積極參與群組事務及協助推廣群組宗旨之條款： 權利與義務之關係乃相輔相成。除基本之遵守規定與尊重他人外，鼓勵成員積極參與群組事務（例如：參與討論、提供建議、協助活動籌辦），可有效匯聚群體之智慧與力量，共同推動群組之發展。同時，協助推廣群組宗旨，例如邀請志同道合之人士加入、分享群組之優質內容，將有助於擴大群組之影響力與規模，吸引更多潛在成員，進而形成正向循環。 關於管理員職責之完善，尤其增訂對成員負責、接受監督及定期公開財務之條款： 管理員作為群組之執行者，其職責之明確化至關重要。 「對成員負責」意指管理員之行為應以群組成員之整體利益為依歸，而非個人私利。 「接受監督」則要求管理員之決策與行為應能經受成員之檢視，例如可設立意見回饋管道或定期舉辦問答環節。 「定期公開財務」儘管原財務章節已移除，但其核心精神仍可體現於管理員對資源使用之透明度上。即使無實際金錢往來，對於群組活動之資源分配、物資使用等，亦應保持公開，以建立成員之信任，確保群組運作之公正性與廉潔性，避免潛在之爭議或不滿。 關於群組會議種類、決議方式與會議紀錄之明確規定，以提升群組運作之透明度： 規範化之會議機制乃群組高效運作之保障。 明確會議種類（例如：定期例會、臨時緊急會議）有助於區分不同事項之處理時效與重要性。 「決議方式」之規定（例如：過半數同意、特別多數決）確保了決策之合法性與代表性，避免少數人專斷。 要求「會議紀錄」之作成與公開，則能為群組之發展留下清晰之軌跡，方便成員回溯重要決議，亦可作為未來管理員交接或新人了解群組歷史之重要參考資料，進而提升群組治理之透明度與延續性。 關於監察機制之增訂，以強化群組之監督功能： 獨立之監察機制對於維護群組之健康發展至關重要。其可作為管理員權力之制衡，受理成員之申訴，調查潛在之違規行為或不當管理，從而保障成員之權益，並提升群組之公信力。即使群組規模較小，亦可由部分成員輪流擔任監察角色，以確保權力不被濫用，促進群組之長期穩定與和諧。 關於附則之增訂，以確保憲法施行之順暢性： 附則之存在為憲法提供了必要之彈性。其允許在憲法未涵蓋或未來可能出現之新情況下，透過群組會議決議制定補充細則，以應對不斷變化之群組需求與外部環境。此舉確保了憲法不會因僵化而失去效力，而是能隨著群組之成長與演變，持續保持其適用性與指導性，使群組治理更具韌性。">
                            <ul class="list-disc list-inside ml-4 space-y-3">
                                <li><strong>關於群組性質、目標與成員組成之明確化，以利群組定位之確立：</strong> 透過對群組性質（例如：學術交流社群、興趣同好會、專業討論區等）及主要成員構成（例如：特定專業人士、學生族群、某領域愛好者等）進行精確界定，可有效吸引目標受眾，避免群組內容之發散，並確保成員間具備共同之基礎與交流範疇。此種清晰之定位對於群組文化之塑形、成員發言方向之引導，以及未來活動規劃之明確指引，均具有關鍵意義。例如，一個以「程式設計學習」為核心目標之群組，其內容與活動自將圍繞程式語言、專案實作、技術分享等相關議題，而非其他不相干之主題。</li>
                                <li><strong>關於成員權利之擴充，尤其納入知情權、選舉權與被選舉權，以強化成員權益之保障：</strong> 賦予成員更為全面之權利，乃建立公平透明群組環境之基石。
                                    <ul class="list-circle list-inside ml-6 mt-1 space-y-1">
                                        <li><strong>知情權</strong>之確立，旨在確保成員能夠充分了解群組之運作狀況、重要決策程序，乃至於財務收支（如適用）等資訊。此舉有助於提升成員對管理團隊之信任感，並能及時發現潛在問題。例如，管理員應定期發布群組公告，詳述近期活動、重要決議或資源使用情況。</li>
                                        <li><strong>選舉權與被選舉權</strong>之引入，則進一步強化了成員之參與感與歸屬感，使成員有機會透過民主程序推選或擔任群組之管理者，直接影響群組之發展方向。此不僅有助於選出更具代表性之管理團隊，亦能促進管理員與成員間之良性互動與溝通。</li>
                                    </ul>
                                </li>
                                <li><strong>關於成員義務之強化，尤其增訂積極參與群組事務及協助推廣群組宗旨之條款：</strong> 權利與義務之關係乃相輔相成。除基本之遵守規定與尊重他人外，鼓勵成員積極參與群組事務（例如：參與討論、提供建議、協助活動籌辦），可有效匯聚群體之智慧與力量，共同推動群組之發展。同時，協助推廣群組宗旨，例如邀請志同道合之人士加入、分享群組之優質內容，將有助於擴大群組之影響力與規模，吸引更多潛在成員，進而形成正向循環。</li>
                                <li><strong>關於管理員職責之完善，尤其增訂對成員負責、接受監督及定期公開財務之條款：</strong> 管理員作為群組之執行者，其職責之明確化至關重要。
                                    <ul class="list-circle list-inside ml-6 mt-1 space-y-1">
                                        <li>「對成員負責」意指管理員之行為應以群組成員之整體利益為依歸，而非個人私利。</li>
                                        <li>「接受監督」則要求管理員之決策與行為應能經受成員之檢視，例如可設立意見回饋管道或定期舉辦問答環節。</li>
                                        <li>「定期公開財務」儘管原財務章節已移除，但其核心精神仍可體現於管理員對資源使用之透明度上。即使無實際金錢往來，對於群組活動之資源分配、物資使用等，亦應保持公開，以建立成員之信任，確保群組運作之公正性與廉潔性，避免潛在之爭議或不滿。</li>
                                    </ul>
                                </li>
                                <li><strong>關於群組會議種類、決議方式與會議紀錄之明確規定，以提升群組運作之透明度：</strong> 規範化之會議機制乃群組高效運作之保障。
                                    <ul class="list-circle list-inside ml-6 mt-1 space-y-1">
                                        <li>明確會議種類（例如：定期例會、臨時緊急會議）有助於區分不同事項之處理時效與重要性。</li>
                                        <li>「決議方式」之規定（例如：過半數同意、特別多數決）確保了決策之合法性與代表性，避免少數人專斷。</li>
                                        <li>要求「會議紀錄」之作成與公開，則能為群組之發展留下清晰之軌跡，方便成員回溯重要決議，亦可作為未來管理員交接或新人了解群組歷史之重要參考資料，進而提升群組治理之透明度與延續性。</li>
                                    </ul>
                                </li>
                                <li><strong>關於監察機制之增訂，以強化群組之監督功能：</strong> 獨立之監察機制對於維護群組之健康發展至關重要。其可作為管理員權力之制衡，受理成員之申訴，調查潛在之違規行為或不當管理，從而保障成員之權益，並提升群組之公信力。即使群組規模較小，亦可由部分成員輪流擔任監察角色，以確保權力不被濫用，促進群組之長期穩定與和諧。</li>
                                <li><strong>關於附則之增訂，以確保憲法施行之順暢性：</strong> 附則之存在為憲法提供了必要之彈性。其允許在憲法未涵蓋或未來可能出現之新情況下，透過群組會議決議制定補充細則，以應對不斷變化之群組需求與外部環境。此舉確保了憲法不會因僵化而失去效力，而是能隨著群組之成長與演變，持續保持其適用性與指導性，使群組治理更具韌性。</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>

            <div id="content-penal" class="content-section bg-white p-6 rounded-b-lg shadow">
                <p class="intro-paragraph">
                    本節闡述「群組刑法」之相關規定。群組刑法旨在規範成員行為，明確違規事項及相應處罰，以維護群組秩序與成員權益。請仔細閱讀各章節條文，或利用搜尋功能查找特定規範。
                </p>
                <input type="text" id="search-penal" class="search-input" placeholder="搜尋刑法條文內容...">
                <div class="section-container">
                    <div class="chapter-group">
                        <h2 class="chapter-title-main">第一章：總則</h2>
                        <div class="article-item" data-searchable-content="第一條： 本刑法之適用範圍應涵蓋所有群組成員。"><span class="article-title">第一條：</span> 本刑法之適用範圍應涵蓋所有群組成員。</div>
                        <div class="article-item" data-searchable-content="第二條： 凡違反群組規定之行為，均應依本刑法之規定予以處罰。"><span class="article-title">第二條：</span> 凡違反群組規定之行為，均應依本刑法之規定予以處罰。</div>
                        <div class="article-item" data-searchable-content="第三條： 處罰之種類茲列舉如下： 警告： 包含口頭或書面形式之告誡。此類處罰適用於初次違規或情節輕微之行為，旨在提醒違規者其行為已偏離群組規範，並促使其改正。 禁言： 限制其發言權利之行使，其期限可依違規情節之輕重予以裁定。此類處罰旨在遏止持續性或對群組秩序造成一定干擾之言論違規行為，以維護群組交流環境之清淨。 踢出： 移除其群組成員資格。此類處罰適用於情節較為嚴重，或經警告、禁言後仍未改正之違規行為，旨在將對群組造成負面影響之成員排除於群體之外。 除名： 永久性移除其群組成員資格，並應對外公告周知。此類處罰為最嚴厲之制裁，僅適用於嚴重破壞群組核心價值、造成重大損害或屢次惡意違規且無悔改之意圖者，以維護群組之整體利益與聲譽。"><span class="article-title">第三條：</span> 處罰之種類茲列舉如下：<ul class="list-disc list-inside ml-4 mt-2"><li><strong>警告：</strong> 包含口頭或書面形式之告誡。此類處罰適用於初次違規或情節輕微之行為，旨在提醒違規者其行為已偏離群組規範，並促使其改正。</li><li><strong>禁言：</strong> 限制其發言權利之行使，其期限可依違規情節之輕重予以裁定。此類處罰旨在遏止持續性或對群組秩序造成一定干擾之言論違規行為，以維護群組交流環境之清淨。</li><li><strong>踢出：</strong> 移除其群組成員資格。此類處罰適用於情節較為嚴重，或經警告、禁言後仍未改正之違規行為，旨在將對群組造成負面影響之成員排除於群體之外。</li><li><strong>除名：</strong> 永久性移除其群組成員資格，並應對外公告周知。此類處罰為最嚴厲之制裁，僅適用於嚴重破壞群組核心價值、造成重大損害或屢次惡意違規且無悔改之意圖者，以維護群組之整體利益與聲譽。</li></ul></div>
                        <div class="article-item" data-searchable-content="第四條： 處罰之輕重，應審慎考量違規行為之動機、所採手段、情節嚴重性及所造成之影響等諸多因素。管理員於裁量時，應秉持客觀公正之原則，確保處罰之適當性與比例原則。"><span class="article-title">第四條：</span> 處罰之輕重，應審慎考量違規行為之動機、所採手段、情節嚴重性及所造成之影響等諸多因素。管理員於裁量時，應秉持客觀公正之原則，確保處罰之適當性與比例原則。</div>
                        <div class="article-item" data-searchable-content="第五條： 管理員應被賦予執行本刑法之權力，並得視具體情況，酌情從輕或從重予以處罰。此項權力之行使，應以維護群組整體利益及秩序為最高指導原則。"><span class="article-title">第五條：</span> 管理員應被賦予執行本刑法之權力，並得視具體情況，酌情從輕或從重予以處罰。此項權力之行使，應以維護群組整體利益及秩序為最高指導原則。</div>
                        <div class="article-item" data-searchable-content="第六條： 本刑法之解釋與適用，應以符合本憲法之精神為前提，並應避免任何可能導致歧視或不公之情形。"><span class="article-title">第六條：</span> 本刑法之解釋與適用，應以符合本憲法之精神為前提，並應避免任何可能導致歧視或不公之情形。</div>
                        <div class="article-item" data-searchable-content="第七條： 為維護群組秩序之安定，管理員得採取必要之即時處置措施，此等措施包含但不限於刪除違規內容、暫停成員發言權利等。此類措施之目的在於迅速制止違規行為之擴散，降低其對群組造成之潛在損害。"><span class="article-title">第七條：</span> 為維護群組秩序之安定，管理員得採取必要之即時處置措施，此等措施包含但不限於刪除違規內容、暫停成員發言權利等。此類措施之目的在於迅速制止違規行為之擴散，降低其對群組造成之潛在損害。</div>
                        <div class="article-item" data-searchable-content="第八條： 若成員之違規行為同時牴觸本群組憲法及刑法之規定，則得合併予以處罰。此原則旨在確保對違規行為之全面性處理，以維護群組規範體系之完整性與權威性。"><span class="article-title">第八條：</span> 若成員之違規行為同時牴觸本群組憲法及刑法之規定，則得合併予以處罰。此原則旨在確保對違規行為之全面性處理，以維護群組規範體系之完整性與權威性。</div>
                    </div>
                     <div class="chapter-group">
                        <h2 class="chapter-title-main">第二章：分則</h2>
                        <div class="article-item" data-searchable-content="第九條： 凡有以下行為之一者，應處以警告： 初次違反群組規定，且經評估其情節屬輕微者。此類行為通常不涉及對他人之實質損害或對群組秩序之重大干擾。 使用不雅言詞，惟經判斷其語氣或內容未造成顯著不良影響，且無惡意者。 未經其他成員明確同意而轉發其發言，但經發現後已立即自行刪除，並未造成不良後果者。 其他經管理員依據本刑法之精神，認定應處以警告之行為。"><span class="article-title">第九條：</span> 凡有以下行為之一者，應處以警告：<ul class="list-disc list-inside ml-4 mt-2"><li>初次違反群組規定，且經評估其情節屬輕微者。此類行為通常不涉及對他人之實質損害或對群組秩序之重大干擾。</li><li>使用不雅言詞，惟經判斷其語氣或內容未造成顯著不良影響，且無惡意者。</li><li>未經其他成員明確同意而轉發其發言，但經發現後已立即自行刪除，並未造成不良後果者。</li><li>其他經管理員依據本刑法之精神，認定應處以警告之行為。</li></ul></div>
                        <div class="article-item" data-searchable-content="第十條： 凡有以下行為之一者，應處以禁言： 屢次違反群組規定，經警告後仍無改善，或其行為已對群組秩序造成持續性干擾者。 使用不雅言詞，且經判斷已造成不良影響或引發成員不適者。 惡意洗版、灌水或其他形式之濫用群組資源，導致正常交流受阻者。 其他經管理員依據本刑法之精神，認定應處以禁言之行為。禁言期限之設定應與違規情節相符。"><span class="article-title">第十條：</span> 凡有以下行為之一者，應處以禁言：<ul class="list-disc list-inside ml-4 mt-2"><li>屢次違反群組規定，經警告後仍無改善，或其行為已對群組秩序造成持續性干擾者。</li><li>使用不雅言詞，且經判斷已造成不良影響或引發成員不適者。</li><li>惡意洗版、灌水或其他形式之濫用群組資源，導致正常交流受阻者。</li><li>其他經管理員依據本刑法之精神，認定應處以禁言之行為。禁言期限之設定應與違規情節相符。</li></ul></div>
                        <div class="article-item" data-searchable-content="第十一條： 凡有以下行為之一者，應處以踢出： 違反群組規定，且經評估其情節屬重大者，例如對群組聲譽造成實質損害或嚴重破壞群組和諧者。 對其他成員進行人身攻擊、惡意謾罵或誹謗，且造成受害者之精神或名譽損害者。 散布涉及色情、暴力、恐怖主義或其他違反法律規定之內容者。 從事未經許可之商業廣告、詐騙、釣魚或其他以謀取私利為目的之行為，並對群組成員造成潛在風險或實際損害者。 其他經管理員依據本刑法之精神，認定應處以踢出之行為。"><span class="article-title">第十一條：</span> 凡有以下行為之一者，應處以踢出：<ul class="list-disc list-inside ml-4 mt-2"><li>違反群組規定，且經評估其情節屬重大者，例如對群組聲譽造成實質損害或嚴重破壞群組和諧者。</li><li>對其他成員進行人身攻擊、惡意謾罵或誹謗，且造成受害者之精神或名譽損害者。</li><li>散布涉及色情、暴力、恐怖主義或其他違反法律規定之內容者。</li><li>從事未經許可之商業廣告、詐騙、釣魚或其他以謀取私利為目的之行為，並對群組成員造成潛在風險或實際損害者。</li><li>其他經管理員依據本刑法之精神，認定應處以踢出之行為。</li></ul></div>
                        <div class="article-item" data-searchable-content="第十二條： 凡有以下行為之一者，應處以除名： 嚴重破壞群組秩序，並造成難以彌補之實質損害，致使群組運作遭受嚴重影響者。 組織、煽動或參與群組成員進行任何形式之違法活動，或對群組外部造成負面法律後果者。 對群組造成重大且不可逆之損害，並經全體管理員一致決議，認為其行為已嚴重背離群組宗旨與核心價值者。 其他經管理員依據本刑法之精神，認定應處以除名之行為。此類處罰通常為永久性，且應視情況對外公告，以維護群組之純潔性與警示其他成員。"><span class="article-title">第十二條：</span> 凡有以下行為之一者，應處以除名：<ul class="list-disc list-inside ml-4 mt-2"><li>嚴重破壞群組秩序，並造成難以彌補之實質損害，致使群組運作遭受嚴重影響者。</li><li>組織、煽動或參與群組成員進行任何形式之違法活動，或對群組外部造成負面法律後果者。</li><li>對群組造成重大且不可逆之損害，並經全體管理員一致決議，認為其行為已嚴重背離群組宗旨與核心價值者。</li><li>其他經管理員依據本刑法之精神，認定應處以除名之行為。此類處罰通常為永久性，且應視情況對外公告，以維護群組之純潔性與警示其他成員。</li></ul></div>
                    </div>
                    <div class="chapter-group">
                        <h2 class="chapter-title-main">第三章：非事實事件或言論之罪責</h2>
                        <div class="article-item" data-searchable-content="第十三條： 凡成員故意散布非事實事件、虛假資訊或惡意言論，足以損害其他成員之名譽、隱私、財產權益，或對群組之正常運作及公共秩序造成重大干擾者，應依其情節輕重，處以禁言、踢出或除名之處罰。"><span class="article-title">第十三條：</span> 凡成員故意散布非事實事件、虛假資訊或惡意言論，足以損害其他成員之名譽、隱私、財產權益，或對群組之正常運作及公共秩序造成重大干擾者，應依其情節輕重，處以禁言、踢出或除名之處罰。</div>
                        <div class="article-item" data-searchable-content="第十四條： 前條所稱之非事實事件、虛假資訊或惡意言論，係指經查證與客觀事實不符，或經主觀判斷具有惡意攻擊、毀損、煽動性質之內容。"><span class="article-title">第十四條：</span> 前條所稱之非事實事件、虛假資訊或惡意言論，係指經查證與客觀事實不符，或經主觀判斷具有惡意攻擊、毀損、煽動性質之內容。</div>
                        <div class="article-item" data-searchable-content="第十五條： 凡成員明知或可得而知所散布之資訊為非事實，仍執意為之者，其處罰應從重。"><span class="article-title">第十五條：</span> 凡成員明知或可得而知所散布之資訊為非事實，仍執意為之者，其處罰應從重。</div>
                    </div>
                    <div class="chapter-group">
                        <h2 class="chapter-title-main">第四章：偽造文書之罪責</h2>
                        <div class="article-item" data-searchable-content="第十六條： 凡成員偽造、變造群組內部之任何文書、紀錄、證明或其他電子文件，或使用偽造、變造之文書、紀錄、證明或其他電子文件，足以損害群組或成員之權益者，應依其情節輕重，處以踢出或除名之處罰。"><span class="article-title">第十六條：</span> 凡成員偽造、變造群組內部之任何文書、紀錄、證明或其他電子文件，或使用偽造、變造之文書、紀錄、證明或其他電子文件，足以損害群組或成員之權益者，應依其情節輕重，處以踢出或除名之處罰。</div>
                        <div class="article-item" data-searchable-content="第十七條： 前條所稱之文書，包含但不限於群組公告、會議紀錄、成員名單、活動報名表、財務憑證等。"><span class="article-title">第十七條：</span> 前條所稱之文書，包含但不限於群組公告、會議紀錄、成員名單、活動報名表、財務憑證等。</div>
                        <div class="article-item" data-searchable-content="第十八條： 凡成員教唆、幫助或共同實施偽造文書行為者，應與實施者負相同之罪責。"><span class="article-title">第十八條：</span> 凡成員教唆、幫助或共同實施偽造文書行為者，應與實施者負相同之罪責。</div>
                    </div>
                </div>
            </div>

            <div id="content-civil" class="content-section bg-white p-6 rounded-b-lg shadow">
                <p class="intro-paragraph">
                    本節規範「群組民法」之內容。群組民法主要處理成員間的互動行為與權利義務關係，並提供糾紛解決機制。透過本節，您可以了解成員間應如何互動，以及在發生爭議時的處理程序。
                </p>
                <input type="text" id="search-civil" class="search-input" placeholder="搜尋民法條文內容...">
                <div class="section-container">
                    <div class="chapter-group">
                        <h2 class="chapter-title-main">第一章：總則</h2>
                        <div class="article-item" data-searchable-content="第一條： 本民法之適用範圍應涵蓋所有群組成員。"><span class="article-title">第一條：</span> 本民法之適用範圍應涵蓋所有群組成員。</div>
                        <div class="article-item" data-searchable-content="第二條： 群組成員間之互動，應本於誠實信用原則進行，此原則要求所有成員於群組內之行為，無論為言論發表、資訊分享或活動參與，均應以善意為基礎，避免任何欺詐、誤導或損害他人權益之行為。"><span class="article-title">第二條：</span> 群組成員間之互動，應本於誠實信用原則進行，此原則要求所有成員於群組內之行為，無論為言論發表、資訊分享或活動參與，均應以善意為基礎，避免任何欺詐、誤導或損害他人權益之行為。</div>
                        <div class="article-item" data-searchable-content="第三條： 群組成員間所產生之糾紛，應優先透過協商途徑予以解決。此一機制旨在鼓勵當事人以和平、理性之方式，直接溝通並尋求共識，以避免不必要之衝突升級。"><span class="article-title">第三條：</span> 群組成員間所產生之糾紛，應優先透過協商途徑予以解決。此一機制旨在鼓勵當事人以和平、理性之方式，直接溝通並尋求共識，以避免不必要之衝突升級。</div>
                        <div class="article-item" data-searchable-content="第四條： 若協商未能達成共識，當事人得向管理員提出協助調解之請求。管理員作為中立第三方，將介入引導雙方進行對話，並嘗試促成和解。"><span class="article-title">第四條：</span> 若協商未能達成共識，當事人得向管理員提出協助調解之請求。管理員作為中立第三方，將介入引導雙方進行對話，並嘗試促成和解。</div>
                        <div class="article-item" data-searchable-content="第五條： 管理員於執行調解職務時，應秉持中立公正之立場，不得偏袒任何一方，並應以事實為依據，協助雙方釐清爭議點。"><span class="article-title">第五條：</span> 管理員於執行調解職務時，應秉持中立公正之立場，不得偏袒任何一方，並應以事實為依據，協助雙方釐清爭議點。</div>
                        <div class="article-item" data-searchable-content="第六條： 本民法之解釋與適用，應以符合本憲法之精神為前提，並應考量群組之特殊性質與成員之共同利益。任何條文之詮釋，均不得與群組之核心宗旨相悖。"><span class="article-title">第六條：</span> 本民法之解釋與適用，應以符合本憲法之精神為前提，並應考量群組之特殊性質與成員之共同利益。任何條文之詮釋，均不得與群組之核心宗旨相悖。</div>
                    </div>
                    <div class="chapter-group">
                        <h2 class="chapter-title-main">第二章：權利義務關係</h2>
                        <div class="article-item" data-searchable-content="第七條： 成員於群組中發表之言論，應被視為同意其他成員在合理範圍內予以引用。此項原則旨在促進資訊之流通與知識之共享，惟引用時應註明出處，並不得斷章取義或扭曲原意。"><span class="article-title">第七條：</span> 成員於群組中發表之言論，應被視為同意其他成員在合理範圍內予以引用。此項原則旨在促進資訊之流通與知識之共享，惟引用時應註明出處，並不得斷章取義或扭曲原意。</div>
                        <div class="article-item" data-searchable-content="第八條： 成員對於其他成員公開分享之資訊，應享有瀏覽及學習之權利，惟未經原發布者明確同意，不得將其用於商業用途。此條款旨在保護成員之智慧財產權，並防止資訊被不當利用。"><span class="article-title">第八條：</span> 成員對於其他成員公開分享之資訊，應享有瀏覽及學習之權利，惟未經原發布者明確同意，不得將其用於商業用途。此條款旨在保護成員之智慧財產權，並防止資訊被不當利用。</div>
                        <div class="article-item" data-searchable-content="第九條： 成員參與群組活動時，應遵守活動規則，並應注意自身安全。活動規則之制定旨在確保活動之順利進行與參與者之安全，任何違反規則之行為均可能導致參與資格之喪失或相關責任之承擔。"><span class="article-title">第九條：</span> 成員參與群組活動時，應遵守活動規則，並應注意自身安全。活動規則之制定旨在確保活動之順利進行與參與者之安全，任何違反規則之行為均可能導致參與資格之喪失或相關責任之承擔。</div>
                        <div class="article-item" data-searchable-content="第十條： 成員因個人行為導致其他成員遭受損害時，應負擔相應之賠償責任。此損害可包括但不限於名譽損害、財產損失或其他可量化之損失。賠償之範圍與方式應依據損害之實際情況與相關法律原則予以認定。"><span class="article-title">第十條：</span> 成員因個人行為導致其他成員遭受損害時，應負擔相應之賠償責任。此損害可包括但不限於名譽損害、財產損失或其他可量化之損失。賠償之範圍與方式應依據損害之實際情況與相關法律原則予以認定。</div>
                        <div class="article-item" data-searchable-content="第十一條： 成員間之財物借貸、贈與等行為，應由當事人自行負責，群組不介入處理，惟可提供必要之協助。此條款旨在明確群組不承擔成員間私人財物往來之風險，但若有需要，管理員可提供協調或資訊查詢等非直接介入之協助。"><span class="article-title">第十一條：</span> 成員間之財物借貸、贈與等行為，應由當事人自行負責，群組不介入處理，惟可提供必要之協助。此條款旨在明確群組不承擔成員間私人財物往來之風險，但若有需要，管理員可提供協調或資訊查詢等非直接介入之協助。</div>
                        <div class="article-item" data-searchable-content="第十二條： 成員間之交易行為，應確保資訊之公開透明，並應遵守相關法律規定。群組得提供交易平台，惟不負擔交易風險。此條款旨在鼓勵成員間之公平交易，同時明確群組作為平台提供者之責任界限，提醒成員應自行評估交易風險。"><span class="article-title">第十二條：</span> 成員間之交易行為，應確保資訊之公開透明，並應遵守相關法律規定。群組得提供交易平台，惟不負擔交易風險。此條款旨在鼓勵成員間之公平交易，同時明確群組作為平台提供者之責任界限，提醒成員應自行評估交易風險。</div>
                    </div>
                    <div class="chapter-group">
                        <h2 class="chapter-title-main">第三章：糾紛處理</h2>
                        <div class="article-item" data-searchable-content="第十三條： 成員之間發生糾紛時，應首先嘗試以理性、和平之方式進行溝通。此為解決糾紛之首要途徑，旨在透過直接對話化解誤會或分歧。"><span class="article-title">第十三條：</span> 成員之間發生糾紛時，應首先嘗試以理性、和平之方式進行溝通。此為解決糾紛之首要途徑，旨在透過直接對話化解誤會或分歧。</div>
                        <div class="article-item" data-searchable-content="第十四條： 若無法自行解決，當事人得向管理員提出調解申請。申請時應提供相關事實與證據，以便管理員進行初步判斷。"><span class="article-title">第十四條：</span> 若無法自行解決，當事人得向管理員提出調解申請。申請時應提供相關事實與證據，以便管理員進行初步判斷。</div>
                        <div class="article-item" data-searchable-content="第十五條： 管理員於受理調解申請後，應儘速召集雙方當事人進行協商。協商之地點與時間應由管理員協調，並確保雙方均能參與。"><span class="article-title">第十五條：</span> 管理員於受理調解申請後，應儘速召集雙方當事人進行協商。協商之地點與時間應由管理員協調，並確保雙方均能參與。</div>
                        <div class="article-item" data-searchable-content="第十六條： 調解過程中，管理員得基於事實與群組規範，提出解決方案，供雙方當事人參考。此解決方案旨在提供一個公平合理之基礎，以促成雙方達成和解。"><span class="article-title">第十六條：</span> 調解過程中，管理員得基於事實與群組規範，提出解決方案，供雙方當事人參考。此解決方案旨在提供一個公平合理之基礎，以促成雙方達成和解。</div>
                        <div class="article-item" data-searchable-content="第十七條： 調解成立時，雙方當事人應簽署和解協議書，並共同遵守。和解協議書應明確記載雙方之權利義務與解決方案，以作為未來行為之依據。"><span class="article-title">第十七條：</span> 調解成立時，雙方當事人應簽署和解協議書，並共同遵守。和解協議書應明確記載雙方之權利義務與解決方案，以作為未來行為之依據。</div>
                        <div class="article-item" data-searchable-content="第十八條： 若調解未能成立，當事人得自行循法律途徑解決。此條款旨在告知當事人，群組之調解機制僅為非強制性之協助，最終之法律權利仍應由當事人自行主張。"><span class="article-title">第十八條：</span> 若調解未能成立，當事人得自行循法律途徑解決。此條款旨在告知當事人，群組之調解機制僅為非強制性之協助，最終之法律權利仍應由當事人自行主張。</div>
                        <div class="article-item" data-searchable-content="第十九條： 管理員得視情況公告調解結果，以儆效尤，並維護群組秩序。惟當事人之隱私應受保護，公告內容應僅限於事件之概況與最終處理結果，不得揭露個人敏感資訊。"><span class="article-title">第十九條：</span> 管理員得視情況公告調解結果，以儆效尤，並維護群組秩序。惟當事人之隱私應受保護，公告內容應僅限於事件之概況與最終處理結果，不得揭露個人敏感資訊。</div>
                    </div>
                    <div class="chapter-group">
                        <h2 class="chapter-title-main">第四章：非事實事件或言論所生之民事責任</h2>
                        <div class="article-item" data-searchable-content="第二十條： 凡成員因散布非事實事件、虛假資訊或惡意言論，致使其他成員遭受財產損失、名譽損害或精神損害時，應負擔相應之損害賠償責任。此損害賠償之範圍，應涵蓋直接損失及因該非事實事件或言論所導致之合理間接損失。"><span class="article-title">第二十條：</span> 凡成員因散布非事實事件、虛假資訊或惡意言論，致使其他成員遭受財產損失、名譽損害或精神損害時，應負擔相應之損害賠償責任。此損害賠償之範圍，應涵蓋直接損失及因該非事實事件或言論所導致之合理間接損失。</div>
                        <div class="article-item" data-searchable-content="第二十一條： 前條所稱之損害賠償責任，其認定應基於受損害方所提供之確鑿證據，並經管理員或調解機制之審慎評估。賠償金額之確定，應遵循公平合理原則。"><span class="article-title">第二十一條：</span> 前條所稱之損害賠償責任，其認定應基於受損害方所提供之確鑿證據，並經管理員或調解機制之審慎評估。賠償金額之確定，應遵循公平合理原則。</div>
                        <div class="article-item" data-searchable-content="第二十二條： 受損害之成員得請求管理員協助調解，或逕行向散布者主張權利，以維護其合法權益。"><span class="article-title">第二十二條：</span> 受損害之成員得請求管理員協助調解，或逕行向散布者主張權利，以維護其合法權益。</div>
                    </div>
                    <div class="chapter-group">
                        <h2 class="chapter-title-main">第五章：偽造文書所生之民事責任</h2>
                        <div class="article-item" data-searchable-content="第二十三條： 凡成員因偽造、變造或使用偽造、變造之文書，致使其他成員或群組遭受財產損失或其他權益損害時，應負擔相應之損害賠償責任。此損害賠償之範圍，應包含因偽造、變造行為所直接或間接造成之所有可量化損失。"><span class="article-title">第二十三條：</span> 凡成員因偽造、變造或使用偽造、變造之文書，致使其他成員或群組遭受財產損失或其他權益損害時，應負擔相應之損害賠償責任。此損害賠償之範圍，應包含因偽造、變造行為所直接或間接造成之所有可量化損失。</div>
                        <div class="article-item" data-searchable-content="第二十四條： 因偽造、變造文書所簽訂之任何協議或產生之任何權利義務關係，原則上應被視為無效或可撤銷，惟此無效或可撤銷之認定，不應影響善意第三人之合法權益。"><span class="article-title">第二十四條：</span> 因偽造、變造文書所簽訂之任何協議或產生之任何權利義務關係，原則上應被視為無效或可撤銷，惟此無效或可撤銷之認定，不應影響善意第三人之合法權益。</div>
                        <div class="article-item" data-searchable-content="第二十五條： 受損害之成員或群組得請求管理員協助調解，或逕行向偽造、變造或使用者主張權利，以追究其民事責任。"><span class="article-title">第二十五條：</span> 受損害之成員或群組得請求管理員協助調解，或逕行向偽造、變造或使用者主張權利，以追究其民事責任。</div>
                    </div>
                </div>
            </div>
        </main>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const tabs = document.querySelectorAll('.tab-button');
            const contentSections = document.querySelectorAll('.content-section');
            const searchInputs = {
                'content-constitution': document.getElementById('search-constitution'),
                'content-penal': document.getElementById('search-penal'),
                'content-civil': document.getElementById('search-civil')
            };

            // Initialize first tab as active
            if (tabs.length > 0) {
                tabs[0].classList.add('active');
                const initialTargetId = tabs[0].dataset.tabTarget.substring(1); // Remove #
                document.getElementById(initialTargetId).classList.add('active');
            }

            tabs.forEach(tab => {
                tab.addEventListener('click', () => {
                    tabs.forEach(t => t.classList.remove('active'));
                    tab.classList.add('active');

                    const targetId = tab.dataset.tabTarget.substring(1); // Remove #
                    contentSections.forEach(section => {
                        section.classList.remove('active');
                        if (section.id === targetId) {
                            section.classList.add('active');
                        }
                    });
                    // Clear search for the newly activated tab and reset display
                    if (searchInputs[targetId]) {
                       // searchInputs[targetId].value = ''; // Optionally clear search on tab switch
                        filterContent(searchInputs[targetId].value.toLowerCase(), targetId);
                    }
                });
            });

            function filterContent(searchTerm, contentSectionId) {
                const section = document.getElementById(contentSectionId);
                if (!section) return;

                const articles = section.querySelectorAll('.article-item');
                const chapterGroups = section.querySelectorAll('.chapter-group');

                articles.forEach(article => {
                    const content = article.dataset.searchableContent || article.textContent || article.innerText;
                    const isVisible = content.toLowerCase().includes(searchTerm);
                    article.style.display = isVisible ? '' : 'none';
                    if (isVisible && searchTerm) {
                        article.classList.add('highlight');
                    } else {
                        article.classList.remove('highlight');
                    }
                });

                chapterGroups.forEach(group => {
                    const visibleArticlesInGroup = group.querySelectorAll('.article-item[style*="display:"]:not([style*="display: none"])');
                    if (visibleArticlesInGroup.length === 0 && searchTerm) { // Only hide chapter if search term is active
                        group.style.display = 'none';
                    } else {
                        group.style.display = '';
                    }
                });
            }

            Object.keys(searchInputs).forEach(sectionId => {
                const input = searchInputs[sectionId];
                if (input) {
                    input.addEventListener('input', (e) => {
                        filterContent(e.target.value.toLowerCase(), sectionId);
                    });
                }
            });
        });
    </script>
</body>
</html>
