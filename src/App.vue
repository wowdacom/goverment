<template>
  <div id="app">
    <indicator></indicator>
    <Header :outLinkList="outLinkList" ></Header>
    <cover :position="srcRWD('leftCenter', 'centerCenter')" :src="require('../public/mob2_cover.jpg')" :src-web="require('../public/web2_cover.jpg')">
      <h3>政府就是洩漏個資的兇手</h3><h1>數位人權誰來把關？</h1>
    </cover>
    <content-container>
      <p><br></p>
      <p><br></p>
      <p><br></p>
      <p>全世界誰擁有你最多的隱私資料呢？答案不是馬克‧祖克伯（臉書創辦人），而是你每年繳稅的政府。</p>
      <p><br></p>
      <p>為了治理，我們從搖籃到墓地的所有資料，都被政府一手掌握：</p>
      <p><br></p>
      <p><span class="highlight">內政部</span>擁有全國戶政系統，加上「一人一號」的身分證制度，更以此為基底，製發「自然人憑證」，用來報稅及處理金融事務。</p>
      <p><br></p>
      <p><span class="highlight">教育部</span>則有全國各級學校學生的學業成績及必要個資，都可與身分證一號勾串，形成個人圖像（profiling），連學生家長的個資也全都掌控。</p>
      <p><br></p>
      <p><span class="highlight">警政系統</span>則有民眾的不良素行與前科。</p>
      <p><br></p>
      <p><span class="highlight">衛福部</span>依法有強制納保的全民健保資料庫，你曾補了哪顆牙，或不欲人知的隱疾，政府都知道。如此完善的健康資料庫，被製業巨頭視為全球罕有的「研發新藥的資料金礦」。</p>
      <p><br></p>
      <p><br></p>
      
      <p><br></p>
      
    </content-container>
    <DynamicDigit :countNumber="100" unit="次" :amount="65000">
        <span slot="title">超過</span>
        <div><p slot="description">2015年-2016年，共有11個政府機關向網路業者聲請65000多次網路個人資料</p></div>
      </DynamicDigit>
      <p><br></p>
      <DynamicDigit :countNumber="50" unit="件" :amount="20000">
        <span slot="title">超過</span>
        <div><p>每年通訊監察（對人民監聽）案件量超過20000件</p></div>
      </DynamicDigit>
      <p><br></p>
      <DynamicDigit :countNumber="1" unit="%以上" :amount="95">
        <div><p>檢警調辦案單位占總請求數95%以上</p></div>
      </DynamicDigit>
      
    <content-container>
      <p style="font-size:18px;color: #888;margin: 20px 0;">資料來源／2018台灣網路透明度報告</p>
      <p><br></p>
      <p><br></p>
      <p><br></p>
      <h3>駭客視政府為最大「隱私供應商」</h3>
      <p><br></p>
      <p>既然你我都在政府的龐大資料庫中，<b>我們必須關心的是：第一，政府有沒有好好保護個資的能力？第二，政府拿這些資料做了哪些用途？第三，我們有沒有選擇不參加的權利（opt out）？</b></p>
      <p><br></p>
      <p>如何監督政府不濫用個資，是當前數位治理的新挑戰；資安更是動搖國本的課題，一個防護不周，政府機構就會變成駭客眼中最大的「隱私供應商」。</p>
      <p><br></p>
      <p>願景工程團隊採訪各方專家，發現擁有最大人民個資的政府，在數位治理上存有四大風險和兩大迷思：</p>
      <p><br></p>
      <p><br></p>
      <p><br></p>
      <h3>風險一</h3>
      <h3>政府握有最大的人民資料庫</h3>
      <p><br></p>
      <p>政府握有最大量的人民資料，而且不像商業服務你可以拒絕使用，政府要的資料，人民幾乎無權拒絕被蒐集。</p>
      <p><br></p>
      <h4>國安局「查水表」  監控社群網路</h4>
      <p><br></p>
      <p>通訊保障與監察是另一個問題。政府的手伸向網路服務業者及電信業者，要求提供用戶個資，但人民不知道自己被查了。<b>2018年市長選舉期間，國安局通令國內七大情治系統，對網路假消息展開情蒐</b>，許多網紅或意見領袖成為「情治」蒐證對象，嚇壞不少網路鍵盤酸民。</p>
      <p><br></p>
      <p><br></p>
      <p><br></p>
    </content-container>
    <column-one description="「老大哥正在看著你」，2018年市長選舉期間，國安局下令監控社群網路包括詆毀元首等情資。" 
      :src="require('../public/mob2_001.jpg')" :src-web="require('../public/web2_001.jpg')"></column-one>
    <content-container>
      <p><br></p>
      <p><br></p>
      <p>台權會秘書長邱依翎說，網路與雲端科技發達，警方到嫌犯住處找不到犯罪證據，「直接向網路公司調資料」反而有效。當警方要破門而入前需要搜索票，但向網路或電信業者調資料，還沒有妥善的規範。</p>
      <p><br></p>
      <quote text='"「開放政府」須建立索取用戶資料或下架內容的SOP，「刑事訴訟法」及「通訊保障監察法」都需要跟上時代。"'></quote>
      <p><br></p>
      <p>台權會2018年出版<a style="text-decoration: none;color: #4356ff;" href="https://www.tahr.org.tw/publication/2241" target="_blank">《2018台灣網路透明度報告》</a>，從2015年至2016年間，共有11個政府機關向LINE、Facebook等業者聲請65000多次網路個人資料，檢警調辦案單位占逾9成5，包括用戶門號、通訊者個資、地點、甚至通訊內容。</p>
      <p><br></p>
      <p>台權會的統計顯示，本土業者包括四大電信業者，對於政府要求提供資料的配合度幾乎百分之百；相較之下，跨境業者合作的比率只有6成5。例如，檢調單位向LINE台灣調閱一筆涉及盜刷的信用卡資料，僅憑一個帳號就要求業者提供使用者資料，遭LINE直接否決。</p>
      <p><br></p>
      <p><br></p>
      <p><br></p>
      <h4>3000筆愛滋病患資料外洩 出包9年才發現</h4>
      <p><br></p>
      <p>2007年，北市聯合醫院驚傳3000筆愛滋病患的資料外洩，包含姓名、身分證字號、出生年月日等個資，甚至連疫調單編號全都露。事後聯醫追查，發現竟然只是有人準備投影片報告時，不慎將統計母體資料一併貼上檔案，導致有心人士一鍵就可取得病患資料。但聯合醫院直到2016年經告知才發現這件事情，花了一段時間才刪除已下載的資料。</p>
      <p><br></p>
      <p>愛滋病患事件發生後，衛福部資訊處長龐一鳴坦言，<b>其實公務機關或一般民眾對資安認知極低，使用資料的公務人員對資安認識不足，更增加個資外洩機率。</b></p>
      <p><br></p>
      <p>事件發生後，衛福部還特地加強告知教育公務人員，使用文書軟體時可能讓個資外洩的行為。最近則成立科學資料中心，學術研究單位須在監控下使用，包含使用紙張、軟體，要把資料帶出去，必須使用專屬的隨身碟，且由中心人員操作，不得自行操作，防堵個資外洩。</p>
      <p><br></p>
      <p><br></p>
    </content-container>
    <column-one description="公部門握有最大量的人民資料，但公務人員對資安認識不足，增加民眾個資外洩風險。" 
      :src="require('../public/mob2_002.jpg')" :src-web="require('../public/web2_002.jpg')"></column-one>
    <content-container>
      <p><br></p>
      <p><br></p>
      <p><br></p>
      <h4>高教資料庫蒐集學生個資 教育部強調合法</h4>
      <br>
      <p>最近教育部建立高教資料庫，蒐集學生及家長個資引發疑慮。教育部強調，資料來源合法，學生事後若拒絕學校使用資料，也可反映。受委託維護資料庫的台北科大看不到學生姓名、身分證字號等個人資料。</p>
      <p><br></p>
      <p>教育部高教司專員宋雯倩說，資料主要來自各校學生入學時所填的基本資料卡。資料是由各校加密上傳到國網中心，台北科大研究人員只能觀看數據趨勢變化，看不見學生姓名、身分證字號，「頂多知道學生所屬系所」。且教育部規定，各校用來上傳原始資料的電腦，須鎖IP，且從旁架設攝影機，「隨時記錄誰碰過電腦」，以利後續追蹤。</p>
      <p><br></p>
      <p><br></p>
      <p><br></p>
      <h4>警察外洩民眾個資 違法賣給徵信社</h4>
      <p><br></p>
      <p>警察機關曾傳員警外洩民眾個資，甚至賣給徵信社的違法行為。警政署說，警察因職掌治安、偵防犯罪，得依職權利用警政資訊系統查詢相關個資，早年或因管制不夠嚴謹、或員警法治觀念不足，發生不少個資外洩事件，近年建立有效防杜機制，加強員警教育，情況已大幅減少。</p>
      <p><br></p>
      <p>一名曾辦過警察利用職權將查到的民眾個資賣給徵信社的法官則提醒，政府擁有龐大的民眾個人資料，在數位化的時代，如何監督有權取得這些隱私資料者不濫用，對政府是新挑戰、也是不得不面對的課題。</p>

      <p><br></p>
      <p><br></p>
      <p><br></p>
      <h4>公部門資料庫門戶洞開</h4>
      <p><br></p>
      <div class="department-block" :key="item.title" v-for="item in departmentData">
        <h4 class="title">{{ item.title }}</h4>
        <ul class="event-lists">
          <li class="list">{{ item.event1 }}</li>
          <li class="list">{{ item.event2 }}</li>
        </ul>
        <br>
      </div>
      <p><br></p>
      <p><br></p>
      <p><br></p>
      <h3>風險二</h3>
      <h3>沒有獨立的個資專責機關</h3>
      <p><br></p>
      <p>台灣人權協會專案經理何明諠說，歐盟GDPR（一般資料保護規則）要求歐盟各國都應成立「獨立的個人資料保護專責機關」，從人事任命、財務上保持獨立性。</p>
      <p><br></p>
      <p>但是，如今《個資法》的主管機關是設在國發會之下，成立專案辦公室，這有很大的問題：</p>
      <p><br></p>
      <ol>
        <li>國發會原本是規劃國家發展，尤其是經濟發展，這與保護民眾個資矛盾。</li>
        <li>人事、預算都非獨立，也沒有法規定出權責，要人民如何相信？</li>
        <li>個資法落實標準不一，過去法務部都推說資源不足、無能為力，現換成國發會，問題就會消失嗎？</li>
      </ol>
      <p><br></p>
      <quote text="何明諠說，政府一貫搪塞理由是：「中央行政機關組織基準法」卡在那，就是無法再有獨立機關了；但是「黨產會及促轉會等獨立機關不也是在這兩年成立了嗎？」"></quote>
      <p><br></p>
      <p><br></p>
      <p><br></p>
      <h3>風險三</h3>
      <h3>個資法跟不上時代</h3>
      <p><br></p>
      <p>行政院前院長陳沖一直關切個人資料保護法的效力，「我擔心就是大家只要大數據的好處，卻忘了個人資料的保護。」個資法立法的時候，世界上還沒有App，雖然2015年個資法剛修正，但新科技、新商業模式也正不斷遽變，須滾動修正。</p>
      <p><br></p>
      <p>另一位前閣揆張善政說，台灣的個資法確實到了要與其他相關法令配套、全面盤整的時候。他認為，科技與法律間不是衝突，而是應該互動，必要時應該讓科技先行，蒐集到實務經驗與數據後，再作為法律跟進修改的依據，也不要成為企業絆腳石。</p>
      <p><br></p>
      <p><br></p>
      <p><br></p>
      <h3>風險四</h3>
      <h3>人民事前未被告知</h3>
      <p><br></p>
      <p>當前政府講究大數據，檢警的毒品大數據庫，將所有曾經被抓過的毒品犯全數建檔、分析，用來追根溯源，但當毒犯、愛滋病患等資料庫都可被連線蒐集、甚至交叉、分析運用時，民眾並不知道自己的敏感個資被政府使用的範圍。</p>
      <p><br></p>
      <p>何明諠說，「資料利用的不透明是很個很大的問題，如何處理、帶來何種效果，使用者難以知道。」</p>
      <p><br></p>
      <p><br></p>
    </content-container>
    <column-one description="人民的「資訊自主權」──我的資料我有權決定如何被使用，一直受政府漠視。" 
      :src="require('../public/mob2_003.jpg')" :src-web="require('../public/web2_003.jpg')"></column-one>
      <content-container>
        <p><br></p>
        <p><br></p>
        <p><br></p>
        <h3>迷思一</h3>
        <h3>去識別無效 個資仍會全都露</h3>
        <p><br></p>
        <p>何明諠說，<b>個資法限制個資使用，但對「學術研究／公共利益」都從寬解釋。</b>衛福部健保署在聲稱<span class="dictionary-btn" @click="handleDictionary">去個人識別 <font-awesome-icon :icon="['fas', 'info-circle']" /></span>
          <span class="dictionary" v-show="isDictionaryShow">去識別化（de-identification）：簡單說，就是透過一些技術或遮蔽方式，使得一筆資料不再與特定個人有連結。最常見也最簡單的例子，像是提及人名時，時常可見以「哆拉○夢」這樣的方式進行表示（儘管這也時常是失敗的去識別化的案例）。針對比較大量的資料，常見的去識別化方式有Ｋ匿名法、差分隱私等，可讓兩個資料庫串連時，匿名性不會失敗。</span>
        處理後，將全民健保資料釋出到「健康資料加值研究中心」，作為「全民健保研究資料庫」，台權會提起行政訴訟及於前年提釋憲，要求民眾有權退出這項「健保目的外利用」。</p>
        <p><br></p>
        <p><b>但衛福部及法院見解是對外提供都是匿名，名字與身分字號都去掉了，所以可以不經當事人同意供學者使用。</b></p>
        <p><br></p>
        <p>這樣，有道理嗎？</p>
        <p><br></p>
        <quote text="政治大學法律系教授劉宏恩說：「政府迷信『去名化』就是『去識別』，就是『隱私保密』，其實，根本不是有效保護個資的方法。」"></quote>
        <p><br></p>
        <p>中研院資科所副研究員莊庭瑞指出，政府對公眾資料在自行聲明「已去個人識別處理」後，就轉為「特定目的以外的利用」。這作法實在太寬鬆。</p>
        <p><br></p>
        <p>更重要的是，目前去識別化作法仍可回溯追出你的身分。前立委黃淑英等人曾由健保資料庫申請出某群資料，在無姓名等資料下，仍能辨識出自己的健康資料。</p>
        <p><br></p>
        <p><b>台灣人權協會曾拿到研究後棄置的醫療個資光碟，發現去識別化只是把姓名跟身分證字號隱去，其他資料「全都露」</b>；再者，被抽出的民眾<b>「根本沒有被告知將被研究，更別說同意了，就連退出的權利都沒有」</b>。</p>
        <p><br></p>
        <p><br></p>
        <p><br></p>
        <h3>迷思二</h3>
        <h3>數位政府 換來便利還是侵犯隱私？</h3>
        <p><br></p>
        <p>民進黨立委尤美女表示，個人資料保護是新興議題，現在強調大數據、數位政府，但在大數據的資料蒐集中，很多資訊可能會被曝光，個人隱私權與大數據的便利性之間，平衡點何在，是未來制定法律、政策時，都應注意的事項。</p>
        <p><br></p>
        <p>她也直言，現在政府握有大批民眾資料，但各部會的資安防禦能力不夠，而駭客技術能力日新月異，民眾當然會擔心政府個資外流。</p>
        <p><br></p>
        <p>行政院政務委員唐鳳說，要讓民眾對政府或企業有數位信任，重點是政府蒐集、處理、使用資料的方式本身，一定要符合當責 （accountability）的精神，決策、蒐集、誰使用、如何使用，過程透明清楚，民眾才能信任。</p>
        <p><br></p>
        <p><br></p>
        <p><br></p>
        
      </content-container>
      <Banner></Banner>
      <content-container style="background-color: white">
        <p><br></p>
        <p><br></p>
        <p><br></p>
        <div class="survey-wrapper">
          <a href="https://www.surveycake.com/s/KpQKN">
            <div class="survey">
              填寫問卷調查體驗
            </div>
          </a>
        </div>
        <p><br></p>
        <div class="share-wrapper">
          <share href="https://udn.com/upf/newmedia/2019_data/digital_privacy/government/index.html"></share>
          <Logo></Logo>
        </div>
        <p><br></p>
        <p><br></p>
        <Editor>
        <div>採訪團隊：蕭白雪、梁玉芳、彭慧明、章凱閎、馮靖惠、張錦弘、陳雨鑫、陳金松、廖炳棋</div>
        <div>製作人：蔡佩蓉</div>
        <div>影像：林澔一、報系資料照、123RF</div>
        <div>視覺設計：張心慈、蘇士堯</div>
        <div>網頁製作：胡凈悟、楊若榆</div>
        <div>監製：林秀姿、潘如瑩、董谷音</div>
        <div>2019.03.25</div>
      </Editor>
      <p><br></p>
      <Relate title="延伸閱讀"
        href1="https://udn.com/news/story/6656/3455275?from=udn-referralnews_ch2artbottom" :img1="require('../public/mob2_r001.jpg')" text1="網上不能「詆毀」蔡總統 國安局緊盯你我臉書" 
        href2="https://udn.com/news/story/6656/3527582" :img2="require('../public/mob2_r002.jpg')" text2="政院修法阻假訊息 藍委：用刑罰製造寒蟬效應" 
        href3="https://udn.com/news/story/12553/3537294" :img3="require('../public/mob2_r003.jpg')" text3="台權會：捍衛言論自由才是對付假訊息武器" 
        href4="https://udn.com/news/story/7266/3366615" :img4="require('../public/mob2_r004.jpg')" text4="國道ETC抓超速 法務部認有適法性疑慮" > 
      </Relate>
      <p><br></p>
        <fb-comment href="https://udn.com/upf/newmedia/2019_data/digital_privacy/government/index.html"></fb-comment>
      </content-container>
      <back-top></back-top>
    <foot></foot>
  </div>
</template>

<script>
// import Logo from './components/Logo.vue'
import DynamicDigit from './components/DynamicDigit.vue'
import { setInterval, clearInterval } from 'timers';
import { TweenLite } from "gsap";
import srcRWD from './mixin/srcRWD.js'
import Utils from 'udn-newmedia-utils'
import { library } from '@fortawesome/fontawesome-svg-core';
import { fas } from '@fortawesome/free-solid-svg-icons';
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';
import Banner from './components/Banner.vue';
import Logo from './components/Logo.vue';
import Share from './components/Share.vue';
import Header from './components/Header.vue'

library.add(fas)

export default {
  name: 'app',
  data () {
    return {
       outLinkList: [
        {
          name: '數位隱私變商品',
          link: 'https://udn.com/upf/newmedia/2019_data/digital_privacy/',
        },
        {
          name: '政府正在監控你',
          link: 'https://udn.com/upf/newmedia/2019_data/digital_privacy/government/',
        },
        {
          name: '測驗透明人指數',
          link: 'https://udn.com/upf/newmedia/2019_data/digital_privacy/quiz/',
        },
      ],
      isDictionaryShow: false,
      departmentData: [
        {
          title: '內政部',
          event1: '擁有民眾身分證、戶籍地址資料',
          event2: '曾被外洩給詐騙集團或徵信社'
        },
        {
          title: '衛福部',
          event1: '擁有民眾健保醫療資料、家暴、愛滋等傳染疾病資料',
          event2: '曾發生3000筆愛滋病患個資外洩事件'
        },
        {
          title: '司法院',
          event1: '法院判決資料建檔管理',
          event2: '曾被駭客入侵公布資料、內控出問題讓少年犯身分曝光'
        },
        {
          title: '法務部',
          event1: '監所人犯前科、病歷資料建檔列管',
          event2: '特殊個資與健保資料庫連結'
        },
        {
          title: '高檢署、刑事局',
          event1: '建立毒品、詐騙集團大數據資料庫',
          event2: '蒐集有關者資料做進一步分析'
        },
        {
          title: 'ETC',
          event1: '蒐集行車軌跡紀錄',
          event2: '政府用作分析外，可拿來追蹤個人行蹤'
        },
      ],
      spotLight1: {
        number: 65000,
        describe: '2015年-2016年，共有11個政府機關向網路業者聲請65000多次網路個人資料'
      },
      spotLight2: {
        number: 20000,
        describe: '每年通訊監察（對人民監聽）案件量超過20000件'
      },
      spotLight3: {
        number: 95,
        describe: '檢警調辦案單位占總請求數95%以上'
      }

    }
  },
  components: {
    DynamicDigit,
    Logo,
    Banner,
    Share,
    Header,
    'font-awesome-icon': FontAwesomeIcon
  },
  mixins: [srcRWD],
  methods: {
    handleDictionary () {
      window.ga("newmedia.send", {
        "hitType": "event",
        "eventCategory": "dictionary",
        "eventAction": "click",
        "eventLabel": "[" + Utils.detectPlatform() + "] [" + document.querySelector('title').innerHTML + "] [小辭典]]"
      })
      this.isDictionaryShow = !this.isDictionaryShow;
    }
  },
  mounted () {

  }
}
</script>

<style lang="scss">
@import './assets/reset.css';
@import './assets/UdnFontSize.css';


html, body {
  margin: 0;
  ol {
    li {
      margin-left: 20px;
    }
  }
  p {
    margin: 0;
  }
  h3 {
    font-size: 24px;
    font-weight: 800;
    line-height: 1.5;
    margin: 0;
    @media (min-width: 768px) and (max-width: 1023px) {
      font-size: 34px;
    }
    @media screen and (min-width: 1024px) {
      font-size: 34px;
    }
  }
  h4 {
    font-size: 20px;
    font-weight: 800;
    @media (min-width: 768px) and (max-width: 1023px) {
      font-size: 28px;
    }
    @media screen and (min-width: 1024px) {
      font-size: 28px;
    }
  }
}

#app {
  font-family: Arial, "微軟正黑體", sans-serif;
  background-color: rgb(246, 246, 246);
  .dictionary-btn {
    color: rgb(213, 54, 54);
    cursor: pointer;
  }
  .dictionary {
    display: block;
    padding: 30px;
    color: rgb(213, 54, 54);
    padding: 45px;
    margin: 25px 0;
    font-weight: 400;
    font-size: 18px;
    line-height: 1.9;
    border: solid 1px rgb(213, 54, 54);
  }
  .highlight {
    font-weight: 900;
    color: rgb(67, 86, 255);
  }
  .number-ani-wrapper {
    font-weight: bolder;
    .dynamic-number {
      color: #4356ff;
      .number {
        font-size: 50px;
      }
    }
    .content {

    }
  }
  .department-block {
    .title {
      font-size: 15px;
      line-height: 2.5;
      @media (min-width: 569px) {
         font-size: 18px;
         line-height: 2.5;
         font-weight: 600;
      }
      @media (min-width: 768px) {
        font-size: 28px;
        line-height: 2.5;
      }
      @media screen and (min-width: 1024px) {
        
      }
    }
    .event-lists {
      list-style: none;
      padding-left: 12px;
      border-left: 1px solid rgba(#7e7e7e, 0.5);
      @media (min-width: 569px) {
        list-style: none;
        border-left: 1px solid rgba(#7e7e7e, 0.5);
        padding-left: 11px;
      }
      @media (min-width: 768px) {
        list-style: none;
        border-left: 3px solid rgba(#7e7e7e, 0.5);
        padding-left: 15px;
      }
      @media screen and (min-width: 1024px) {
        line-height: 1.5;
        border-left: 1px solid #c3bcbc;
        padding-left: 15px;
        color: #7e7e7e;
        
      }
      .list {
        font-size: 15px;
        color: #7e7e7e;
        font-weight: 500;
        @media (min-width: 569px) {
          font-size: 15px;
        }
        @media (min-width: 768px) {
          font-size: 15px;
        }
        @media screen and (min-width: 1024px) {
          font-size: 21px;
        }
      }
    }
  }
  .survey-wrapper {
    a, u {
        text-decoration: none;
        color: #5d5d5d;
        &:hover {
          color: black;
        }
    }
    .survey {
      margin: 0 auto;
      max-width: 250px;
      line-height: 70px;
      margin: 0 auto;
      border-radius: 50px;
      text-align: center;
      background-color: #f7f6f6;
      color: #636363;
    }
  }
  .share-wrapper {
    vertical-align: top;
    margin: 30px 0;
    display: flex;
    align-items: baseline;
    flex-direction: column;
    @media (min-width: 768px) {
      justify-content: space-between;
      
    } 
    @media screen and (min-width: 1024px) {
      justify-content: space-between;
      flex-direction: row;
    }
  }
}
</style>
