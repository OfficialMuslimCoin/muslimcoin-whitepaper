# muslimcoin-whitepaper
Official repository for MuslimCoin - a halal web3 project built for the Ummah. 
# 🕌 MuslimCoin

**A Halal-Centric Web3 Ecosystem for the Global Muslim Ummah**

---

## ❇️ Introduction
import { Tabs, TabsContent, TabsList, TabsTrigger } from "@/components/ui/tabs";
import Header from '@/components/Header';
import Footer from '@/components/Footer';

const Whitepaper = () => {
  return <div className="min-h-screen">
      <Header />
      <main className="pt-20">
        <div className="container mx-auto px-4 py-16">
          <div className="text-center mb-12">
            <h1 className="text-4xl md:text-5xl font-bold mb-4">
              <span className="gradient-text">MuslimCoin Whitepaper</span>
            </h1>
            <p className="text-xl text-gray-600 max-w-2xl mx-auto">
              The comprehensive guide to the world's first faith-based cryptocurrency
            </p>
          </div>

          <Tabs defaultValue="abstract" className="max-w-6xl mx-auto">
            <TabsList className="grid w-full grid-cols-6 lg:grid-cols-11 mb-8">
              <TabsTrigger value="abstract">Abstract</TabsTrigger>
              <TabsTrigger value="introduction">Introduction</TabsTrigger>
              <TabsTrigger value="problem">Problem</TabsTrigger>
              <TabsTrigger value="solution">Solution</TabsTrigger>
              <TabsTrigger value="tokenomics">Tokenomics</TabsTrigger>
              <TabsTrigger value="technology">Technology </TabsTrigger>
              <TabsTrigger value="roadmap">Roadmap</TabsTrigger>
              <TabsTrigger value="team">Team</TabsTrigger>
              <TabsTrigger value="compliance">Compliance</TabsTrigger>
              <TabsTrigger value="community">Community</TabsTrigger>
              <TabsTrigger value="conclusion">Conclusion</TabsTrigger>
            </TabsList>

            <TabsContent value="abstract" className="bg-white p-8 rounded-2xl shadow-lg">
              <h2 className="text-3xl font-bold mb-6 gradient-text">Abstract</h2>
              <div className="prose max-w-none text-gray-700 leading-relaxed">
                <p className="mb-4 text-lg font-medium">
                  Muslim coin is a decentralised cryptocurrency project designed to bridge gap between modern financial innovation and islamic ethical principles in a rapidly evolving digital economy, the global muslim community remains underepresented in the crypto space due to concerns over riba (interest), transparency and compliance with halal standards.
                  Muslim Coin aims to provide a trusted shariah compliant financial solution that empowers individuals and businesses to participate in the digital economy without compromising their faith through a secure, transparent and values driven ecosystem.
                  Muslim coin seeks to redefine ethical finance and unlock new opportunities for inclusive economic growth. Muslim Coin is a next generation cryptocurrency project created to align with the values of the islamic economy while embracing the innovation of blockchain technology built with shariah compliance at its core, Muslim Coin aims to serve as a trusted financial instrument for the global muslim community starting with the forward looking and digitally savvy population of the muslim ummah, by offering a halal; interest free ecosystem that supports ethical finance.
                  Muslim Coin empowers individuals, businesses and institutions to participate in the digital economy without compromising their faith through partnerships, transparency, and innovation.
                  Muslim Coin positions itself as a key player in the muslim vision for a blockchain-enabled future.
                </p>
                <p className="mb-4 text-zinc-950">
                </p>
                <p>
                </p>
              </div>
            </TabsContent>

            <TabsContent value="introduction" className="bg-white p-8 rounded-2xl shadow-lg">
              <h2 className="text-3xl font-bold mb-6 gradient-text">Introduction</h2>
              <div className="prose max-w-none text-gray-700 leading-relaxed">
                <p className="text-lg mb-6">
                  The rise of web3 and decentralised finance (DeFi) is reshaping the global economy, introducing new forms of ownership, financial freedom and digital interaction. However, much of this innovation has yet to fully align with the values and spiritual principles of the global Muslim Ummah.
                </p>
                
                <p className="text-lg mb-6">
                  Muslim Coin is built to change that. It is a purpose-driven digital asset designed to bring meaningful, halal-aligned utility to the web3 space, empowering Muslims not just financially but spiritually by integrating faith-based actions into token mining.
                </p>
                
                <div className="bg-emerald-50 p-6 rounded-lg mb-6 border-l-4 border-emerald-500">
                  <p className="text-lg font-medium text-emerald-800 mb-3">
                    🌙 Transforming Worship into Economic Participation
                  </p>
                  <p className="text-emerald-700">
                    Muslim Coin turns everyday worship into economic participation. This project aims to place the Muslim ummah in a state of <em>Alhamdulillah</em> - where digital advancement and divine consciousness co-exist.
                  </p>
                </div>
                
                <p className="text-lg mb-4">
                  It invites believers to enter the future of finance without compromising their values, using blockchain not just for profit but for purpose.
                </p>
                
                <div className="grid md:grid-cols-2 gap-6 mt-8">
                  <div className="bg-gradient-to-br from-emerald-50 to-emerald-100 p-6 rounded-xl">
                    <h3 className="text-xl font-semibold mb-3 text-emerald-700">💎 Faith-Driven Innovation</h3>
                    <p className="text-emerald-600">
                      Bridging the gap between Islamic principles and cutting-edge blockchain technology to create meaningful digital experiences.
                    </p>
                  </div>
                  
                  <div className="bg-gradient-to-br from-gold-50 to-gold-100 p-6 rounded-xl">
                    <h3 className="text-xl font-semibold mb-3 text-gold-700">🤲 Spiritual Empowerment</h3>
                    <p className="text-gold-600">
                      Transforming daily acts of worship into tangible value while strengthening the connection between faith and financial participation.
                    </p>
                  </div>
                </div>
              </div>
            </TabsContent>

            <TabsContent value="problem" className="bg-white p-8 rounded-2xl shadow-lg">
              <h2 className="text-3xl font-bold mb-6 gradient-text">Problem Statement</h2>
              <div className="prose max-w-none text-gray-700 leading-relaxed">
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">1. Lack of Halal-Compliant Crypto Options</h3>
                <p className="mb-6">
                  Despite the rapid growth of web3 and decentralised finance (DeFi), there remains a significant gap in the availability of cryptocurrency projects that align with Islamic principles. Many Muslims are hesitant to engage with crypto due to concerns about religious compliance, creating a barrier for a substantial portion of the global population to participate in the digital financial revolution.
                </p>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">2. Distrust in Conventional DeFi Systems</h3>
                <p className="mb-6">
                  Many members of the Muslim community view traditional DeFi systems with skepticism due to their association with high volatility, interest-bearing mechanisms, and speculative practices. These systems often lack the ethical and spiritual framework that Muslims seek when engaging in financial activities. As a result, there is a growing demand for a decentralised financial ecosystem that is rooted in Islamic ethics and offers both spiritual and financial value.
                </p>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">3. Need for Ethical and Inclusive Financial Tools</h3>
                <p className="mb-6">
                  The global Muslim population, over 2 billion strong, remains largely underserved in the crypto space. There is a growing need for financial tools that are not only Shariah-compliant but also ethically designed to be inclusive, transparent, and socially impactful. Many existing crypto solutions prioritize profit over purpose, leaving behind communities that value faith, responsibility, and long-term empowerment.
                </p>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">4. Absence of Unified Faith-Based Digital Ecosystem</h3>
                <p className="mb-4">
                  While Islamic finance is well established in traditional banking, its presence in the digital and web3 landscape remains fragmented. There is currently no comprehensive platform that seamlessly integrates spiritual practices with digital rewards, community engagement, and halal financial tools. This lack of a unified ecosystem limits the potential of Muslim users to benefit from the web3 revolution in a way that aligns with their values and daily practices.
                </p>
                
                <div className="mt-8 p-6 bg-red-50 border-l-4 border-red-400 rounded-r-lg">
                  <h4 className="text-lg font-semibold mb-2 text-red-700">The Gap in the Market</h4>
                  <p className="text-red-600">
                    This convergence of challenges has created a massive opportunity gap: a global community of 2+ billion Muslims seeking digital financial solutions that honor their faith, promote ethical practices, and provide meaningful spiritual engagement alongside economic participation.
                  </p>
                </div>
              </div>
            </TabsContent>

            <TabsContent value="solution" className="bg-white p-8 rounded-2xl shadow-lg">
              <h2 className="text-3xl font-bold mb-6 gradient-text">Solution</h2>
              <div className="prose max-w-none text-gray-700 leading-relaxed">
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Faith-Based Mining System</h3>
                <p className="mb-4">Muslim Coin mission and vision: Muslim Coin is a faith driven cryptocurrency project built on the principles of trust, transparency, and ethical finance. Our mission is to empower communities with a halal compliant digital currency that aligns with Islamic values, while fostering global financial inclusion through decentralized technology. We aim to bridge tradition and innovation offering a secure, interest free ecosystem for all who believe in fair and just economic system. Muslim Coin key strengths: 
* Identity: Instantly recognizable and resonates with a global muslim community. 
* Trust and Ethics: Suggest alignment with halal principles, ethical finance and transparency. 
* Community Appeal: Can foster a strong niche following based on shared values. 
EMPOWERING THE UMMAH THROUGH BLOCKCHAIN. MUSLIM-COIN USECASE:
Faith Based Actions. 
AI Validation. 
Incentivized Engagement.</p>
                <ul className="mb-4 list-disc pl-6">
                  <li>Daily prayers (Salah) - 20 MPoints per prayer</li>
                  <li>Quran recitation - 5 MPoints per chapter</li>
                  <li>Mosque attendance - 10 MPoints per visit</li>
                  <li>Zakat contributions - 50 MPoints per donation</li>
                  <li>Community service - Variable MPoints based on activity</li>
                </ul>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">PURPOSE AND USE-CASE SUMMARY:
              </h3>
                <p className="mb-4">Muslim-Coin is more than just a cryptocurrency, it is a movement to reward spiritual discipline and community engagement through a decentralized valued-driven digital eco-system.  Muslim Coin introduces a unique mining model based on real world Islamic practices, verified through AI technology. Using the Muslim Coin mobile mining App, users earn MPoints by performing specific faith based actions. These points are later converted into Muslim Coin tokens. Mining Tasks Includes: 
1. Performing Wudu (Ablution)  
2. Walking To The Mosque  
3. Taking A Photo Inside The Mosque 
4. Recording The Adhzan (Call To Prayer) 
 {'=>'} To maintain the systems integrity, The app is integrated with AI algorithms that verify the authenticity of each action and detect fraudulent submissions. This innovative model ensures that mining Muslim Coin isn`t just about computation its about intention, action, and community participation turning faith into value while promoting daily worship and ethical engagement. To ensure meaningful engagement and alignment with Islamic values. Users must complete all five daily prayers to fully unlock and convert their accumulated Mpoints into Muslim Coin tokens.  
                {'=>'} Advanced AI integration within the app verifies task authenticity, detects fraudulent submissions and maintains the integrity of the mining process. This ensures that rewards are granted only for genuine verifiable actions, reinforcing trust across the ecosystem. 
                {'=>'} This system reinforces consistency in worship and positions the mining process as a spiritually driven activity rather than a purely transaction one. By tying tokens rewards to the daily prayer schedule. Muslim Coin encourages users to maintain regular devotion when participating in the digital economy. Muslim Coin presents a ground-breaking solution that merges decentralized technology with ethical foundations of Islamic finance designed to serve as a faith aligned alternative in the web3 space, Muslim Coin empowers users to participate in the digital economy while honoring their religious values.  


1. Riba-Free Ecosystem: Muslim Coin strictly avoids interest-based mechanisms (riba), ensuring that all financial interactions are transparent, fair, and compliant with Islamic law. 
2. Integrated Zakat Framework: The ecosystem includes a built-in zakat contribution system, allowing users to automatically calculate and donate a potion of their wealth to verified charitable causes, thereby fulfilling one of the core pillars of Islam.  
3. Ethical Mining Through Spiritual Actions: The mining process is based on performing acts of worship such as ablution, mosque attendance, adhzan participation. This spiritually infused mining model turns faith into utility rewarding users with Mpoints that are later converted into Muslim coin. 
4. AI-driven Authenticity Verification: Advanced AI is integrated to validate users actions and prevent manipulation or deceit in task submission-ensuring trust, accountability, and halal compliance. 
5. Inclusive Rewards Via Iman-Jar: The optional "Iman-jar" feature offers bonus rewards for supplementary spiritual activities like reciting daily adhzkar and supplications, encouraging deeper personal growth. 
6. Shariah Advisory And Institutional Collaboration: Muslim coin seeks to partner with reputable Islamic institutions and commissions (e.g. Hajj boards). To provide payment infrastructure for pilgrimage related expenses and other religious activities. Muslim Coin is designed as a utility token that fuels a values-driven ecosystem. beyond earning through faith-based actions, holders of Muslim Coin can engage in a wide range of ethical financial and community functions. The tokens utility is central to its mission-supporting both spiritual growth and digital empowerment. 
1. Reward And Incentive Mechanism: Muslim Coin is primarily earned through verifiable acts of worship and Islamic lifestyle engagement. This mining model encourages consistency in daily prayers and rewards, encouraging meaningful behavior not computation or capital investment. 
2. Peer-To-Peer Transactions: Users can send and receive Muslim coin seamlessly via the app, enabling; 
* Everyday halal transactions. 
* Charitable giving (Sadaqah, Zakat).
* Remittance among community members.
 3. Community Engagement And Governance. Muslim Coin holders may gain access to voting rights within the ecosystems development roadmap, charitable allocation, or feature prioritization -promoting transparency and shared ownership. 
4. Access To Premium Features: The token can unlock advanced features within the app such as, 
* Enhanced spiritual analytics (e g. prayer tracking overtime).
* AI based religious learning tools.
* Early access to educational or partner programs.
5. Integration with Islamic financial services. Future utility includes potential interactions with:
 * Halal certified defi products. 
 * Digital marketplaces focused on Islamic goods and services.
 * In-app microloans, savings, or business funding all shariah compliant. </p>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">GENDER INCLUSIVE MINING DESIGN</h3>
                <p>Muslim-coin is built on the foundation of Islamic ethics, spiritual accountability, and inclusivity. Recognising the different roles and expectations for men and women on islamic practice - particularly around congregational prayer- our mining model is designed to ensure both genders can participate equitably. CORE REQUIREMENTS: COMPLETION OF FIVE DAILY PRAYERS. Regardless of gender, users must complete all five daily prayers to fully unlock and convert their earned Mpoints into Muslim coin tokens. This shared condition promotes spiritual discipline and daily consistency across the community. 
TASK VALIDITY BY ROLE AND CONTEXT: 
* For Men: Task emphasize communal and mosque based engagement.
1. Performing Wudu (Ablution). 
2. Walking To The Mosque (GPS-VERIFIED). 
3. Photo Proof Inside The Mosque.
4. Recording The Adzhan FOR WOMEN: Recognizing the Islamic view that women are encouraged (But not required) to attend the mosque, The app offers spiritually equivalent tasks. 
1. Performing Wudu (Ablution). 
2. Praying At Home (Verified by time\location consistency). 
3. Reciting Quran or Engaging In Dhikr (Verified by Audio Or App Prompts) 
4. Logging charitable acts or Islamic learning sessions AI Driven Integrity And Privacy. 
Muslim-Coin integrates AI technology -to verify user actions while respecting privacy.
* Behavioral Patterns (prayer times, app activity)
* Non-invasive proof methods (geotagging, voice confirmation, time-based logs) 
* Fraud detection to ensure fairness without constant surveillance.
 This inclusive structure ensures all users can contribute meaningfully and ethically to the Muslim Coin ecosystem, regardless of gender or personal circumstance.
                {'=>'} FOR MEN TASKS LIKE WALKING TO THE MOSQUE AND MOSQUE-BASED PROOFS CAN STAY AS IS.
                {'=>'} FOR WOMEN EQUIVALENT SPIRITUAL TASKS CAN BE REWARDED SUCH AS:
                {'=>'} Praying at home with time based verification.
                {'=>'} Reciting Quran or engaging in dhikr (using voice recognition or app prompts). 
                {'=>'} Charity acts, such as logging sadaqah or community support. 
Private space recognition. 
* The app can verify prayer location (e.g. home) without invading privacy, using simple geotagging or motion detection rather than photos. 
Separate Proof-Of-Prayer Validation.
 * Introduce an honor-based proof system, enhanced by AI to detect consistency over time rather than instant photo/video proof.
 * Periodic checks, not constant tracking, can maintain balance between respect and reliability. UNIFIED REWARDS THRESHOLD. * The key Requirements Remain: Five daily prayers must be completed. * But the tasks that earn Mpoints can differ slightly between men and women, reflecting both shariah and practical norms.</p>
              </div>
            </TabsContent>

            <TabsContent value="tokenomics" className="bg-white p-8 rounded-2xl shadow-lg">
              <h2 className="text-3xl font-bold mb-6 gradient-text">Tokenomics</h2>
              <div className="prose max-w-none text-gray-700 leading-relaxed">
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Token Utility</h3>
                <p className="mb-4">
                  The Muslim Coin (MSMC) is designed to be more than just a store of value. It is a functional utility token that powers the ecosystem and incentivizes both spiritual engagement and community participation.
                </p>
                
                <h4 className="text-lg font-semibold mb-2 text-emerald-600">1. Payment Transactions</h4>
                <p className="mb-4">
                  Muslim Coin serves as a halal medium of exchange for goods and services within and beyond the app ecosystem:
                </p>
                <ul className="list-disc pl-6 mb-4">
                  <li>Donations and Zakat payments to verified charities</li>
                  <li>Purchases of Islamic digital contents (e.g books, courses, lectures)</li>
                  <li>Transactions with partner vendors, especially for Hajj/Umrah services</li>
                </ul>
                
                <h4 className="text-lg font-semibold mb-2 text-emerald-600">2. Governance</h4>
                <p className="mb-4">
                  Token holders will have the ability to participate in governance decisions via a shura-inspired voting system:
                </p>
                <ul className="list-disc pl-6 mb-4">
                  <li>Voting on app updates and new mining tasks</li>
                  <li>Proposals for charitable partnerships or ecosystem expansions</li>
                  <li>Community-based decision making on zakat fund allocations</li>
                </ul>
                
                <h4 className="text-lg font-semibold mb-2 text-emerald-600">3. Mining & Reward Conversion</h4>
                <p className="mb-4">
                  MSMC is the end-product of mining via spiritual tasks as users accumulate MPoints through verified actions (e.g Prayer, Ablution, etc.) these are converted into MSMC tokens at a set rate.
                </p>
                
                <h4 className="text-lg font-semibold mb-2 text-emerald-600">4. Ecosystem Fuel</h4>
                <p className="mb-4">
                  All interactions within the app require or reward MSMC, driving continuous utility demand for unlocking advanced features, using the Iman jar, participating in challenges, or accessing premium spiritual content.
                </p>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Halal Incentive Model</h3>
                <p className="mb-4">
                  Muslim Coin is built with a deep commitment to Islamic ethical standards. To ensure full shariah compliance, we have opted not to implement conventional staking, which often involves earning fixed or speculative returns potentially falling under riba (INTEREST) which is strictly prohibited in Islam.
                </p>
                
                <h4 className="text-lg font-semibold mb-2 text-emerald-600">Proof-of-Deeds Alternative</h4>
                <p className="mb-4">
                  Instead of staking, Muslim Coin introduces a unique "proof-of-deeds" model that rewards users for engaging in spiritual, ethical and socially beneficial actions:
                </p>
                <ul className="list-disc pl-6 mb-4">
                  <li>Performing and documenting daily prayers</li>
                  <li>Walking to the mosque (verified by GPS)</li>
                  <li>Reciting supplications (via voice input)</li>
                  <li>Recording the adzan or attending Jumu'ah</li>
                  <li>Donating to verified charitable causes (zakat/sadaqah)</li>
                </ul>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Iman-Jar: Spiritual Bonus Mining</h3>
                <div className="bg-emerald-50 p-6 rounded-lg mb-6">
                  <h4 className="text-lg font-semibold mb-2 text-emerald-700">🏺 "Fill Your Jar, Grow Your Iman"</h4>
                  <p className="mb-4">
                    A virtual jar that fills as users complete bonus tasks. Once filled, users earn bonus MPoints. The Iman-jar serves as a digital repository of spiritual effort, allowing users to complete optional bonus tasks rooted in Islamic practice.
                  </p>
                  
                  <h5 className="font-semibold mb-2">How It Works:</h5>
                  <ol className="list-decimal pl-6 mb-4">
                    <li>Access "Iman-jar" tab in the app</li>
                    <li>Choose from available tasks</li>
                    <li>Submit required proof (voice check-in, button tap)</li>
                    <li>Jar visually fills with each task</li>
                    <li>Once full → bonus reward released into wallet or Iman-jar rank upgraded</li>
                  </ol>
                  
                  <h5 className="font-semibold mb-2">Sample Tasks & Rewards:</h5>
                  <div className="overflow-x-auto">
                    <table className="min-w-full mt-4">
                      <thead>
                        <tr className="border-b">
                          <th className="text-left py-2">Task</th>
                          <th className="text-left py-2">Proof</th>
                          <th className="text-left py-2">Reward</th>
                        </tr>
                      </thead>
                      <tbody>
                        <tr className="border-b">
                          <td className="py-2">Morning/Evening Adhkar</td>
                          <td className="py-2">Audio or Manual check</td>
                          <td className="py-2">+3 MPoints</td>
                        </tr>
                        <tr className="border-b">
                          <td className="py-2">Recite Surah Al-Falaq</td>
                          <td className="py-2">Voice input (AI Optional)</td>
                          <td className="py-2">+5 MPoints</td>
                        </tr>
                        <tr className="border-b">
                          <td className="py-2">Night Prayer (Tahajjud)</td>
                          <td className="py-2">Check-in or manual Log</td>
                          <td className="py-2">+10 MPoints</td>
                        </tr>
                        <tr className="border-b">
                          <td className="py-2">Watch 1-min Hadith clip</td>
                          <td className="py-2">In-app Video Player</td>
                          <td className="py-2">+2 MPoints</td>
                        </tr>
                      </tbody>
                    </table>
                  </div>
                </div>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Supply & Distribution</h3>
                <div className="bg-emerald-50 p-4 rounded-lg mb-4">
                  <p><strong>Total Supply:</strong> 2,000,000,000 MSMC (2 Billion Muslim Coins)</p>
                  <p className="text-sm mt-2">Capped and fixed to reflect scarcity, long-term sustainability, and alignment with the global Muslim population.</p>
                </div>
                
                <div className="overflow-x-auto mb-6">
                  <table className="min-w-full">
                    <thead>
                      <tr className="border-b-2 border-emerald-200">
                        <th className="text-left py-3">Category</th>
                        <th className="text-left py-3">Amount (MSMC)</th>
                        <th className="text-left py-3">Allocation</th>
                        <th className="text-left py-3">Notes</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr className="border-b border-emerald-100">
                        <td className="py-2">Community Mining Rewards</td>
                        <td className="py-2">700,000,000</td>
                        <td className="py-2">35%</td>
                        <td className="py-2">Earned via verified spiritual tasks</td>
                      </tr>
                      <tr className="border-b border-emerald-100">
                        <td className="py-2">Rewards & Ecosystem Incentives</td>
                        <td className="py-2">300,000,000</td>
                        <td className="py-2">15%</td>
                        <td className="py-2">Iman-Jar bonuses, user rewards</td>
                      </tr>
                      <tr className="border-b border-emerald-100">
                        <td className="py-2">Foundation & Treasury</td>
                        <td className="py-2">200,000,000</td>
                        <td className="py-2">10%</td>
                        <td className="py-2">Managed by DAO for development</td>
                      </tr>
                      <tr className="border-b border-emerald-100">
                        <td className="py-2">Team & Advisors</td>
                        <td className="py-2">200,000,000</td>
                        <td className="py-2">10%</td>
                        <td className="py-2">Subject to vesting</td>
                      </tr>
                      <tr className="border-b border-emerald-100">
                        <td className="py-2">Private Sale</td>
                        <td className="py-2">200,000,000</td>
                        <td className="py-2">10%</td>
                        <td className="py-2">For initial funding rounds</td>
                      </tr>
                      <tr className="border-b border-emerald-100">
                        <td className="py-2">Partnership & Strategic Growth</td>
                        <td className="py-2">200,000,000</td>
                        <td className="py-2">10%</td>
                        <td className="py-2">Religious institutions, merchants</td>
                      </tr>
                      <tr className="border-b border-emerald-100">
                        <td className="py-2">Public Sale</td>
                        <td className="py-2">100,000,000</td>
                        <td className="py-2">5%</td>
                        <td className="py-2">For broader market access</td>
                      </tr>
                      <tr className="border-b border-emerald-100">
                        <td className="py-2">Zakat & Sadaqah Reserve</td>
                        <td className="py-2">100,000,000</td>
                        <td className="py-2">5%</td>
                        <td className="py-2">Used for charitable allocations</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Vesting Schedule</h3>
                <div className="overflow-x-auto mb-6">
                  <table className="min-w-full">
                    <thead>
                      <tr className="border-b-2 border-emerald-200">
                        <th className="text-left py-3">Allocation</th>
                        <th className="text-left py-3">Cliff Period</th>
                        <th className="text-left py-3">Vesting Duration</th>
                        <th className="text-left py-3">Release Details</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr className="border-b border-emerald-100">
                        <td className="py-2">Team & Advisor</td>
                        <td className="py-2">6 Months post-TGE</td>
                        <td className="py-2">24 Months Linear</td>
                        <td className="py-2">Monthly release after cliff</td>
                      </tr>
                      <tr className="border-b border-emerald-100">
                        <td className="py-2">Private Sale</td>
                        <td className="py-2">3 Months post-TGE</td>
                        <td className="py-2">12 Months Linear</td>
                        <td className="py-2">Gradual release to prevent dumps</td>
                      </tr>
                      <tr className="border-b border-emerald-100">
                        <td className="py-2">Community Mining</td>
                        <td className="py-2">5 Years</td>
                        <td className="py-2">12 Months</td>
                        <td className="py-2">Progressive mining based on MPoints</td>
                      </tr>
                      <tr className="border-b border-emerald-100">
                        <td className="py-2">Foundation & Treasury</td>
                        <td className="py-2">None</td>
                        <td className="py-2">36 Months Linear</td>
                        <td className="py-2">Ensure long-term sustainability</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Evergreen DAO</h3>
                <div className="bg-gold-50 p-6 rounded-lg mb-6">
                  <h4 className="text-lg font-semibold mb-3 text-gold-700">🌱 Sustainable Community Impact</h4>
                  <p className="mb-4">
                    Muslim Coin will dedicate 5% of all transaction fees collected post-TGE to support the EvergreenDAO - a transparent, community-driven, and impact-oriented initiative.
                  </p>
                  
                  <h5 className="font-semibold mb-2">Purpose:</h5>
                  <ul className="list-disc pl-6 mb-4">
                    <li>Empowering Ummah-based social causes: Education, healthcare, orphan care</li>
                    <li>Fostering Islamic digital innovation: Funding Islamic fintech startups</li>
                    <li>Promoting environmental stewardship: Clean water, reforestation projects</li>
                    <li>Serving as a Waqf-inspired mechanism for perpetual community benefit</li>
                  </ul>
                  
                  <h5 className="font-semibold mb-2">Expected Impact:</h5>
                  <ul className="list-disc pl-6">
                    <li>Over $1 million in projected contributions by Year 3</li>
                    <li>Hundreds of community-benefiting micro-projects</li>
                    <li>An ecosystem of Muslim-built, Muslim-owned, and Muslim-benefiting technology</li>
                  </ul>
                </div>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Liquidity & Burning Strategy</h3>
                <ul className="list-disc pl-6 mb-4">
                  <li><strong>Initial DEX Offering (IDO):</strong> 5% of public sale tokens for liquidity pools on halal-compliant DEXs</li>
                  <li><strong>Token Burning:</strong> Small percentage of unclaimed MPoints may be burned to manage inflation</li>
                  <li><strong>Charity Matching:</strong> Users donating MSMC to verified zakat causes may receive matched bonuses</li>
                </ul>
              </div>
            </TabsContent>

            <TabsContent value="technology" className="bg-white p-8 rounded-2xl shadow-lg">
              <h2 className="text-3xl font-bold mb-6 gradient-text">Technology & Infrastructure</h2>
              <div className="prose max-w-none text-gray-700 leading-relaxed">
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Blockchain Layer: Haqq Network</h3>
                <p className="mb-4">
                  Muslim Coin is built on the Haqq blockchain, a Layer 1 proof-of-stake network designed specifically for Shariah-compliant decentralized finance (Islamic DeFi). The Haqq ecosystem ensures that all transactions, smart contracts, and ecosystem DApps align with ethical standards rooted in Islamic jurisprudence.
                </p>
                <p className="mb-4">
                  Haqq is a Layer 1 proof-of-stake (PoS) network that merges the power of Web3 with the ethics of Islam. Haqq (meaning "truth" in Arabic), offers an ecosystem that is compliant with Islamic financial principles, governed by a Shariah board and driven by ethical innovation.
                </p>

                <h4 className="text-lg font-semibold mb-3 text-emerald-600">Why Haqq?</h4>
                <ul className="list-disc pl-6 mb-6">
                  <li><strong>Shariah Compliance:</strong> Haqq is governed by the Islamic Coin Shariah Board, ensuring all smart contracts and network operations avoid riba, gharar, and haram activities.</li>
                  <li><strong>Sustainable PoS Mechanism:</strong> Uses energy-efficient proof-of-stake consensus, minimizing environmental impact.</li>
                  <li><strong>Native Token ($ISLM):</strong> Used for network gas fees, governance participation, and ecosystem services.</li>
                  <li><strong>Modular Smart Contracts:</strong> Enables custom halal logic such as zakat automation, ethical wallets, and purpose-driven DApps.</li>
                  <li><strong>Modular and Scalable Architecture:</strong> Supports rollups and sidechains for long-term performance.</li>
                  <li><strong>Governed by the Islamic Coin Shariah Board:</strong> A credible body overseeing contract and DApps compliance.</li>
                </ul>

                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Muslim Coin App Architecture</h3>
                <p className="mb-4">
                  The Muslim Coin app interfaces with the Haqq through a secure and scalable backend that supports:
                </p>
                <ul className="list-disc pl-6 mb-6">
                  <li><strong>AI-powered Mining Validation:</strong> Tasks like prayer tracking, adzan recording, and masjid attendance are verified using GPS, camera input, and AI behavior detection algorithms.</li>
                  <li><strong>Wallet & Token Bridge:</strong> Allow users to withdraw earned Muslim Coin to their Haqq-compatible wallets, with transparent gas usage powered by $ISLM.</li>
                  <li><strong>Anti-fraud and Phishing Protection:</strong> AI models detect spoofed or dishonest submissions to ensure that mining remains merit-based and spiritually authentic.</li>
                  <li><strong>MPoints Ledger and Conversion Engine:</strong> User actions generate MPoints, which are verified and converted into Muslim Coin tokens according to predefined spiritual criteria.</li>
                </ul>

                <h3 className="text-xl font-semibold mb-3 text-emerald-700">The Muslim Coin Ecosystem Architecture</h3>
                <p className="mb-4">
                  The Muslim Coin infrastructure is a combination of blockchain, AI, mobile tech and secure backend systems all working together to create a spiritual and financial platform.
                </p>

                <h4 className="text-lg font-semibold mb-3 text-emerald-600">A. Mobile App (Front-end)</h4>
                <ul className="list-disc pl-6 mb-4">
                  <li><strong>User Interface:</strong> Intuitive design for prayer-related tasks, rewards, and wallet access.</li>
                  <li><strong>Real Time Verification Engine:</strong> GPS, image capture, and time stamps are used to verify user actions (e.g., being in the masjid).</li>
                  <li><strong>AI-assisted Task Validation:</strong> Prevents fraudulent behavior using audio, visual and location-based filters.</li>
                </ul>

                <h4 className="text-lg font-semibold mb-3 text-emerald-600">B. App Backend (Middleware Layer)</h4>
                <ul className="list-disc pl-6 mb-4">
                  <li><strong>MPoints Engine:</strong> Calculate and tracks user spiritual actions (wudu, salat, adzan, etc.) as MPoints.</li>
                  <li><strong>Conversion Protocol:</strong> MPoints are converted to Muslim Coin based on a transparent algorithm and unlock criteria (e.g., completion of 5 daily prayers).</li>
                  <li><strong>Security Layer:</strong> Manages authentication, encrypted storage, and user data privacy.</li>
                </ul>

                <h4 className="text-lg font-semibold mb-3 text-emerald-600">C. Smart Contracts (Deployed on Haqq)</h4>
                <ul className="list-disc pl-6 mb-6">
                  <li><strong>Reward Distribution:</strong> Fair issuance of Muslim tokens based on on-chain or validated off-chain actions.</li>
                  <li><strong>Governance Contracts:</strong> Enable token holders to vote on upgrades and charity (zakat/sadaqah) disbursement.</li>
                  <li><strong>Withdrawal Mechanism:</strong> Lets users transfer Muslim tokens to their Haqq-compatible wallets with $ISLM gas support.</li>
                  <li><strong>Donation and Charity Pools:</strong> Allow users to contribute their earnings to verified Islamic causes.</li>
                </ul>

                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Scalability and Future-Proofing</h3>
                <ul className="list-disc pl-6 mb-6">
                  <li><strong>Layer 2 Integration:</strong> The architecture can adopt L2 solutions like Arbitrum/zkSync if needed for lower fees and higher throughput.</li>
                  <li><strong>Rollout in Phases:</strong> MVP focuses on prayer-based mining, followed by masjid-based campaigns, and finally integration with e-commerce, charities, and Hajj services.</li>
                </ul>

                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Privacy and Ethics</h3>
                <ul className="list-disc pl-6 mb-6">
                  <li><strong>Data Minimization:</strong> Only necessary user data is collected, mostly anonymized where possible.</li>
                  <li><strong>Zero Knowledge Proof (ZKP) Potential:</strong> ZKPs can be used in the future to prove prayer participation without sharing sensitive data.</li>
                  <li><strong>Shariah Review:</strong> All technology is subject to periodic review by Islamic scholars and independent auditors to ensure ongoing compliance.</li>
                </ul>

                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Gas Fees and Transaction Costs</h3>
                <p className="mb-4">
                  Muslim Coin respects financial transparency while Haqq requires $ISLM for gas. Muslim Coin will:
                </p>
                <ul className="list-disc pl-6 mb-6">
                  <li><strong>Subsidize Gas Fees:</strong> For new or low-income users during the early phases.</li>
                  <li><strong>Use a Transparent Fee Policy:</strong> Ensuring users know when and why a fee is incurred.</li>
                  <li><strong>Explore Meta-transactions:</strong> Or gasless interactions for core spiritual tasks.</li>
                </ul>

                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Security and Transparency</h3>
                <ul className="list-disc pl-6 mb-6">
                  <li>All smart contracts are audited before deployment.</li>
                  <li>All user actions are logged immutably on-chain (where necessary) and off-chain for sensitive private spiritual tasks.</li>
                  <li>Regular third-party Shariah audits and open-source disclosures will maintain accountability.</li>
                </ul>

                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Scalability and Security Details</h3>
                
                <h4 className="text-lg font-semibold mb-3 text-emerald-600">Scalability</h4>
                <p className="mb-4">
                  Muslim Coin is engineered with a modular, future-ready infrastructure designed to handle adoption across the global Muslim community.
                </p>
                
                <h5 className="font-semibold mb-2">Key Strategies for Scalability:</h5>
                <ul className="list-disc pl-6 mb-6">
                  <li><strong>Built on Haqq Blockchain:</strong> Leveraging the efficiency and speed of a purpose-built, EVM-compatible Islamic Layer-1 blockchain.</li>
                  <li><strong>Layer-2 Integration (Future Phase):</strong> Plans to integrate Layer 2 solutions such as Arbitrum or zkRollups to enable low-cost, high-throughput transactions while preserving decentralization and Shariah-compliance.</li>
                  <li><strong>Decentralized Task Processing:</strong> As the number of users and tasks increase, the app architecture will offload verifications (GPS, AI checks, etc.) using scalable cloud functions and decentralized oracles.</li>
                  <li><strong>Microservices-based Backend:</strong> The backend system is modular, making it easier to scale specific features (e.g., prayer-tracking, MPoints validation, user wallets) independently as demand grows.</li>
                  <li><strong>International Rollout Strategy:</strong> Scalability is also geographical, with phased launches across countries, accommodating regional regulations and local religious oversight bodies.</li>
                </ul>

                <h4 className="text-lg font-semibold mb-3 text-emerald-600">Security</h4>
                <p className="mb-4">
                  Security is a cornerstone of Muslim Coin both in protecting users and in upholding the sanctity of the spiritual actions it rewards.
                </p>

                <h5 className="font-semibold mb-2">Core Security Principles:</h5>
                <ul className="list-disc pl-6 mb-4">
                  <li><strong>Smart Contract Audits:</strong> All deployed contracts on Haqq undergo regular audits by reputable Web3 security firms to ensure vulnerability-free operations.</li>
                </ul>

                <h5 className="font-semibold mb-2">Data Protection and Privacy:</h5>
                <ul className="list-disc pl-6 mb-4">
                  <li><strong>End-to-End Encryption:</strong> All user data including images, GPS, and task verification is encrypted during transmission and storage.</li>
                  <li><strong>Minimal Data Collection:</strong> Only essential data for task validation is collected; optional biometric or camera input is handled with user consent.</li>
                </ul>

                <ul className="list-disc pl-6 mb-6">
                  <li><strong>AI Integrity Layer:</strong> Prevents manipulation of proof-based tasks (e.g., falsified masjid check-ins or pre-recorded adzan audio) through behavioral pattern recognition and anomaly detection.</li>
                  <li><strong>Secure Wallet Integration:</strong> Transfers between the Muslim Coin mining app and the Haqq wallet use encrypted transaction signing and require 2FA where applicable.</li>
                  <li><strong>Phishing and Fraud Protection:</strong> In-app alerts, AI filters and user education campaigns will help protect users from social engineering attacks.</li>
                  <li><strong>Zakat and Sadaqah Safeguards:</strong> Charitable pools are governed by multi-signature wallets and subject to DAO governance for transparent fund management.</li>
                </ul>
              </div>
            </TabsContent>

            <TabsContent value="roadmap" className="bg-white p-8 rounded-2xl shadow-lg">
              <h2 className="text-3xl font-bold mb-6 gradient-text">Development Roadmap</h2>
              <div className="prose max-w-none text-gray-700 leading-relaxed">
                <p className="text-lg mb-8 text-center">
                  <strong>Key Milestones from Idea to Post-TGE</strong>
                </p>
                
                <div className="space-y-8">
                  <div className="border-l-4 border-emerald-500 pl-6 bg-emerald-50 p-6 rounded-r-lg">
                    <h3 className="text-xl font-bold text-emerald-700 mb-3">Phase 1: Ideation and Validation</h3>
                    <p className="text-sm text-emerald-600 font-medium mb-4">Q3 2025 - Q4 2025</p>
                    <ul className="list-disc pl-6 space-y-2">
                      <li>Whitepaper drafting and tokenomics development</li>
                      <li>Branding, logo design, and app interface mockups</li>
                      <li>Conceptualization of Muslim Coin's mining model via Islamic practices</li>
                      <li>Community channels launched: Telegram, Instagram, Twitter, LinkedIn, Discord, YouTube</li>
                      <li>Community outreach and early Shariah advisory consultations</li>
                      <li>Domain and web presence established (Muslimcoin.org)</li>
                      <li>Roll-out referral program</li>
                      <li>App prototype for MPoints system</li>
                      <li>Early AI models for task verification</li>
                    </ul>
                  </div>
                  
                  <div className="border-l-4 border-gold-500 pl-6 bg-gold-50 p-6 rounded-r-lg">
                    <h3 className="text-xl font-bold text-gold-700 mb-3">Phase 2: App Development and Soft Rollout</h3>
                    <p className="text-sm text-gold-600 font-medium mb-4">Q4 2025 - Q1 2026</p>
                    <ul className="list-disc pl-6 space-y-2">
                      <li>Design and build Muslim Coin mining app MVP</li>
                      <li>Integrate AI features for mining task validation (ablution, mosque check-in etc.)</li>
                      <li>Beta-test with early adopters and feedback</li>
                      <li>Launch the Iman-Jar bonus reward system</li>
                      <li>Begin onboarding early users</li>
                      <li>Onboarding religious institutions for app compliance review</li>
                    </ul>
                  </div>
                  
                  <div className="border-l-4 border-blue-500 pl-6 bg-blue-50 p-6 rounded-r-lg">
                    <h3 className="text-xl font-bold text-blue-700 mb-3">Phase 3: Growth, Utility and Ecosystem Building</h3>
                    <p className="text-sm text-blue-600 font-medium mb-4">Q1 2026 - Q4 2026</p>
                    <ul className="list-disc pl-6 space-y-2">
                      <li>Full scale app launch</li>
                      <li>Mining phase begins (no public token yet)</li>
                      <li>Strategic partnerships with masjids, Islamic institutions, and Hajj boards etc.</li>
                      <li>Content campaigns to educate on halal DeFi</li>
                      <li>Rollout AI-powered mining verification globally</li>
                      <li>Launch community governance feature</li>
                      <li>Integrate educational tools and Quran-linked achievements</li>
                    </ul>
                  </div>
                  
                  <div className="border-l-4 border-purple-500 pl-6 bg-purple-50 p-6 rounded-r-lg">
                    <h3 className="text-xl font-bold text-purple-700 mb-3">Phase 4: Token Infrastructure and Ecosystem Readiness</h3>
                    <p className="text-sm text-purple-600 font-medium mb-4">Q2 2026 - Q4 2026</p>
                    <ul className="list-disc pl-6 space-y-2">
                      <li>Build token infrastructure on Haqq blockchain</li>
                      <li>Finalize smart contracts (halal, no riba, no staking) "ERC-20" Compatible</li>
                      <li>Internal audit and compliance check, security validation</li>
                      <li>Educate users on gas-fee structure and wallet management</li>
                      <li>KYC for users</li>
                    </ul>
                  </div>
                  
                  <div className="border-l-4 border-red-500 pl-6 bg-red-50 p-6 rounded-r-lg">
                    <h3 className="text-xl font-bold text-red-700 mb-3">Phase 5: Pre-Token Generation Event (PRE-TGE)</h3>
                    <p className="text-sm text-red-600 font-medium mb-4">Q3 2026 - Q4 2026</p>
                    <ul className="list-disc pl-6 space-y-2">
                      <li>Reach out to whale investors and halal venture funds</li>
                      <li>Launch marketing campaigns targeting the global Muslim audience</li>
                      <li>Secure religious and scholarly endorsements</li>
                      <li>Build strategic partnerships with Islamic fintechs and institutions</li>
                      <li>Initial token distribution to early backers and community</li>
                      <li>Enable in-app token transfers: sadaqah, and zakat functions</li>
                    </ul>
                  </div>
                  
                  <div className="border-l-4 border-green-500 pl-6 bg-green-50 p-6 rounded-r-lg">
                    <h3 className="text-xl font-bold text-green-700 mb-3">Phase 6: Token Generation Event (TGE) and Investor Rounds</h3>
                    <p className="text-sm text-green-600 font-medium mb-4">Q4 2026 - Q2 2027</p>
                    <ul className="list-disc pl-6 space-y-2">
                      <li>Public token launch (IDO/ICO)</li>
                      <li>Wallet integration and user onboarding</li>
                      <li>Listings on halal compliant DEXs and CEXs (Shariah compliant exchanges preferred)</li>
                      <li>Initial partnerships with Hajj, Umrah, and Islamic commerce platforms</li>
                    </ul>
                  </div>
                  
                  <div className="border-l-4 border-indigo-500 pl-6 bg-indigo-50 p-6 rounded-r-lg">
                    <h3 className="text-xl font-bold text-indigo-700 mb-3">Phase 7: Post-TGE Expansion</h3>
                    <p className="text-sm text-indigo-600 font-medium mb-4">Q2 2027 - Onwards</p>
                    <div className="grid md:grid-cols-2 gap-4">
                      <div>
                        <h4 className="font-semibold text-indigo-600 mb-2">Core Utilities & Partnerships</h4>
                        <ul className="list-disc pl-6 space-y-1 text-sm">
                          <li>Introduce utilities: payments, zakat, governance</li>
                          <li>Partner with Islamic ecommerce and Hajj platforms for use cases</li>
                          <li>Global Islamic finance bodies collaboration</li>
                          <li>Bridge to other halal token ecosystems</li>
                        </ul>
                      </div>
                      <div>
                        <h4 className="font-semibold text-indigo-600 mb-2">Technology & Security</h4>
                        <ul className="list-disc pl-6 space-y-1 text-sm">
                          <li>Ongoing security audits and tech upgrades</li>
                          <li>Educational programs on ethical Web3 use</li>
                          <li>Exploration of cross-chain bridges and Layer 2 scaling</li>
                        </ul>
                      </div>
                      <div>
                        <h4 className="font-semibold text-indigo-600 mb-2">Global Expansion</h4>
                        <ul className="list-disc pl-6 space-y-1 text-sm">
                          <li>Scale platform into other Muslim-majority regions</li>
                          <li>Multilingual support and localized religious rulings</li>
                          <li>Regular updates and community reward programs</li>
                        </ul>
                      </div>
                      <div>
                        <h4 className="font-semibold text-indigo-600 mb-2">Islamic Finance Integration</h4>
                        <ul className="list-disc pl-6 space-y-1 text-sm">
                          <li>Collaborate with Islamic charities and zakat organizations</li>
                          <li>Explore Halal DeFi offerings (savings, loans, liquidity pools)</li>
                          <li>Begin integration with Waqf and mosque funding networks</li>
                        </ul>
                      </div>
                    </div>
                  </div>
                </div>
                
                <div className="mt-12 p-6 bg-gradient-to-r from-emerald-50 to-gold-50 rounded-xl border border-emerald-200">
                  <h3 className="text-lg font-bold text-center mb-4 gradient-text">🌙 Timeline Overview</h3>
                  <div className="text-center text-gray-700">
                    <p className="mb-2"><strong>Development Phase:</strong> Q3 2025 - Q4 2026 (15 months)</p>
                    <p className="mb-2"><strong>Token Launch:</strong> Q4 2026 - Q2 2027 (6 months)</p>
                    <p><strong>Expansion & Growth:</strong> Q2 2027 onwards</p>
                  </div>
                </div>
              </div>
            </TabsContent>

            <TabsContent value="team" className="bg-white p-8 rounded-2xl shadow-lg">
              <h2 className="text-3xl font-bold mb-6 gradient-text">Team & Advisors</h2>
              <div className="prose max-w-none text-gray-700 leading-relaxed">
                <p className="text-lg mb-6">
                  Muslim Coin is guided by a multidisciplinary team of committed Muslims with expertise across blockchain technology, AI development, Islamic finance, and community building.
                </p>
                
                <h3 className="text-xl font-semibold mb-4 text-emerald-700">Core Team</h3>
                <div className="grid md:grid-cols-2 gap-6 mb-8">
                  <div className="bg-emerald-50 p-6 rounded-lg">
                    <h4 className="text-lg font-semibold mb-2 text-emerald-700">🌟 Founder and Visionary</h4>
                    <p className="text-sm">
                      Leads the mission to build a Shariah-aligned decentralized finance platform that empowers Muslims globally through innovative blockchain technology.
                    </p>
                  </div>
                  
                  <div className="bg-blue-50 p-6 rounded-lg">
                    <h4 className="text-lg font-semibold mb-2 text-blue-700">⚡ Blockchain Developer</h4>
                    <p className="text-sm">
                      Leads smart contract development and ensures secure integration with the Haqq Blockchain and DeFi ecosystem.
                    </p>
                  </div>
                  
                  <div className="bg-purple-50 p-6 rounded-lg">
                    <h4 className="text-lg font-semibold mb-2 text-purple-700">🤖 AI Integration Engineer</h4>
                    <p className="text-sm">
                      Responsible for implementing AI mechanisms that validate mining tasks, ensuring authenticity and fairness in the spiritual mining process.
                    </p>
                  </div>
                  
                  <div className="bg-orange-50 p-6 rounded-lg">
                    <h4 className="text-lg font-semibold mb-2 text-orange-700">🎨 UI/UX and App Developer</h4>
                    <p className="text-sm">
                      Designs and builds the user interface of the Muslim Coin mining app with a clean, intuitive, and inclusive experience.
                    </p>
                  </div>
                  
                  <div className="bg-green-50 p-6 rounded-lg md:col-span-2">
                    <h4 className="text-lg font-semibold mb-2 text-green-700">📈 Community and Growth Manager</h4>
                    <p className="text-sm">
                      Oversees social platforms and partnership outreach, building an engaged, values-aligned community across multiple channels including Telegram, Instagram, Twitter, LinkedIn, Discord, and YouTube.
                    </p>
                  </div>
                </div>
                
                <h3 className="text-xl font-semibold mb-4 text-emerald-700">Advisory Board (In Formation)</h3>
                <p className="mb-6">
                  We aim to form a respected advisory board comprising distinguished experts across multiple domains to ensure Muslim Coin's success and compliance:
                </p>
                
                <div className="space-y-4 mb-8">
                  <div className="border-l-4 border-emerald-500 pl-6 bg-emerald-50 p-4 rounded-r-lg">
                    <h4 className="text-lg font-semibold mb-2 text-emerald-700">📖 Shariah Scholars</h4>
                    <p className="text-sm">
                      To ensure ongoing compliance with Islamic principles, particularly in areas like staking, riba, zakat, and ethical use of technology in religious contexts.
                    </p>
                  </div>
                  
                  <div className="border-l-4 border-blue-500 pl-6 bg-blue-50 p-4 rounded-r-lg">
                    <h4 className="text-lg font-semibold mb-2 text-blue-700">🔗 Crypto and Web3 Experts</h4>
                    <p className="text-sm">
                      Advising on scaling strategies, investor relations, security best practices, and tokenomics optimization for sustainable growth.
                    </p>
                  </div>
                  
                  <div className="border-l-4 border-gold-500 pl-6 bg-gold-50 p-4 rounded-r-lg">
                    <h4 className="text-lg font-semibold mb-2 text-gold-700">💰 Islamic Finance Consultants</h4>
                    <p className="text-sm">
                      Guiding halal financial integrations and ensuring Muslim Coin fits seamlessly into the Islamic economic framework and existing Shariah-compliant financial systems.
                    </p>
                  </div>
                  
                  <div className="border-l-4 border-purple-500 pl-6 bg-purple-50 p-4 rounded-r-lg">
                    <h4 className="text-lg font-semibold mb-2 text-purple-700">⚖️ Legal and Regulatory Advisors</h4>
                    <p className="text-sm">
                      Providing guidance across multiple jurisdictions, ensuring Muslim Coin aligns with local and global cryptocurrency regulations while maintaining Islamic compliance.
                    </p>
                  </div>
                </div>
                
                <div className="bg-gradient-to-r from-emerald-50 to-gold-50 p-6 rounded-xl border border-emerald-200">
                  <h3 className="text-lg font-bold mb-3 gradient-text">🤝 Collaborative Leadership</h3>
                  <p className="text-gray-700">
                    Together, this dedicated team and advisory board will guide the growth of Muslim Coin through its early mining phase, token launch, and eventual utility integrations across the global Islamic financial ecosystem. Our commitment to Islamic principles, combined with cutting-edge technology expertise, positions Muslim Coin as a trusted bridge between faith and digital innovation.
                  </p>
                </div>
              </div>
            </TabsContent>

            <TabsContent value="compliance" className="bg-white p-8 rounded-2xl shadow-lg">
              <h2 className="text-3xl font-bold mb-6 gradient-text">Compliance & Ethics</h2>
              <div className="prose max-w-none text-gray-700 leading-relaxed">
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Sharia Compliance</h3>
                <p className="mb-4">
                  Every aspect of MuslimCoin undergoes rigorous Sharia compliance review by our Islamic Advisory Board, ensuring adherence to Islamic principles including:
                </p>
                <ul className="list-disc pl-6 mb-4">
                  <li>Prohibition of riba (interest)</li>
                  <li>Avoidance of gharar (excessive uncertainty)</li>
                  <li>Asset-backed value proposition</li>
                  <li>Ethical business practices</li>
                </ul>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Regulatory Compliance</h3>
                <p className="mb-4">
                  We work closely with regulatory bodies in key markets to ensure full compliance with local laws while maintaining our Islamic principles.
                </p>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Transparency & Accountability</h3>
                <p className="mb-4">
                  Regular audits, public reporting of zakat distributions, and open-source development practices ensure complete transparency.
                </p>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Data Privacy</h3>
                <p>
                  User privacy is protected according to both Islamic principles and international data protection standards.
                </p>
              </div>
            </TabsContent>

            <TabsContent value="community" className="bg-white p-8 rounded-2xl shadow-lg">
              <h2 className="text-3xl font-bold mb-6 gradient-text">Community & Ecosystem</h2>
              <div className="prose max-w-none text-gray-700 leading-relaxed">
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Global Muslim Network</h3>
                <p className="mb-4">
                  MuslimCoin creates a digital bridge connecting Muslims worldwide, fostering community bonds through shared faith-based activities and mutual support.
                </p>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Ecosystem Partners</h3>
                <ul className="list-disc pl-6 mb-4">
                  <li>Islamic banks and financial institutions</li>
                  <li>Halal businesses and merchants</li>
                  <li>Islamic educational institutions</li>
                  <li>Charitable organizations</li>
                  <li>Mosque networks</li>
                </ul>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Community Governance</h3>
                <p className="mb-4">
                  Following the Islamic principle of Shura (consultation), major decisions are made through community consensus and transparent voting mechanisms.
                </p>
                
                <h3 className="text-xl font-semibold mb-3 text-emerald-700">Educational Initiatives</h3>
                <p>
                  Comprehensive educational programs help community members understand both Islamic finance principles and blockchain technology.
                </p>
              </div>
            </TabsContent>

            <TabsContent value="conclusion" className="bg-white p-8 rounded-2xl shadow-lg">
              <h2 className="text-3xl font-bold mb-6 gradient-text">Conclusion</h2>
              <div className="prose max-w-none text-gray-700 leading-relaxed">
                <p className="text-lg mb-4">
                  MuslimCoin represents more than just a cryptocurrency—it's a movement to empower the global Muslim community through technology that aligns with our values and strengthens our faith.
                </p>
                
                <p className="mb-4">
                  By combining blockchain innovation with Islamic principles, we create a unique ecosystem where spiritual practice generates real-world value, community bonds are strengthened, and charitable giving is seamlessly integrated into daily life.
                </p>
                
                <p className="mb-4">
                  Our vision extends beyond financial transactions to encompass education, community building, and the preservation of Islamic values in the digital age. Through MuslimCoin, we aim to demonstrate that technology can serve faith, rather than replace it.
                </p>
                
                <div className="bg-emerald-50 p-6 rounded-lg mt-6">
                  <h3 className="text-xl font-semibold mb-3 text-emerald-700">Join the Movement</h3>
                  <p className="mb-0">
                    Together, we can build a more inclusive, ethical, and faith-based digital economy. Join us in making MuslimCoin a reality and be part of the future of Islamic finance.
                  </p>
                </div>
                
                <div className="text-center mt-8">
                  <p className="text-emerald-600 font-semibold">
                    🌙 Halal • Blessed • Decentralized
                  </p>
                </div>
              </div>
            </TabsContent>
          </Tabs>
        </div>
      </main>
      <Footer />
    </div>;
};

export default Whitepaper;

MuslimCoin is a decentralized, Shariah-compliant digital currency designed to **reward Islamic practices**, promote **financial inclusion**, and build a value-driven Web3 economy rooted in **ethical, faith-based principles**.

Through a unique **mine-to-earn** system built on the **Haqq Blockchain**, users earn **MuslimCoin (MUSC)** by completing verifiable Islamic tasks such as ablution, attending the mosque, and making adhan — all tracked and authenticated through AI.

---

## 🛠️ Project Features

- 📱 **Mobile Mining App** – Earn MPoints by completing faith-aligned daily tasks.
- 🤖 **AI Verification** – Verifies ablution, masjid presence, adhkar recordings.
- 💰 **Token Utility** – Use MUSC for payments, zakat, sadaqah, and governance.
- 🎁 **Iman Jar** – Bonus reward system for du’as, extra worship, and da’wah.
- 🌙 **DAO Governance** – Community voting on key proposals.
- 📢 **Refer-to-Earn** – Invite others and gain bonus MPoints.

---

## 🧩 Built With

- 🔗 [Haqq Blockchain](https://haqq.network) – Shariah-compliant Layer 1 blockchain
- 🧠 AI/ML – Verifies user-submitted Islamic tasks (coming soon)
- 📱 React Native – Mobile app (MVP)
- 🪙 Solidity – Token smart contracts (ERC-20)

---

## 🔒 Shariah Compliance

- ❌ No Riba (interest-based staking removed)
- ✅ Zakat integration
- ✅ Waqf & charity support
- ✅ Halal investment pools (screened & vetted)

---

## 🛣️ Roadmap Snapshot

**Phase 1 – Ideation (Q3 2025):** Branding, whitepaper, prototype, community  
**Phase 2 – App Dev (Q4 2025):** AI validation, MVP rollout  
**Phase 3 – Ecosystem Growth (2026):** Full mining app, DAO governance  
**Phase 4 – Token Infra (2026):** Smart contracts, audit, user education  
**Phase 5 – Pre-TGE (Late 2026):** Investor outreach, token distribution  
**Phase 6 – TGE & Listing (2027):** Public token launch  
**Phase 7 – Post-TGE Expansion:** Use-case scale, zakat integration, cross-chain bridges

---

## 🤝 Join the Movement

> MuslimCoin aims to serve over **2 billion Muslims worldwide** with a Web3 economy that reflects our values.

---

## 📬 Contact

- **Website:** [https://officialmuslimcoin.org](https://officialmuslimcoin.org)
- **Telegram:** [t.me/MuslimCoinOfficial](https://t.me/MuslimCoinOfficial)
- **X (Twitter):** [@ThemuslimCoin](https://twitter.com/MuslimCoinApp)
- **Email:** muslimcoinproject@outlook.com

---

## 📜 License

MIT License – Open-source for collaboration and community building.

---

> _“Empowering the Ummah through faith-driven innovation.”_

👉 [Read our Contribution Guide](CONTRIBUTING.md)