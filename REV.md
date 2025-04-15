
	{
		"name": "Slave Market",
		"replaces": "Market",
		"uniqueTo": "Macrobia",
		"specialistSlots": {"Merchant": 1},
		"hurryCostModifier": 25,
		"gold": 4,
		"percentStatBonus": {"gold": 25},
		"uniques": ["Free [Worker] appears"],
		"requiredTech": "Currency"
	},
	    {
		"name": "Smeltery",
        "replaces": "Forge",
		"uniqueTo": "Nok",
        "maintenance": 1,
		"production": 1,
        "hurryCostModifier": 25,
        "requiredTech": "Iron Working",
        "uniques": ["Provides [2] [Iron]","[+15]% Production when constructing [Spaceship part] units [in this city]",
			"[+15]% Production when constructing [Land] units [in this city]",
			"[+1 Production] from [Iron] tiles [in this city]"]
    },{
		"name": "Stupa",
		"replaces": "Temple",
		"uniqueTo": "Champa", 
		"maintenance": 2,
		"faith": 2,
		"culture": 1,
		"hurryCostModifier": 25,
       		"cost": 100,
		"uniques": ["[+1 Faith] from [Jungle] tiles [in this city]"],
		"requiredTech": "Philosophy"
	},
	{
		"name": "Khachkar",
		"replaces": "Shrine",
		"uniqueTo": "Armenia", 
		"faith": 1,
		"cost": 40,
		"requiredTech": "Pottery",
		"hurryCostModifier": 40,
		"uniques": ["[+2 Faith] from [Mountain] tiles [in this city]"]
	},
	{
        "name": "IRRI",
        "science": 3,
        "percentStatBonus": {"science": 25, "food": 10},
        "specialistSlots": {"Scientist": 3},
        "replaces": "University",
        "uniqueTo": "Philippines",
        "maintenance": 3,
        "hurryCostModifier": 25,
        "uniques": ["[+2 Science] from [Farm] tiles [in this city]"],
        "requiredTech": "Education"
    },
	{ 
		"name": "Palengke",
		"replaces": "Market",
		"uniqueTo": "Philippines",
		"gold": 2,
		"specialistSlots": {"Merchant": 1},
		"hurryCostModifier": 23,
		"percentStatBonus": {"gold": 30},
		"uniques": [
			"Comment [[+1 Food, +1 Gold, +1 Production] from each Trade Route (doubled from the [Industrial era] onwards)]",
			"Comment [[+1 Gold, +1 Production] from [Stone] tiles; and [+1 Gold, +1 Food] from other [Bonus resource] tiles [in this city]]",
			"Comment [[+1 Production, +1 Food] from [Horses] tiles; and [+1 Production, +1 Gold] from other [Strategic resource] tiles [in this city]]",
			"[+1 Gold, +1 Production, +1 Happiness] from [Luxury resource] tiles [in this city]",
			"[+1 Food, +1 Gold, +1 Production] from each Trade Route <before the [Industrial era]> <hidden from users>",
			"[+2 Food, +2 Gold, +2 Production] from each Trade Route <starting from the [Industrial era]> <hidden from users>",
			"[+1 Food, +1 Gold] from [Bonus resource] tiles [in this city] <in tiles without [Stone]> <hidden from users>",
			"[+1 Production, +1 Gold] from [Stone] tiles [in this city] <hidden from users>",
			"[+1 Production, +1 Gold] from [Strategic resource] tiles [in this city] <in tiles without [Horses]> <hidden from users>",
			"[+1 Production, +1 Food] from [Horses] tiles [in this city] <hidden from users>"
		],
		"requiredTech": "Currency"
	},
    {
        "name": "Forum",
        "replaces": "Amphitheater",
        "uniqueTo": "Rome",
        "cost": 95,
        "culture": 3,
        "faith": 1,
        "happiness": 2,
        "requiredBuilding": "Monument",
        "maintenance": 2,
        "hurryCostModifier": 25,
        "uniques": [
            "Destroyed when the city is captured",
            "Comment [Has 1 Great Work of Writing Slot]"
        ],
        "requiredTech": "Drama and Poetry"
    },
    {
        "name": "Research Institute",
	"replaces": "Public School",
	"uniqueTo": "Russia",
	"science": 3,
        "specialistSlots": {"Scientist": 1},
        "requiredBuilding": "University",
        "maintenance": 3,
        "hurryCostModifier": 0,
        "uniques": [
            "[+2 Science] per [2] population [in this city]",
            "[+2 Science] from [Forest] tiles [in this city]"
        ],
        "requiredTech": "Scientific Theory"
    },
    {
        "name": "Sacrificial Altar",
        "uniqueTo": "Aztecs",
        "replaces": "Courthouse",
        "culture": 1,
        "faith": 2,
        "happiness": 3,
        "hurryCostModifier": 50,
        "uniques": [
            "Remove extra unhappiness from annexed cities",
            "Can only be built <in [Annexed] cities>"
        ],
        "requiredTech": "Mathematics"
    },
    {
        "name": "Supermarket",
	"requiredBuilding": "Grocer",
	"cost": 400,
        "food": 3,
        "production": 3,
        "maintenance": 4,
        "percentStatBonus": {"gold": 10},
        "requiredTech": "Replaceable Parts"
    },
    {
        "name": "Mall",
	"requiredBuilding": "Grocer",
	"uniqueTo": "America",
	"cost": 400,
        "food": 2,
        "culture": 2,
	"production": 2,
        "maintenance": 4,
        "percentStatBonus": {"gold": 10},
        "requiredTech": "Replaceable Parts"
    },
    {
        "name": "Hypermarket",
	"requiredBuilding": "Grocer",
        "uniqueTo": "Colziand",
	"cost": 400,
        "food": 2,
	"gold": 2,
        "production": 2,
        "maintenance": 4,
        "percentStatBonus": {"gold": 10},
        "requiredTech": "Replaceable Parts"
    },
	{
		"name": "Philippines",
		"leaderName": "Andrés Bonifacio",
		"adjective": ["Filipino"],
		"favoredReligion": "Catholicism",
		"startBias": ["Coast"],
        "preferredVictoryType": "Scientific",

		"startIntroPart1": "Greetings, Supremo Andres Bonifacio. Your great intellect and strong understanding of the Filipino plight allowed you to forge numerous successful victories against the Spaniards and the Americans.",
		"startIntroPart2": "Most courageous and magnanimous Supremo, Philippines once again requires the service of a compassionate and determined leader, one who can reunite the country and establish a strong foundation for the years to come. Can you establish your nation through strong civil institutions, or will you work to conquer your enemies through the use of force? Can you build a civilization that will stand the test of time?",
		"declaringWar": "Your ways have been revealed. Time to fight for what is ours!",
		"attacked": "This insolence will cost you dearly!",
		"defeated": "The Filipino people is worth dying for",
		"introduction": "Welcome to the Philippines. I am Supremo Andres Bonifacio.",
		"neutralHello": "Greetings.",
		"hateHello": "Hello! What do you want?",
		"tradeRequest": "This offer won't be valid for a lot of time, think about it.",
		"outerColor": [139,0,0],
		"innerColor": [255,255,255],
		"uniqueName": "Sovereign Tagalog Nation",
		"uniques": ["Gain an extra spy <upon entering the [Modern era]>","Starts with [Navigation School] adopted",
			"[+2 Production] from every [Farm]","[+2 Food] from every [Terrace farm]","[+2 Production, +2 Food] from every [Polder]"],
		"cities": ["Manila","Cavite","Bulácan","Santa Cruz","Batangas","Bacolor","Cabanatuan","Tárlac","Vigan","Puerto Princesa","Davao","Aparri","Ilo-ilo","Zamboanga","Albay","Cebú",
			"Iligan","Balanga","Tacloban","Surigao","Mórong","Bacolód","Tayabas","Tagbilaran","Daet","Catbalogan","Nueva Cáceres","Cápix","Sorsogon","Concepción","Binangonan",
			"San José de Buenavista","Iba","Dumaguete","Calapan","Dagupan","Baler","Bayombong","La Trinidad","San Fernando","Ilagan","Cagayán","Binorungan","Bangued","Laoag","Sabah-Borneo"
	   		]
	},
	{
		"name": "Epirus",
		"leaderName": "Pyrrhus",
		"adjective": ["Epirote"],
		"preferredVictoryType": "Domination",
		
		"startIntroPart1": "TBD",
		"startIntroPart2": "TBD",
		
		"declaringWar": "There can be only one king. Prepare for battle!",
		"attacked": "I think my emissary must have been late, I already declared war on you!",
		"defeated":  "You were a worthy opponent. The gods will welcome me!",
		"introduction":  "Welcome to Epirus, friend. I am king Pyrrhus. Are you another expenda... I mean Ally... or perhaps a next target of my army?",
		
		"neutralHello": "Greeting",
		"neutralLetsHearIt": ["Yes.","Let's discuss."],
		"neutralNo": ["No way.","Never!"],
		"neutralYes": ["Very good.","Of course, yes.","I accept."],
		"hateHello": "Go on!",
		"hateLetsHearIt": ["Speak!"],
		"hateNo": ["I can't accept!","You need to try harder."],
		"hateYes": ["Let it be.","This offer is too good to reject."],
		
		"afterPeace": "Hail, great lord. This was indeed a good fight.",
		"tradeRequest": "That should do.",

		"innerColor": [	232, 170, 158],
		"outerColor": [	94, 50, 0],
		"uniqueName": "Pyrrhic Victory",
		"uniqueText": "All military units have + 25% more strength when attacking cities, but suffer -25% penalty when defending against cities. +25% [Production] when constructing military units in capital. Gains a free [Great General] upon researching Bronze Working and Steel",
		"uniques": ["[Military] units gain the [March] promotion","[+25]% Production when constructing [Military] units [in capital]","Free [Great General] appears <upon discovering [Bronze Working] technology>","Free [Great General] appears <upon discovering [Steel] technology>"],
		"cities": ["Ambracia","Phoenike","Passaron"]
	},
	{
		"name": "Champa",
		"leaderName": "Chế Bồng Nga",
		"adjective": ["Cham"],
		"startBias": ["Jungle","Grassland","Coast"],
		"preferredVictoryType": "Cultural",
		
		"startIntroPart1": "Greetings, Po Binasuor, last great king of Champa! Your enemies have never ceased to tremble at your legend! An Austronesian people, the Cham came to occupy a key position on the Indochinese coast mediating international sea trade with China. Yet, lacking the fertile rice fields of their neighbors, Champa grew to exploit these lucrative waters and developed a unique plunder based economy, gaining notoriety throughout the region for piracy. Champa would represent a melting-pot of Southeast Asia, introducing technology from China, trading with Indonesian merchants, intermarrying with the Khmer kings, and building unforgettable temples to the gods of ancient India. Yet, seemingly always at war, Champa fell, broken and desolate, to conquerors from the north.",
		"startIntroPart2": "Red King, it was you who reunited the tattered remains of your people and, outnumbered six to one, almost claimed victory over your bitter enemies, the Dai Viet! Will you now return to recalim your lost homeland? Can you build a civilization that will stand the test of time?",
		
		"declaringWar": "We tolerated you way longer than we should, and now we demand you pay with your blood.",
		"attacked": "We will ensure you will remember the day you turned on us.",
		"defeated":  "So that's how it all ends. That is not how I've imagined my last moments.",
		"introduction":  "I am the Red King of Champa, Chế Bồng Nga! Are you here to trade?",
		
		"neutralHello": "Greetings, friend.",
		"neutralLetsHearIt": ["Yes.","Let's discuss."],
		"neutralNo": ["No way.","Never!"],
		"neutralYes": ["Very good.","Of course, yes.","I accept."],
		"hateHello": "Go on!",
		"hateLetsHearIt": ["Speak!"],
		"hateNo": ["You dare to joke in my presence!?","Don't make me laugh!"],
		"hateYes": ["I must accept, even if i don't like you.","Fine."],
		
		"afterPeace": "I hope this won't happen again and even if it does - We've learned a lesson!",
		"tradeRequest": "Will this work or do I need to propose you a better deal?",

		"outerColor": [	78, 154, 230],
		"innerColor": [	204, 56, 53],
		"uniqueName": "Traders of the Shore",
		"uniques": ["[+1 Gold] from every [Luxury resource]","[1] Movement point cost to disembark <for [All] units>","[1] Movement point cost to embark <for [All] units>","[+1 Culture] from every [Trading post]"],
		"cities": ["Indrapura","My So'n","Vijaya","Mang Ly","Lam Ap Pho","Amaravati","Kauthara","Panduranga",
			"Thi Li Bi Nai","Trivakramapura","Balonga","Hamu Lithit","Dong Hoi","Aya Ru","Bingi",
			"Hve","Kon Tum","Yang Prong","Daknan","Kandarpapura","Eatran","Vishnupura","Tuy Hoa"]
	},
			{
		"name": "Republic of Genoa",
		"leaderName": "Simone Boccanegra",
		"adjective": ["Genoese"],
		"startBias": ["Coast"],
		"preferredVictoryType": "Diplomatic",
		
		"startIntroPart1": "Live long and prosper, Simone Boccanegra, Doge of mighty Genoa! Your reign was marked by an intense cliud of intrigue and subterfuge. Genoa, one of the contending powers for domination of the Mediterranean, was ruled by an aristocratic elite. Once elected Doge, you disposed of the established upper class in a revolutionary upheaval that would forever change Genoa's political landscape. Entrenched in a long war with Venice, that would eventually be lost, you fought off would-be assassins and rivals for five long years before being forced to resign. But your successors were less tenacious as you, and soon enough you came back to power. Your rule would last another seven years, before a poisoning attempt was finally successful.",
		"startIntroPart2": "Revolutionari Doge, your people are once again surrounded by enemies plotting Genoa's demise. Will you see through the ploys of your many rivals, and once again establish Genoa as a force to be reckoned with? Will you seize control of the seas, and establish dominance over the trade routes of this new world? Can you build a civilization that will stand the test of time?",
		
		"declaringWar": "I think we might have conflicting interests, actually - I am certain!",
		"attacked": "I hope you studied that thoroughly, because there will be no mercy.",
		"defeated": "I must leave... Farewell.",
		"introduction": "You stand in front of Simone Boccanera, the doge of Republic of Genoa. Would you mind a cup of wine? Or two?",
		
		"neutralHello": "Greetings.",
		"neutralLetsHearIt": ["Yes.","Speak."],
		"neutralNo": ["No.","That's unacceptable."],
		"neutralYes": ["I can't refuse.","I gladly accept."],
		"hateHello": "Don't waste my time!",
		"hateLetsHearIt": ["What's your offer?"],
		"hateNo": ["..."],
		"hateYes": ["We must accept."],
		
		"afterPeace": "Hopefully that little war did not impact our economic relations much.",
		"tradeRequest": "What is your proposal?",

		"outerColor": [255, 255, 255],
		"innerColor": [255, 0, 0],
		"uniqueName": "The Spark of the Renaissance",
		"uniques": ["[+15]% [Gold] [in all cities connected to capital]","[+15]% [Science] <during the [Medieval era]>"],
		"cities": ["Genoa","Ajaccio","Costanza","Albenga","Monaco","Savona","San Remo","Laiazzo","Giaffa","Basta","Porto-Vecchio","Sassari","Alghero","Nuoro","Olbia","Bonifacio"]
	},
			{
		"name": "Macrobia",
		"leaderName": "Sayid",
		"adjective": ["Macrobian"],
		"startBias": ["Coast"],
		"preferredVictoryType": "Domination",
		
		"startIntroPart1": "TBD",
		"startIntroPart2": "TBD",
		
		"declaringWar": "You have had your chance, now prepare for war!",
		"attacked": "You DARE declare war on us? We shall make you suffer!",
		"defeated":  "So that is how it all ends. I've never expected to end as a slave!",
		"introduction":  "Who are you? I bet You are here to admire our wealth.",
		
		"neutralHello": "Greetings.",
		"neutralLetsHearIt": ["Yes.","Go on."],
		"neutralNo": ["Do not test my patience!","Never!"],
		"neutralYes": ["Very good.","Of course, yes.","We accept."],
		"hateHello": "Don't waste much of my time!",
		"hateLetsHearIt": ["Speak!"],
		"hateNo": ["You can't be serious!","No one would agree to that. Ever."],
		"hateYes": ["Fine.","You can't simply refuse such offer."],
		
		"afterPeace": "We shall now pray for the better, I mean more profitable, days!",
		"tradeRequest": "I bring you an excellent offer!",

		"outerColor": [	84, 215, 247],
		"innerColor": [	255, 255, 255],
		"uniqueName": "Shackles of Gold",
		"uniqueText": "Earns [Gold] for killing enemy land units", 
		"uniques": ["Earn [75]% of killed [Land] unit's [Strength] as [Gold]"],
		"cities": ["Mogadishu","Avalite","Botiala","Gondal","Toniki","Salweyn","Miandi","Sarapion","Hannassa","Bulhar",
		"Essina","Famo","Mosylon","Opone","Nikon","Mundus"]
	},
		{
		"name": "The Olmec",
		"leaderName": "U Kix Chan",
		"adjective": ["Olmec"],
		"startBias": ["Jungle","Coast"],
		"preferredVictoryType": "Scientific",
		
		"startIntroPart1": "Oh mighty and righteous U Kix Chan, King of Palenque and son of the Lady White Quetzal, your people prostrate themselves in awe and reverence! A skilled and ingenious people, the Olmec emerged along the Coatzacoalcos river basin in what is today the southern Mexican Gulf Coast. Quick to exploit the natural wonders of their surroundings, they developed new technologies - boiling rubber from tree sap - and carved colossal monuments from the basalt boulders of the Tuxtlas Mountains. From this cradle, Mesoamerican civilization would flourish: as the Maya would rise in the Yucatan to the east and the Aztecs in the Valley of Mexico to the west, the true legacy of the Olmec would be the indelible mark left on these great empires to come.",
		"startIntroPart2": "Ancient King, history has not been kind to your land. Foreign crowns have crossed the sea to kill your children and ravage their civilizations. The people of Mesoamerica now pray to their ancestors for guidance. Will you return to restore the glory of your culture and legacy? Can you build a civilization that will stand the test of time?",
		
		"declaringWar": "War! The Feathered Serpent demands sacrificial blood!",
		"attacked": "Is it bravery or stupidity?",
		"defeated":  "That's the greatest sacrifice I can offer You!",
		"introduction":  "Were you send by the great Serpent?",
		
		"neutralHello": "Hello, friend.",
		"neutralLetsHearIt": ["Yes.","Let's discuss."],
		"neutralNo": ["No way.","Never!"],
		"neutralYes": ["Very good.","Of course, yes.","I accept."],
		"hateHello": "Go on!",
		"hateLetsHearIt": ["Speak!"],
		"hateNo": ["I can't accept!"],
		"hateYes": ["Let it be."],
		
		"afterPeace": "What such bloodhirsty beast might want?",
		"tradeRequest": "What do you think?",

		"outerColor": [	91, 176, 156],
		"innerColor": [ 40, 94, 68],
		"uniqueName": "Feathered Serpent",
		"uniqueText": "May buy National Wonders with [Faith].",
		"uniques": ["May buy [National Wonder] buildings with [Faith] for [2] times their normal Production cost"],
		"cities": ["La Venta","San Lorenzo","Tres Zapotes","Izapa","Tzapotl","Tonala","Texpa","Tlapocoya","Xoc","Coatztitlan","Izacoya"]
	},
			{
		"name": "Nok",
		"leaderName": "Olori",
		"adjective": ["Nok"],
		"startBias": ["Jungle","Iron"],
		"preferredVictoryType": "Cultural",
		
		"startIntroPart1": "Welcome, King Olori, leader of the Nok culture, architect of the cradle of North African civilization! For millennia, your people endured a hunter-gather existance, isolated from other peoples. It was not until the turn of the first millennium BC that your people discovered iron from the north, enabling them to craft their dominion of what is northern Nigeria today: pottery, architecture and artist expression thrived. But it was not to last, as overpopulation, coupled with rapid climate shifts, spelled the end of your culture. Your people persisted, however, forming the formidable Benin, Nri, Yoruba and Hausa kingdoms and ethnic groups lasting into the modern day.",
		"startIntroPart2": "Olori, your people feel their culture has been vandalised and forgotten, and seek a new chapter in west African history that will return to its artistic roots, forging a culture that will embrace new technology. Can you craft their legacy once again? Can you build a civilization that will stand the test of time?",
		
		"declaringWar": "You must be destroyed!",
		"attacked": "Oh, I see. I did not expect anything else from you.",
		"defeated":  "We might die, but our culture is eternal.",
		"introduction":  "Welcome to our lands. May there be peace among us!",
		
		"neutralHello": "Hello, friend.",
		"neutralLetsHearIt": ["Yes.","Let's discuss."],
		"neutralNo": ["No way.","Never!"],
		"neutralYes": ["Very good.","Of course, yes.","I accept."],
		"hateHello": "Go on!",
		"hateLetsHearIt": ["Speak!"],
		"hateNo": ["I can't accept!","You need to try harder."],
		"hateYes": ["Let it be.","This offer is too good to reject."],
		
		"afterPeace": "Oh?",
		"tradeRequest": "Do you like it?",

		"outerColor": [	189, 182, 125],
		"innerColor": [	82, 70, 55],
		"uniqueName": "African Treasures",
		"uniqueText": "All cities gain a free Smeltery. +1 [Science] from every Iron.",
		"uniques": ["Gain a free [Smeltery] [in all cities]","[+1 Science] from every [Iron]"],
		"cities": ["Nok","Jos","Ife","Samun","Kagara","Janjala","Kwoi","Jere","Dokku","Bokkos","Riyom","Ogbabu","Pangajere","Taruga","Kamrun","Vom","Chakwama","Dogo-Dogo","Jagwa"]
	},
	{
		"name": "Georgia",
		"leaderName": "Tamar",
		"adjective": [
			"Georgian"
		],
		"preferredVictoryType": "Domination",
		"declaringWar": "God fights with us. You stand alone.",
		"attacked": "Georgian hearts will not tremble before your multitudes.",
		"defeated": "Walls weren't enough to save Georgia from ruin. Neither was I.",
		"introduction": "I am Tamar of Georgia. Say what you will and be on your way.",
		"neutralHello": "I notice your sincerity.",
		"hateHello": "You are a detestable person.",
		"tradeRequest": "Georgian merchants bring many gifts.",
		"outerColor": [
			255,
			255,
			255
		],
		"innerColor": [
			254,
			124,
			19
		],
		"uniqueName": "Strength in Unity",
		"uniqueText": "+150% Production when constructing Walls in all cities, +2 Movement for all units during Golden Age, +10% Strength for all units during a Golden Age.",
		"uniques": [
			"[+150]% Production when constructing [Ancient Walls] buildings [in all cities]",
			"[+2] Movement <for [All] units> <during a Golden Age>",
			"[+10]% Strength <for [All] units> <during a Golden Age>"
		],
		"cities": [
			"Tbilisi",
			"Kaspi",
			"Rustavi",
			"Tskhumi",
			"Akhalkalaki",
			"Kutaisi",
			"Zugdidi",
			"Batumi",
			"Gori",
			"Mtskheta",
			"Poti",
			"Telavi",
			"Akhali Atoni",
			"Akhaltsikhe",
			"Bichvinta",
			"Borjomi",
			"Dedoplistsqaro",
			"Dmanisi",
			"Geguti",
			"Mutso",
			"Nicopsia",
			"Omalo",
			"Oni",
			"Tianeti",
			"Tmogvi",
			"Tsageri",
			"Amasya",
			"Tsalka",
			"Tskhinvali",
			"Urbnisi",
			"Zestafoni"
		]
	},
	{
		"name": "Gran Colombia",
		"leaderName": "Bolivar Simon",
		"adjective": [
			"Gran Colombian"
		],
		"preferredVictoryType": "Domination",
		"declaringWar": "Your tyranny, if unchecked, dooms the world to darkness, and for this reason I must declare war on you.",
		"attacked": "Recourse to war is regrettable, but necessary, when dealing with vipers like you.",
		"defeated": "Everything I have done, I did for the nation of Gran Colombia. I remain a patriot to the very end.",
		"introduction": "I, President Simon Bolivar, welcome you to Gran Colombia.",
		"neutralHello": "Excellent!",
		"hateHello": "Tyrant!.",
		"tradeRequest": "I send to you a delegation of my finest horsemen. Will you let them in?",
		"outerColor": [
			1,
			42,
			108
		],
		"innerColor": [
			245,
			217,
			0
		],
		"uniqueName": "Ejército Patriota",
		"uniques": [
			"[+3] Movement <for [non-air] units>"
		],
		"cities": [
			"Bogotá",
			"Caracas",
			"Quito",
			"Valencia De Carabobo",
			"Cali",
			"Medellín",
			"Maracaibo",
			"Cumaná",
			"Guayaquil",
			"Panamá",
			"Cartagena de Indias",
			"Popayán",
			"Cuenca",
			"Barinas",
			"Santa Marta",
			"Loja",
			"Angostura",
			"Pasto",
			"Nueva Barcelona",
			"Neiva",
			"Mérida",
			"Portoviejo",
			"Riobamba",
			"Ibarra",
			"Riohacha",
			"Quibdó",
			"Nueva Pamplona",
			"Santiago de Veraguas",
			"La Asunción",
			"Achaguas",
			"Honda",
			"Socorro",
			"Mompós",
			"Trujillo",
			"Santa Fe de Antioquia",
			"Pore",
			"Cúcuta",
			"Mariquita",
			"San Fernando de Apure",
			"Barquisimeto"
		]
	},
	{
		"name": "Mali",
		"leaderName": "Mansa Musa",
		"startBias": [
			"Desert"
		],
		"adjective": [
			"Malian"
		],
		"declaringWar": "Your transgressions are as deep as oceans. O God, grant that I may chastise this one!",
		"attacked": "Enough! My forbearance ends here! We must have war between us, instead of a false peace.",
		"defeated": "Wealth is fleeting; learning is vanity. All I have done, O God, I did in your name.",
		"introduction": "I am Sultan Musa, lord of Mali, andâ€”thanks be to Godâ€”a very, very rich man. I am pleased to meet you.",
		"neutralHello": "I am pleased.",
		"hateHello": "Serpent! Tempter! Wretch!",
		"tradeRequest": "Please accept these simple gifts of one hundred porters carrying sacks of gold dust.",
		"outerColor": [
			121,
			0,
			2
		],
		"innerColor": [
			234,
			225,
			158
		],
		"uniqueName": "Songs of the Jeli",
		"uniqueText": "Cities get +1 Food, +1 Faith for every adjacent desert, -1 Production and +4 Gold from every Mine, -30% Production when constructing Buildings and Military Units in all cities, -20% Gold and Faith cost of purchasing items after discovering currency",
		"uniques": [
			"[+1 Food, +1 Faith] [in all cities] <with [1] to [1] neighboring [Desert] tiles>",
			"[+2 Food, +2 Faith] [in all cities] <with [2] to [2] neighboring [Desert] tiles>",
			"[+3 Food, +3 Faith] [in all cities] <with [3] to [3] neighboring [Desert] tiles>",
			"[+4 Food, +4 Faith] [in all cities] <with [4] to [4] neighboring [Desert] tiles>",
			"[+5 Food, +5 Faith] [in all cities] <with [5] to [5] neighboring [Desert] tiles>",
			"[+6 Food, +6 Faith] [in all cities] <with [6] to [6] neighboring [Desert] tiles>",
			"[-1 Production, +4 Gold] from every [Mine]",
			"[-30]% Production when constructing [All] buildings [in all cities]",
			"[-30]% Production when constructing [All] units [in all cities]",
			"[Gold] cost of purchasing items in cities [-20]% <after discovering [Currency]>",
			"[Faith] cost of purchasing items in cities [-20]% <after discovering [Currency]>"
		],
		"cities": [
			"Niani",
			"Timbuktu",
			"Jenne",
			"Gao",
			"Kumbi Saleh",
			"Walata",
			"Tawdenni",
			"Tadmekka",
			"Awdaghust",
			"Kirina",
			"Segu",
			"Nioro",
			"Kangaba",
			"Kouroussa",
			"Niagassola",
			"Diara",
			"Kayes",
			"N'teret",
			"Dia",
			"Arawan",
			"Kiri",
			"Mopti",
			"Narena",
			"Dakadiala",
			"Kukya",
			"Siby",
			"Fadama",
			"Tabon",
			"Siguiri",
			"Kaniana"
		]
	},
	{
		"name": "The Maori",
		"leaderName": "Kupi",
		"startBias": [
			"Coast"
		],
		"adjective": [
			"MÄ?ori"
		],
		"declaringWar": "You choose death! Your people wail and moan! The pillars of your houses shake, all your lands are shaking!",
		"attacked": "Look at the big civ leader over there with the war declaration! Great job, mate. Really shows off how hard you are.",
		"defeated": "I have done my utmost, but your strength was greater. My heart, at least, will beat undefeated.",
		"introduction": "I am Kupe the navigator, and you approach the place of the Maori. Will you tell me about yourself?",
		"neutralHello": "Yeah you're alright.",
		"hateHello": "Yeah nah.",
		"tradeRequest": "Here are gifts of pounamu, korowai cloaks and huhu grubs.",
		"outerColor": [
			205,
			0,
			1
		],
		"innerColor": [
			125,
			235,
			228
		],
		"uniqueName": "Mana",
		"uniqueText": "Starts with Sailing and Shipbuilding unlocked and the ability to enter Ocean tiles. Embarked units can defend themselves. +1 Production for unimproved Forest and Jungle tiles, enhanced to +2 with Mercantilism, +1 Food from Fishing Boats. Great Artists cannot be earned.",
		"uniques": [
			"Starts with [Sailing]",
			"Enables embarkation for land units <starting from the [Ancient era]>",
			"Enables [All] units to enter ocean tiles <starting from the [Ancient era]>",
			"[+2] Movement <for [Embarked] units>",
			"[+1] Sight <for [Embarked] units>",
			"Defense bonus when embarked <for [All] units>",
			"[Great Artist] is earned [-100]% faster",
			"[+1 Food] from every [Fishing Boats]",
			"[+1 Production] from every [Forest] <in tiles without [Lumber mill]> <in tiles without [Camp]> <in tiles without [Plantation]>",
			"[+1 Production] from every [Forest] <in tiles without [Lumber mill]> <in tiles without [Camp]> <in tiles without [Plantation]> <after adopting [Mercantilism]>",
			"[+1 Production] from every [Jungle] <in tiles without [Lumber mill]> <in tiles without [Camp]> <in tiles without [Plantation]>",
			"[+1 Production] from every [Jungle] <in tiles without [Lumber mill]> <in tiles without [Camp]> <in tiles without [Plantation]> <after adopting [Mercantilism]>",
		],
		"cities": [
			"Te Hokianga-nui-a-kupe",
			"Ngaruawahia",
			"Opango",
			"Whakarewarewa",
			"Kaiapoi",
			"Whanganui",
			"Kawhia",
			"Taumutu",
			"Kapiti",
			"Te Pokohiwi",
			"Otatara pa",
			"Motupohue",
			"Ruatoria",
			"Maungakiekie pa",
			"Taupiri",
			"Whaingaroa",
			"Pukemaire",
			"Pari-ru",
			"Taumatawhana pa",
			"Whanganui-a-Tara",
			"Waimapihi pa",
			"Kororipo pa",
			"Motakiora"
		]
	},
	{
		"name": "The Mapuche",
		"leaderName": "Lautaro",
		"adjective": [
			"Mapuche"
		],
		"startBias": [
			"Hill"
		],
		"preferredVictoryType": "Domination",
		"declaringWar": "It comes to war. Mapuche shall use your own weapons against you!",
		"attacked": "I knew you could not be trusted! We have long prepared for this war. Have you?",
		"defeated": "We resisted to the last, but it was too late â€¦ too late.",
		"introduction": "I am Lautaro, the Swift Hawk. Mapuche honor me with respect. Will I see the same from you?",
		"neutralHello": "You honor Mapuche with this.",
		"hateHello": "You offend me.",
		"tradeRequest": "Mapuche send gifts. Please accept these.",
		"outerColor": [
			0,
			79,
			205
		],
		"innerColor": [
			117,
			163,
			243
		],
		"uniqueName": "Toqui",
		"uniques": [
			"[50]% XP gained from combat <for [Military] units>",
			"[+10]% Strength <for [All] units> <during a Golden Age>"
		],
		"cities": [
			"Ngulu Mapu",
			"Puel Mapu",
			"Pikun Mapu",
			"Nag Mapu",
			"Willi Mapu",
			"Pewen Mapu",
			"Wente Mapu",
			"Huilli Mapu",
			"Lafken Mapu",
			"Ina Pire Mapu",
			"Mamull Mapu",
			"Rangkul Mapu",
			"Chadi Mapu",
			"Pehuen Mapu",
			"Puel Willi Mapu",
			"Bafkeh Mapu",
			"Peni Mapu",
			"Boroa Mapu",
			"Lelfun Mapu",
			"Kallfu Mapu",
			"Chol Chol Mapu",
			"Makewe Mapu",
			"Forowe Mapu",
			"Warria Mapu",
			"Tehuel Mapu",
			"Kunko Mapu",
			"Molu Mapu",
			"Rani Mapu",
			"Xuf Xuf Mapu",
			"Fudi Mapu"
		]
	},
	{
		"name": "The Cree",
		"leaderName": "Poundmaker",
		"adjective": [
			"Cree"
		],
		"declaringWar": "I do not care to inflict the terrors of war upon youâ€”but justice requires it.",
		"attacked": "You could have found another way. Now, your regrets will be measured in blood.",
		"defeated": "Had I wanted war, I would not be here now. You did not catch me. I gave myself up.",
		"introduction": "I am Poundmaker, and I represent the Cree. May there always be peace between us.",
		"neutralHello": "Good, good.",
		"hateHello": "Your word is worthless.",
		"tradeRequest": "My people send you gifts. With these you will last through winter.",
		"outerColor": [
			1,
			42,
			108
		],
		"innerColor": [
			70,
			175,
			10
		],
		"uniqueName": "Nihithaw",
		"uniques": [
			"Free [Worker] appears <upon discovering [Pottery] technology>",
			"[+2 Gold] from each Trade Route",
			"[-50]% Gold cost of acquiring tiles [in all cities]"
		],
		"cities": [
			"Mikisiw-Wacîhk",
			"Pihtokahanapiwiyin",
			"Mistahi-Sipihk",
			"Paskwaw-Askhik",
			"Piyesiw-Awasis",
			"Mistawasis",
			"Makwa-Sakahikan",
			"Ka-Peyakwaskonam",
			"Ahtahkakoop",
			"Wihkasko-Kiseyin",
			"Chemawawin",
			"Ka-kiwistahaw",
			"Ka-ohpawakastahk",
			"Kawacatoose",
			"Kawawachikamach",
			"Kinosew-Sakahikan",
			"Maskotew",
			"Missanabie",
			"Moosomin",
			"Natashquan",
			"Nekaneet",
			"Ochapowace",
			"Okanese",
			"Papewe",
			"Peepeekisis",
			"Posakanacihk",
			"Tataskweyak",
			"Wapi-maskwa",
			"Waskahikanihk",
			"Whapmagoostui"
		]
	},
	{
		"name": "Scythia",
		"leaderName": "Tomyris",
		"adjective": [
			"Sycthian"
		],
		"startBias": [
			"Horses",
			"Grassland",
			"Plains"
		],
		"preferredVictoryType": "Domination",
		"declaringWar": "The Empress calls for your head. You will be drowned in your own blood!",
		"attacked": "You have betrayed the trust of Tomyris and now you will pay!",
		"defeated": "The Empress falls, but I will be remembered. Will you?",
		"introduction": "Let it be known between us: I will repay treachery with blood! But, if you are a true friend, we will have peace.",
		"neutralHello": "Thank you, friend.",
		"hateHello": "No one will believe your hollow lies.",
		"tradeRequest": "I have sent you a trade delegation bearing a decorated gorytos as a gift for you. You do have a bow, yes?",
		"outerColor": [
			254,
			178,
			60
		],
		"innerColor": [
			121,
			0,
			2
		],
		"uniqueName": "People of the Steppe",
		"uniques": [
			"[+100]% Production when constructing [Mounted] units [in all cities]"
		],
		"cities": [
			"Pokrovka",
			"Issyk",
			"Kul Oba",
			"Gelonus",
			"Pazyryk",
			"Chertomlyk",
			"Neapolis",
			"Kostromskaya",
			"Myriv",
			"Solokha",
			"Malkop",
			"Kamianka-Dniprovska",
			"Tolstaya",
			"Seven Brothers",
			"Olbia",
			"Kelermes",
			"Solocha",
			"Ulski",
			"Arzhan",
			"Elizavetovskaya",
			"Melgunov",
			"Panticapaeum",
			"Tsarskaya",
			"Ogüz",
			"Tanais",
			"Alexandropol",
			"Kurdzhips",
			"Tsymbalka",
			"Theodosia",
			"Kozei"
		]
	},
[
   {
		"name": "Tradition",
		"era": "Ancient era",
		"uniques": ["[+3 Culture] [in capital]", "[-25]% Culture cost of natural border growth [in all cities]","Unlocks building the Hanging Gardens"],
		"policies": [
			{
				"name": "Aristocracy",
				"uniques": ["[+15]% Production when constructing [All] wonders [in all cities]", "[+1 Happiness] per [10] population [in all cities]"],
				"row": 1,
				"column": 2
			},
			{
				"name": "Oligarchy",
				"uniques": ["Units in cities cost no Maintenance", "[+50]% Strength for cities <with a garrison> <when attacking>"],
				"row": 1,
				"column": 4
			},
            {
				"name": "Harmony",
				"requires": ["Aristocracy"],
				"uniques": [
					"[+1 Happiness, +1 Food, +1 Faith, +1 Culture, +3 Production] <in cities with at least [7] [Population]>",
					"[-10]% Unhappiness from [Population] [in all cities]"
				],
				"row": 2,
				"column": 2
			},
						{
				"name": "Legalism",
				"uniques":["Provides the cheapest [Culture] building in your first [4] cities for free"],
				"requires": ["Oligarchy"],
				"row": 2,
				"column": 4
			},
			{
				"name": "Landed Elite",
				"uniques": ["[+10]% growth [in capital]", "[+2 Food] [in capital]"],
				"requires": ["Legalism"],
				"row": 3,
				"column": 3
			},
			{
				"name": "Monarchy",
				"uniques": ["[+1 Gold, +1 Happiness] per [2] population [in capital]"],
				"requires": ["Legalism"],
				"row": 3,
				"column": 5
			},
			{
				"name": "Tradition Complete",
				"uniques": ["[+15]% growth [in all cities]","Provides a [Aqueduct] in your first [8] cities for free","May buy [Great Engineer] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"]
			}
		]
	},
	{
		"name": "Liberty",
		"era": "Classical era",
		"uniques": ["[+1 Culture] [in all cities]", "Unlocks building the Pyramids"],
		"policies": [
			{
				"name": "Republic",
				"uniques": ["[+1 Production] [in all cities]", "[+5]% Production when constructing [All] buildings [in all cities]"],
				"row": 1,
				"column": 1
			},
			{
				"name": "Citizenship",
				"uniques": ["[-25]% construction time for [All] improvements", "Free [Worker] appears"],
				"row": 1,
				"column": 4
			},
			{
				"name": "Collective Rule",
				"uniques": ["[+50]% Production when constructing [Settler] units [in capital]", "Free [Settler] appears"],
				"requires": ["Republic"],
				"row": 2,
				"column": 1
			},
			{
				"name": "Representation",
				"uniques": ["Each city founded increases culture cost of policies [33]% less than normal", "Empire enters golden age"],
				"requires": ["Citizenship"],
				"row": 2,
				"column": 3
			},
			{
				"name": "Meritocracy",
				"uniques": ["[+1 Happiness] [in all cities connected to capital]", "[-5]% Unhappiness from [Population] [in all non-occupied cities]"],
				"requires": ["Citizenship"],
				"row": 2,
				"column": 5
			},
            {
                "name": "Nationalism",
                "requires": ["Representation"],
                "uniques": [
                    "[+10]% Strength <for [All] units> <when fighting in [Friendly Land] tiles>"
                ],
                "row": 3,
                "column": 3
            },
			{
				"name": "Liberty Complete",
				"uniques": ["Free Great Person"]
			}
		]
	},
	{
		"name": "Honor",
		"era": "Ancient era",
		"uniques": ["[+33]% Strength <vs [Barbarian] units>", "Earn [100]% of killed [Barbarian] unit's [Strength] as [Culture]",
			"Notified of new Barbarian encampments", "Unlocks building the Statue of Zeus"],
		"policies": [
			{
				"name": "Warrior Code",
				"uniques":["[+15]% Production when constructing [Melee] units [in all cities]", "Free [Great General] appears","[Great General] is earned [50]% faster"],
				"row": 1,
				"column": 2
			},
			{
				"name": "Discipline",
				"uniques":["[+15]% Strength <for [Melee] units> <when adjacent to a [Military] unit>"],
				"row": 1,
				"column": 4
			},
			{
				"name": "Military Tradition",
				"uniques":["[+50]% XP gained from combat <for [Military] units>"],
				"requires": ["Warrior Code"],
				"row": 2,
				"column": 2
			},
			{
				"name": "Military Caste",
				"uniques": ["[+1 Happiness, +2 Culture] [in all cities with a garrison]"],
				"requires": ["Discipline"],
				"row": 2,
				"column": 4
			},
			{
				"name": "Mercenary Army",
				"requires": ["Military Tradition"],
				"uniques": ["May buy [Landsknecht] units with [Gold] for [5] times their normal Production cost"],
				"row": 3,
				"column": 2
			},
			{
				"name": "Professional Army",
				"uniques": ["[-33]% Gold cost of upgrading <for [Military] units>","[+50]% Production when constructing [Barracks] buildings [in all cities]"
				,"[+50]% Production when constructing [Armory] buildings [in all cities]","[+50]% Production when constructing [Military Academy] buildings [in all cities]"
				],
				"requires": ["Military Caste"],
				"row": 3,
				"column": 4
			},
			{
				"name": "Honor Complete",
				"uniques": ["Earn [10]% of killed [Military] unit's [Cost] as [Gold]","May buy [Great General] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"]
			}
		]
	},
    {
		"name": "Piety",
		"era": "Ancient era",
		"uniques": ["Only available <before adopting [Rationalism]>","[+100]% Production when constructing [Shrine] buildings [in all cities]", "[+100]% Production when constructing [Temple] buildings [in all cities]", "Unlocks building the Great Mosque of Djenne"],
		"policies": [
			{
				"name": "Organized Religion",
				"uniques": ["[+1 Faith] from every [Shrine]","[+1 Faith] from every [Temple]"],
				"row": 1,
				"column": 2
			},
			{
				"name": "Mandate Of Heaven",
				"uniques": ["[Faith] cost of purchasing items in cities [-20]%"],
				"row": 1,
				"column": 5
			},
			{
				"name": "Theocracy",
				"uniques": ["[+25]% [Gold] from every [Temple]","[+3 Gold] from every [Holy site]"],
				"requires": ["Organized Religion"],
				"row": 2,
				"column": 1
			},
			{
				"name": "Reformation",
				"uniques": ["[+33]% [Culture] [in all cities with a world wonder]", "Empire enters golden age"],
				"requires": ["Organized Religion"],
				"row": 2,
				"column": 3
			},
			{
                		"name": "Planned Economy",
				"requires": ["Theocracy"],
                		"uniques": [
                    			"Free [Inquisitor] appears","[-15]% [Science] from every [Shrine]",
					"[+15]% Strength <for [All] units> <when fighting in [Desert] tiles>"
                			],
                		"row": 3,
                		"column": 2
            		},
			{
				"name": "Free Religion",
				"uniques": ["[-10]% Culture cost of adopting new Policies"],
				"requires": ["Mandate Of Heaven", "Reformation"],
				"row": 3,
				"column": 4
			},
			{
				"name": "Piety Complete",
				"uniques": ["Free [Great Prophet] appears", "[+3 Culture] from every [Holy site]"]
			}
		]
	},
    {
		"name": "Patronage",
		"era": "Classical era",
		"uniques": ["[-25]% City-State Influence degradation", "Unlocks building the Forbidden Palace"],
		"policies": [
			{
				"name": "Philantropy",
				"uniques":["Gifts of Gold to City-States generate [25]% more Influence"],
				"row": 1,
				"column": 2
			},
			{
				"name": "Consulates",
				"uniques":["Resting point for Influence with City-States is increased by [20]"],
				"row": 1,
				"column": 4
			},
			{
				"name": "Scholasticism",
				"uniques":["Allied City-States provide [Science] equal to [25]% of what they produce for themselves"],
				"requires": ["Philantropy"],
				"row": 2,
				"column": 2
			},
			{
				"name": "Cultural Diplomacy",
				"uniques": ["[+100]% resources gifted by City-States",
					"[+50]% Happiness from luxury resources gifted by City-States"],
				"requires": ["Scholasticism"],
				"row": 3,
				"column": 1
			},
			{
				"name": "Educated Elite",
				"requires": ["Scholasticism","Consulates"],
				"uniques": ["Allied City-States will occasionally gift Great People"],
				"row": 3,
				"column": 3
			},
			{
                		"name": "United Front",
				"requires": ["Consulates"],
                		"uniques": [
                    		"Militaristic City-States grant units [2] times as fast when you are at war with a common nation","[-100]% weight to this choice for AI decisions"
                			],
                			"row": 3,
                			"column": 5
            		},
			{
				"name": "Patronage Complete",
				"uniques": ["Influence of all other civilizations with all city-states degrades [33]% faster", 
					"Triggers the following global alert: [Our influence with City-States has started dropping faster!]"]
			} 
		]
	},
	{
		"name": "Commerce",
		"uniques": ["Only available <after adopting [Patronage]>","[+25]% [Gold] [in capital]", "Unlocks building Big Ben"],
		"era": "Medieval era",
		"policies": [
			{
				"name": "Wagon Trains",
				"uniques": ["[-50]% maintenance on road & railroads", "[+2 Gold] from each Trade Route"
				],
				"row": 1,
				"column": 1
			},
			{
				"name": "Capitalism",
				"uniques": ["[+1 Happiness] from every [Mint]","[+1 Happiness] from every [Bank]","[+1 Happiness] from every [Stock Exchange]"],
				"row": 1,
				"column": 3
			},
			{
            			"name": "Trade Unions",
            			"uniques": [
                			"[+1 Gold] from every [Trading post]","[+2 Culture] from each Trade Route","[+1 Food] from every [Trading post]"
            				],
            			"row": 1,
            			"column": 5
        		},
			{
				"name": "Entrapreneurship",
				"uniques": [ "[+100]% Gold from Great Merchant trade missions","[Great Merchant] is earned [25]% faster"],
				"requires": ["Capitalism"],
				"row": 2,
				"column": 1
			},
			{
				"name": "Mercantilism",
				"requires": ["Capitalism"],
				"uniques": ["[Gold] cost of purchasing items in cities [-25]%", "[+1 Science] from every [Mint]", "[+1 Science] from every [Market]",
					"[+1 Science] from every [Bank]", "[+1 Science] from every [Stock Exchange]"],
				"row": 2,
				"column": 3
			},
			
			{
				"name": "Protectionism",
				"uniques": ["[+2] Happiness from each type of luxury resource"],
				"requires": ["Trade Unions"],
				"row": 2,
				"column": 5
			},
			{
				"name": "Commerce Complete",
				"uniques": ["[+1 Gold] from every [Customs house]",
					"May buy [Great Merchant] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
				]
			}
		]
	},
	{
		"name": "Exploration",
		"uniques": ["[+1] Movement <for [{Military} {Water}] units>",
			"[+1] Sight <for [{Military} {Water}] units>","Unlocks building the Louvre"],
		"era": "Medieval era",
		"policies": [
			{
				"name": "Maritime Infrastructure",
				"uniques": ["[+3 Production] [in all coastal cities]"],
				"row": 1,
				"column": 2
			},
						{
				"name": "Naval Tradition",
				"uniques": ["[+1 Happiness] from every [Lighthouse]","[+1 Happiness] from every [Harbor]","[+1 Happiness] from every [Seaport]"],
				"row": 1,
				"column": 4
			},
			{
				"name": "Merchant Navy",
				"uniques": ["[+1 Gold] from every [Lighthouse]","[+1 Gold] from every [Harbor]","[+1 Gold] from every [Seaport]","[+4 Production, +4 Culture] from every [East India Company]"],
				"requires": ["Maritime Infrastructure","Naval Tradition"],
				"row": 2,
				"column": 3
			},
			{
				"name": "Navigation School",
				"uniques": ["[+2 Science] [in all coastal cities]"],
				"requires": ["Naval Tradition"],
				"row": 2,
				"column": 5
			},
			{
				"name": "Fortune Wheel",
				"uniques": ["[+2 Production, +2 Faith] from each Trade Route","[+22]% [Culture] from every [Harbor]"],
				"row": 3,
				"column": 1
			},
			{
				"name": "Treasure Fleets",
				"uniques": ["[+4 Gold] from each Trade Route"],
				"requires": ["Navigation School"],
				"row": 3,
				"column": 3
			},
			{
				"name": "Exploration Complete",
				"uniques": ["[+3 Culture] [in all coastal cities]"]
			}
		]
	},
	{
		"name": "Aesthetics",
		"era": "Classical era",
		"uniques": ["[Great Artist] is earned [33]% faster","Unlocks building the Uffizi"],
		"policies": [
			{
				"name": "Cultural Centers",
				"uniques": ["[+100]% Production when constructing [Monument] buildings [in all cities]",
					"[+100]% Production when constructing [Amphitheater] buildings [in all cities]",
					"[+100]% Production when constructing [Opera House] buildings [in all cities]",
					"[+100]% Production when constructing [Museum] buildings [in all cities]",
					"[+100]% Production when constructing [Broadcast Tower] buildings [in all cities]"],
				"row": 1,
				"column": 2
			},
			{
				"name": "Fine Arts",
				"uniques": ["[50]% of excess happiness converted to [Culture]"],
				"row": 1,
				"column": 4
			},
			{
                		"name": "Populism",
				"requires": ["Cultural Centers"],
                		"uniques": ["[+25]% Great Person generation [in all cities]","[+100]% weight to this choice for AI decisions"],
                		"row": 2,
                		"column": 1
            		},
						{
				"name": "Flourishing of the Arts",
				"uniques": ["[+33]% [Culture] [in all cities with a world wonder]","Empire enters golden age"],
				"requires": ["Cultural Centers", "Fine Arts"],
				"row": 2,
				"column": 3
			},
						{
				"name": "Artistic Genius",
				"uniques": ["Free [Great Artist] appears"],
				"requires": ["Fine Arts"],
				"row": 2,
				"column": 5
			},
			{
				"name": "Cultural Exchange",
				"uniques": ["[+20]% [Culture] from every [Museum]","[+20]% [Culture] from every [Opera House]","[+20]% [Culture] from every [Broadcast Tower]"],
				"requires": ["Flourishing of the Arts"],
				"row": 3,
				"column": 3
			},
			{
				"name": "Aesthetics Complete",
				"uniques": ["[+4 Culture] from every [Landmark]","Free Social Policy","May buy [Great Artist] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"]
			}
		]
	},
	 {
		"name": "Rationalism",
		"era": "Renaissance era",
		"uniques": ["Only available <before adopting [Piety]>","Only available <after adopting [Liberty]>","[+10]% [Science] <while the empire is happy>", "Unlocks building the Porcelain Tower"],
		"policies": [
			{
				"name": "Secularism",
				"uniques": ["[+2 Science] from every specialist [in all cities]"],
				"row": 1,
				"column": 1
			},
			{
				"name": "Humanism",
				"uniques": ["[Great Scientist] is earned [25]% faster"],
				"row": 1,
				"column": 3
			},
				{
				"name": "Sovereignty",
				"uniques": ["[+1 Gold] from all [Science] buildings"],
				"row": 1,
				"column": 5
			},
			{
				"name": "Scientific Revolution",
				"uniques": ["Science gained from research agreements [+50]%"],
				"requires": ["Secularism","Humanism"],
				"row": 2,
				"column": 1
			},
			{
				"name": "Free Thought",
				"requires": ["Humanism","Sovereignty"],
				"uniques": ["[+1 Science] from every [Trading post]", "[+17]% [Science] from every [University]"],
				"row": 2,
				"column": 5
			},
			{
				"name": "Christ",
				"uniques": ["[+2 Production, +2 Food, +2 Gold, +2 Faith, +2 Culture, +2 Science, +2 Happiness] per [5] population [in all cities]",
					"[Faith] cost of purchasing [Missionary] units [-20]%","[2] free [Missionary] units appear"],
				"requires": ["Humanism"],
				"row": 3,
				"column": 3
			},
			{
				"name": "Rationalism Complete",
				"uniques": ["[1] Free Technologies","[-10]% unhappiness from the number of cities",
					"May buy [Great Scientist] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
				]
			}
		]
	},
	{
		"name": "Freedom",
		"era": "Modern era",
		"uniques": ["[+25]% Great Person generation [in all cities]", "Unlocks building the Statue of Liberty", "Only available <before adopting [Autocracy]>", 
			"Only available <before adopting [Order]>","Only available <after adopting [Rationalism]>"],
		"policies": [
			{
				"name": "Civil Society",
				"uniques": ["[-50]% Food consumption by specialists [in all cities]"],
				"row": 1,
				"column": 1
			},
			{
				"name": "Promised Land",
				"uniques": [
					"[+15]% Strength <for [All] units> <when fighting in [Plains] tiles>",
					"[+15]% Strength <for [All] units> <when fighting in [Jungle] tiles>",
					"[+15]% Strength <for [All] units> <when fighting in [Hill] tiles>",
					"[+15]% Strength <for [All] units> <when fighting in [Forest] tiles>",
					"[+15]% Strength <for [All] units> <when fighting in [Grassland] tiles>"
				],
				"row": 1,
				"column": 3
			},
			
						{
				"name": "Universal Healthcare",
				"uniques": ["[+1 Happiness] from every [National Wonder]"],
				"row": 1,
				"column": 5
			},
			{
				"name": "Volunteer Army",
				"uniques": ["[6] units cost no maintenance", "[6] free [Foreign Legion] units appear"],
				"requires": ["Civil Society","Promised Land","Universal Healthcare"],
				"row": 2,
				"column": 2
			},
			{
				"name": "Urbanization",
				"uniques": ["[+1 Happiness] from every [Water Mill]","[+1 Happiness] from every [Hospital]","[+1 Happiness] from every [Medical Lab]"],
				"requires": ["Universal Healthcare","Promised Land"],
				"row": 2,
				"column": 4
			},
			{
                		"name": "Democracy",
                		"uniques": [
                    			"[-50]% Unhappiness from [Specialists] [in all cities]"
                				],
                		"requires": ["Volunteer Army","Urbanization"],
                		"row": 3,
                		"column": 3
            		},
			{
				"name": "Freedom Complete",
				"uniques": ["[+100]% Yield from every [Great Improvement]", "[+50]% Golden Age length","[-20]% unhappiness from the number of cities"]
			}
		]
	},
	{
		"name": "Autocracy",
		"era": "Industrial era",
		"uniques": ["[Gold] cost of purchasing [All] units [-33]%", "Only available <before adopting [Order]>", "Only available <before adopting [Freedom]>", "Unlocks building the Prora"],
		"policies": [
			{
				"name": "Nazism",
				"uniques": ["[+100]% Production when constructing [Constabulary] buildings [in all cities]",
					"[+100]% Production when constructing [Police Station] buildings [in all cities]",
					"[-3 Food, -3 Science] [in annexed cities]","[-3 Food, -3 Science] [in puppeted cities]"],
				"row": 1,
				"column": 1
			},
			{
				"name": "Elite Forces",
				"uniques": ["[+25]% Strength <for [Wounded] units>"],
				"row": 1,
				"column": 3
			},
			{
				"name": "Fortified Borders",
				"uniques": ["[+1 Happiness] from every [Castle]","[+1 Happiness] from every [Arsenal]","[+1 Happiness] from every [Military Base]"],
				"row": 1,
				"column": 5
			},
			{
				"name": "Militarism",
				"uniques": ["[+2 Happiness] from every [Barracks]","[+2 Happiness] from every [Armory]","[+2 Happiness] from every [Military Academy]"]
				"requires": ["Nazism","Elite Forces"],
				"row": 2,
				"column": 2
			},
			{
				"name": "Police State",
				"uniques": ["[+3 Happiness] from every [Courthouse]", "[+100]% Production when constructing [Courthouse] buildings [in all cities]"],
				"requires": ["Elite Forces","Fortified Borders"],
				"row": 2,
				"column": 4
			},
			{
				"name": "Scorched Earth",
				"requires": ["Nazism","Militarism"],
				"uniques": [
					"[+15]% Strength <vs cities>",
					"Cities are razed [2] times as fast",
					"No movement cost to pillage <for [Melee] units>",
					"[+2] Movement <for [Great General] units>"
				],
				"row": 3,
				"column": 1
			},
			{
                		"name": "Fascism",
                		"uniques": [
                   		"Quantity of strategic resources produced by the empire +[100]%",
                    		"[+2] Movement <for [Great General] units>"
                		],
                		"requires": ["Militarism","Elite Forces","Police State"],
                		"row": 3,
                		"column": 3
            		},
			{
				"name": "Total War",
				"uniques": ["[+25]% Production when constructing [Military] units [in all cities]", "New [Military] units start with [15] Experience [in all cities]"],
				"requires": ["Fortified Borders","Police State"],
				"row": 3,
				"column": 5
			},
			
			{
				"name": "Autocracy Complete",
				"uniques": ["[+25]% Strength <when attacking> <for [Military] units> <for [50] turns>","[+20]% unhappiness from the number of cities"]
			}
		]
	},
	{
    "name": "Order",
    "era": "Industrial era",
	"uniques": ["[+2 Happiness] from every [Monument]", "Unlocks building the Kremlin", "Only available <before adopting [Autocracy]>", "Only available <before adopting [Freedom]>"],
    "policies": [
        {
            "name": "Young Pioneers",
			"uniques": ["[+1 Happiness] from every [Workshop]","[+1 Happiness] from every [Factory]","[+1 Happiness] from every [Nuclear Plant]","[+1 Happiness] from every [Hydro Plant]","[+1 Happiness] from every [Solar Plant]"],
            "row": 1,
            "column": 2
        },
		{
			"name": "Patriotic War",
			"uniques": ["[+15]% Strength <for [All] units> <when fighting in [Friendly Land] tiles>"],
			"row": 1,
			"column": 4
		},
				{
			"name": "Workers' Faculties",
			"uniques": ["[+25]% [Science] from every [Factory]", "[+100]% Production when constructing [Factory] buildings [in all cities]"],
			"requires": ["Young Pioneers"],
			"row": 2,
			"column": 1
		},
        {
            "name": "Academy of Sciences",
            "requires": ["Patriotic War"],
			"uniques": ["[+1 Happiness] from every [Observatory]","[+1 Happiness] from every [Public School]","[+1 Happiness] from every [Research Lab]"],
            "row": 2,
            "column": 5
        },
	{
                "name": "Socialism",
                "requires": ["Patriotic War", "Young Pioneers"],
                "uniques": [
                    "[-15]% maintenance cost for buildings [in all cities]"
                ],
                "row": 2,
                "column": 3
            },
            {
                "name": "Communism",
                "requires": ["Socialism"],
                "uniques": [
                    "[-15]% [Science] from every [Temple]","[+50]% Unhappiness from [Population] [in all cities]"
                ],
                "row": 3,
                "column": 2
            },
	    
        {
            "name": "Five-Year Plan",
            "requires": ["Workers' Faculties"],
			"uniques": ["[+2 Production] [in all cities]", "[+1 Production] from every [Mine]", "[+1 Production] from every [Quarry]"],
            "row": 3,
            "column": 4
        },
        {
            "name": "Order Complete",
			"uniques": ["[+1 Food, +1 Production, +1 Science, +1 Gold, +1 Culture] [in all cities]","[+10]% unhappiness from the number of cities"]
        }
    ]
}
		]
