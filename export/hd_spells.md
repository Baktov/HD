---
classes: Barde|Clerc|Druide|Ensorceleur|Magicien|Ombrelame|Paladin|Rôdeur|Sorcier
levels: Sorts mineurs|Niveau 1|Niveau 2|Niveau 3|Niveau 4|Niveau 5|Niveau 6|Niveau 7|Niveau 8|Niveau 9
schools: Abjuration|Divination|Enchantement|Évocation|Illusion|Invocation|Nécromancie|Transmutation
rituals: Rituel|-
casting_times: 1 action|1 action bonus|1 réaction|1 minute|10 minutes|1 heure|8 heures|12 heures|24 heures
ranges: personnel|contact|vision|selon l'arme utilisée|spéciale|1,5 mètre|3 mètres|4,50 mètres|9 mètres|12 mètres|18 mètres|27 mètres|30 mètres|36 mètres|45 mètres|90 mètres|150 mètres|450 mètres|1 kilomètre|1,5 kilomètre|7,5 kilomètres|750 kilomètres|illimitée
verbal_components: V|-
somatic_components: S|-
material_components: M|-
concentrations: concentration|-
durations: instantané|1 round|1 minute|10 minutes|1 heure|2 heures|8 heures|24 heures|1 jour|7 jours|10 jours|30 jours|dissipation|déclenchement|spéciale
sources: SRD|MDR
family: SpellHD
sub_items:
- family: SpellHD
  level: 2
  type: Transmutation
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (une pincée de limaille de fer)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de limaille de fer)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#agrandirrétrécir
  title: Agrandir/rétrécir
  alias: Enlarge/Reduce
  source: (MDR p320)(SRD)
- family: SpellHD
  level: 2
  type: Abjuration
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (une minuscule bandelette de tissu blanc)
  verbal_component: V
  somatic_component: S
  material_component: M (une minuscule bandelette de tissu blanc)
  duration: 8 heures
  classes: '[Clerc](hd_cleric.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#aide
  title: Aide
  alias: Aid
  source: (MDR p320)(SRD)
- family: SpellHD
  level: 1
  type: Abjuration
  ritual: rituel
  casting_time: 1 minute
  range: 9 mètres
  components: V, S, M (une minuscule clochette et un filament en argent)
  verbal_component: V
  somatic_component: S
  material_component: M (une minuscule clochette et un filament en argent)
  duration: 8 heures
  classes: '[Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#alarme
  title: Alarme
  alias: Alarm
  source: (MDR p320)(SRD)
- family: SpellHD
  level: 6
  type: Invocation
  casting_time: 10 minutes
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#allié-planaire
  title: Allié planaire
  alias: Planar Ally
  source: (MDR p320)(SRD)
- family: SpellHD
  level: 2
  type: Transmutation
  casting_time: 1 action
  range: contact
  components: V, S, M (des poils ou des plumes venant d'un animal)
  verbal_component: V
  somatic_component: S
  material_component: M (des poils ou des plumes venant d'un animal)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md)'
  id: spells_hd.md#amélioration-de-caractéristique
  title: Amélioration de caractéristique
  alias: Enhance Ability
  source: (MDR p321)(SRD)
- family: SpellHD
  level: 1
  type: Enchantement
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (un peu de nourriture)
  verbal_component: V
  somatic_component: S
  material_component: M (un peu de nourriture)
  duration: 24 heures
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#amitié-avec-les-animaux
  title: Amitié avec les animaux
  alias: Animal Friendship
  source: (MDR p321)(SRD)
- family: SpellHD
  level: 3
  type: Nécromancie
  casting_time: 1 minute
  range: 3 mètres
  components: V, S, M (une goutte de sang, un lambeau de chair et une pincée de poudre d'os)
  verbal_component: V
  somatic_component: S
  material_component: M (une goutte de sang, un lambeau de chair et une pincée de poudre d'os)
  duration: instantanée
  classes: '[Clerc](hd_cleric.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#animation-des-morts
  title: Animation des morts
  alias: Animate Dead
  source: (MDR p321)(SRD)
- family: SpellHD
  level: 5
  type: Transmutation
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#animation-des-objets
  title: Animation des objets
  alias: Animate Objects
  source: (MDR p322)(SRD)
- family: SpellHD
  level: 2
  type: Enchantement
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md)'
  id: spells_hd.md#apaisement-des-émotions
  title: Apaisement des émotions
  alias: Calm Emotions
  source: (MDR p322)(SRD)
- family: SpellHD
  level: 5
  type: Illusion
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 8 heures
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#apparence-trompeuse
  title: Apparence trompeuse
  alias: Seeming
  source: (MDR p323)(SRD)
- family: SpellHD
  level: 1
  type: Invocation
  ritual: rituel
  casting_time: 1 heure
  range: 3 mètres
  components: V, S, M (10 po de charbon, d'encens et d'herbe à faire brûler dans un brasero en laiton)
  verbal_component: V
  somatic_component: S
  material_component: M (10 po de charbon, d'encens et d'herbe à faire brûler dans un brasero en laiton)
  duration: instantanée
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#appel-de-familier
  title: Appel de familier
  alias: Find Familiar
  source: (MDR p323)(SRD)
- family: SpellHD
  level: 3
  type: Invocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#appel-de-la-foudre
  title: Appel de la foudre
  alias: Call Lightning
  source: (MDR p324)(SRD)
- family: SpellHD
  level: 5
  type: Enchantement
  casting_time: 1 action
  range: contact
  components: V, S, M (un arc)
  verbal_component: V
  somatic_component: S
  material_component: M (un arc)
  duration: 1 minute
  classes: '[Rôdeur](hd_ranger.md)'
  id: spells_hd.md#arc-enchanté
  title: Arc enchanté
  source: (MDR p324)
- family: SpellHD
  level: 2
  type: Transmutation
  casting_time: 1 action bonus
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Magicien](hd_wizard.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#arme-magique
  title: Arme magique
  alias: Magic Weapon
  source: (MDR p324)(SRD)
- family: SpellHD
  level: 3
  type: Transmutation
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#arme-sainte
  title: Arme sainte
  source: (MDR p324)
- family: SpellHD
  level: 2
  type: Évocation
  casting_time: 1 action bonus
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 minute
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#arme-spirituelle
  title: Arme spirituelle
  alias: Spiritual Weapon
  source: (MDR p324)(SRD)
- family: SpellHD
  level: 1
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S, M (un bout de cuir tanné)
  verbal_component: V
  somatic_component: S
  material_component: M (un bout de cuir tanné)
  duration: 8 heures
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#armure-du-mage
  title: Armure du mage
  alias: Mage Armor
  source: (MDR p324)(SRD)
- family: SpellHD
  level: 9
  type: Transmutation
  casting_time: 1 action
  range: personnelle
  components: V
  verbal_component: V
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#arrêt-du-temps
  title: Arrêt du temps
  alias: Time Stop
  source: (MDR p325)(SRD)
- family: SpellHD
  level: tour de magie
  type: Invocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#aspersion-acide
  title: Aspersion acide
  alias: Acid Splash
  source: (MDR p325)(SRD)
- family: SpellHD
  level: 4
  type: Illusion
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#assassin-imaginaire
  title: Assassin imaginaire
  alias: Phantasmal Killer
  source: (MDR p325)(SRD)
- family: SpellHD
  level: tour de magie
  type: Divination
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md)'
  id: spells_hd.md#assistance
  title: Assistance
  alias: Guidance
  source: (MDR p325)(SRD)
- family: SpellHD
  level: 2
  type: Divination
  casting_time: 1 minute
  range: personnelle
  components: V, S, M (bâtonnets, os ou petits objets similaires d'une valeur minimale de 25 po, portant des marques spéciales)
  verbal_component: V
  somatic_component: S
  material_component: M (bâtonnets, os ou petits objets similaires d'une valeur minimale de 25 po, portant des marques spéciales)
  duration: instantanée
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#augure
  title: Augure
  alias: Augury
  source: (MDR p325)(SRD)
- family: SpellHD
  level: 5
  type: Abjuration
  casting_time: 1 action
  range: 9 mètres
  components: V
  verbal_component: V
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#aura-de-force
  title: Aura de force
  source: (MDR p325)
- family: SpellHD
  level: tour de magie
  type: Enchantement
  casting_time: 1 action
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#aura-du-héros
  title: Aura du héros
  source: (MDR p326)
- family: SpellHD
  level: 2
  type: Illusion
  casting_time: 1 action
  range: contact
  components: V, S, M (un petit carré de soie)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit carré de soie)
  duration: 24 heures
  classes: '[Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#aura-magique-de-larcaniste
  title: Aura magique de l'arcaniste
  alias: Arcanist's Magic Aura
  source: (MDR p326)
- family: SpellHD
  level: 8
  type: Abjuration
  casting_time: 1 action
  range: personnelle
  components: V, S, M (un petit reliquaire d'une valeur minimum de 1 000 po contenant une relique sacrée, comme un bout de la robe d'un saint ou un morceau de parchemin prélevé sur un texte sacré)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit reliquaire d'une valeur minimum de 1 000 po contenant une relique sacrée, comme un bout de la robe d'un saint ou un morceau de parchemin prélevé sur un texte sacré)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#aura-sacrée
  title: Aura sacrée
  alias: Holy Aura
  source: (MDR p326)
- family: SpellHD
  level: 8
  type: Transmutation
  casting_time: 1 action
  range: personnelle
  components: V
  verbal_component: V
  duration: 1 heure
  classes: '[Barde](hd_bard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#bagou
  title: Bagou
  alias: Glibness
  source: (MDR p326)(SRD)
- family: SpellHD
  level: 1
  type: Transmutation
  casting_time: 1 action
  range: contact
  components: V, S, M (un brin de gui)
  verbal_component: V
  somatic_component: S
  material_component: M (un brin de gui)
  duration: instantanée
  classes: '[Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#baies-nourricières
  title: Baies nourricières
  alias: Goodberry
  source: (MDR p326)(SRD)
- family: SpellHD
  level: 1
  type: Évocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 round
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#balisage
  title: Balisage
  alias: Guiding Bolt
  source: (MDR p327)(SRD)
- family: SpellHD
  level: 4
  type: Abjuration
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (un objet qui répugne à la cible)
  verbal_component: V
  somatic_component: S
  material_component: M (un objet qui répugne à la cible)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Clerc](hd_cleric.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Paladin](hd_paladin.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#bannissement
  title: Bannissement
  alias: Banishment
  source: (MDR p327)(SRD)
- family: SpellHD
  level: 6
  type: Évocation
  casting_time: 1 action
  range: 27 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#barrière-de-lames
  title: Barrière de lames
  alias: Blade Barrier
  source: (MDR p327)(SRD)
- family: SpellHD
  level: 1
  type: Enchantement
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (un peu d'eau bénite à asperger)
  verbal_component: V
  somatic_component: S
  material_component: M (un peu d'eau bénite à asperger)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Clerc](hd_cleric.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#bénédiction
  title: Bénédiction
  alias: Bless
  source: (MDR p327)(SRD)
- family: SpellHD
  level: 3
  type: Divination
  casting_time: 1 action
  range: 18 mètres
  components: V
  verbal_component: V
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#bénédiction-héroïque
  title: Bénédiction héroïque
  source: (MDR p327)
- family: SpellHD
  level: 1
  type: Nécromancie
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#blessure
  title: Blessure
  alias: Inflict Wounds
  source: (MDR p327)(SRD)
- family: SpellHD
  level: 2
  type: Illusion
  ritual: rituel
  casting_time: 1 minute
  range: 9 mètres
  components: V, S, M (un rayon de miel et de la poussière de jade d'une valeur de 10 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (un rayon de miel et de la poussière de jade d'une valeur de 10 po, que le sort consume)
  duration: jusqu'à dissipation
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#bouche-magique
  title: Bouche magique
  alias: Magic Mouth
  source: (MDR p328)(SRD)
- family: SpellHD
  level: 1
  type: Abjuration
  casting_time: 1 réaction à effectuer lorsque vous êtes touché par une attaque ou un sort de _[projectile magique](hd_spells_projectile_magique.md)_
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 round
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#bouclier
  title: Bouclier
  alias: Shield
  source: (MDR p328)(SRD)
- family: SpellHD
  level: 4
  type: Évocation
  casting_time: 1 action
  range: personnelle
  components: V, S, M (un morceau de phosphore ou une luciole)
  verbal_component: V
  somatic_component: S
  material_component: M (un morceau de phosphore ou une luciole)
  duration: 10 minutes
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#bouclier-de-feu
  title: Bouclier de feu
  alias: Fire Shield
  source: (MDR p328)(SRD)
- family: SpellHD
  level: 1
  type: Abjuration
  casting_time: 1 action bonus
  range: 18 mètres
  components: V, S, M (un petit parchemin avec un extrait de texte sacré)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit parchemin avec un extrait de texte sacré)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Clerc](hd_cleric.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#bouclier-de-la-foi
  title: Bouclier de la foi
  alias: Shield of Faith
  source: (MDR p328)(SRD)
- family: SpellHD
  level: tour de magie
  type: Invocation
  casting_time: 1 action
  range: 3 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Druide](hd_druid.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#bouffée-de-poison
  title: Bouffée de poison
  alias: Poison Spray
  source: (MDR p328)(SRD)
- family: SpellHD
  level: 3
  type: Évocation
  casting_time: 1 action
  range: 45 mètres
  components: V, S, M (une petite boule de guano de chauve-souris et du soufre)
  verbal_component: V
  somatic_component: S
  material_component: M (une petite boule de guano de chauve-souris et du soufre)
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#boule-de-feu
  title: Boule de feu
  alias: Fireball
  source: (MDR p328)(SRD)
- family: SpellHD
  level: 7
  type: Évocation
  casting_time: 1 action
  range: 45 mètres
  components: V, S, M (une petite boule de guano de chauve-souris et du soufre)
  verbal_component: V
  somatic_component: S
  material_component: M (une petite boule de guano de chauve-souris et du soufre)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#boule-de-feu-à-explosion-retardée
  title: Boule de feu à explosion retardée
  alias: Delayed Blast Fireball
  source: (MDR p329)(SRD)
- family: SpellHD
  level: 2
  type: Évocation
  casting_time: 1 action
  range: personnelle (ligne de 18 mètres)
  components: V, S, M (une graine de légume)
  verbal_component: V
  somatic_component: S
  material_component: M (une graine de légume)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#bourrasque
  title: Bourrasque
  alias: Gust of Wind
  source: (MDR p329)(SRD)
- family: SpellHD
  level: 2
  type: Évocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (un éclat de mica)
  verbal_component: V
  somatic_component: S
  material_component: M (un éclat de mica)
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#briser
  title: Briser
  alias: Shatter
  source: (MDR p330)(SRD)
- family: SpellHD
  level: 1
  type: Évocation
  casting_time: 1 action
  range: personnelle
  components: V
  verbal_component: V
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#brûlure-du-juste
  title: Brûlure du juste
  source: (MDR p330)
- family: SpellHD
  level: 7
  type: Évocation
  casting_time: 1 action
  range: 30 mètres
  components: V, S, M (poussière de rubis d'une valeur de 1 500 po)
  verbal_component: V
  somatic_component: S
  material_component: M (poussière de rubis d'une valeur de 1 500 po)
  duration: 1 heure
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#cage-de-force
  title: Cage de force
  alias: Forcecage
  source: (MDR p330)(SRD)
- family: SpellHD
  level: 3
  type: Nécromancie
  casting_time: 1 action
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#caresse-du-vampire
  title: Caresse du vampire
  alias: Vampiric Touch
  source: (MDR p330)(SRD)
- family: SpellHD
  level: 3
  type: Nécromancie
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (un petit morceau de linceul)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit morceau de linceul)
  duration: 1 heure
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#catalepsie
  title: Catalepsie
  source: (MDR p331)
- family: SpellHD
  level: 2
  type: Nécromancie
  casting_time: 1 action
  range: 9 mètres
  components: V
  verbal_component: V
  duration: 1 minute
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#cécitésurdité
  title: Cécité/surdité
  alias: Blindness/Deafness
  source: (MDR p331)(SRD)
- family: SpellHD
  level: 6
  type: Nécromancie
  casting_time: 1 action
  range: 45 mètres
  components: V, S, M (la poudre d'une perle noire broyée d'une valeur minimale de 500 po)
  verbal_component: V
  somatic_component: S
  material_component: M (la poudre d'une perle noire broyée d'une valeur minimale de 500 po)
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#cercle-de-mort
  title: Cercle de mort
  alias: Circle of Death
  source: (MDR p331)(SRD)
- family: SpellHD
  level: 5
  type: Invocation
  casting_time: 1 minute
  range: 3 mètres
  components: V, M (des craies et des encres rares contenant des extraits de pierres précieuses pour une valeur de 50 po, que le sort consume)
  verbal_component: V
  material_component: M (des craies et des encres rares contenant des extraits de pierres précieuses pour une valeur de 50 po, que le sort consume)
  duration: 1 round
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#cercle-de-téléportation
  title: Cercle de téléportation
  alias: Teleportation Circle
  source: (MDR p331)(SRD)
- family: SpellHD
  level: 3
  type: Abjuration
  casting_time: 1 minute
  range: 3 mètres
  components: V, S, M (eau bénite ou poudre d'argent et de fer d'une valeur minimale de 100 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (eau bénite ou poudre d'argent et de fer d'une valeur minimale de 100 po, que le sort consume)
  duration: 1 heure
  classes: '[Clerc](hd_cleric.md), [Magicien](hd_wizard.md), [Paladin](hd_paladin.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#cercle-magique
  title: Cercle magique
  alias: Magic Circle
  source: (MDR p331)(SRD)
- family: SpellHD
  level: 6
  type: Évocation
  casting_time: 1 action
  range: 450 mètres
  components: V, S, M (un éclat d'ambre, de verre ou de cristal, trois épingles en argent et un morceau de fourrure)
  verbal_component: V
  somatic_component: S
  material_component: M (un éclat d'ambre, de verre ou de cristal, trois épingles en argent et un morceau de fourrure)
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#chaîne-déclairs
  title: Chaîne d'éclairs
  alias: Chain Lightning
  source: (MDR p332)
- family: SpellHD
  level: 8
  type: Abjuration
  casting_time: 1 action
  range: personnelle (sphère de 3 mètres de rayon)
  components: V, S, M (une pincée de poudre de fer ou de limaille)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de poudre de fer ou de limaille)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Clerc](hd_cleric.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#champ-antimagie
  title: Champ antimagie
  alias: Antimagic Field
  source: (MDR p332)(SRD)
- family: SpellHD
  level: 9
  type: Transmutation
  casting_time: 1 action
  range: personnelle
  components: V, S, M (un diadème de jade d'une valeur minimale de 1 500 po, que vous devez coiffer avant de lancer le sort)
  verbal_component: V
  somatic_component: S
  material_component: M (un diadème de jade d'une valeur minimale de 1 500 po, que vous devez coiffer avant de lancer le sort)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Druide](hd_druid.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#changement-de-forme
  title: Changement de forme
  alias: Shapechange
  source: (MDR p333)(SRD)
- family: SpellHD
  level: 7
  type: Invocation
  casting_time: 1 action
  range: contact
  components: V, S, M (un diapason de métal valant au moins 250 po, harmonisé avec un plan d'existence donné)
  verbal_component: V
  somatic_component: S
  material_component: M (un diapason de métal valant au moins 250 po, harmonisé avec un plan d'existence donné)
  duration: instantanée
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#changement-de-plan
  title: Changement de plan
  alias: Plane Shift
  source: (MDR p333)(SRD)
- family: SpellHD
  level: 1
  type: Enchantement
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 heure
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#charme-personne
  title: Charme-personne
  alias: Charm Person
  source: (MDR p333)(SRD)
- family: SpellHD
  level: 2
  type: Transmutation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (un bout de fer et une flamme)
  verbal_component: V
  somatic_component: S
  material_component: M (un bout de fer et une flamme)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md)'
  id: spells_hd.md#chauffer-le-métal
  title: Chauffer le métal
  alias: Heat Metal
  source: (MDR p334)(SRD)
- family: SpellHD
  level: 4
  type: Invocation
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (un petit sifflet en argent, un éclat d'os et une ficelle)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit sifflet en argent, un éclat d'os et une ficelle)
  duration: 8 heures
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#chien-de-garde
  title: Chien de garde
  alias: Faithful Hound
  source: (MDR p334)
- family: SpellHD
  level: 1
  type: Enchantement
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 minute
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#choc-des-titans
  title: Choc des titans
  source: (MDR p334)
- family: SpellHD
  level: 3
  type: Divination
  casting_time: 10 minutes
  range: 1,5 kilomètre
  components: V, S, M (un focaliseur d'une valeur minimale de 100 po, soit une corne incrustée de pierreries pour l'ouïe, soit un oeil de verre pour la vue)
  verbal_component: V
  somatic_component: S
  material_component: M (un focaliseur d'une valeur minimale de 100 po, soit une corne incrustée de pierreries pour l'ouïe, soit un oeil de verre pour la vue)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#clairvoyance
  title: Clairvoyance
  alias: Clairvoyance
  source: (MDR p334)(SRD)
- family: SpellHD
  level: 3
  type: Transmutation
  casting_time: 1 action
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 minute
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#clignotement
  title: Clignotement
  alias: Blink
  source: (MDR p334)(SRD)
- family: SpellHD
  level: 8
  type: Nécromancie
  casting_time: 1 heure
  range: contact
  components: V, S, M (un diamant valant au moins 1 000 po et un cube d'au moins 2,5 centimètres d'arête de chair de la créature à cloner, le sort consommant ces deux composantes, ainsi qu'un réceptacle d'une valeur minimale de 2 000 po qui dispose d'un couvercle susceptible d'être scellé, et assez grand pour contenir une créature de taille M, comme une grande urne, un cercueil, un cavité remplie de boue creusée dans la terre ou un récipient de cristal rempli d'eau salée)
  verbal_component: V
  somatic_component: S
  material_component: M (un diamant valant au moins 1 000 po et un cube d'au moins 2,5 centimètres d'arête de chair de la créature à cloner, le sort consommant ces deux composantes, ainsi qu'un réceptacle d'une valeur minimale de 2 000 po qui dispose d'un couvercle susceptible d'être scellé, et assez grand pour contenir une créature de taille M, comme une grande urne, un cercueil, un cavité remplie de boue creusée dans la terre ou un récipient de cristal rempli d'eau salée)
  duration: instantanée
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#clone
  title: Clone
  alias: Clone
  source: (MDR p335)(SRD)
- family: SpellHD
  level: 5
  type: Enchantement
  casting_time: 1 minute
  range: 18 mètres
  components: V
  verbal_component: V
  duration: 30 jours
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md), [Magicien](hd_wizard.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#coercition-mystique
  title: Coercition mystique
  alias: Geas
  source: (MDR p335)(SRD)
- family: SpellHD
  level: 4
  type: Invocation
  casting_time: 1 action
  range: contact
  components: V, S, M (un superbe coffre de 90x60x60 centimètres, fait de matériaux rares d'une valeur minimale de 5 000 po et une réplique du coffre de taille TP, faite des mêmes matériaux et valant au moins 50 po)
  verbal_component: V
  somatic_component: S
  material_component: M (un superbe coffre de 90x60x60 centimètres, fait de matériaux rares d'une valeur minimale de 5 000 po et une réplique du coffre de taille TP, faite des mêmes matériaux et valant au moins 50 po)
  duration: instantanée
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#coffre-secret
  title: Coffre secret
  alias: Secret Chest
  source: (MDR p335)
- family: SpellHD
  level: 3
  type: Invocation
  casting_time: 1 action
  range: 30 mètres
  components: V, S, M (un peu de cendre et de poussière d'os)
  verbal_component: V
  somatic_component: S
  material_component: M (un peu de cendre et de poussière d'os)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Sorcier](hd_warlock.md)'
  id: spells_hd.md#colère-des-damnés
  title: Colère des damnés
  source: (MDR p336)
- family: SpellHD
  level: 2
  type: Invocation
  casting_time: 1 action
  range: 12 mètres
  components: V, S, M (une ficelle)
  verbal_component: V
  somatic_component: S
  material_component: M (une ficelle)
  duration: 1 heure
  classes: '[Rôdeur](hd_ranger.md)'
  id: spells_hd.md#collet-magique
  title: Collet magique
  source: (MDR p336)
- family: SpellHD
  level: 5
  type: Évocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (une pincée de soufre)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de soufre)
  duration: instantanée
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#colonne-de-flamme
  title: Colonne de flamme
  alias: Flame Strike
  source: (MDR p336)(SRD)
- family: SpellHD
  level: 1
  type: Divination
  ritual: rituel
  casting_time: 1 action
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 10 minutes
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#communication-avec-les-animaux
  title: Communication avec les animaux
  alias: Speak with Animals
  source: (MDR p336)(SRD)
- family: SpellHD
  level: 3
  type: Nécromancie
  casting_time: 1 action
  range: 3 mètres
  components: V, S, M (encens incandescent)
  verbal_component: V
  somatic_component: S
  material_component: M (encens incandescent)
  duration: 10 minutes
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md)'
  id: spells_hd.md#communication-avec-les-morts
  title: Communication avec les morts
  alias: Speak with Dead
  source: (MDR p336)(SRD)
- family: SpellHD
  level: 3
  type: Transmutation
  casting_time: 1 action
  range: personnelle (9 mètres de rayon)
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 10 minutes
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#communication-avec-les-plantes
  title: Communication avec les plantes
  alias: Speak with Plants
  source: (MDR p337)(SRD)
- family: SpellHD
  level: 5
  type: Divination
  ritual: rituel
  casting_time: 1 minute
  range: personnelle
  components: V, S, M (de l'encens et une fiole d'eau bénite ou maudite)
  verbal_component: V
  somatic_component: S
  material_component: M (de l'encens et une fiole d'eau bénite ou maudite)
  duration: 1 minute
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#communion
  title: Communion
  alias: Commune
  source: (MDR p337)(SRD)
- family: SpellHD
  level: 5
  type: Divination
  ritual: rituel
  casting_time: 1 minute
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#communion-avec-la-nature
  title: Communion avec la nature
  alias: Commune with Nature
  source: (MDR p337)(SRD)
- family: SpellHD
  level: 2
  type: Enchantement
  casting_time: 1 minute
  range: 12 mètres
  components: V, S, M (un peu de nourriture adaptée à l'animal)
  verbal_component: V
  somatic_component: S
  material_component: M (un peu de nourriture adaptée à l'animal)
  duration: 24 heures
  classes: '[Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#compagnon-animal
  title: Compagnon animal
  source: (MDR p337)
- family: SpellHD
  level: 1
  type: Divination
  ritual: rituel
  casting_time: 1 action
  range: personnelle
  components: V, S, M (une pincée de suie et de sel)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de suie et de sel)
  duration: 1 heure
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#compréhension-des-langues
  title: Compréhension des langues
  alias: Comprehend Languages
  source: (MDR p338)(SRD)
- family: SpellHD
  level: 4
  type: Enchantement
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#compulsion
  title: Compulsion
  alias: Compulsion
  source: (MDR p338)(SRD)
- family: SpellHD
  level: 5
  type: Évocation
  casting_time: 1 action
  range: personnelle (cône de 18 mètres)
  components: V, S, M (un petit cône de cristal ou de verre)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit cône de cristal ou de verre)
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#cône-de-froid
  title: Cône de froid
  alias: Cone of Cold
  source: (MDR p338)(SRD)
- family: SpellHD
  level: 4
  type: Enchantement
  casting_time: 1 action
  range: 27 mètres
  components: V, S, M (trois coquilles de noix)
  verbal_component: V
  somatic_component: S
  material_component: M (trois coquilles de noix)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#confusion
  title: Confusion
  alias: Confusion
  source: (MDR p338)(SRD)
- family: SpellHD
  level: tour de magie
  type: Nécromancie
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 round
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#contact-glacial
  title: Contact glacial
  alias: Chill Touch
  source: (MDR p339)(SRD)
- family: SpellHD
  level: 5
  type: Divination
  ritual: rituel
  casting_time: 1 minute
  range: personnelle
  components: V
  verbal_component: V
  duration: 1 minute
  classes: '[Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#contacter-un-autre-plan
  title: Contacter un autre plan
  alias: Contact Other Plane
  source: (MDR p339)(SRD)
- family: SpellHD
  level: 5
  type: Nécromancie
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 7 jours
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md)'
  id: spells_hd.md#contagion
  title: Contagion
  alias: Contagion
  source: (MDR p339)(SRD)
- family: SpellHD
  level: 6
  type: Nécromancie
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#contamination
  title: Contamination
  alias: Harm
  source: (MDR p340)(SRD)
- family: SpellHD
  level: 6
  type: Évocation
  casting_time: 10 minutes
  range: personnelle
  components: V, S, M (une statuette de vous taillée dans l'ivoire et ornée de gemmes d'une valeur minimum de 1 500 po)
  verbal_component: V
  somatic_component: S
  material_component: M (une statuette de vous taillée dans l'ivoire et ornée de gemmes d'une valeur minimum de 1 500 po)
  duration: 10 jours
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#contingence
  title: Contingence
  alias: Contingency
  source: (MDR p340)(SRD)
- family: SpellHD
  level: 3
  type: Abjuration
  casting_time: 1 réaction à utiliser quand vous voyez une créature située dans un rayon de 18 mètres autour de vous lancer un sort
  range: 18 mètres
  components: S
  somatic_component: S
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#contresort
  title: Contresort
  alias: Counterspell
  source: (MDR p340)(SRD)
- family: SpellHD
  level: 4
  type: Transmutation
  casting_time: 1 action
  range: 90 mètres
  components: V, S, M (une goutte d'eau et une pincée de poussière)
  verbal_component: V
  somatic_component: S
  material_component: M (une goutte d'eau et une pincée de poussière)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#contrôle-de-leau
  title: Contrôle de l'eau
  alias: Control Water
  source: (MDR p340)
- family: SpellHD
  level: 8
  type: Transmutation
  casting_time: 10 minutes
  range: personnelle (rayon de 7,5 kilomètres)
  components: V, S, M (encens incandescent et un peu de bois et de terre mélangés dans de l'eau)
  verbal_component: V
  somatic_component: S
  material_component: M (encens incandescent et un peu de bois et de terre mélangés dans de l'eau)
  concentration: concentration
  duration: jusqu'à 8 heures
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#contrôle-du-climat
  title: Contrôle du climat
  alias: Control Weather
  source: (MDR p341)(SRD)
- family: SpellHD
  level: 6
  type: Invocation
  ritual: rituel
  casting_time: 1 minute
  range: contact
  components: V, S, M (un saphir d'une valeur de 1 000 po)
  verbal_component: V
  somatic_component: S
  material_component: M (un saphir d'une valeur de 1 000 po)
  duration: jusqu'à dissipation
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#convocations-instantanées
  title: Convocations instantanées
  alias: Instant Summons
  source: (MDR p342)
- family: SpellHD
  level: 5
  type: Abjuration
  casting_time: 1 action
  range: personnelle (3 mètres de rayon)
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#coquille-antivie
  title: Coquille antivie
  alias: Antilife Shell
  source: (MDR p342)(SRD)
- family: SpellHD
  level: 2
  type: Transmutation
  casting_time: 1 action
  range: contact
  components: V, S, M (extrait de maïs en poudre et boucle de parchemin torsadé)
  verbal_component: V
  somatic_component: S
  material_component: M (extrait de maïs en poudre et boucle de parchemin torsadé)
  duration: 1 heure
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#corde-enchantée
  title: Corde enchantée
  alias: Rope Trick
  source: (MDR p342)(SRD)
- family: SpellHD
  level: 1
  type: Illusion
  casting_time: 1 action
  range: personnelle (cône de 4,50 mètres)
  components: V, S, M (une poignée de poudre ou de sable, colorée en rouge, jaune et bleu)
  verbal_component: V
  somatic_component: S
  material_component: M (une poignée de poudre ou de sable, colorée en rouge, jaune et bleu)
  duration: 1 round
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#couleurs-dansantes
  title: Couleurs dansantes
  alias: Color Spray
  source: (MDR p343)(SRD)
- family: SpellHD
  level: 5
  type: Illusion
  casting_time: 1 minute
  range: 9 mètres
  components: V, S, M (un petit bout de matière de même type que l'objet que vous voulez créer)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit bout de matière de même type que l'objet que vous voulez créer)
  duration: spéciale
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#création
  title: Création
  alias: Creation
  source: (MDR p343)(SRD)
- family: SpellHD
  level: 6
  type: Nécromancie
  casting_time: 1 minute
  range: 3 mètres
  components: V, S, M (un pot d'argile rempli de poussière tombale, un pot d'argile rempli d'eau saumâtre et un onyx noir d'une valeur de 150 po par cadavre)
  verbal_component: V
  somatic_component: S
  material_component: M (un pot d'argile rempli de poussière tombale, un pot d'argile rempli d'eau saumâtre et un onyx noir d'une valeur de 150 po par cadavre)
  duration: instantanée
  classes: '[Clerc](hd_cleric.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#création-de-mort-vivant
  title: Création de mort-vivant
  alias: Create Undead
  source: (MDR p343)(SRD)
- family: SpellHD
  level: 3
  type: Invocation
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Clerc](hd_cleric.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#création-de-nourriture-et-deau
  title: Création de nourriture et d'eau
  alias: Create Food and Water
  source: (MDR p344)
- family: SpellHD
  level: 1
  type: Transmutation
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (une goutte d'eau pour créer de l'eau ou quelques grains de sable pour en détruire)
  verbal_component: V
  somatic_component: S
  material_component: M (une goutte d'eau pour créer de l'eau ou quelques grains de sable pour en détruire)
  duration: instantanée
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md)'
  id: spells_hd.md#création-ou-destruction-deau
  title: Création ou destruction d'eau
  alias: Create or Destroy Water
  source: (MDR p344)
- family: SpellHD
  level: 2
  type: Transmutation
  casting_time: 1 action
  range: 45 mètres
  components: V, S, M (sept épines acérées ou sept brindilles taillées en pointe)
  verbal_component: V
  somatic_component: S
  material_component: M (sept épines acérées ou sept brindilles taillées en pointe)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#croissance-dépines
  title: Croissance d'épines
  alias: Spike Growth
  source: (MDR p344)
- family: SpellHD
  level: 3
  type: Transmutation
  casting_time: 1 action ou 8 heures
  range: 45 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#croissance-végétale
  title: Croissance végétale
  alias: Plant Growth
  source: (MDR p344)(SRD)
- family: SpellHD
  level: 6
  type: Enchantement
  casting_time: 1 action
  range: 9 mètres
  components: V
  verbal_component: V
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#danse-irrésistible
  title: Danse irrésistible
  alias: Irresistible Dance
  source: (MDR p344)
- family: SpellHD
  level: 2
  type: Transmutation
  casting_time: 1 action
  range: 18 mètres
  components: V
  verbal_component: V
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#déblocage
  title: Déblocage
  alias: Knock
  source: (MDR p345)(SRD)
- family: SpellHD
  level: 1
  type: Illusion
  casting_time: 1 action
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 heure
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#déguisement
  title: Déguisement
  alias: Disguise Self
  source: (MDR p345)(SRD)
- family: SpellHD
  level: 8
  type: Invocation
  casting_time: 1 action
  range: 18 mètres
  components: S
  somatic_component: S
  duration: 1 heure
  classes: '[Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#demi-plan
  title: Demi-plan
  alias: Demiplane
  source: (MDR p345)(SRD)
- family: SpellHD
  level: 6
  type: Transmutation
  casting_time: 1 action
  range: 36 mètres
  components: "V, S, M (une lame de fer et un petit sac contenant un mélange de terres : de l'argile, du terreau et du sable)"
  verbal_component: V
  somatic_component: S
  material_component: "M (une lame de fer et un petit sac contenant un mélange de terres : de l'argile, du terreau et du sable)"
  concentration: concentration
  duration: jusqu'à 2 heures
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#déplacer-la-terre
  title: Déplacer la terre
  alias: Move Earth
  source: (MDR p345)(SRD)
- family: SpellHD
  level: 6
  type: Transmutation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (de la magnétite et une pincée de poussière)
  verbal_component: V
  somatic_component: S
  material_component: M (de la magnétite et une pincée de poussière)
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#désintégration
  title: Désintégration
  alias: Disintegrate
  source: (MDR p346)(SRD)
- family: SpellHD
  level: 2
  type: Transmutation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (une goutte d'eau)
  verbal_component: V
  somatic_component: S
  material_component: M (une goutte d'eau)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#dessiccation
  title: Dessiccation
  source: (MDR p346)
- family: SpellHD
  level: 1
  type: Divination
  ritual: rituel
  casting_time: 1 action
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Paladin](hd_paladin.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#détection-de-la-magie
  title: Détection de la magie
  alias: Detect Magic
  source: (MDR p346)(SRD)
- family: SpellHD
  level: 2
  type: Divination
  casting_time: 1 action
  range: personnelle
  components: V, S, M (une pièce de cuivre)
  verbal_component: V
  somatic_component: S
  material_component: M (une pièce de cuivre)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#détection-des-pensées
  title: Détection des pensées
  alias: Detect Thoughts
  source: (MDR p346)(SRD)
- family: SpellHD
  level: 1
  type: Divination
  casting_time: 1 action
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Clerc](hd_cleric.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#détection-du-mal-et-du-bien
  title: Détection du mal et du bien
  alias: Detect Evil and Good
  source: (MDR p347)(SRD)
- family: SpellHD
  level: 1
  type: Divination
  ritual: rituel
  casting_time: 1 action
  range: personnelle
  components: V, S, M (un brin d'if)
  verbal_component: V
  somatic_component: S
  material_component: M (un brin d'if)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md), [Paladin](hd_paladin.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#détection-du-poison-et-des-maladies
  title: Détection du poison et des maladies
  alias: Detect Poison and Disease
  source: (MDR p347)(SRD)
- family: SpellHD
  level: 1
  type: Invocation
  ritual: rituel
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (une goutte de mercure)
  verbal_component: V
  somatic_component: S
  material_component: M (une goutte de mercure)
  duration: 1 heure
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#disque-flottant
  title: Disque flottant
  alias: Floating Disk
  source: (MDR p347)
- family: SpellHD
  level: 3
  type: Abjuration
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Paladin](hd_paladin.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#dissipation-de-la-magie
  title: Dissipation de la magie
  alias: Dispel Magic
  source: (MDR p347)(SRD)
- family: SpellHD
  level: 5
  type: Abjuration
  casting_time: 1 action
  range: personnelle
  components: V, S, M (eau bénite ou poudre d'argent et de fer)
  verbal_component: V
  somatic_component: S
  material_component: M (eau bénite ou poudre d'argent et de fer)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Clerc](hd_cleric.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#dissipation-du-mal-et-du-bien
  title: Dissipation du mal et du bien
  alias: Dispel Evil and Good
  source: (MDR p347)(SRD)
- family: SpellHD
  level: 4
  type: Divination
  ritual: rituel
  casting_time: 1 action
  range: personnelle
  components: V, S, M (de l'encens et une offrande sacrificielle adaptée à votre religion, l'ensemble valant au moins 25 po, et le sort consume les deux)
  verbal_component: V
  somatic_component: S
  material_component: M (de l'encens et une offrande sacrificielle adaptée à votre religion, l'ensemble valant au moins 25 po, et le sort consume les deux)
  duration: instantanée
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#divination
  title: Divination
  alias: Divination
  source: (MDR p348)(SRD)
- family: SpellHD
  level: 7
  type: Nécromancie
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#doigt-de-mort
  title: Doigt de mort
  alias: Finger of Death
  source: (MDR p348)(SRD)
- family: SpellHD
  level: 5
  type: Enchantement
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#dominer-un-humanoïde
  title: Dominer un humanoïde
  alias: Dominate Person
  source: (MDR p348)(SRD)
- family: SpellHD
  level: 8
  type: Enchantement
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#dominer-un-monstre
  title: Dominer un monstre
  alias: Dominate Monster
  source: (MDR p349)(SRD)
- family: SpellHD
  level: 4
  type: Enchantement
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md)'
  id: spells_hd.md#dominer-une-bête
  title: Dominer une bête
  alias: Dominate Beast
  source: (MDR p349)(SRD)
- family: SpellHD
  level: 2
  type: Nécromancie
  ritual: rituel
  casting_time: 1 action
  range: contact
  components: V, S, M (une pincée de sel et une pièce de cuivre à poser sur chaque oeil du cadavre et qui doivent rester en place pendant toute la durée du sort)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de sel et une pièce de cuivre à poser sur chaque oeil du cadavre et qui doivent rester en place pendant toute la durée du sort)
  duration: 10 jours
  classes: '[Clerc](hd_cleric.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#doux-repos
  title: Doux repos
  alias: Gentle Repose
  source: (MDR p349)(SRD)
- family: SpellHD
  level: tour de magie
  type: Transmutation
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#druidisme
  title: Druidisme
  alias: Druidcraft
  source: (MDR p349)(SRD)
- family: SpellHD
  level: 3
  type: Évocation
  casting_time: 1 action
  range: personnelle (ligne de 30 mètres)
  components: V, S, M (un peu de fourrure et une baguette en ambre, en cristal ou en verre)
  verbal_component: V
  somatic_component: S
  material_component: M (un peu de fourrure et une baguette en ambre, en cristal ou en verre)
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#Éclair
  title: Éclair
  alias: Lightning Bolt
  source: (MDR p350)(SRD)
- family: SpellHD
  level: tour de magie
  type: Invocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (une écharde de bois)
  verbal_component: V
  somatic_component: S
  material_component: M (une écharde de bois)
  duration: instantanée
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#Éclat-de-bois
  title: Éclat de bois
  source: (MDR p350)
- family: SpellHD
  level: 8
  type: Évocation
  casting_time: 1 action
  range: 45 mètres
  components: V, S, M (du feu et un éclat d'héliotrope)
  verbal_component: V
  somatic_component: S
  material_component: M (du feu et un éclat d'héliotrope)
  duration: instantanée
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#Éclat-du-soleil
  title: Éclat du soleil
  alias: Sunburst
  source: (MDR p350)(SRD)
- family: SpellHD
  level: 7
  type: Évocation
  casting_time: 1 action
  range: personnelle (cône de 18 mètres)
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#embruns-prismatiques
  title: Embruns prismatiques
  alias: Prismatic Spray
  source: (MDR p350)(SRD)
- family: SpellHD
  level: 9
  type: Abjuration
  casting_time: 1 minute
  range: 9 mètres
  components: V, S, M (un portrait sur un vélin ou une statuette sculptée à l'effigie de la cible et une composante spéciale qui varie en fonction de la version du sort choisie et vaut au moins 500 po par dé de vie de la cible)
  verbal_component: V
  somatic_component: S
  material_component: M (un portrait sur un vélin ou une statuette sculptée à l'effigie de la cible et une composante spéciale qui varie en fonction de la version du sort choisie et vaut au moins 500 po par dé de vie de la cible)
  duration: jusqu'à dissipation
  classes: '[Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#emprisonnement
  title: Emprisonnement
  alias: Imprisonment
  source: (MDR p351)(SRD)
- family: SpellHD
  level: 1
  type: Invocation
  casting_time: 1 action
  range: 27 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#enchevêtrement
  title: Enchevêtrement
  alias: Entangle
  source: (MDR p352)(SRD)
- family: SpellHD
  level: 5
  type: Abjuration
  casting_time: 1 heure
  range: 18 mètres
  components: V, S, M (un bijou d'une valeur minimale de 1 000 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (un bijou d'une valeur minimale de 1 000 po, que le sort consume)
  duration: 24 heures
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#entrave-planaire
  title: Entrave planaire
  alias: Planar Binding
  source: (MDR p352)(SRD)
- family: SpellHD
  level: 3
  type: Évocation
  casting_time: 1 action
  range: illimitée
  components: V, S, M (un petit bout de fil de cuivre)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit bout de fil de cuivre)
  duration: 1 round
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#envoi-de-message
  title: Envoi de message
  alias: Sending
  source: (MDR p352)(SRD)
- family: SpellHD
  level: 2
  type: Enchantement
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 minute
  classes: '[Barde](hd_bard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#envoûtement
  title: Envoûtement
  alias: Enthrall
  source: (MDR p352)(SRD)
- family: SpellHD
  level: tour de magie
  type: Nécromancie
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#Épargner-les-mourants
  title: Épargner les mourants
  alias: Spare the Dying
  source: (MDR p352)(SRD)
- family: SpellHD
  level: 5
  type: Évocation
  casting_time: 1 action
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#Épée-du-juste
  title: Épée du juste
  source: (MDR p353)
- family: SpellHD
  level: 7
  type: Évocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (une épée en platine miniature avec le pommeau et la poignée en cuivre et zinc, d'une valeur de 250 po)
  verbal_component: V
  somatic_component: S
  material_component: M (une épée en platine miniature avec le pommeau et la poignée en cuivre et zinc, d'une valeur de 250 po)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#Épée-magique
  title: Épée magique
  alias: Arcane Sword
  source: (MDR p353)
- family: SpellHD
  level: 8
  type: Enchantement
  casting_time: 1 action
  range: 45 mètres
  components: V, S, M (une poignée de sphères en argile, en cristal, en verre ou minérales)
  verbal_component: V
  somatic_component: S
  material_component: M (une poignée de sphères en argile, en cristal, en verre ou minérales)
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#esprit-faible
  title: Esprit faible
  alias: Feeblemind
  source: (MDR p353)(SRD)
- family: SpellHD
  level: 8
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 24 heures
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#esprit-impénétrable
  title: Esprit impénétrable
  alias: Mind Blank
  source: (MDR p353)(SRD)
- family: SpellHD
  level: 3
  type: Invocation
  casting_time: 1 action
  range: personnelle (4,50 mètres de rayon)
  components: V, S, M (un symbole sacré)
  verbal_component: V
  somatic_component: S
  material_component: M (un symbole sacré)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#esprits-gardiens
  title: Esprits gardiens
  alias: Spirit Guardians
  source: (MDR p353)(SRD)
- family: SpellHD
  level: 9
  type: Illusion
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#Étrangeté
  title: Étrangeté
  alias: Weird
  source: (MDR p354)(SRD)
- family: SpellHD
  level: 5
  type: Transmutation
  casting_time: 8 heures
  range: contact
  components: V, S, M (une agate d'une valeur minimale de 1 000 po, que le sort consomme)
  verbal_component: V
  somatic_component: S
  material_component: M (une agate d'une valeur minimale de 1 000 po, que le sort consomme)
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md)'
  id: spells_hd.md#Éveil
  title: Éveil
  alias: Awaken
  source: (MDR p354)(SRD)
- family: SpellHD
  level: 8
  type: Transmutation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (une cuillère)
  verbal_component: V
  somatic_component: S
  material_component: M (une cuillère)
  duration: instantanée
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#excavation
  title: Excavation
  source: (MDR p354)
- family: SpellHD
  level: 4
  type: Évocation
  casting_time: 1 action bonus
  range: personnelle
  components: V
  verbal_component: V
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#expiation-du-juste
  title: Expiation du juste
  source: (MDR p354)
- family: SpellHD
  level: tour de magie
  type: Évocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Sorcier](hd_warlock.md)'
  id: spells_hd.md#explosion-occulte
  title: Explosion occulte
  alias: Eldritch Blast
  source: (MDR p354)(SRD)
- family: SpellHD
  level: 4
  type: Transmutation
  casting_time: 10 minutes
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#fabrication
  title: Fabrication
  alias: Fabricate
  source: (MDR p354)(SRD)
- family: SpellHD
  level: 4
  type: Transmutation
  casting_time: 1 action
  range: contact
  components: V, S, M (argile molle, à façonner pour lui donner approximativement la forme de l'objet de pierre désiré)
  verbal_component: V
  somatic_component: S
  material_component: M (argile molle, à façonner pour lui donner approximativement la forme de l'objet de pierre désiré)
  duration: instantanée
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#façonnage-de-la-pierre
  title: Façonnage de la pierre
  alias: Stone Shape
  source: (MDR p355)(SRD)
- family: SpellHD
  level: 1
  type: Évocation
  casting_time: 1 action bonus
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#faveur-divine
  title: Faveur divine
  alias: Divine Favor
  source: (MDR p355)(SRD)
- family: SpellHD
  level: 6
  type: Invocation
  casting_time: 10 minutes
  range: 9 mètres
  components: V, S, M (un bol incrusté de gemmes d'une valeur minimale de 1 000 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (un bol incrusté de gemmes d'une valeur minimale de 1 000 po, que le sort consume)
  duration: instantanée
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md)'
  id: spells_hd.md#festin-des-héros
  title: Festin des héros
  alias: Heroes' Feast
  source: (MDR p355)(SRD)
- family: SpellHD
  level: 1
  type: Invocation
  casting_time: 1 action
  range: personnelle
  components: V, S, M (morceau d'onyx)
  verbal_component: V
  somatic_component: S
  material_component: M (morceau d'onyx)
  duration: instantanée
  classes: '[Sorcier](hd_warlock.md)'
  id: spells_hd.md#flamboiement-funeste
  title: Flamboiement funeste
  source: (MDR p355)
- family: SpellHD
  level: 2
  type: Évocation
  casting_time: 1 action
  range: contact
  components: V, S, M (poussière de rubis d'une valeur de 50 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (poussière de rubis d'une valeur de 50 po, que le sort consume)
  duration: jusqu'à dissipation
  classes: '[Clerc](hd_cleric.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#flamme-éternelle
  title: Flamme éternelle
  alias: Continual Flame
  source: (MDR p355)(SRD)
- family: SpellHD
  level: tour de magie
  type: Évocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#flamme-sacrée
  title: Flamme sacrée
  alias: Sacred Flame
  source: (MDR p355)(SRD)
- family: SpellHD
  level: 1
  type: Enchantement
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (une goutte de sang)
  verbal_component: V
  somatic_component: S
  material_component: M (une goutte de sang)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md)'
  id: spells_hd.md#fléau
  title: Fléau
  alias: Bane
  source: (MDR p356)(SRD)
- family: SpellHD
  level: 5
  type: Invocation
  casting_time: 1 action
  range: 90 mètres
  components: V, S, M (un peu de sucre en poudre, quelques graines de céréales et une tache de graisse)
  verbal_component: V
  somatic_component: S
  material_component: M (un peu de sucre en poudre, quelques graines de céréales et une tache de graisse)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md)'
  id: spells_hd.md#fléau-dinsectes
  title: Fléau d'insectes
  alias: Insect Plague
  source: (MDR p356)
- family: SpellHD
  level: 2
  type: Évocation
  casting_time: 1 action
  range: 27 mètres
  components: V, S, M (poudre de feuille de rhubarbe et estomac de vipère)
  verbal_component: V
  somatic_component: S
  material_component: M (poudre de feuille de rhubarbe et estomac de vipère)
  duration: instantanée
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#flèche-acide
  title: Flèche acide
  alias: Acid Arrow
  source: (MDR p356)
- family: SpellHD
  level: 4
  type: Nécromancie
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#flétrissement
  title: Flétrissement
  alias: Blight
  source: (MDR p356)(SRD)
- family: SpellHD
  level: 2
  type: Illusion
  casting_time: 1 action
  range: personnelle
  components: V
  verbal_component: V
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#flou
  title: Flou
  alias: Blur
  source: (MDR p356)(SRD)
- family: SpellHD
  level: 7
  type: Transmutation
  casting_time: 1 action
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: jusqu'à 8 heures
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#forme-éthérée
  title: Forme éthérée
  alias: Etherealness
  source: (MDR p356)(SRD)
- family: SpellHD
  level: 3
  type: Transmutation
  casting_time: 1 action
  range: contact
  components: V, S, M (un morceau de gaze et une volute de fumée)
  verbal_component: V
  somatic_component: S
  material_component: M (un morceau de gaze et une volute de fumée)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#forme-gazeuse
  title: Forme gazeuse
  alias: Gaseous Form
  source: (MDR p357)(SRD)
- family: SpellHD
  level: 8
  type: Transmutation
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 24 heures
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#formes-animales
  title: Formes animales
  alias: Animal Shapes
  source: (MDR p357)(SRD)
- family: SpellHD
  level: 1
  type: Enchantement
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (de minuscules tartes et une plume à agiter dans les airs)
  verbal_component: V
  somatic_component: S
  material_component: M (de minuscules tartes et une plume à agiter dans les airs)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#fou-rire
  title: Fou rire
  alias: Hideous Laughter
  source: (MDR p357)
- family: SpellHD
  level: 1
  type: Évocation
  casting_time: 1 action bonus
  range: personnelle
  components: V
  verbal_component: V
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#frappe-du-juste
  title: Frappe du juste
  source: (MDR p358)
- family: SpellHD
  level: 2
  type: Évocation
  casting_time: 1 action bonus
  range: personnelle
  components: V
  verbal_component: V
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#frappe-lumineuse
  title: Frappe lumineuse
  alias: Branding Smite
  source: (MDR p358)(SRD)
- family: SpellHD
  level: 3
  type: Transmutation
  ritual: rituel
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 8 heures
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md)'
  id: spells_hd.md#fusion-dans-la-pierre
  title: Fusion dans la pierre
  alias: Meld into Stone
  source: (MDR p358)(SRD)
- family: SpellHD
  level: 4
  type: Invocation
  casting_time: 1 action
  range: 9 mètres
  components: V
  verbal_component: V
  duration: 8 heures
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#gardien-de-la-foi
  title: Gardien de la foi
  alias: Guardian of Faith
  source: (MDR p358)(SRD)
- family: SpellHD
  level: 1
  type: Évocation
  casting_time: 1 action
  range: 27 mètres
  components: V, S, M (une petite poire remplie d'air)
  verbal_component: V
  somatic_component: S
  material_component: M (une petite poire remplie d'air)
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md)'
  id: spells_hd.md#geyser-dénergie
  title: Geyser d'énergie
  source: (MDR p359)
- family: SpellHD
  level: 6
  type: Abjuration
  casting_time: 1 action
  range: personnelle (3 mètres de rayon)
  components: V, S, M (une perle de verre ou de cristal qui explose à la fin du sort)
  verbal_component: V
  somatic_component: S
  material_component: M (une perle de verre ou de cristal qui explose à la fin du sort)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#globe-dinvulnérabilité
  title: Globe d'invulnérabilité
  alias: Globe of Invulnerability
  source: (MDR p359)
- family: SpellHD
  level: 3
  type: Abjuration
  casting_time: 1 heure
  range: contact
  components: V, S, M (encens et poudre de diamant d'une valeur minimale de 200 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (encens et poudre de diamant d'une valeur minimale de 200 po, que le sort consume)
  duration: jusqu'à dissipation ou déclenchement
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#glyphe-de-protection
  title: Glyphe de protection
  alias: Glyph of Warding
  source: (MDR p359)(SRD)
- family: SpellHD
  level: tour de magie
  type: Transmutation
  casting_time: 1 action bonus
  range: contact
  components: V, S, M (du gui, une feuille de trèfle et un bâton ou un gourdin)
  verbal_component: V
  somatic_component: S
  material_component: M (du gui, une feuille de trèfle et un bâton ou un gourdin)
  duration: 1 minute
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#gourdin-magique
  title: Gourdin magique
  alias: Shillelagh
  source: (MDR p360)(SRD)
- family: SpellHD
  level: 1
  type: Invocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (de la couenne de porc ou du beurre)
  verbal_component: V
  somatic_component: S
  material_component: M (de la couenne de porc ou du beurre)
  duration: 1 minute
  classes: '[Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#graisse
  title: Graisse
  alias: Grease
  source: (MDR p360)(SRD)
- family: SpellHD
  level: 1
  type: Transmutation
  casting_time: 1 action
  range: contact
  components: V, S, M (une pincée de poussière)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de poussière)
  duration: 1 heure
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Magicien](hd_wizard.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#grande-foulée
  title: Grande foulée
  alias: Longstrider
  source: (MDR p360)(SRD)
- family: SpellHD
  level: 6
  type: Évocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md)'
  id: spells_hd.md#guérison
  title: Guérison
  alias: Heal
  source: (MDR p360)(SRD)
- family: SpellHD
  level: 9
  type: Évocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#guérison-de-groupe
  title: Guérison de groupe
  alias: Mass Heal
  source: (MDR p)(SRD)
- family: SpellHD
  level: 9
  type: Évocation
  casting_time: 1 action
  range: 12 mètres
  components: V, S, M (un verre en cristal d'une valeur de 500 po)
  verbal_component: V
  somatic_component: S
  material_component: M (un verre en cristal d'une valeur de 500 po)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md)'
  id: spells_hd.md#harmonique-miraculeuse
  title: Harmonique miraculeuse
  source: (MDR p)
- family: SpellHD
  level: 3
  type: Transmutation
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (un copeau de racine de réglisse)
  verbal_component: V
  somatic_component: S
  material_component: M (un copeau de racine de réglisse)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#hâte
  title: Hâte
  alias: Haste
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Enchantement
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#héroïsme
  title: Héroïsme
  alias: Heroism
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Divination
  ritual: rituel
  casting_time: 1 minute
  range: contact
  components: V, S, M (une perle d'une valeur minimale de 100 po et une plume de hibou)
  verbal_component: V
  somatic_component: S
  material_component: M (une perle d'une valeur minimale de 100 po et une plume de hibou)
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#identification
  title: Identification
  alias: Identify
  source: (MDR p)(SRD)
- family: SpellHD
  level: tour de magie
  type: Illusion
  casting_time: 1 action
  range: 9 mètres
  components: S, M (un morceau de toison)
  somatic_component: S
  material_component: M (un morceau de toison)
  duration: 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#illusion-mineure
  title: Illusion mineure
  alias: Minor Illusion
  source: (MDR p)(SRD)
- family: SpellHD
  level: 6
  type: Illusion
  casting_time: 1 action
  range: 36 mètres
  components: V, S, M (un morceau de toison et de la poussière de jade d'une valeur de 25 po)
  verbal_component: V
  somatic_component: S
  material_component: M (un morceau de toison et de la poussière de jade d'une valeur de 25 po)
  duration: jusqu'à dissipation
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#illusion-programmée
  title: Illusion programmée
  alias: Programmed Illusion
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Illusion
  casting_time: 1 action
  range: 36 mètres
  components: V, S, M (un morceau de toison)
  verbal_component: V
  somatic_component: S
  material_component: M (un morceau de toison)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#image-majeure
  title: Image majeure
  alias: Major Image
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Illusion
  casting_time: 1 action
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 minute
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#image-miroir
  title: Image miroir
  alias: Mirror Image
  source: (MDR p)(SRD)
- family: SpellHD
  level: 7
  type: Illusion
  casting_time: 1 action
  range: 750 kilomètres
  components: V, S, M (une petite réplique de votre personne construite avec des matériaux valant au moins 5 po)
  verbal_component: V
  somatic_component: S
  material_component: M (une petite réplique de votre personne construite avec des matériaux valant au moins 5 po)
  concentration: concentration
  duration: jusqu'à 1 jour
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#image-projetée
  title: Image projetée
  alias: Project Image
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Illusion
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (un morceau de toison)
  verbal_component: V
  somatic_component: S
  material_component: M (un morceau de toison)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#image-silencieuse
  title: Image silencieuse
  alias: Silent Image
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Enchantement
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (un petit morceau de fer bien droit)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit morceau de fer bien droit)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#immobiliser-un-humanoïde
  title: Immobiliser un humanoïde
  alias: Hold Person
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Enchantement
  casting_time: 1 action
  range: 27 mètres
  components: V, S, M (un petit morceau de fer bien droit)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit morceau de fer bien droit)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#immobiliser-un-monstre
  title: Immobiliser un monstre
  alias: Hold Monster
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Enchantement
  casting_time: 1 action
  range: 18 mètres
  components: V
  verbal_component: V
  duration: 1 round
  classes: '[Clerc](hd_cleric.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#injonction
  title: Injonction
  alias: Command
  source: (MDR p)(SRD)
- family: SpellHD
  level: 4
  type: Transmutation
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#insecte-géant
  title: Insecte géant
  alias: Giant Insect
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Illusion
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (un archet et un morceau d'os)
  verbal_component: V
  somatic_component: S
  material_component: M (un archet et un morceau d'os)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md)'
  id: spells_hd.md#instrument-fantomatique
  title: Instrument fantomatique
  source: (MDR p)
- family: SpellHD
  level: 6
  type: Abjuration
  ritual: rituel
  casting_time: 10 minutes
  range: contact
  components: V, S, M (un peu d'eau bénite, un encens rare et un rubis en poudre d'une valeur minimale de 1 000 po)
  verbal_component: V
  somatic_component: S
  material_component: M (un peu d'eau bénite, un encens rare et un rubis en poudre d'une valeur minimale de 1 000 po)
  duration: 1 jour
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#interdiction
  title: Interdiction
  alias: Forbiddance
  source: (MDR p)(SRD)
- family: SpellHD
  level: 7
  type: Transmutation
  casting_time: 1 action
  range: 30 mètres
  components: V, S, M (de la magnétite et de la limaille de fer)
  verbal_component: V
  somatic_component: S
  material_component: M (de la magnétite et de la limaille de fer)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#inversion-de-la-gravité
  title: Inversion de la gravité
  alias: Reverse Gravity
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Illusion
  casting_time: 1 action
  range: contact
  components: V, S, M (un cil enrobé de gomme arabique)
  verbal_component: V
  somatic_component: S
  material_component: M (un cil enrobé de gomme arabique)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#invisibilité
  title: Invisibilité
  alias: Invisibility
  source: (MDR p)(SRD)
- family: SpellHD
  level: 4
  type: Illusion
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#invisibilité-supérieure
  title: Invisibilité supérieure
  alias: Greater Invisibility
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Invocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#invoquer-des-animaux
  title: Invoquer des animaux
  alias: Conjure Animals
  source: (MDR p)(SRD)
- family: SpellHD
  level: 4
  type: Invocation
  casting_time: 1 minute
  range: 27 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Druide](hd_druid.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#invoquer-des-élémentaires-mineurs
  title: Invoquer des élémentaires mineurs
  alias: Conjure Minor Elementals
  source: (MDR p)(SRD)
- family: SpellHD
  level: 4
  type: Invocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (une baie de houx par créature invoquée)
  verbal_component: V
  somatic_component: S
  material_component: M (une baie de houx par créature invoquée)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#invoquer-des-êtres-des-bois
  title: Invoquer des êtres des bois
  alias: Conjure Woodland Beings
  source: (MDR p)(SRD)
- family: SpellHD
  level: 7
  type: Invocation
  casting_time: 1 minute
  range: 27 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#invoquer-un-céleste
  title: Invoquer un céleste
  alias: Conjure Celestial
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Invocation
  casting_time: 1 minute
  range: 27 mètres
  components: V, S, M (encens à brûler pour l'air, argile molle pour la terre, soufre et phosphore pour le feu, ou sable et eau pour l'eau)
  verbal_component: V
  somatic_component: S
  material_component: M (encens à brûler pour l'air, argile molle pour la terre, soufre et phosphore pour le feu, ou sable et eau pour l'eau)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Druide](hd_druid.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#invoquer-un-élémentaire
  title: Invoquer un élémentaire
  alias: Conjure Elemental
  source: (MDR p)(SRD)
- family: SpellHD
  level: 6
  type: Invocation
  casting_time: 1 minute
  range: 27 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Druide](hd_druid.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#invoquer-une-fée
  title: Invoquer une fée
  alias: Conjure Fey
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Nécromancie
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#jeter-une-malédiction
  title: Jeter une malédiction
  alias: Bestow curse
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Nécromancie
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#jugement-dernier
  title: Jugement dernier
  source: (MDR p)
- family: SpellHD
  level: 8
  type: Invocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#labyrinthe
  title: Labyrinthe
  alias: Maze
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Évocation
  casting_time: 1 action bonus
  range: personnelle
  components: V, S, M (feuille de sumac)
  verbal_component: V
  somatic_component: S
  material_component: M (feuille de sumac)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#lame-de-feu
  title: Lame de feu
  alias: Flame Blade
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Transmutation
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#lance-du-juste
  title: Lance du juste
  source: (MDR p)
- family: SpellHD
  level: 3
  type: Divination
  casting_time: 1 action
  range: contact
  components: V, M (un modèle réduit de ziggourat en argile)
  verbal_component: V
  material_component: M (un modèle réduit de ziggourat en argile)
  duration: 1 heure
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#langues
  title: Langues
  alias: Tongues
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Divination
  casting_time: 10 minutes
  range: personnelle
  components: V, S, M (de l'encens d'une valeur minimale de 250 po que le sort consume et quatre bandelettes d'ivoire valant au moins 50 po chaque)
  verbal_component: V
  somatic_component: S
  material_component: M (de l'encens d'une valeur minimale de 250 po que le sort consume et quatre bandelettes d'ivoire valant au moins 50 po chaque)
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#légende
  title: Légende
  alias: Legend Lore
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Transmutation
  casting_time: 1 réaction, que vous effectuez quand vous-même ou une créature située dans un rayon de 18 mètres tombe soudain
  range: 18 mètres
  components: V, M (une petite plume ou un peu de duvet)
  verbal_component: V
  material_component: M (une petite plume ou un peu de duvet)
  duration: 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#léger-comme-une-plume
  title: Léger comme une plume
  alias: Feather Fall
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Transmutation
  casting_time: 1 action
  range: 36 mètres
  components: V, S, M (une goutte de mélasse)
  verbal_component: V
  somatic_component: S
  material_component: M (une goutte de mélasse)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#lenteur
  title: Lenteur
  alias: Slow
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Clerc](hd_cleric.md), [Magicien](hd_wizard.md), [Paladin](hd_paladin.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#lever-une-malédiction
  title: Lever une malédiction
  alias: Remove Curse
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Transmutation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (soit une petite boucle de cuir, soit un bout de fil de métal doré formant la silhouette d'une cuillère au long manche)
  verbal_component: V
  somatic_component: S
  material_component: M (soit une petite boucle de cuir, soit un bout de fil de métal doré formant la silhouette d'une cuillère au long manche)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#lévitation
  title: Lévitation
  alias: Levitate
  source: (MDR p)(SRD)
- family: SpellHD
  level: 4
  type: Invocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#liane-chasseresse
  title: Liane chasseresse
  source: (MDR p)
- family: SpellHD
  level: 4
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S, M (un lien de cuir enroulé autour d'un bras ou d'un appendice similaire)
  verbal_component: V
  somatic_component: S
  material_component: M (un lien de cuir enroulé autour d'un bras ou d'un appendice similaire)
  duration: 1 heure
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md), [Ombrelame](hd_rogue_ombrelame.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#liberté-de-mouvement
  title: Liberté de mouvement
  alias: Freedom of Movement
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S, M (une paire d'anneaux de platine valant chacun au moins 50 po, que la cible et vous devez porter pendant toute la durée)
  verbal_component: V
  somatic_component: S
  material_component: M (une paire d'anneaux de platine valant chacun au moins 50 po, que la cible et vous devez porter pendant toute la durée)
  duration: 1 heure
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#lien-de-protection
  title: Lien de protection
  alias: Warding Bond
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Divination
  ritual: rituel
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (bouts de coquille d'oeuf issus de deux espèces de créatures différentes)
  verbal_component: V
  somatic_component: S
  material_component: M (bouts de coquille d'oeuf issus de deux espèces de créatures différentes)
  duration: 1 heure
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#lien-télépathique
  title: Lien télépathique
  alias: Telepathic Bond
  source: (MDR p)
- family: SpellHD
  level: 2
  type: Divination
  ritual: rituel
  casting_time: 1 action
  range: contact
  components: V, S, M (des poils de chien de chasse)
  verbal_component: V
  somatic_component: S
  material_component: M (des poils de chien de chasse)
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#localiser-des-animaux-ou-des-plantes
  title: Localiser des animaux ou des plantes
  alias: Locate Animals or Plants
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Divination
  casting_time: 1 action
  range: personnelle
  components: V, S, M (une branche fourchue)
  verbal_component: V
  somatic_component: S
  material_component: M (une branche fourchue)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Paladin](hd_paladin.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#localiser-un-objet
  title: Localiser un objet
  alias: Locate Object
  source: (MDR p)(SRD)
- family: SpellHD
  level: 4
  type: Divination
  casting_time: 1 action
  range: personnelle
  components: V, S, M (des poils de chien de chasse)
  verbal_component: V
  somatic_component: S
  material_component: M (des poils de chien de chasse)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md), [Magicien](hd_wizard.md), [Paladin](hd_paladin.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#localiser-une-créature
  title: Localiser une créature
  alias: Locate Creature
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Abjuration
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#lueur-despoir
  title: Lueur d'espoir
  alias: Beacon of Hope
  source: (MDR p)
- family: SpellHD
  level: 1
  type: Évocation
  casting_time: 1 action
  range: 18 mètres
  components: V
  verbal_component: V
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#lueurs-féeriques
  title: Lueurs féeriques
  alias: Faerie Fire
  source: (MDR p)(SRD)
- family: SpellHD
  level: tour de magie
  type: Évocation
  casting_time: 1 action
  range: contact
  components: V, M (une luciole ou de la mousse phosphorescente)
  verbal_component: V
  material_component: M (une luciole ou de la mousse phosphorescente)
  duration: 1 heure
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#lumière
  title: Lumière
  alias: Light
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Évocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 heure
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Paladin](hd_paladin.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#lumière-du-jour
  title: Lumière du jour
  alias: Daylight
  source: (MDR p)(SRD)
- family: SpellHD
  level: tour de magie
  type: Évocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S, M (un bout de phosphore ou d'orme, ou un ver luisant)
  verbal_component: V
  somatic_component: S
  material_component: M (un bout de phosphore ou d'orme, ou un ver luisant)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#lumières-dansantes
  title: Lumières dansantes
  alias: Dancing Lights
  source: (MDR p)(SRD)
- family: SpellHD
  level: tour de magie
  type: Invocation
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#main-du-mage
  title: Main du mage
  alias: Mage Hand
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Évocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S, M (une coquille d'oeuf et un gant en peau de serpent)
  verbal_component: V
  somatic_component: S
  material_component: M (une coquille d'oeuf et un gant en peau de serpent)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#main-magique
  title: Main magique
  alias: Arcane Hand
  source: (MDR p)
- family: SpellHD
  level: 1
  type: Évocation
  casting_time: 1 action
  range: personnelle (cône de 4,50 mètres)
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#mains-brûlantes
  title: Mains brûlantes
  alias: Burning Hands
  source: (MDR p)(SRD)
- family: SpellHD
  level: 7
  type: Invocation
  casting_time: 1 minute
  range: 90 mètres
  components: V, S, M (un portrait miniature gravé dans de l'ivoire, un bout de marbre poli et une minuscule cuillère en argent, chaque objet devant valoir au minimum 5 po)
  verbal_component: V
  somatic_component: S
  material_component: M (un portrait miniature gravé dans de l'ivoire, un bout de marbre poli et une minuscule cuillère en argent, chaque objet devant valoir au minimum 5 po)
  duration: 24 heures
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#manoir-somptueux
  title: Manoir somptueux
  alias: Magnificent Mansion
  source: (MDR p)
- family: SpellHD
  level: 1
  type: Abjuration
  casting_time: 1 action
  range: personnelle
  components: V, S, M (un peu d'eau)
  verbal_component: V
  somatic_component: S
  material_component: M (un peu d'eau)
  duration: 8 heures
  classes: '[Sorcier](hd_warlock.md)'
  id: spells_hd.md#manteau-de-givre
  title: Manteau de givre
  source: (MDR p)
- family: SpellHD
  level: 3
  type: Transmutation
  ritual: rituel
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (un bout de liège)
  verbal_component: V
  somatic_component: S
  material_component: M (un bout de liège)
  duration: 1 heure
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#marche-sur-leau
  title: Marche sur l'eau
  alias: Water Walk
  source: (MDR p)
- family: SpellHD
  level: 6
  type: Transmutation
  casting_time: 1 minute
  range: 9 mètres
  components: V, S, M (du feu et de l'eau bénite)
  verbal_component: V
  somatic_component: S
  material_component: M (du feu et de l'eau bénite)
  duration: 8 heures
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#marche-sur-le-vent
  title: Marche sur le vent
  alias: Wind Walk
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Divination
  casting_time: 1 action bonus
  range: 27 mètres
  components: V
  verbal_component: V
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Rôdeur](hd_ranger.md)'
  id: spells_hd.md#marque-du-chasseur
  title: Marque du chasseur
  alias: Hunter's Mark
  source: (MDR p)(SRD)
- family: SpellHD
  level: 6
  type: Nécromancie
  casting_time: 1 action
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#mauvais-oeil
  title: Mauvais oeil
  alias: Eyebite
  source: (MDR p)(SRD)
- family: SpellHD
  level: tour de magie
  type: Transmutation
  casting_time: 1 action
  range: 36 mètres
  components: V, S, M (un petit bout de fil de cuivre)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit bout de fil de cuivre)
  duration: 1 round
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#message
  title: Message
  alias: Message
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Enchantement
  ritual: rituel
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (un peu de nourriture)
  verbal_component: V
  somatic_component: S
  material_component: M (un peu de nourriture)
  duration: 24 heures
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#messager-animal
  title: Messager animal
  alias: Animal Messenger
  source: (MDR p)(SRD)
- family: SpellHD
  level: 4
  type: Transmutation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (un cocon de chenille)
  verbal_component: V
  somatic_component: S
  material_component: M (un cocon de chenille)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#métamorphose
  title: Métamorphose
  alias: Polymorph
  source: (MDR p)(SRD)
- family: SpellHD
  level: 9
  type: Transmutation
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (une goutte de mercure, une cuillerée de gomme arabique et une volute de fumée)
  verbal_component: V
  somatic_component: S
  material_component: M (une goutte de mercure, une cuillerée de gomme arabique et une volute de fumée)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#métamorphose-suprême
  title: Métamorphose suprême
  alias: True Polymorph
  source: (MDR p)(SRD)
- family: SpellHD
  level: 7
  type: Illusion
  casting_time: 10 minutes
  range: vision
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 10 jours
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#mirage
  title: Mirage
  alias: Mirage Arcane
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Enchantement
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: "jusqu'à 1 minute "
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#modification-de-mémoire
  title: Modification de mémoire
  alias: Modify Memory
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Transmutation
  casting_time: 1 action
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#modifier-son-apparence
  title: Modifier son apparence
  alias: Alter Self
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Illusion
  ritual: rituel
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 heure
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#monture-fantôme
  title: Monture fantôme
  alias: Phantom Steed
  source: (MDR p)(SRD)
- family: SpellHD
  level: tour de magie
  type: Enchantement
  casting_time: 1 action
  range: 18 mètres
  components: V
  verbal_component: V
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#moquerie-cruelle
  title: Moquerie cruelle
  alias: Vicious Mockery
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Évocation
  casting_time: 1 action bonus
  range: 18 mètres
  components: V
  verbal_component: V
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md)'
  id: spells_hd.md#mot-de-guérison
  title: Mot de guérison
  alias: Healing Word
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Évocation
  casting_time: 1 action bonus
  range: 18 mètres
  components: V
  verbal_component: V
  duration: instantanée
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#mot-de-guérison-de-groupe
  title: Mot de guérison de groupe
  alias: Mass Healing Word
  source: (MDR p)(SRD)
- family: SpellHD
  level: 8
  type: Enchantement
  casting_time: 1 action
  range: 18 mètres
  components: V
  verbal_component: V
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#mot-de-pouvoir-étourdissant
  title: Mot de pouvoir étourdissant
  alias: Power Word Stun
  source: (MDR p)(SRD)
- family: SpellHD
  level: 9
  type: Enchantement
  casting_time: 1 action
  range: 18 mètres
  components: V
  verbal_component: V
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#mot-de-pouvoir-mortel
  title: Mot de pouvoir mortel
  alias: Power Word Kill
  source: (MDR p)(SRD)
- family: SpellHD
  level: 6
  type: Invocation
  casting_time: 1 action
  range: 1,5 mètre
  components: V
  verbal_component: V
  duration: instantanée
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#mot-de-retour
  title: Mot de retour
  alias: Word of Recall
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Illusion
  casting_time: 1 action
  range: 36 mètres
  components: S, M (un bâtonnet d'encens incandescent ou une fiole de cristal remplie d'une matière phosphorescente)
  somatic_component: S
  material_component: M (un bâtonnet d'encens incandescent ou une fiole de cristal remplie d'une matière phosphorescente)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#motif-hypnotique
  title: Motif hypnotique
  alias: Hypnotic Pattern
  source: (MDR p)(SRD)
- family: SpellHD
  level: 6
  type: Invocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S, M (une poignée d'épines)
  verbal_component: V
  somatic_component: S
  material_component: M (une poignée d'épines)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#mur-dépines
  title: Mur d'épines
  alias: Wall of Thorns
  source: (MDR p)
- family: SpellHD
  level: 4
  type: Évocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S, M (un éclat de phosphore)
  verbal_component: V
  somatic_component: S
  material_component: M (un éclat de phosphore)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#mur-de-feu
  title: Mur de feu
  alias: Wall of Fire
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Évocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S, M (une pincée de poudre de gemme translucide)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de poudre de gemme translucide)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#mur-de-force
  title: Mur de force
  alias: Wall of Force
  source: (MDR p)(SRD)
- family: SpellHD
  level: 6
  type: Évocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S, M (un éclat de quartz)
  verbal_component: V
  somatic_component: S
  material_component: M (un éclat de quartz)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#mur-de-glace
  title: Mur de glace
  alias: Wall of Ice
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Évocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S, M (un petit bloc de granite)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit bloc de granite)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#mur-de-pierre
  title: Mur de pierre
  alias: Wall of Stone
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Évocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S, M (un petit éventail et une plume exotique)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit éventail et une plume exotique)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#mur-de-vent
  title: Mur de vent
  alias: Wind Wall
  source: (MDR p)(SRD)
- family: SpellHD
  level: 9
  type: Abjuration
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 10 minutes
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#mur-prismatique
  title: Mur prismatique
  alias: Prismatic Wall
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Invocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#nappe-de-brouillard
  title: Nappe de brouillard
  alias: Fog Cloud
  source: (MDR p)(SRD)
- family: SpellHD
  level: 4
  type: Abjuration
  casting_time: 1 action
  range: personnelle
  components: V
  verbal_component: V
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#nimbe-de-bienfaisance
  title: Nimbe de bienfaisance
  source: (MDR p)
- family: SpellHD
  level: 3
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S, M (une pincée de poussière de diamant d'une valeur de 25 po, que le sort consume une fois saupoudrée sur la cible)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de poussière de diamant d'une valeur de 25 po, que le sort consume une fois saupoudrée sur la cible)
  duration: 8 heures
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#non-détection
  title: Non-détection
  alias: Nondetection
  source: (MDR p)(SRD)
- family: SpellHD
  level: 8
  type: Invocation
  casting_time: 1 action
  range: 45 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#nuage-incendiaire
  title: Nuage incendiaire
  alias: Incendiary Cloud
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Invocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#nuage-mortel
  title: Nuage mortel
  alias: Cloudkill
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Invocation
  casting_time: 1 action
  range: 27 mètres
  components: V, S, M (un oeuf pourri ou des feuilles de chou pourri)
  verbal_component: V
  somatic_component: S
  material_component: M (un oeuf pourri ou des feuilles de chou pourri)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#nuage-puant
  title: Nuage puant
  alias: Stinking Cloud
  source: (MDR p)(SRD)
- family: SpellHD
  level: 9
  type: Évocation
  casting_time: 1 action
  range: 1,5 kilomètre
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#nuée-de-météores
  title: Nuée de météores
  alias: Meteor Swarm
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Invocation
  casting_time: 1 action bonus
  range: selon l'arme utilisée
  components: V, S, M (un projectile)
  verbal_component: V
  somatic_component: S
  material_component: M (un projectile)
  duration: instantanée
  classes: '[Rôdeur](hd_ranger.md)'
  id: spells_hd.md#nuée-de-projectiles
  title: Nuée de projectiles
  source: (MDR p)
- family: SpellHD
  level: 4
  type: Divination
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (des poils de chauve-souris)
  verbal_component: V
  somatic_component: S
  material_component: M (des poils de chauve-souris)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#oeil-magique
  title: Oeil magique
  alias: Arcane Eye
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Enchantement
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#offrande-inéluctable
  title: Offrande inéluctable
  source: (MDR p)
- family: SpellHD
  level: 2
  type: Illusion
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (un morceau de charbon)
  verbal_component: V
  somatic_component: S
  material_component: M (un morceau de charbon)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#ombres-imaginaires
  title: Ombres imaginaires
  source: (MDR p)
- family: SpellHD
  level: 4
  type: Abjuration
  casting_time: 1 action
  range: personnelle (3 mètres de rayon)
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: Instantanée
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#panacée
  title: Panacée
  source: (MDR p)
- family: SpellHD
  level: 7
  type: Évocation
  casting_time: 1 action bonus
  range: 9 mètres
  components: V
  verbal_component: V
  duration: instantanée
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#parole-divine
  title: Parole divine
  alias: Divine Word
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Invocation
  casting_time: 1 action bonus
  range: personnelle
  components: V
  verbal_component: V
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#pas-brumeux
  title: Pas brumeux
  alias: Misty Step
  source: (MDR p)(SRD)
- family: SpellHD
  level: 6
  type: Invocation
  casting_time: 1 action
  range: 150 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#passage-dimensionnel
  title: Passage dimensionnel
  source: (MDR p)
- family: SpellHD
  level: 5
  type: Invocation
  casting_time: 1 action
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#passage-par-les-arbres
  title: Passage par les arbres
  alias: Tree Stride
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Abjuration
  casting_time: 1 action
  range: personnelle
  components: V, S, M (cendres d'une feuille de gui et une brindille d'épicéa)
  verbal_component: V
  somatic_component: S
  material_component: M (cendres d'une feuille de gui et une brindille d'épicéa)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#passage-sans-trace
  title: Passage sans trace
  alias: Pass without Trace
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Transmutation
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (une pincée de graines de sésame)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de graines de sésame)
  duration: 1 heure
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#passe-muraille
  title: Passe-muraille
  alias: Passwall
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Transmutation
  casting_time: 1 action
  range: contact
  components: V, S, M (une goutte de bitume et une araignée)
  verbal_component: V
  somatic_component: S
  material_component: M (une goutte de bitume et une araignée)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#pattes-daraignée
  title: Pattes d'araignée
  alias: Spider Climb
  source: (MDR p)
- family: SpellHD
  level: 2
  type: Transmutation
  casting_time: 1 action
  range: contact
  components: V, S, M (une poignée d'écorce de chêne)
  verbal_component: V
  somatic_component: S
  material_component: M (une poignée d'écorce de chêne)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#peau-décorce
  title: Peau d'écorce
  alias: Barkskin
  source: (MDR p)
- family: SpellHD
  level: 4
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S, M (poussière de diamant d'une valeur de 100 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (poussière de diamant d'une valeur de 100 po, que le sort consume)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#peau-de-pierre
  title: Peau de pierre
  alias: Stoneskin
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Évocation
  ritual: rituel
  casting_time: 1 minute
  range: personnelle (hémisphère de 3 mètres de rayon)
  components: V, S, M (une petite perle de cristal)
  verbal_component: V
  somatic_component: S
  material_component: M (une petite perle de cristal)
  duration: 8 heures
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#petite-hutte
  title: Petite hutte
  alias: Tiny Hut
  source: (MDR p)
- family: SpellHD
  level: 6
  type: Transmutation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (une pincée de chaux, de l'eau et de la terre)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de chaux, de l'eau et de la terre)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#pétrification
  title: Pétrification
  alias: Flesh to Stone
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Illusion
  casting_time: 1 action
  range: personnelle (cône de 9 mètres)
  components: V, S, M (une plume blanche ou un coeur de poule)
  verbal_component: V
  somatic_component: S
  material_component: M (une plume blanche ou un coeur de poule)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#peur
  title: Peur
  alias: Fear
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Invocation
  casting_time: 1 action bonus
  range: selon l'arme utilisée
  components: V, S, M (un projectile)
  verbal_component: V
  somatic_component: S
  material_component: M (un projectile)
  duration: instantanée
  classes: '[Rôdeur](hd_ranger.md)'
  id: spells_hd.md#pluie-de-projectiles
  title: Pluie de projectiles
  source: (MDR p)
- family: SpellHD
  level: tour de magie
  type: Évocation
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#poigne-électrique
  title: Poigne électrique
  alias: Shocking Grasp
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Invocation
  casting_time: 1 action bonus
  range: personnelle
  components: V
  verbal_component: V
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Ombrelame](hd_rogue_ombrelame.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#poison-naturel
  title: Poison naturel
  source: (MDR p)
- family: SpellHD
  level: 9
  type: Invocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (un diamant d'une valeur minimale de 5 000 po)
  verbal_component: V
  somatic_component: S
  material_component: M (un diamant d'une valeur minimale de 5 000 po)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Clerc](hd_cleric.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#portail
  title: Portail
  alias: Gate
  source: (MDR p)(SRD)
- family: SpellHD
  level: 4
  type: Invocation
  casting_time: 1 action
  range: 150 mètres
  components: V
  verbal_component: V
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#porte-dimensionnelle
  title: Porte dimensionnelle
  alias: Dimension Door
  source: (MDR p)(SRD)
- family: SpellHD
  level: tour de magie
  type: Abjuration
  casting_time: 1 action
  range: personnel
  components: V, S, M (objet porte-bonheur)
  verbal_component: V
  somatic_component: S
  material_component: M (objet porte-bonheur)
  duration: 1 round
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#porte-bonheur
  title: Porte-bonheur
  source: (MDR p)
- family: SpellHD
  level: 6
  type: Nécromancie
  casting_time: 1 minute
  range: personnelle
  components: V, S, M (une gemme, un cristal, un reliquaire ou un autre réceptacle ornemental d'une valeur minimale de 500 po)
  verbal_component: V
  somatic_component: S
  material_component: M (une gemme, un cristal, un reliquaire ou un autre réceptacle ornemental d'une valeur minimale de 500 po)
  duration: jusqu'à dissipation
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#possession
  title: Possession
  alias: Magic Jar
  source: (MDR p)(SRD)
- family: SpellHD
  level: 9
  type: Divination
  casting_time: 1 minute
  range: contact
  components: V, S, M (une plume d'oiseau chanteur)
  verbal_component: V
  somatic_component: S
  material_component: M (une plume d'oiseau chanteur)
  duration: 8 heures
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#prémonition
  title: Prémonition
  alias: Foresight
  source: (MDR p)(SRD)
- family: SpellHD
  level: tour de magie
  type: Transmutation
  casting_time: 1 action
  range: 3 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: jusqu'à 1 heure
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#prestidigitation
  title: Prestidigitation
  alias: Prestidigitation
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Évocation
  casting_time: 10 minutes
  range: 9 mètres
  components: V
  verbal_component: V
  duration: instantanée
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#prière-de-soins
  title: Prière de soins
  alias: Prayer of Healing
  source: (MDR p)(SRD)
- family: SpellHD
  level: tour de magie
  type: Invocation
  casting_time: 1 action
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 10 minutes
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#produire-une-flamme
  title: Produire une flamme
  alias: Produce Flame
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Évocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#projectile-magique
  title: Projectile magique
  alias: Magic Missile
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Invocation
  casting_time: 1 action bonus
  range: selon l'arme utilisée
  components: V, S, M (un projectile)
  verbal_component: V
  somatic_component: S
  material_component: M (un projectile)
  duration: instantanée
  classes: '[Ombrelame](hd_rogue_ombrelame.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#projectile-toxique
  title: Projectile toxique
  source: (MDR p)
- family: SpellHD
  level: 9
  type: Nécromancie
  casting_time: 1 heure
  range: 3 mètres
  components: V, S, M (un zircon jaune d'une valeur minimale de 1 000 po et un lingot d'argent gravé d'une valeur minimale de 100 po par créature ; le sort consomme ces composantes)
  verbal_component: V
  somatic_component: S
  material_component: M (un zircon jaune d'une valeur minimale de 1 000 po et un lingot d'argent gravé d'une valeur minimale de 100 po par créature ; le sort consomme ces composantes)
  duration: spéciale
  classes: '[Clerc](hd_cleric.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#projection-astrale
  title: Projection astrale
  alias: Astral Projection
  source: (MDR p)(SRD)
- family: SpellHD
  level: 4
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 8 heures
  classes: '[Clerc](hd_cleric.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#protection-contre-la-mort
  title: Protection contre la mort
  alias: Death Ward
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S, M (eau bénite ou poudre de fer et d'argent, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (eau bénite ou poudre de fer et d'argent, que le sort consume)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Clerc](hd_cleric.md), [Magicien](hd_wizard.md), [Paladin](hd_paladin.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#protection-contre-le-mal-et-le-bien
  title: Protection contre le mal et le bien
  alias: Protection from Evil and Good
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 heure
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md), [Paladin](hd_paladin.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#protection-contre-le-poison
  title: Protection contre le poison
  alias: Protection from Poison
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Ombrelame](hd_rogue_ombrelame.md)'
  id: spells_hd.md#protection-contre-les-énergies
  title: Protection contre les énergies
  alias: Protection from Energy
  source: (MDR p)
- family: SpellHD
  level: 6
  type: Abjuration
  casting_time: 10 minutes
  range: contact
  components: V, S, M (encens incandescent, petite dose de soufre et d'huile, cordelette avec des noeuds, petite dose de sang d'ombre des roches et petit sceptre en argent d'une valeur minimale de 10 po)
  verbal_component: V
  somatic_component: S
  material_component: M (encens incandescent, petite dose de soufre et d'huile, cordelette avec des noeuds, petite dose de sang d'ombre des roches et petit sceptre en argent d'une valeur minimale de 10 po)
  duration: 24 heures
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#protections-et-sceaux
  title: Protections et sceaux
  alias: Guards and Wards
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Transmutation
  ritual: rituel
  casting_time: 1 action
  range: 3 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#purification-de-la-nourriture-et-de-leau
  title: Purification de la nourriture et de l'eau
  alias: Purify Food and Drink
  source: (MDR p)
- family: SpellHD
  level: 1
  type: Nécromancie
  casting_time: 1 action
  range: 30 mètres
  components: V, S, M
  verbal_component: V
  somatic_component: S
  material_component: M
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Sorcier](hd_warlock.md)'
  id: spells_hd.md#putréfaction
  title: Putréfaction
  source: (MDR p)
- family: SpellHD
  level: 5
  type: Nécromancie
  casting_time: 1 heure
  range: contact
  components: V, S, M (un diamant d'une valeur minimale de 500 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (un diamant d'une valeur minimale de 500 po, que le sort consume)
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#rappel-à-la-vie
  title: Rappel à la vie
  alias: Raise Dead
  source: (MDR p)
- family: SpellHD
  level: 2
  type: Nécromancie
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#rayon-affaiblissant
  title: Rayon affaiblissant
  alias: Ray of Enfeeblement
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Évocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#rayon-ardent
  title: Rayon ardent
  alias: Scorching Ray
  source: (MDR p)(SRD)
- family: SpellHD
  level: tour de magie
  type: Évocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#rayon-de-givre
  title: Rayon de givre
  alias: Ray of Frost
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Évocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S, M (quelques graines de lierre, peu importe l'espèce, et un éclat de feldspath opalescent)
  verbal_component: V
  somatic_component: S
  material_component: M (quelques graines de lierre, peu importe l'espèce, et un éclat de feldspath opalescent)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#rayon-de-lune
  title: Rayon de lune
  alias: Moonbeam
  source: (MDR p)(SRD)
- family: SpellHD
  level: 6
  type: Évocation
  casting_time: 1 action
  range: personnelle (ligne de 18 mètres)
  components: V, S, M (une loupe)
  verbal_component: V
  somatic_component: S
  material_component: M (une loupe)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#rayon-de-soleil
  title: Rayon de soleil
  alias: Sunbeam
  source: (MDR p)(SRD)
- family: SpellHD
  level: 7
  type: Transmutation
  casting_time: 1 minute
  range: contact
  components: V, S, M (un moulin à prières et de l'eau bénite)
  verbal_component: V
  somatic_component: S
  material_component: M (un moulin à prières et de l'eau bénite)
  duration: 1 heure
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md)'
  id: spells_hd.md#régénération
  title: Régénération
  alias: Regenerate
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Transmutation
  casting_time: 1 heure
  range: contact
  components: V, S, M (huiles et onguents rares d'une valeur minimale de 1 000 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (huiles et onguents rares d'une valeur minimale de 1 000 po, que le sort consume)
  duration: instantanée
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#réincarnation
  title: Réincarnation
  alias: Reincarnate
  source: (MDR p)(SRD)
- family: SpellHD
  level: tour de magie
  type: Transmutation
  casting_time: 1 minute
  range: contact
  components: V, S, M (deux magnétites)
  verbal_component: V
  somatic_component: S
  material_component: M (deux magnétites)
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#réparation
  title: Réparation
  alias: Mending
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Transmutation
  casting_time: 1 action bonus
  range: personnelle
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#repli-expéditif
  title: Repli expéditif
  alias: Expeditious Retreat
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Évocation
  casting_time: 1 réaction en réponse aux dégâts que vous inﬂige une créature située dans votre champ de vision et dans un rayon de 18 mètres autour de vous
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Sorcier](hd_warlock.md)'
  id: spells_hd.md#représailles-infernales
  title: Représailles infernales
  alias: Hellish Rebuke
  source: (MDR p)(SRD)
- family: SpellHD
  level: 8
  type: Enchantement
  casting_time: 1 heure
  range: 18 mètres
  components: V, S, M (un cristal d'alun trempé dans le vinaigre pour répulsion ou une goutte de miel pour attirance)
  verbal_component: V
  somatic_component: S
  material_component: M (un cristal d'alun trempé dans le vinaigre pour répulsion ou une goutte de miel pour attirance)
  duration: 10 jours
  classes: '[Druide](hd_druid.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#répulsionattirance
  title: Répulsion/attirance
  alias: Antipathy/Sympathy
  source: (MDR p)(SRD)
- family: SpellHD
  level: tour de magie
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S, M (une cape miniature)
  verbal_component: V
  somatic_component: S
  material_component: M (une cape miniature)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md)'
  id: spells_hd.md#résistance
  title: Résistance
  alias: Resistance
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Transmutation
  ritual: rituel
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (un petit roseau ou un brin de paille)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit roseau ou un brin de paille)
  duration: 24 heures
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#respiration-aquatique
  title: Respiration aquatique
  alias: Water Breathing
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md), [Paladin](hd_paladin.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#restauration-inférieure
  title: Restauration inférieure
  alias: Lesser Restoration
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S, M (poussière de diamant d'une valeur minimale de 100 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (poussière de diamant d'une valeur minimale de 100 po, que le sort consume)
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md)'
  id: spells_hd.md#restauration-supérieure
  title: Restauration supérieure
  alias: Greater Restoration
  source: (MDR p)(SRD)
- family: SpellHD
  level: 7
  type: Nécromancie
  casting_time: 1 heure
  range: contact
  components: V, S, M (un diamant d'une valeur minimale de 1 000 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (un diamant d'une valeur minimale de 1 000 po, que le sort consume)
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md)'
  id: spells_hd.md#résurrection
  title: Résurrection
  alias: Resurrection
  source: (MDR p)(SRD)
- family: SpellHD
  level: 9
  type: Nécromancie
  casting_time: 1 heure
  range: contact
  components: V, S, M (un peu d'eau bénite à asperger et des diamants d'une valeur minimale de 25 000 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (un peu d'eau bénite à asperger et des diamants d'une valeur minimale de 25 000 po, que le sort consume)
  duration: instantanée
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md)'
  id: spells_hd.md#résurrection-suprême
  title: Résurrection suprême
  alias: True Resurrection
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Illusion
  casting_time: 1 minute
  range: spéciale
  components: V, S, M (une poignée de sable, une goutte d'encre et une plume d'écrivain prélevée sur un oiseau endormi)
  verbal_component: V
  somatic_component: S
  material_component: M (une poignée de sable, une goutte d'encre et une plume d'écrivain prélevée sur un oiseau endormi)
  duration: 8 heures
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#rêve
  title: Rêve
  alias: Dream
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Nécromancie
  casting_time: 1 action
  range: contact
  components: V, S, M (diamant d'une valeur de 300 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (diamant d'une valeur de 300 po, que le sort consume)
  duration: instantanée
  classes: '[Clerc](hd_cleric.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#revigorer
  title: Revigorer
  alias: Revivify
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Évocation
  casting_time: 24 heures
  range: contact
  components: V, S, M (herbes, huiles et encens d'une valeur minimale de 1 000 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (herbes, huiles et encens d'une valeur minimale de 1 000 po, que le sort consume)
  duration: jusqu'à dissipation
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#sanctification
  title: Sanctification
  alias: Hallow
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Abjuration
  casting_time: 1 action bonus
  range: 9 mètres
  components: V, S, M (un petit miroir en argent)
  verbal_component: V
  somatic_component: S
  material_component: M (un petit miroir en argent)
  duration: 1 minute
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#sanctuaire
  title: Sanctuaire
  alias: Sanctuary
  source: (MDR p)(SRD)
- family: SpellHD
  level: 4
  type: Abjuration
  casting_time: 10 minutes
  range: 36 mètres
  components: V, S, M (une mince feuille de plomb, un morceau de verre opaque, un bout de coton ou de tissu et de la chrysolite en poudre)
  verbal_component: V
  somatic_component: S
  material_component: M (une mince feuille de plomb, un morceau de verre opaque, un bout de coton ou de tissu et de la chrysolite en poudre)
  duration: 24 heures
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#sanctuaire-privé
  title: Sanctuaire privé
  alias: Private Sanctum
  source: (MDR p)
- family: SpellHD
  level: 1
  type: Nécromancie
  casting_time: 1 action
  range: contact
  components: V, S, M (une fiole d'un mélange de sang et d'acide)
  verbal_component: V
  somatic_component: S
  material_component: M (une fiole d'un mélange de sang et d'acide)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#sang-du-démon
  title: Sang du démon
  source: (MDR p)
- family: SpellHD
  level: 1
  type: Transmutation
  casting_time: 1 action
  range: contact
  components: V, S, M (une patte arrière de sauterelle)
  verbal_component: V
  somatic_component: S
  material_component: M (une patte arrière de sauterelle)
  duration: 1 minute
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#saut
  title: Saut
  alias: Jump
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Divination
  casting_time: 10 minutes
  range: personnelle
  components: V, S, M (un focaliseur d'une valeur minimale de 1 000 po comme une boule de cristal, un miroir en argent ou un bénitier rempli d'eau bénite)
  verbal_component: V
  somatic_component: S
  material_component: M (un focaliseur d'une valeur minimale de 1 000 po comme une boule de cristal, un miroir en argent ou un bénitier rempli d'eau bénite)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#scrutation
  title: Scrutation
  alias: Scrying
  source: (MDR p)(SRD)
- family: SpellHD
  level: 7
  type: Transmutation
  casting_time: 1 action
  range: contact
  components: V, S, M (une poudre de diamant, d'émeraude, de rubis et de saphir d'une valeur minimum de 5 000 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (une poudre de diamant, d'émeraude, de rubis et de saphir d'une valeur minimum de 5 000 po, que le sort consume)
  duration: jusqu'à dissipation
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#séquestration
  title: Séquestration
  alias: Sequester
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Invocation
  ritual: rituel
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (un bout de ficelle et un morceau de bois)
  verbal_component: V
  somatic_component: S
  material_component: M (un bout de ficelle et un morceau de bois)
  duration: 1 heure
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#serviteur-invisible
  title: Serviteur invisible
  alias: Unseen Servant
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Illusion
  ritual: rituel
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#silence
  title: Silence
  alias: Silence
  source: (MDR p)(SRD)
- family: SpellHD
  level: 7
  type: Illusion
  casting_time: 12 heures
  range: contact
  components: V, S, M (de la neige ou de la glace en quantité suffisante pour faire une reproduction grandeur nature de la créature à dupliquer ; des cheveux, des rognures d'ongles ou un autre échantillon de la créature à dupliquer, à placer dans la neige ou la glace, et de la poudre de rubis d'une valeur minimale de 1 500 po que le sort consume, à saupoudrer sur le double)
  verbal_component: V
  somatic_component: S
  material_component: M (de la neige ou de la glace en quantité suffisante pour faire une reproduction grandeur nature de la créature à dupliquer ; des cheveux, des rognures d'ongles ou un autre échantillon de la créature à dupliquer, à placer dans la neige ou la glace, et de la poudre de rubis d'une valeur minimale de 1 500 po que le sort consume, à saupoudrer sur le double)
  duration: jusqu'à dissipation
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#simulacre
  title: Simulacre
  alias: Simulacrum
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Nécromancie
  casting_time: 1 action
  range: personnelle
  components: V, S, M (une petite quantité d'alcool ou de spiritueux)
  verbal_component: V
  somatic_component: S
  material_component: M (une petite quantité d'alcool ou de spiritueux)
  duration: 1 heure
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#simulacre-de-vie
  title: Simulacre de vie
  alias: False Life
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Évocation
  casting_time: 1 action
  range: contact
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md), [Paladin](hd_paladin.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#soin-des-blessures
  title: Soin des blessures
  alias: Cure Wounds
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Évocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md)'
  id: spells_hd.md#soin-des-blessures-de-groupe
  title: Soin des blessures de groupe
  alias: Mass Cure Wounds
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Enchantement
  casting_time: 1 action
  range: 27 mètres
  components: V, S, M (une pincée de sable fin, des pétales de rose ou un criquet)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de sable fin, des pétales de rose ou un criquet)
  duration: 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#sommeil
  title: Sommeil
  alias: Sleep
  source: (MDR p)(SRD)
- family: SpellHD
  level: 9
  type: Invocation
  casting_time: 1 action
  range: personnelle
  components: V
  verbal_component: V
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#souhait
  title: Souhait
  alias: Wish
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Invocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (un bout de suif, une pincée de soufre et un peu de poudre de fer)
  verbal_component: V
  somatic_component: S
  material_component: M (un bout de suif, une pincée de soufre et un peu de poudre de fer)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Druide](hd_druid.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#sphère-de-feu
  title: Sphère de feu
  alias: Flaming Sphere
  source: (MDR p)(SRD)
- family: SpellHD
  level: 6
  type: Évocation
  casting_time: 1 action
  range: 90 mètres
  components: V, S, M (une petite sphère de cristal)
  verbal_component: V
  somatic_component: S
  material_component: M (une petite sphère de cristal)
  duration: instantanée
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#sphère-glacée
  title: Sphère glacée
  alias: Freezing Sphere
  source: (MDR p)
- family: SpellHD
  level: 4
  type: Évocation
  casting_time: 1 action
  range: 9 mètres
  components: V, S, M (un bout de cristal transparent hémisphérique et son équivalent en gomme arabique)
  verbal_component: V
  somatic_component: S
  material_component: M (un bout de cristal transparent hémisphérique et son équivalent en gomme arabique)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#sphère-résiliente
  title: Sphère résiliente
  alias: Resilient Sphere
  source: (MDR p)
- family: SpellHD
  level: 2
  type: Invocation
  casting_time: 1 action
  range: 30 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#stalagmites-fulgurantes
  title: Stalagmites fulgurantes
  source: (MDR p)
- family: SpellHD
  level: 1
  type: Invocation
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#strangulation
  title: Strangulation
  source: (MDR p)
- family: SpellHD
  level: 2
  type: Enchantement
  casting_time: 1 action
  range: 9 mètres
  components: V, M (une langue de serpent et soit un rayon de miel, soit une goutte d'huile d'olive)
  verbal_component: V
  material_component: M (une langue de serpent et soit un rayon de miel, soit une goutte d'huile d'olive)
  concentration: concentration
  duration: jusqu'à 8 heures
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#suggestion
  title: Suggestion
  alias: Suggestion
  source: (MDR p)(SRD)
- family: SpellHD
  level: 6
  type: Enchantement
  casting_time: 1 action
  range: 18 mètres
  components: V, M (une langue de serpent et soit un rayon de miel, soit une goutte d'huile d'olive)
  verbal_component: V
  material_component: M (une langue de serpent et soit un rayon de miel, soit une goutte d'huile d'olive)
  duration: 24 heures
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#suggestion-de-groupe
  title: Suggestion de groupe
  alias: Mass Suggestion
  source: (MDR p)(SRD)
- family: SpellHD
  level: 7
  type: Abjuration
  casting_time: 1 minute
  range: contact
  components: V, S, M (mercure, phosphore et poudre de diamant et d'opale d'une valeur totale d'au moins 1 000 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (mercure, phosphore et poudre de diamant et d'opale d'une valeur totale d'au moins 1 000 po, que le sort consume)
  duration: jusqu'à dissipation ou déclenchement
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#symbole
  title: Symbole
  alias: Symbol
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Transmutation
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#télékinésie
  title: Télékinésie
  alias: Telekinesis
  source: (MDR p)(SRD)
- family: SpellHD
  level: 7
  type: Invocation
  casting_time: 1 action
  range: 3 mètres
  components: V
  verbal_component: V
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#téléportation
  title: Téléportation
  alias: Teleport
  source: (MDR p)(SRD)
- family: SpellHD
  level: 7
  type: Évocation
  casting_time: 1 action
  range: 45 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md)'
  id: spells_hd.md#tempête-de-feu
  title: Tempête de feu
  alias: Fire Storm
  source: (MDR p)(SRD)
- family: SpellHD
  level: 4
  type: Évocation
  casting_time: 1 action
  range: 90 mètres
  components: V, S, M (une pincée de poussière et quelques gouttes d'eau)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de poussière et quelques gouttes d'eau)
  duration: instantanée
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#tempête-de-grêle
  title: Tempête de grêle
  alias: Ice Storm
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Invocation
  casting_time: 1 action
  range: 45 mètres
  components: V, S, M (une pincée de poussière et quelques gouttes d'eau)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de poussière et quelques gouttes d'eau)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#tempête-de-neige
  title: Tempête de neige
  alias: Sleet Storm
  source: (MDR p)(SRD)
- family: SpellHD
  level: 8
  type: Invocation
  casting_time: 1 action
  range: 1 kilomètre
  components: V, S, M (une rose des sables)
  verbal_component: V
  somatic_component: S
  material_component: M (une rose des sables)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#tempête-de-sable
  title: Tempête de sable
  source: (MDR p)
- family: SpellHD
  level: 9
  type: Invocation
  casting_time: 1 action
  range: champ de vision
  components: V, S
  verbal_component: V
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#tempête-vengeresse
  title: Tempête vengeresse
  alias: Storm of Vengeance
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Évocation
  casting_time: 1 action
  range: 18 mètres
  components: V, M (des poils de chauve-souris et une goutte de poix ou un bout de charbon)
  verbal_component: V
  material_component: M (des poils de chauve-souris et une goutte de poix ou un bout de charbon)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#ténèbres
  title: Ténèbres
  alias: Darkness
  source: (MDR p)(SRD)
- family: SpellHD
  level: 4
  type: Invocation
  casting_time: 1 action
  range: 27 mètres
  components: V, S, M (un bout de tentacule appartenant à une pieuvre ou un calmar géant)
  verbal_component: V
  somatic_component: S
  material_component: M (un bout de tentacule appartenant à une pieuvre ou un calmar géant)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#tentacules-noirs
  title: Tentacules noirs
  alias: Black Tentacles
  source: (MDR p)
- family: SpellHD
  level: 4
  type: Illusion
  casting_time: 10 minutes
  range: 90 mètres
  components: V, S, M (une pierre, une brindille et un bout de plante verte)
  verbal_component: V
  somatic_component: S
  material_component: M (une pierre, une brindille et un bout de plante verte)
  duration: 24 heures
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#terrain-hallucinatoire
  title: Terrain hallucinatoire
  alias: Hallucinatory Terrain
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Illusion
  ritual: rituel
  casting_time: 1 minute
  range: contact
  components: S, M (de l'encre à base de plomb valant au minimum 10 po, que le sort consume)
  somatic_component: S
  material_component: M (de l'encre à base de plomb valant au minimum 10 po, que le sort consume)
  duration: 10 jours
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#texte-illusoire
  title: Texte illusoire
  alias: Illusory Script
  source: (MDR p)(SRD)
- family: SpellHD
  level: tour de magie
  type: Transmutation
  casting_time: 1 action
  range: 9 mètres
  components: V
  verbal_component: V
  duration: jusqu'à 1 minute
  classes: '[Clerc](hd_cleric.md)'
  id: spells_hd.md#thaumaturgie
  title: Thaumaturgie
  alias: Thaumaturgy
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Invocation
  casting_time: 1 action
  range: 18 mètres
  components: V, S, M (un bout de toile d'araignée)
  verbal_component: V
  somatic_component: S
  material_component: M (un bout de toile d'araignée)
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#toile-daraignée
  title: Toile d'araignée
  alias: Web
  source: (MDR p)
- family: SpellHD
  level: tour de magie
  type: Évocation
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#trait-de-feu
  title: Trait de feu
  alias: Fire Bolt
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Invocation
  casting_time: 1 action bonus
  range: personnelle
  components: V
  verbal_component: V
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Rôdeur](hd_ranger.md)'
  id: spells_hd.md#transpercer
  title: Transpercer
  source: (MDR p)
- family: SpellHD
  level: 6
  type: Invocation
  casting_time: 1 action
  range: 3 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 round
  classes: '[Druide](hd_druid.md)'
  id: spells_hd.md#transport-végétal
  title: Transport végétal
  alias: Transport via Plants
  source: (MDR p)(SRD)
- family: SpellHD
  level: 8
  type: Évocation
  casting_time: 1 action
  range: 150 mètres
  components: V, S, M (une pincée de poussière, un caillou et un peu d'argile)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de poussière, un caillou et un peu d'argile)
  concentration: concentration
  duration: jusqu'à 1 minute
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md)'
  id: spells_hd.md#tremblement-de-terre
  title: Tremblement de terre
  alias: Earthquake
  source: (MDR p)(SRD)
- family: SpellHD
  level: 5
  type: Illusion
  casting_time: 1 action
  range: personnelle
  components: S
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 heure
  classes: '[Barde](hd_bard.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#tromperie
  title: Tromperie
  alias: Mislead
  source: (MDR p)
- family: SpellHD
  level: 2
  type: Divination
  casting_time: 1 action
  range: 36 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Clerc](hd_cleric.md), [Druide](hd_druid.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#trouver-les-pièges
  title: Trouver les pièges
  alias: Find Traps
  source: (MDR p)(SRD)
- family: SpellHD
  level: 6
  type: Divination
  casting_time: 1 minute
  range: personnelle
  components: V, S, M (un ensemble d'instruments de divination comme des os, des bâtonnets en ivoire, des cartes, des dents ou des runes gravées d'une valeur de 100 po et un objet venant de l'endroit que vous cherchez)
  verbal_component: V
  somatic_component: S
  material_component: M (un ensemble d'instruments de divination comme des os, des bâtonnets en ivoire, des cartes, des dents ou des runes gravées d'une valeur de 100 po et un objet venant de l'endroit que vous cherchez)
  concentration: concentration
  duration: jusqu'à 1 jour
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Druide](hd_druid.md)'
  id: spells_hd.md#trouver-un-chemin
  title: Trouver un chemin
  alias: Find the Path
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Invocation
  casting_time: 10 minutes
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#trouver-une-monture
  title: Trouver une monture
  alias: Find Steed
  source: (MDR p)(SRD)
- family: SpellHD
  level: 1
  type: Évocation
  casting_time: 1 action
  range: personnelle (cube de 4,50 mètres)
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: instantanée
  classes: '[Barde](hd_bard.md), [Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#vague-tonnante
  title: Vague tonnante
  alias: Thunderwave
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Abjuration
  casting_time: 1 action
  range: contact
  components: V, S, M (poussière d'or d'une valeur minimum de 25 po, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (poussière d'or d'une valeur minimum de 25 po, que le sort consume)
  duration: jusqu'à dissipation
  classes: '[Magicien](hd_wizard.md)'
  id: spells_hd.md#verrou-magique
  title: Verrou magique
  alias: Arcane Lock
  source: (MDR p)(SRD)
- family: SpellHD
  level: tour de magie
  type: Divination
  casting_time: 1 action
  range: 9 mètres
  components: S
  somatic_component: S
  concentration: concentration
  duration: jusqu'à 1 round
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#viser-juste
  title: Viser juste
  alias: True Strike
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Transmutation
  casting_time: 1 action
  range: contact
  components: V, S, M (une pincée de carotte séchée ou une agate)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de carotte séchée ou une agate)
  duration: 8 heures
  classes: '[Druide](hd_druid.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Ombrelame](hd_rogue_ombrelame.md), [Rôdeur](hd_ranger.md)'
  id: spells_hd.md#vision-dans-le-noir
  title: Vision dans le noir
  alias: Darkvision
  source: (MDR p)(SRD)
- family: SpellHD
  level: 6
  type: Divination
  casting_time: 1 action
  range: contact
  components: V, S, M (un collyre coûtant 25 po, fait de poudre de champignon, de safran et de graisse, que le sort consume)
  verbal_component: V
  somatic_component: S
  material_component: M (un collyre coûtant 25 po, fait de poudre de champignon, de safran et de graisse, que le sort consume)
  duration: 1 heure
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#vision-suprême
  title: Vision suprême
  alias: True Seeing
  source: (MDR p)(SRD)
- family: SpellHD
  level: 3
  type: Évocation
  casting_time: 1 action
  range: 9 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 1 minute
  classes: '[Paladin](hd_paladin.md)'
  id: spells_hd.md#vitalité
  title: Vitalité
  source: (MDR p)
- family: SpellHD
  level: 2
  type: Divination
  casting_time: 1 action
  range: personnelle
  components: V, S, M (une pincée de talc et un saupoudrage de poudre d'argent)
  verbal_component: V
  somatic_component: S
  material_component: M (une pincée de talc et un saupoudrage de poudre d'argent)
  duration: 1 heure
  classes: '[Barde](hd_bard.md), [Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md)'
  id: spells_hd.md#voir-linvisible
  title: Voir l'invisible
  alias: See Invisibility
  source: (MDR p)
- family: SpellHD
  level: 3
  type: Transmutation
  casting_time: 1 action
  range: contact
  components: V, S, M (une rémige)
  verbal_component: V
  somatic_component: S
  material_component: M (une rémige)
  concentration: concentration
  duration: jusqu'à 10 minutes
  classes: '[Ensorceleur](hd_sorcerer.md), [Magicien](hd_wizard.md), [Sorcier](hd_warlock.md)'
  id: spells_hd.md#vol
  title: Vol
  alias: Fly
  source: (MDR p)(SRD)
- family: SpellHD
  level: 2
  type: Enchantement
  casting_time: 1 action
  range: 18 mètres
  components: V, S
  verbal_component: V
  somatic_component: S
  duration: 10 minutes
  classes: '[Barde](hd_bard.md), [Clerc](hd_cleric.md), [Paladin](hd_paladin.md)'
  id: spells_hd.md#zone-de-vérité
  title: Zone de vérité
  alias: Zone of Truth
  source: (MDR p)(SRD)
id: spells_hd.md#sorts
title: Sorts
alias: Spells
---
Vous agrandissez ou rétrécissez une créature ou un objet situé à portée et dans votre champ de vision pendant toute la durée du sort. Choisissez soit une créature, soit un objet qui n'est ni porté ni transporté. Si la cible n'est pas consentante, elle a droit à un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). Si elle le réussit, le sort est sans effet.

Si la cible est une créature, tout ce qu'elle porte et tout ce qu'elle transporte change de taille avec elle. En revanche, si elle lâche un objet, il reprend sa taille normale sur-le-champ.

**_Agrandir._** La cible double dans toutes les dimensions, et son poids est multiplié par huit. Cette croissance augmente sa catégorie de taille d'un cran, de M à G par exemple. Si la cible n'a pas assez de place pour doubler de volume, elle atteint la taille maximale possible dans l'espace dont elle dispose. Elle bénéficie d'un avantage lors des tests de [Force](hd_abilities_strength.md) et des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md) jusqu'à la fin du sort. Les armes de la cible grandissent pour s'adapter à sa nouvelle taille. Tant qu'elles sont ainsi agrandies, elles infligent 1d4 dégâts de plus.

**_Rétrécir._** La cible réduit de moitié dans toutes les dimensions et son poids est divisé par huit. Ce rétrécissement réduit sa catégorie de taille d'un cran, de M à P par exemple. La cible subit un désavantage lors des tests de [Force](hd_abilities_strength.md) et des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md) jusqu'à la fin du sort. Les armes de la cible rétrécissent pour s'adapter à sa nouvelle taille. Tant qu'elles sont ainsi réduites, elles infligent 1d4 dégâts de moins (avec un minimum de 1 dégât).

Le sort renforce vos alliés, qui deviennent plus robustes et plus résolus. Choisissez jusqu'à trois créatures à portée. Le maximum de points de vie et les points de vie actuels de chacune d'entre elles augmentent de 5 pendant toute la durée du sort.

**_À plus haut niveau._** Quand vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, les points de vie de chaque cible augmentent de 5 points supplémentaires pour chaque niveau au-delà du niveau 2.

Vous installez une alarme pour vous avertir en cas d'intrusion. Choisissez une porte, une fenêtre ou une zone à portée qui n'occupe pas plus d'espace qu'un cube de 6 mètres de côté. Tant que le sort fait effet, une alarme vous prévient dès qu'une créature de taille TP ou supérieure touche la zone protégée ou y pénètre. Au moment où vous lancez le sort, vous pouvez désigner des créatures qui ne déclencheront pas l'alarme. Vous pouvez aussi choisir si l'alarme sera audible ou mentale.

Une alarme mentale vous avertit d'un tintement dans votre tête tant que vous vous trouvez dans un rayon de 1,5 kilomètre autour de la zone protégée. Ce tintement suffit à vous réveiller si vous êtes endormi.

Une alarme audible émet le même son qu'une cloche d'alerte pendant 10 secondes et retentit dans un rayon de 18 mètres.

Vous demandez de l'aide à une entité appartenant à un autre monde. Vous devez connaître cet être, que ce soit un dieu, un primordial, un prince démoniaque ou une autre créature à la puissance cosmique. L'entité vous envoie un céleste, un élémentaire ou un fiélon qui lui est loyal. Cette créature apparaît dans un emplacement libre à portée. Si vous connaissez le nom d'une créature spécifique, vous pouvez le mentionner lors de l'incantation pour demander à ce que ce soit elle que l'entité vous envoie, bien qu'elle puisse tout de même vous envoyer un autre émissaire (c'est au MJ de décider).

Quand la créature apparaît, elle n'a aucune obligation de se comporter d'une manière particulière. Vous pouvez lui demander d'accomplir un service rémunéré, mais elle n'est pas obligée d'accepter. Votre requête peut être très simple (nous faire passer en volant au-dessus de ce précipice, nous aider à livrer un combat…) ou plus complexe (espionner nos ennemis, nous protéger lors de l'exploration de ce donjon…). Pour négocier un service, vous devez être en mesure de communiquer avec la créature.

Le paiement peut se faire sous diverses formes. Un céleste peut demander une importante donation en or ou en objets magiques à un temple allié, tandis qu'un fiélon peut exiger un sacrifice vivant ou un trésor. Certaines créatures monnayent leurs services contre une quête à accomplir de votre côté.

En règle générale, une tâche qui s'accomplit en quelques minutes se paie 100 po la minute. Une tâche qui demande plusieurs heures coûte 1 000 po de l'heure, et une tâche effectuée sur plusieurs jours (10 au maximum) vaut 10 000 po la journée. Le MJ peut modifier le montant en fonction des circonstances dans lesquelles vous lancez le sort. Si la tâche à accomplir s'accorde avec l'éthique de la créature, elle peut réduire son salaire de moitié ou même y renoncer.

Les tâches qui ne présentent aucun risque coûtent souvent la moitié du prix indiqué précédemment, tandis que les missions particulièrement dangereuses valent parfois bien plus cher. Une créature accepte rarement une tâche visiblement suicidaire.

Une fois que la créature a accompli la tâche demandée ou quand la durée de service décidée est arrivée à son terme, elle retourne sur son plan d'origine après vous avoir fait son rapport, si la tâche l'exige et qu'elle est en mesure de le faire.

Si vous êtes incapable de vous mettre d'accord avec la créature sur le prix de ses services, elle retourne immédiatement sur son plan natal.

Une telle créature enrôlée dans votre groupe compte comme un membre à part entière et reçoit sa part de points d'expérience.

Vous touchez une créature pour lui accorder une amélioration magique. Choisissez l'un des effets suivants, dont la cible bénéficiera jusqu'à la fin du sort.

**_Endurance de l'ours._** La cible a l'avantage lors des tests de [Constitution](hd_abilities_constitution.md). Elle gagne aussi 2d6 points de vie temporaires qui disparaissent quand le sort se termine.

**_Force du taureau._** La cible bénéficie d'un avantage lors des tests de [Force](hd_abilities_strength.md) et le poids qu'elle peut porter est doublé.

**_Grâce du chat._** La cible a l'avantage lors des tests de [Dextérité](hd_abilities_dexterity.md). De plus, elle ne subit pas de dégât quand elle chute de 6 mètres ou moins, à condition qu'elle ne soit pas [neutralisée](hd_conditions_neutralise.md).

**_Splendeur de l'aigle._** La cible bénéficie d'un avantage lors des tests de [Charisme](hd_abilities_charisma.md).

**_Ruse du renard._** La cible a l'avantage lors des tests d'[Intelligence](hd_abilities_intelligence.md).

**_Sagesse du hibou._** La cible a l'avantage lors des tests de [Sagesse](hd_abilities_wisdom.md).

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, vous pouvez prendre une créature de plus pour cible par niveau au-delà du niveau 2.

Grâce à ce sort, vous convainquez une bête que vous ne lui voulez aucun mal. Choisissez une bête située dans votre champ de vision et à portée. Elle doit vous voir et vous entendre. Le sort échoue si elle possède une [Intelligence](hd_abilities_intelligence.md) de 4 ou plus. Dans le cas contraire, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) ou être [charmée](hd_conditions_charme.md) par vous pendant toute la durée du sort. Le sort se termine si vous ou l'un de vos camarades blessez la cible.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, vous pouvez affecter une bête supplémentaire par niveau au-delà du niveau 1.

Ce sort crée un serviteur mort-vivant. Choisissez un tas d'os ou le cadavre d'un humanoïde de taille M ou P situé à portée. Votre sort imprègne la cible d'un ignoble simulacre de vie, la relevant sous forme de mort-vivant.

Elle devient un squelette si vous avez lancé le sort sur un tas d'os, et un zombi si vous avez opté pour un cadavre (le MJ dispose du profil technique de la créature).

À chacun de vos tours, vous pouvez utiliser une action bonus pour donner un ordre mental à la créature générée via ce sort si elle se trouve dans un rayon de 18 mètres autour de vous (si vous contrôlez plusieurs créatures, vous pouvez donner un ordre à l'une d'elles, certaines d'entre elles ou à toutes à la fois, à condition de transmettre le même ordre à chacune). À vous de décider quelles actions la créature va entreprendre et à quel endroit elle se déplace au cours du tour suivant, mais vous pouvez aussi lui donner un ordre plus générique, comme de garder une salle ou un couloir. En l'absence d'ordre, la créature se contente de se défendre contre les créatures hostiles. Une fois qu'elle a reçu un ordre, elle continue à le suivre jusqu'à ce qu'elle ait accompli sa tâche.

La créature est placée sous votre contrôle pendant 24 heures, après quoi elle cesse d'obéir aux ordres que vous lui avez donnés. Pour la contrôler pendant 24 heures de plus, il vous faut relancer ce sort sur elle avant la fin de la période de 24 heures pendant laquelle il fait effet. Si vous utilisez ce sort ainsi, il vous permet de réaffirmer votre contrôle sur un maximum de quatre créatures animées grâce à lui plutôt que d'en animer une nouvelle.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, vous animez ou réaffirmez votre contrôle sur deux créatures de plus par niveau au-delà du niveau 3. Chaque créature doit provenir d'un tas d'os ou d'un cadavre différent.

Les objets prennent vie sur votre ordre. Choisissez jusqu'à dix objets non magiques à portée que personne ne porte ni ne transporte. Les cibles de taille M comptent comme deux objets, celles de taille G comme quatre et celles de taille TG comme huit. Vous ne pouvez pas animer d'objet de taille supérieure. Chaque cible s'anime et devient une créature placée sous votre contrôle jusqu'à la fin du sort, ou jusqu'à tomber à 0 point de vie.

Par une action bonus, vous pouvez donner un ordre mental à toute créature créée via ce sort qui se trouve au maximum à 150 mètres de vous (si vous en contrôlez plusieurs, vous pouvez donner un ordre à l'une d'elles, certaines d'entre elles ou toutes à la fois, à condition de donner le même ordre à toutes). À vous de décider quelles actions la créature va entreprendre et à quel endroit elle se déplace au cours du tour suivant, mais vous pouvez aussi lui donner un ordre plus générique, comme de garder une salle ou un couloir. En l'absence d'ordre, la créature se contente de se défendre contre les créatures hostiles. Une fois qu'elle a reçu un ordre, elle continue à le suivre jusqu'à ce qu'elle ait accompli sa tâche.

##### Profil technique des objets animés

|Taille|PV|CA|Attaque|For|Dex|
|---|---|---|---|---|---|
|Très petite|20|18|+8 pour toucher, 1d4+4 dégâts|4|18|
|Petite|25|16|+6 pour toucher, 1d8+2 dégâts|6|14|
|Moyenne|40|13|+5 pour toucher, 2d6+1 dégâts|10|12|
|Grande|50|10|+6 pour toucher, 2d10+2 dégâts|14|10|
|Très grande|80|10|+8 pour toucher, 2d12+4 dégâts|18|6|

Un objet animé est une créature artificielle avec une CA, des points de vie, des attaques, une [Force](hd_abilities_strength.md) et une [Dextérité](hd_abilities_dexterity.md) déterminés par sa taille. Sa [Constitution](hd_abilities_constitution.md) est de 10 tandis que son [Intelligence](hd_abilities_intelligence.md) et sa [Sagesse](hd_abilities_wisdom.md) sont de 3 et son [Charisme](hd_abilities_charisma.md) de 1. Il a une vitesse de 9 mètres. S'il est dépourvu de patte ou d'appendice susceptible de lui permettre de se mouvoir, il gagne à la place la capacité de voler à une vitesse de 9 mètres et peut utiliser le vol stationnaire. Si l'objet est solidement attaché à une surface ou à un objet de plus grande taille, comme une chaîne vissée à un mur, sa vitesse est de 0. L'objet possède la vision aveugle dans un rayon de 9 mètres ; au-delà, il est aveugle.

Quand l'objet animé tombe à 0 point de vie, il reprend sa forme initiale et tout dégât en surplus est infligé à celle-ci.

Si vous ordonnez à un objet animé d'attaquer, il a droit à une attaque au corps-à-corps unique contre une créature située dans un rayon de 1,50 mètre. Il porte une attaque avec un bonus d'attaque et des dégâts contondants déterminés en fonction de sa taille. Le MJ peut tout à fait décider qu'un objet animé inflige des dégâts perforants ou tranchants si sa forme le lui permet.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, vous pouvez animer deux objets supplémentaires par emplacement au-delà du niveau 5.

Vous tentez de supprimer les émotions fortes au sein d'un groupe de gens. Chaque humanoïde qui se trouve dans une sphère de 6 mètres de rayon centrée autour d'un point de votre choix situé à portée doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md). Une créature peut décider de rater volontairement ce jet, sachant que lorsqu'une créature rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), vous l'affectez avec l'un des deux effets suivants, selon votre choix.

* Vous débarrassez temporairement la cible de tout état [charmé](hd_conditions_charme.md) ou [terrorisé](hd_conditions_terrorise.md). Une fois le sort terminé, l'état s'applique de nouveau, à moins que sa durée n'ait expiré.

* Vous rendez la cible indifférente vis-à-vis des créatures de votre choix, envers lesquelles elle était auparavant hostile. Cette indifférence prend fin si la cible est attaquée ou affectée par un sort néfaste, ou bien si elle voit l'un de ses amis être ainsi agressé. La cible redevient hostile dès que le sort se termine, à moins que le MJ n'en décide autrement.

Ce sort vous permet de modifier l'apparence d'autant de créatures que vous voulez, à condition qu'elles se trouvent à portée et dans votre champ de vision. Vous donnez à chacune d'entre elles une nouvelle apparence illusoire.

Une cible non consentante peut faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md). Si elle le réussit, le sort ne l'affecte pas.

Ce sort change l'apparence physique, mais aussi les vêtements, les armures, les armes et le reste de l'équipement.

Vous pouvez faire croire que chaque créature affectée est plus petite ou plus grande de 30 centimètres maximum qu'en réalité, lui donner l'air grosse, maigre ou de corpulence normale. Vous ne pouvez pas changer le type de son corps, et vous devez choisir une forme possédant la même conformation qu'elle au niveau des membres. En dehors de cela, les détails de l'illusion sont laissés à votre imagination. Le sort persiste pendant toute sa durée ou jusqu'à ce que vous utilisiez une action pour le révoquer.

Les changements apportés par le sort ne résistent pas à un examen physique. Par exemple, si vous l'utilisez pour ajouter un chapeau à la tenue de la cible, les objets passent au travers et toute personne qui essaie de le toucher ne sentira que de l'air ou des cheveux et un crâne. Si vous utilisez le sort pour la faire paraître plus mince qu'en réalité, la main de quelqu'un qui tente de la toucher se heurtera à son corps alors que, visuellement, elle semble encore dans le vide.

Une créature peut utiliser son action pour examiner une cible et faire un test d'[Intelligence (Investigation)](hd_abilities_intelligence_investigation.md) contre le DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) du sort. Si elle le réussit, elle comprend que la cible est déguisée.

Vous vous attachez les services d'un familier, un esprit qui prend la forme d'un animal de votre choix : une chauve-souris, un chat, un crabe, une grenouille (ou un crapaud), un faucon, un lézard, une pieuvre, une chouette, un serpent venimeux, un poisson (un piranha), un rat, un corbeau, un hippocampe, une araignée ou une belette. Le familier apparaît dans un emplacement inoccupé à portée et possède le même profil technique que l'animal dont il revêt la forme, bien qu'il soit un céleste, une fée ou un fiélon (à vous de choisir) au lieu d'une bête.

Votre familier agit indépendamment de vous, mais il obéit toujours à vos ordres. Lors d'un combat, il lance son propre dé d'initiative et agit à son tour. Il ne peut pas attaquer, mais il peut effectuer d'autres actions.

Quand le familier tombe à 0 point de vie, il disparaît sans laisser de cadavre derrière lui. Il réapparaît si vous lancez de nouveau ce sort.

Vous pouvez communiquer par télépathie avec votre familier tant qu'il se trouve dans un rayon de 30 mètres autour de vous. De plus, vous pouvez dépenser votre action pour percevoir le monde par les yeux et les oreilles de votre familier jusqu'au début de votre prochain tour. Pendant ce temps, vos yeux et vos oreilles ne fonctionnent plus.

Vous pouvez renvoyer temporairement votre familier en utilisant une action. Il gagne alors une poche dimensionnelle où il attend que vous le rappeliez. Vous pouvez aussi le renvoyer définitivement. Vous pouvez utiliser une action alors qu'il est temporairement renvoyé pour le faire réapparaître dans un emplacement inoccupé situé dans un rayon de 9 mètres autour de vous.

Vous ne pouvez avoir qu'un seul familier à la fois. Si vous lancez ce sort alors que vous avez déjà un familier, vous attribuez simplement une nouvelle forme à celui que vous possédez déjà : choisissez une des formes de la liste précédente, que votre familier adopte immédiatement.

Enfin, quand vous lancez un sort avec une portée de « contact », votre familier peut livrer le sort comme si c'était lui qui le lançait. Il doit se trouver à 30 mètres ou moins de vous et utiliser sa réaction pour transmettre le sort au moment où vous le lancez. Si le sort exige un jet d'attaque, vous utilisez votre propre modificateur d'attaque lors du jet.

Un nuage orageux apparaît sous forme d'un cylindre de 3 mètres de haut pour 18 mètres de rayon, centré sur un point situé dans votre champ de vision et à 30 mètres directement au-dessus de vous. Le sort échoue si vous ne pouvez voir le point situé à cette hauteur, là où le nuage doit se former (si vous vous trouvez dans une pièce trop petite pour accueillir le nuage, par exemple).

Quand vous lancez le sort, vous devez choisir un point situé à portée et dans votre champ de vision. Un éclair jaillit du nuage et vient frapper ce point. Chaque créature située dans un rayon de 1,50 mètre autour de ce point doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Celles qui échouent subissent 3d10 dégâts de foudre, les autres la moitié seulement. À chacun de vos tours jusqu'à la fin du sort, vous pouvez dépenser votre action pour appeler ainsi la foudre, en visant le même point ou un autre.

Si, au moment de l'incantation, vous vous trouvez en extérieur et que les conditions sont déjà orageuses, le sort vous donne le contrôle de l'orage déjà présent au lieu d'en créer un nouveau. Dans ce cas, les dégâts du sort augmentent de 1d10.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, les dégâts augmentent de 1d10 par niveau au-delà du niveau 3.

Vous enchantez votre arc (ou votre arbalète). Pendant 1 minute, à chaque fois que vous l'armez, une flèche (ou un carreau) magique apparaît encochée sur sa corde.

Personne d'autre que vous ne peut l'utiliser et, si vous relâchez la corde sans tirer, la flèche disparaît simplement.

Ces projectiles sont magiques et infligent 1d6 dégâts supplémentaires. De plus, vous pouvez utiliser une action bonus afin d'effectuer une attaque à distance supplémentaire avec l'arc (ou l'arbalète).

Vous touchez une arme non magique. Jusqu'à la fin du sort, elle devient magique et bénéficie d'un bonus de +1 aux jets d'attaque et de dégâts.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, le bonus passe à +2, et à +3 si vous utilisez un emplacement de niveau 6 ou plus.

Vous brandissez votre arme et l'investissez du pouvoir de combattre le mal. Jusqu'à la fin du sort, l'arme est considérée comme étant une arme magique. Lorsque vous attaquez un mort-vivant ou un fiélon avec cette arme, vous bénéficiez d'un avantage à vos jets d'attaque et vous infligez 1d8 dégâts radiants supplémentaires.

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de sort de niveau 5 ou supérieur, le bonus de dégâts passe à 2d8.

Vous créez à portée une arme spectrale flottante qui persiste pendant toute la durée du sort ou jusqu'à ce que vous le lanciez de nouveau. Lors de l'incantation, vous pouvez faire une attaque de sort au corps-à-corps contre une créature située dans un rayon de 1,50 mètre autour de l'arme.

L'attaque inflige des dégâts de force égaux à 1d8 + votre modificateur de caractéristique d'incantation.

À votre tour et au prix d'une action bonus, vous pouvez déplacer l'arme d'un maximum de 6 mètres et répéter l'attaque contre une créature située dans un rayon de 1,50 mètre autour d'elle.

L'arme peut revêtir la forme de votre choix. Les clercs des divinités associées à une arme particulière (tel Thor et son marteau) font en sorte que l'arme générée ressemble à l'arme iconique de leur protecteur.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, les dégâts augmentent de 1d8 tous les 2 niveaux au-delà du niveau 2.

Vous touchez une créature consentante qui ne porte pas d'armure et l'enveloppez d'une force magique protectrice jusqu'à la fin du sort. La CA de base de la cible passe à 13 + son modificateur de [Dextérité](hd_abilities_dexterity.md). Le sort se termine si la cible revêt une armure ou si vous révoquez le sort par une action.

Vous arrêtez brièvement le cours du temps pour tout le monde sauf vous. Le temps ne s'écoule plus pour les autres créatures, tandis que vous disposez de 1d4+1 tours d'affilée, pendant lesquels vous pouvez faire des actions et vous déplacer normalement.

Ce sort se termine si l'une des actions que vous effectuez lors de ce laps de temps ou l'un des effets que vous créez lors de ce laps de temps affecte une créature autre que vous ou un objet porté ou transporté par une créature autre que vous. Le sort se termine également si vous vous éloignez à plus de 300 mètres de l'endroit où vous l'avez lancé.

Vous lancez une boule d'acide. Choisissez une créature à portée, ou deux créatures à portée situées à 1,50 mètre ou moins l'une de l'autre. Une cible doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md), sinon elle subit 1d6 dégâts d'acide.

Les dégâts du sort augmentent de 1d6 quand vous atteignez le niveau 5 (2d6), 11 (3d6) et 17 (4d6).

Vous puisez dans les cauchemars d'une créature située à portée et dans votre champ de vision afin de créer une manifestation illusoire de ses pires terreurs, qu'elle est la seule à voir. La cible doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md). Si elle le rate, elle est [terrorisée](hd_conditions_terrorise.md) pendant toute la durée du sort.

Tant que le sort n'est pas terminé, la cible doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) à la fin de chacun de ses tours.

Elle subit 4d10 dégâts psychiques à chaque échec. Le sort se termine dès qu'elle réussit un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md).

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 5 ou supérieur, les dégâts augmentent de 1d10 par niveau au-delà du niveau 4.

Vous touchez une créature consentante. Une fois avant la fin du sort, la cible peut lancer 1d4 et ajouter le résultat obtenu au test de caractéristique de son choix. Elle peut lancer le dé avant ou après le test. Le sort se termine alors.

Vous lancez des bâtonnets ornés de gemmes ou des os de dragon, tirez des lames de tarot ornementées ou utilisez une autre méthode de divination pour recevoir un présage de la part d'une entité d'un autre monde. Ce présage concerne les résultats de la conduite que vous comptez tenir dans les 30 prochaines minutes. C'est au MJ de choisir l'un des présages suivants :

* Bonheur pour un résultat positif

* Malheur pour un résultat négatif

* Bonheur et malheur pour un résultat comportant du positif et du négatif

* Rien pour un résultat n'étant ni positif ni négatif

Le sort ne tient pas compte d'une éventuelle modification des circonstances, comme l'incantation de sorts supplémentaires, ou la perte ou l'arrivée d'un compagnon.

Si vous lancez ce sort à deux reprises ou plus avant un long repos, il y a 25 % de chances par incantation en sus de la première que vous obteniez une prémonition aléatoire au lieu d'une prémonition fiable. C'est au MJ de faire ce jet en secret.

Vous désignez jusqu'à cinq créatures à portée que vous pouvez voir. Vous et les cibles du sort acquérez la résistance aux dégâts d'acide, de foudre, de feu, de froid et nécrotiques pendant toute la durée du sort. Les créatures ciblées et vous-même bénéficiez également d'un avantage à tous les tests et les [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md).

Une aura captivante émane de vous dans un rayon de 1,50 mètre. Vous bénéficiez d'un avantage à tous vos tests de [Charisme](hd_abilities_charisma.md) visant les créatures situées dans l'aura. À la fin du sort, les créatures qui en ont subi l'influence peuvent faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) d'[Intelligence](hd_abilities_intelligence.md). En cas de réussite, elles se rendent compte avoir été influencées par magie et elles peuvent, à la discrétion du MJ, en concevoir de l'hostilité.

Le rayon d'action de ce sort double lorsque vous atteignez le niveau 5 (3 mètres), puis le niveau 11 (6 mètres) et enfin au niveau 17 (12 mètres).

Vous enveloppez la créature ou l'objet touché d'une illusion, afin que les sorts de divination révèlent des informations erronées à son propos. La cible du sort doit être une créature consentante ou un objet qui n'est ni porté ni transporté par une autre créature.

Lorsque vous lancez le sort, vous choisissez l'un des effets suivants, ou les deux, qui persistent pendant toute la durée du sort. Si vous lancez ce sort sur la même créature ou le même objet chaque jour pendant 30 jours, en lui attribuant le même effet à chaque fois, l'illusion persiste jusqu'à ce que quelqu'un la dissipe.

**_Aura factice._** Vous modifiez la manière dont la cible apparaît vis-à-vis des sorts et effets magiques détectant les auras magiques, comme _[détection de la magie](hd_spells_detection_de_la_magie.md)_. Vous pouvez ainsi faire en sorte qu'un objet magique paraisse dépourvu de magie ou qu'un objet ordinaire semble magique. Vous pouvez aussi modifier l'aura magique de la cible de manière à ce qu'elle paraisse appartenir à l'école de magie de votre choix. Quand vous conférez cet effet à un objet, vous pouvez faire en sorte que la magie factice se manifeste à toute personne qui manipule l'objet.

**_Masque._** Vous modifiez la manière dont la cible apparaît aux sorts et effets magiques qui détectent les types de créatures, comme le sens divin d'un paladin ou le déclencheur d'un sort de [symbole](hd_spells_symbole.md). Vous choisissez un type de créatures : les autres sorts et effets magiques traitent la cible comme si elle appartenait au type ou à l'alignement choisi.

Une lumière divine émane de votre personne dans un rayon de 9 mètres et forme un doux halo qui vous enveloppe.

Les créatures de votre choix qui se trouvent dans cette zone au moment où vous lancez ce sort émettent une faible lumière dans un rayon de 1,50 mètre. De plus, jusqu'à la fin du sort, elles ont l'avantage lors des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) tandis que les autres créatures subissent un désavantage quand elles effectuent un jet d'attaque contre elles. Quand un fiélon ou un mort-vivant touche une créature affectée avec une attaque au corps-à-corps, l'aura qui enveloppe la créature flamboie soudain. L'assaillant doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) ou se retrouver [aveuglé](hd_conditions_aveugle.md) jusqu'à la fin du sort.

Jusqu'à la fin du sort, chaque fois que vous effectuez un test de [Charisme](hd_abilities_charisma.md), vous pouvez remplacer le nombre obtenu au dé par un 15. De plus, quoi que vous disiez, la magie visant à déterminer si vous dites la vérité vous identifie toujours comme sincère.

Un maximum de dix baies apparaissent dans votre main. Elles sont imprégnées de magie pendant une journée.

Une créature peut utiliser son action pour manger une baie, ce qui lui rend 1 point de vie et la nourrit pour la journée.

Les baies perdent leurs propriétés si personne ne les mange dans les 24 heures qui suivent l'incantation.

Un rayon de lumière frappe une créature de votre choix située à portée. Faites un jet d'attaque de sort à distance contre elle. Si vous le réussissez, elle subit 4d6 dégâts radiants et scintille d'une faible lumière mystique jusqu'à la fin de votre prochain tour. D'ici là et grâce à cette lueur, le prochain jet d'attaque effectué contre elle bénéficie d'un avantage.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, les dégâts augmentent de 1d6 par niveau au-delà du niveau 1.

Vous tentez d'envoyer une créature située dans votre champ de vision dans un autre plan d'existence. Elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md) ou être bannie.

Si la cible est native du plan d'existence sur lequel vous vous trouvez, vous l'exilez dans un demi-plan inoffensif.

Elle est [neutralisée](hd_conditions_neutralise.md) tant qu'elle se trouve là-bas et y reste jusqu'à la fin du sort. À ce moment, elle réapparaît à l'endroit qu'elle a quitté, ou dans l'emplacement inoccupé le plus proche si son emplacement de départ est occupé.

Si la cible est originaire d'un plan d'existence autre que celui sur lequel vous vous trouvez, une légère détonation accompagne son retour contraint sur son plan d'origine.

Si le sort se termine avant que 1 minute ne se soit écoulée, la cible réapparaît à l'endroit qu'elle a quitté, ou dans l'emplacement inoccupé le plus proche si son emplacement de départ est occupé. Sinon, elle ne revient pas.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 5 ou supérieur, vous pouvez viser une créature de plus par niveau au-delà du niveau 4.

Vous créez un mur vertical constitué de lames tournoyantes faites d'énergie magique et tranchantes comme des rasoirs. Le mur apparaît à portée et persiste pour toute la durée du sort. Vous pouvez créer un mur droit d'un maximum de 30 mètres de long, 6 mètres de haut et 1,50 mètre d'épaisseur, ou un mur circulaire d'un maximum de 18 mètres de diamètre, 6 mètres de haut et 1,50 mètre d'épaisseur. Le mur offre un abri important aux créatures qui se trouvent derrière lui, et son espace est traité comme un terrain difficile.

Quand une créature pénètre dans la zone du mur pour la première fois au cours de son tour ou quand elle commence son tour dans cette zone, elle doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Si elle le rate, elle subit 6d10 dégâts tranchants ; si elle le réussit, elle en subit seulement la moitié.

Vous bénissez jusqu'à trois créatures de votre choix situées à portée. Quand une cible fait un jet d'attaque ou de sauvegarde avant la fin du sort, elle lance 1d4 et ajoute le résultat obtenu au jet d'attaque ou de sauvegarde.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, vous pouvez affecter une créature de plus par niveau au-delà du niveau 1.

Vous désignez jusqu'à 5 créatures à portée et que vous pouvez voir. Les cibles et vous-même bénéficiez d'un avantage au jet d'attaque sur la première attaque de chacun de vos tours pour toute la durée du sort.

Faites une attaque de sort au corps-à-corps contre une créature située à une distance inférieure ou égale à votre allonge. Si vous la touchez, elle subit 3d10 dégâts nécrotiques.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, les dégâts augmentent de 1d10 par niveau au-delà du niveau 1.

Vous implantez un message dans un objet situé à portée.

On entend le message dès que les conditions qui le déclenchent sont remplies. Choisissez un objet situé dans votre champ de vision qui n'est ni porté ni transporté par une autre créature. Prononcez ensuite le message, qui doit comprendre au maximum vingt-cinq mots, mais peut se répéter pendant un maximum de 10 minutes. Enfin, déterminez les circonstances dans lesquelles le message s'active.

Quand les conditions de déclenchement sont remplies, une bouche magique apparaît sur l'objet et énonce le message avec la même voix que vous et au volume où vous l'avez prononcé. Si l'objet choisi possède une bouche ou quelque chose qui y ressemble (comme la bouche d'une statue), la bouche magique apparaît de manière à donner l'impression que les paroles sortent des lèvres figurées sur l'objet. Lors de l'incantation, vous pouvez décider que le sort se termine une fois le message transmis ou qu'il reste actif et répète le message chaque fois que les conditions de déclenchement sont remplies.

Ces dernières peuvent être aussi génériques ou spécifiques que vous le désirez, mais elles doivent se baser sur des données visuelles ou audibles, perceptibles dans un rayon de 9 mètres autour de l'objet. Par exemple, vous pouvez ordonner à la bouche de parler dès qu'une créature approche à 9 mètres ou moins de l'objet ou quand une cloche d'argent retentit dans un rayon de 9 mètres.

Une barrière [invisible](hd_conditions_invisible.md) faite de force magique apparaît autour de vous et vous protège. Jusqu'au début de votre prochain tour, vous obtenez un bonus de +5 à la CA, y compris contre l'attaque qui a déclenché l'incantation du sort, et vous ne subissez aucun dégât de la part du sort _[projectile magique](hd_spells_projectile_magique.md)_.

De fines volutes de flammes enveloppent votre corps pendant toute la durée du sort, émettant une lumière vive dans un rayon de 3 mètres et une lumière faible dans un rayon additionnel de 3 mètres. Vous pouvez mettre prématurément un terme au sort en utilisant une action.

Les flammes vous offrent un bouclier chaud ou froid, comme bon vous semble. Le bouclier chaud vous apporte une résistance contre les dégâts de froid, le bouclier froid une résistance contre les dégâts de feu.

De plus, quand une créature située dans un rayon de 1,50 mètre autour de vous vous touche avec une attaque au corps-à-corps, le bouclier génère une gerbe de flammes. Si le bouclier est chaud, il inflige 2d8 dégâts de feu à l'assaillant, s'il est froid, il lui inflige 2d8 dégâts de froid.

Un champ scintillant apparaît autour d'une créature de votre choix située à portée et lui confère un bonus de +2 à la CA pendant toute la durée du sort.

Vous tendez la main en direction d'une créature située à portée et dans votre champ de vision et projetez une bouffée de gaz toxique sortie de votre paume. La créature doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) ou subir 1d12 dégâts de poison.

Les dégâts du sort augmentent de 1d12 quand vous atteignez le niveau 5 (2d12), 11 (3d12) et 17 (4d12).

Une traînée luisante part de votre doigt tendu et file vers un point de votre choix situé à portée et dans votre champ de vision, où elle explose dans une gerbe de flammes grondantes. Chaque créature située dans une sphère de 6 mètres de rayon centrée sur ce point doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Celles qui échouent subissent 8d6 dégâts de feu, les autres la moitié seulement.

Le feu s'étend en contournant les angles. Il embrase les objets inflammables de la zone, à moins que quelqu'un ne les porte ou ne les transporte.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, les dégâts augmentent de 1d6 par niveau au-delà du niveau 3.

Un rayon de lumière jaune jaillit de votre doigt tendu et se condense pour former une bille luisante en un point de votre choix situé à portée pendant toute la durée du sort. Quand le sort se termine, soit parce que votre concentration se brise, soit parce que vous y mettez volontairement un terme, la bille se dilate dans un grondement sourd et explose en une gerbe de feu qui s'étend en franchissant les angles éventuels. Toutes les créatures situées dans une sphère de 6 mètres de rayon centrée sur le point où se trouvait la bille doivent faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Celles qui échouent subissent un montant de dégâts de feu égal au total de dégâts accumulés (voir plus loin), les autres la moitié seulement.

À la base, le sort inflige 12d6 dégâts de feu. À la fin de votre tour, si la bille n'a pas encore explosé, ces dégâts augmentent de 1d6.

Si quelqu'un touche la bille avant la fin de l'intervalle, il doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md).

S'il échoue, le sort se termine immédiatement et la bille explose. S'il réussit, il peut lancer la bille à une distance maximale de 12 mètres. Si elle touche un objet solide ou une créature, le sort se termine et la bille explose.

Les flammes endommagent les objets qui se trouvent dans la zone et embrasent les objets inflammables qui ne sont ni portés ni transportés.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 8 ou supérieur, les dégâts de base augmentent de 1d6 par niveau au-delà du niveau 7.

Une zone de fort vent de 18 mètres de long sur 3 mètres de large souffle depuis votre position dans la direction de votre choix pendant toute la durée du sort. Chaque créature qui débute son tour dans la zone doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md), sans quoi elle est rejetée de 4,50 mètres à l'opposé de vous, dans la direction du vent.

Une créature qui se trouve dans la zone doit dépenser 60 centimètres de mouvement pour se rapprocher de vous de 30 centimètres.

La bourrasque disperse les gaz et les vapeurs et éteint les bougies, les torches et autres flammes nues similaires dans la zone. Les flammes protégées, par une lanterne par exemple, s'agitent follement et ont 50 % de chance de s'éteindre.

Vous pouvez changer la direction dans laquelle souffle la bourrasque au moyen d'une action bonus à chacun de vos tours jusqu'à la fin du sort.

Un bruit retentit soudain avec une intensité douloureuse, à partir d'un point situé à portée. Chaque créature située dans une sphère de 3 mètres de rayon centrée sur ce point doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md).

Les créatures qui le ratent subissent 3d8 dégâts de tonnerre, les autres la moitié seulement. Une créature faite de matière inorganique, comme de la pierre, du cristal ou du métal subit un désavantage sur ce [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md).

Un objet non magique que personne ne porte ni ne transporte subit aussi ces dégâts s'il se trouve dans la zone du sort.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, les dégâts augmentent de 1d8 par niveau au-delà du niveau 2.

Votre arme se met à briller d'une lumière intense de pure radiance. Elle émet une lumière vive dans un rayon de 4,50 mètres et une lumière faible sur 4,50 mètres supplémentaires.

La lumière est semblable à la lumière du soleil.

À chaque fois que vous blessez une créature avec cette arme pendant la durée du sort, elle émet un violent flash lumineux qui inflige 1d6 dégâts radiants à tous vos adversaires dans un rayon de 1,50 mètre autour de vous et double momentanément le rayon d'illumination de l'arme. Les créatures affectées peuvent faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) pour ignorer les dégâts.

Les morts-vivants subissent 2d6 points de dégâts et la moitié seulement en cas de [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) réussi.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de sort de niveau 2 ou supérieur, les dégâts augmentent de 1d6 pour chaque niveau au-delà du niveau 1.

Une prison immobile et [invisible](hd_conditions_invisible.md), en forme de cube et faite de force magique, se forme soudain autour d'une zone de votre choix située à portée. Ce peut être une cage ou une boîte hermétique, à votre guise.

* Une prison en forme de cage peut faire un maximum de 6 mètres d'arête et dispose de barreaux de 1 centimètre d'épaisseur placés à 1 centimètre d'intervalle.

* Une prison en forme de boîte peut faire un maximum de 3 mètres d'arête et forme une barrière pleine qui empêche la matière de passer. Elle bloque aussi le passage des sorts lancés vers l'intérieur ou l'extérieur.

Quand vous lancez ce sort, chaque créature qui se trouve entièrement au sein de la zone affectée se retrouve prise au piège. Une créature qui s'y trouve seulement en partie ou qui s'avère trop grande pour y tenir est expulsée vers l'extérieur de la zone jusqu'à ce qu'elle la quitte complètement.

Une créature enfermée dans la cage ne peut pas la quitter par des moyens non-magiques. Si elle tente d'utiliser la téléportation ou les déplacements interplanaires pour s'échapper, elle doit d'abord effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md). Si elle le réussit, elle peut utiliser cette magie pour fuir, sinon elle ne parvient pas à quitter la cage, et l'utilisation du sort ou de l'effet est gaspillée. La cage s'étend aussi sur le plan éthéré, ce qui bloque les déplacements éthérés.

La _[dissipation de la magie](hd_spells_dissipation_de_la_magie.md)_ est sans effet sur ce sort.

Le simple contact de votre main enveloppée d'ombres peut siphonner la force vitale d'autrui pour soigner vos propres plaies. Faites une attaque de sort au corps-àcorps contre une créature située à une distance inférieure ou égale à votre allonge. Si vous touchez, elle subit 3d6 dégâts nécrotiques et vous récupérez un total de points de vie égal à la moitié des dégâts infligés. Vous pouvez dépenser votre action à chacun de vos tours pour répéter cette attaque jusqu'à la fin du sort.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, les dégâts augmentent de 1d6 par niveau au-delà du niveau 3.

Vous placez une créature vivante consentante en état cataleptique qu'il est impossible de distinguer d'un véritable état de mort par des moyens normaux.

Le sujet est [aveuglé](hd_conditions_aveugle.md) et [inconscient](hd_conditions_inconscient.md), incapable de bouger.

Il ne ressent aucune blessure ou autre mauvais traitement et aucune réaction corporelle ne se produit, comme si le sujet était réellement mort. Toutefois, les dégâts sont encaissés normalement. Si la cible était malade ou [empoisonnée](hd_conditions_empoisonne.md) au moment de l'incantation, ou si un poison est introduit dans son corps durant l'action du sort, le poison est retardé pour la durée du sort. Le poison ou la maladie fera à nouveau pleinement effet à la fin du sort.

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de sort de niveau supérieur, sa durée augmente et le sort s'apparente alors à une longue hibernation (la cible ne vieillit plus pendant cette période) : un jour au niveau 4, une semaine au niveau 5, un mois au niveau 6, un an au niveau 7, dix ans au niveau 8 et enfin jusqu'à un siècle au niveau 9. Lorsqu'elle sort de catalepsie, la cible subit un niveau d'épuisement par niveau du sort au-delà du niveau 3 (jusqu'à un maximum de 5).

Au niveau 9, la cible doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de constitution difficulté 8 + 1 tous les dix ans écoulés lorsqu'elle sort du sommeil, ou mourir immédiatement.

Vous pouvez rendre un ennemi sourd ou aveugle.

Choisissez une créature autre que vous qui se situe à portée et dans votre champ de vision. Elle doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). Si elle échoue, elle est soit [aveuglée](hd_conditions_aveugle.md), soit [assourdie](hd_conditions_assourdi.md) (à vous de choisir) pendant toute la durée du sort. Elle a droit à un nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) à la fin de chacun de ses tours, le sort se terminant si elle le réussit.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, vous pouvez viser une créature de plus par niveau au-delà du niveau 2.

Une sphère d'énergie négative s'étend dans un rayon de 18 mètres à partir d'un point situé à portée. Chaque créature située dans la sphère doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). Celles qui échouent subissent 8d6 dégâts nécrotiques, les autres la moitié seulement.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, les dégâts augmentent de 2d6 par niveau au-delà du niveau 6.

Lorsque vous lancez ce sort, vous tracez un cercle de 3 mètres de diamètre au sol et y inscrivez des symboles qui relient l'endroit où vous vous trouvez actuellement à un cercle de téléportation permanent de votre choix dont vous connaissez la séquence de symboles et qui se trouve sur le même plan d'existence que vous. Un portail scintillant s'ouvre dans le cercle que vous avez tracé et reste ouvert jusqu'à la fin de votre prochain tour.

Toute créature qui franchit ce portail apparaît instantanément dans un rayon de 1,50 mètre autour du cercle de destination ou dans l'espace inoccupé le plus proche si le reste est occupé.

Nombre de temples majeurs, de guildes et d'autres lieux d'importance possèdent des cercles de téléportation permanents tracés quelque part dans leur enceinte.

Chacun de ces cercles utilise une séquence de symboles uniques : une série de runes magiques disposées selon un motif particulier. Lorsque vous apprenez à lancer ce sort, vous apprenez la séquence associée à deux destinations situées sur le plan matériel et déterminées par le MJ. Vous pouvez apprendre d'autres séquences de symboles au cours de vos aventures. Pour en mémoriser une, vous devez l'étudier pendant 1 minute.

Vous pouvez créer un cercle de téléportation permanent en lançant ce sort au même endroit tous les jours pendant un an. Vous n'avez pas besoin d'utiliser le cercle pour vous téléporter quand vous lancez ce sort pour cela.

Vous créez un cylindre d'énergie magique de 3 mètres de rayon pour 6 mètres de haut, centré sur un point au sol situé à portée et dans votre champ de vision. Des runes luisantes apparaissent là où le cylindre touche le sol ou une autre surface.

Choisissez l'un des types de créatures suivants : célestes, élémentaires, fées, fiélons ou morts-vivants. Le cercle affecte une créature du type choisi de la manière suivante :

* La créature ne peut pas entrer de son plein gré dans le cylindre par des moyens non magiques.

Si elle tente d'utiliser la téléportation ou le voyage extraplanaire pour y pénétrer, elle doit auparavant réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md).

* La créature subit un désavantage lors des jets d'attaque contre les créatures se trouvant dans le cylindre.

* Les créatures situées dans le cylindre ne peuvent pas être [charmées](hd_conditions_charme.md), [terrorisées](hd_conditions_terrorise.md) ou possédées par la créature.

Quand vous lancez ce sort, vous pouvez décider que sa magie agira à l'envers, empêchant les créatures du type choisi de quitter le cercle et protégeant contre elles les individus situés à l'extérieur.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, la durée du sort augmente d'une heure par niveau au-delà du niveau 3.

Vous créez un arc électrique qui file vers une cible de votre choix, située à portée et dans votre champ de vision.

Trois éclairs bondissent ensuite de cette cible sur un maximum de trois autres cibles qui doivent toutes se trouver dans un rayon de 9 mètres autour de la première.

Une cible peut être une créature ou un objet et ne peut recevoir qu'un seul éclair.

Chaque cible doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md) et subit 10d8 dégâts de foudre en cas d'échec, la moitié en cas de réussite.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, un éclair de plus rebondit de la première cible vers une autre pour chaque niveau au-delà du niveau 6.

Une sphère d'antimagie [invisible](hd_conditions_invisible.md) de 3 mètres de rayon vous entoure. La zone qu'elle englobe est coupée de l'énergie magique qui imprègne le multivers. En son sein, il est impossible de lancer un sort, les créatures invoquées disparaissent et même les objets magiques deviennent ordinaires. La sphère reste centrée sur vous et se déplace avec vous jusqu'à la fin du sort.

Les sorts et autres effets magiques, en dehors de ceux émanant d'un artefact ou d'une divinité, sont supprimés au sein de la sphère et ne peuvent pénétrer son espace. Un emplacement utilisé pour lancer un sort ainsi supprimé est tout de même consommé. L'effet ne fonctionne pas tant qu'il est supprimé, mais le temps passé sous suppression est tout de même décompté de sa durée d'efficacité.

**_Effets visant une cible._** Les sorts et autres effets magiques visant une créature ou un objet situé dans la sphère, comme _[projectile magique](hd_spells_projectile_magique.md)_ ou _[charme-personne](hd_spells_charme_personne.md)_, n'ont aucun effet sur cette cible.

**_Zones de magie._** La zone d'effet d'un sort ou d'un effet magique, comme celle d'une _[boule de feu](hd_spells_boule_de_feu.md)_, ne peut pas s'étendre au sein de la sphère. Si la sphère recouvre une zone de magie existante, l'effet de cette dernière est supprimé dans la partie recouverte par la sphère. Par exemple, les flammes d'un _[mur de feu](hd_spells_mur_de_feu.md)_ sont supprimées au sein de la sphère, créant un trou dans le mur si la partie recouverte est assez grande.

**_Sorts._** Tout sort ou effet magique actif sur une créature ou un objet est supprimé dès qu'elle ou il se trouve à l'intérieur et pendant tout le temps qu'elle ou il y reste.

**_Objets magiques._** Les propriétés et les pouvoirs d'un objet magique sont supprimés une fois au sein de la sphère. Par exemple, une épée longue +1 située dans la sphère fonctionne comme une épée longue ordinaire.

Les propriétés et les pouvoirs d'une arme magique sont supprimés si son utilisateur la manie contre une cible située dans la sphère ou s'il se trouve dans la sphère. Si une arme ou une munition magique quitte entièrement la sphère (par exemple, si vous tirez une flèche magique ou projetez une lance magique en dehors de la sphère), la suppression de magie cesse d'affecter l'objet dès qu'il quitte la sphère.

**_Déplacement magique._** La téléportation et les voyages planaires échouent systématiquement au sein de la sphère, que cette dernière serve de destination ou de point de départ à ce type de déplacement. Un portail menant en un autre lieu, sur un autre monde ou sur un autre plan d'existence se ferme temporairement tant qu'il est englobé dans la sphère, de même que l'ouverture sur un espace extradimensionnel telle celle créée par le sort corde enchantée.

**_Créatures et objets._** Une créature ou un objet invoqués ou créés par magie disparaissent temporairement si la sphère les recouvre. Ils réapparaissent instantanément dès que l'espace qu'ils occupent ne se trouve plus au sein de la sphère.

**_Dissipation de la magie._** Les sorts et les effets magiques comme _[dissipation de la magie](hd_spells_dissipation_de_la_magie.md)_ n'ont aucun effet sur la sphère. De même, les sphères issues de divers sorts de _[champ antimagie](hd_spells_champ_antimagie.md)_ ne s'annulent pas les unes les autres.

Vous prenez la forme d'une créature différente pendant toute la durée du sort. Vous pouvez revêtir l'apparence de n'importe quelle créature dotée d'un indice de dangerosité inférieur ou égal à votre niveau. En revanche, vous ne pouvez pas vous changer en une créature artificielle ni en mort-vivant, et vous devez avoir vu au moins une fois la créature que vous imitez. Vous vous changez en un spécimen ordinaire de cette créature, sans niveau de classe et sans l'aptitude incantations.

Votre profil technique est remplacé par celui de la créature choisie, mais vous conservez votre alignement et vos valeurs d'[Intelligence](hd_abilities_intelligence.md), de [Sagesse](hd_abilities_wisdom.md) et de [Charisme](hd_abilities_charisma.md).

Vous conservez également vos compétences et vos maîtrises de [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), en plus de gagner celles de la créature. Si elle possède les mêmes maîtrises que vous, mais que son bonus est plus élevé, utilisez-le à la place du vôtre. Vous ne pouvez pas utiliser les actions d'antre ni les actions légendaires de la créature.

Vous adoptez les dés de vie et les points de vie de votre nouvelle forme. Quand vous reprenez votre forme initiale, vous revenez au nombre de points de vie qui était le vôtre avant de vous transformer. Si vous reprenez votre forme initiale parce que vous êtes tombé à 0 point de vie, les dégâts en surplus sont déduits de vos points de vie normaux.

Tant que ces dégâts ne font pas tomber les points de vie de votre forme initiale à 0, vous n'êtes pas [inconscient](hd_conditions_inconscient.md).

Vous conservez vos aptitudes de race, de classe et autre, et vous êtes toujours en mesure de les utiliser, à condition que votre nouvelle forme soit physiquement capable de le faire. Vous ne pouvez pas utiliser vos sens spéciaux (comme la vision dans le noir), à moins que votre nouvelle forme n'en soit aussi dotée. Vous pouvez parler uniquement si votre nouvelle forme en est normalement capable.

Quand vous vous transformez, vous choisissez si votre équipement tombe au sol, s'il fusionne avec votre nouvelle forme ou si cette nouvelle forme le porte sur elle, auquel cas il fonctionne normalement. C'est au MJ de déterminer si la nouvelle forme peut porter une pièce d'équipement, en fonction de sa taille et de sa morphologie. Votre équipement ne change pas de forme ni de taille pour s'accorder à votre nouvelle forme ; si cette dernière ne peut s'en accommoder, l'équipement ou certaines pièces d'équipement tombent au sol ou fusionnent avec votre nouvelle silhouette. L'équipement fusionné ne génère aucun effet.

Pendant la durée du sort, vous pouvez utiliser votre action pour prendre une nouvelle forme répondant aux mêmes critères et aux mêmes règles que précédemment, à une exception : si votre nouvelle forme possède plus de points de vie que la précédente, votre nombre de points de vie reste tel qu'il était.

Vous et un maximum de huit autres créatures consentantes vous donnez la main pour former un cercle, et êtes transportés sur un autre plan d'existence. Vous pouvez spécifier une destination en termes génériques, comme le nom d'une cité, d'une région ou d'un endroit spécifique dans l'un des plans. Vous apparaissez alors à cet endroit ou à proximité. C'est au MJ de décider l'endroit exact de votre arrivée.

Sinon, si vous connaissez la séquence de glyphes magiques d'un cercle de téléportation présent sur un autre plan d'existence, ce sort peut vous conduire dans ce cercle.

S'il est trop étroit pour accueillir toutes les créatures qui voyagent avec vous, les créatures en trop apparaissent dans les emplacements inoccupés les plus proches du cercle.

Vous pouvez aussi utiliser ce sort pour bannir une créature non consentante sur un autre plan. Choisissez une créature à votre portée et faites une attaque de sort au corps-à-corps contre elle. Si vous touchez, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md) ou être transporté en un endroit aléatoire du plan d'existence que vous nommez. Une fois à cet endroit, c'est à elle de trouver un moyen de rentrer sur son plan d'origine.

Vous tentez de charmer un humanoïde se trouvant à portée et dans votre champ de vision. Il doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md), pour lequel il dispose d'un avantage si vous ou vos compagnons êtes actuellement en train de le combattre. S'il rate son test, il est [charmé](hd_conditions_charme.md) par vous jusqu'à la fin du sort ou jusqu'à ce que vous ou vos compagnons lui fassiez du mal. La créature [charmée](hd_conditions_charme.md) vous considère comme un ami. Quand le sort se termine, elle sait que vous l'avez [charmée](hd_conditions_charme.md).

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, vous pouvez charmer une créature de plus par niveau au-delà du niveau 1. Toutes les cibles doivent se trouver à 9 mètres ou moins les unes des autres lorsque vous lancez le sort.

Choisissez un objet manufacturé en métal, comme une arme métallique ou une armure métallique lourde ou intermédiaire.

Il doit être situé à portée et dans votre champ de vision et se met alors à luire d'un rouge incandescent.

Une créature en contact physique avec l'objet reçoit 2d8 dégâts de feu lorsque vous lancez le sort. Vous pouvez utiliser une action bonus à chacun de vos tours suivants jusqu'à la fin du sort pour infliger de nouveau ces dégâts.

Si une créature tient l'objet qui lui inflige des dégâts ou le porte sur elle, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md), sans quoi elle le lâche, si elle le peut. Si elle le conserve, elle est affectée par un désavantage lors des jets d'attaque et des tests de caractéristique jusqu'au début de votre prochain tour.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, les dégâts augmentent de 1d8 par niveau au-delà du niveau 2.

Vous invoquez un chien de garde fantomatique dans un emplacement inoccupé situé à portée et dans votre champ de vision. Il reste là pendant toute la durée du sort ou jusqu'à ce que vous le renvoyiez par une action ou que vous vous éloigniez à plus de 30 mètres de lui.

Le chien est [invisible](hd_conditions_invisible.md) pour tout le monde sauf pour vous, et il est impossible de le blesser. Il se met à aboyer dès qu'une créature de taille P ou supérieure arrive à 9 mètres de lui sans prononcer d'abord le mot de passe que vous avez choisi lors de l'incantation. Le chien perçoit les créatures [invisibles](hd_conditions_invisible.md) et voit ce qui se passe sur le plan éthéré. Il ignore les illusions.

Au début de votre tour, le chien tente de mordre une créature qui vous est hostile, située dans un rayon de 1,50 mètre autour de lui. Son bonus d'attaque est égal à votre modificateur de caractéristique d'incantation + votre bonus de maîtrise. S'il touche, il inflige 4d8 dégâts perforants.

Vous défiez un adversaire à portée. Tant que vous n'attaquez que cet adversaire, vous bénéficiez d'un avantage à votre première attaque à chacun de vos tours.

Vous créez un organe sensoriel [invisible](hd_conditions_invisible.md) à portée dans un endroit qui vous est familier (un endroit où vous vous êtes déjà rendu ou que vous avez déjà vu) ou dans un endroit évident qui ne vous est pas familier (comme de l'autre côté d'une porte, derrière un angle de mur, dans un bosquet…). L'organe reste là pendant toute la durée du sort. Il est impossible de l'attaquer ou d'interagir avec.

Vous choisissez la vue ou l'ouïe au moment où vous lancez le sort. Vous pouvez alors utiliser le sens choisi à travers l'organe comme si vous occupiez son emplacement.

Vous pouvez dépenser une action pour passer de la vue à l'ouïe ou inversement.

Une créature capable de voir l'organe sensoriel (en bénéficiant par exemple de voir l'invisible ou de vision parfaite) le perçoit comme un orbe lumineux intangible de la taille de votre poing.

Pendant toute la durée du sort, vous lancez 1d20 à la fin de chacun de vos tours. Sur un 11 ou plus, vous disparaissez de votre plan d'existence actuel et apparaissez sur le plan éthéré (si vous vous trouviez déjà là, le sort échoue et l'incantation est gaspillée). Au début de votre tour suivant et quand le sort se termine alors que vous vous trouvez sur le plan éthéré, vous retournez sur un emplacement inoccupé de votre choix que vous pouvez voir dans un rayon de 3 mètres autour de l'emplacement dont vous avez disparu. S'il n'y a pas d'emplacement disponible dans ce rayon, vous apparaissez dans l'espace inoccupé le plus proche (choisi au hasard s'il y en a plusieurs à égale distance). Vous pouvez révoquer ce sort par une action.

Tant que vous êtes sur le plan éthéré, vous voyez et entendez ce qui se passe sur le plan d'où vous venez, qui apparaît sous forme d'ombres grises, mais votre vision ne porte pas au-delà de 18 mètres. Vous pouvez seulement affecter des créatures se trouvant sur le plan éthéré et elles sont les seules à pouvoir vous affecter. Les créatures qui ne se trouvent pas sur ce plan ne peuvent ni vous percevoir, ni interagir avec vous, à moins qu'elles ne disposent d'un pouvoir le leur permettant.

Ce sort génère la réplique inerte d'une créature vivante, pour la protéger de la mort. Le clone se forme au sein d'un réceptacle scellé et grandit jusqu'à atteindre sa taille adulte et sa maturité en 120 jours ; cependant, vous pouvez décider que le clone sera une version plus jeune de la créature qu'il reproduit. Il reste inerte et indéfiniment dans le même état tant que le réceptacle reste scellé.

Une fois que le clone est arrivé à maturité, si la créature originale meurt, son âme se transfère dans le clone, à condition que cette âme soit libre et désireuse de revenir à la vie. D'un point de vue physique, le clone est identique à l'original. De plus, il possède la même personnalité, les mêmes souvenirs et les mêmes capacités, mais il n'hérite pas de son équipement. Les restes physiques de la créature originale ne disparaissent pas. S'ils ne sont pas détruits, ils deviennent inertes et ne peuvent pas servir à ramener la créature à la vie puisque son âme se trouve ailleurs.

Vous imposez une coercition magique à une créature située à portée et dans votre champ de vision, l'obligeant à vous accorder un service ou l'empêchant de commettre une action ou une suite d'actions, comme bon vous semble.

Si la créature comprend votre langue, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) sans quoi elle est [charmée](hd_conditions_charme.md) par vous pendant toute la durée du sort. Pendant toute cette période, elle subit 5d10 dégâts psychiques chaque fois qu'elle agit de manière directement opposée à vos instructions, mais jamais plus d'une fois par jour. Si la créature ne vous comprend pas, ce sort n'a aucun effet sur elle.

Vous pouvez lui donner n'importe quel ordre de votre choix, en dehors de ceux qui la mènent directement à la mort. Le sort se termine immédiatement si jamais vous donnez un ordre suicidaire.

Vous pouvez mettre prématurément fin au sort en dépensant une action pour le dissiper. Les sorts _[lever une malédiction](hd_spells_lever_une_malediction.md)_, _[restauration supérieure](hd_spells_restauration_superieure.md)_ et _[souhait](hd_spells_souhait.md)_ mettent aussi fin à ce sort.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou 8, il dure 1 an.

Avec un emplacement de sort de niveau 9, il persiste jusqu'à ce que quelqu'un le dissipe avec l'un des sorts mentionnés précédemment.

Vous dissimulez un coffre et son contenu sur le plan éthéré. Pour cela, vous devez toucher le coffre et la réplique qui sert de composante matérielle au sort. Le coffre peut contenir un maximum de 324 décimètres cubes (90 × 60 × 60 centimètres) de matière non vivante.

Tant que le coffre reste sur le plan éthéré, vous pouvez utiliser une action pour toucher la réplique et le rappeler à vous. Il apparaît en un emplacement libre au sol, situé dans un rayon de 1,50 mètre autour de vous. Vous pouvez renvoyer le coffre dans le plan éthéré en utilisant une action et en touchant le coffre et sa réplique.

Au bout de 60 jours, il y a 5 % de chances cumulatifs par jour que les effets du sort se terminent. Ils s'achèvent aussi si vous lancez de nouveau le sort, si la petite réplique du coffre est détruite ou si vous décidez de mettre un terme au sort en recourant à une action.

Si le sort se termine alors que le grand coffre est encore sur le plan éthéré, ce coffre est irrémédiablement perdu.

Vous invoquez la puissance des enfers dans une zone de 6 mètres de rayon autour d'un point situé à portée et dans votre champ de vision. La surface affectée se fissure en laissant échapper les flammes de l'enfer, tandis que des dizaines de bras décharnés et de mains griffues émergent du sol et tentent d'agripper toutes les créatures qui passent à leur portée, dans une cacophonie de plaintes, de suppliques et de cris déchirants. La zone est considérée comme un terrain difficile et toute créature qui y termine son déplacement subit 3d6 dégâts de feu. Une créature qui entre dans la zone ou s'y déplace doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md) ou être immédiatement [entravée](hd_conditions_entrave.md) jusqu'à son prochain tour.

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de sort de niveau 4 ou supérieur, les dégâts augmentent de 1d6 par niveau d'emplacement au-delà du niveau 3.

Vous créez un piège qui s'enroule autour d'un ou plusieurs membres de l'individu ciblé et peut le faire chuter ou le ligoter. Le piège affecte une zone de 3 mètres de rayon autour d'un point que vous désignez à portée. Cette zone doit être placée sur un terrain naturel (pas sur une route ni dans une structure artificielle). La première créature qui traverse la zone piégée doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). En cas de succès, elle est à terre, en cas d'échec elle est de plus [entravée](hd_conditions_entrave.md). Une créature à terre termine immédiatement son déplacement et perd l'action en cours.

Elle peut se relever normalement avec sa prochaine action.

Une créature [entravée](hd_conditions_entrave.md) peut utiliser son action à chaque tour pour faire un nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md) ou de [Force](hd_abilities_strength.md) au choix afin de se délivrer. Toutefois, à chaque fois qu'elle lutte pour échapper aux liens, ceux-ci se resserrent et lui infligent 1d6 dégâts tranchants. Tant qu'elle n'essaye pas de se délivrer, elle ne subit pas de dégât.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, le sort affecte une cible supplémentaire par niveau au-delà du niveau 2.

Une colonne verticale de feu divin rugissant surgit des cieux et s'abat à l'endroit de votre choix. Toute créature située dans un cylindre de 3 mètres de rayon et 12 mètres de haut centré sur le point de votre choix à portée doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md).

Celles qui échouent subissent 4d6 dégâts de feu et 4d6 dégâts radiants, les autres la moitié seulement.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, les dégâts de feu ou les dégâts radiants (à vous de choisir) augmentent de 1d6 par niveau au-delà du niveau 5.

Vous devenez capable de comprendre les bêtes et de communiquer verbalement avec elles pendant toute la durée du sort. Les connaissances et le degré de conscience de nombreuses bêtes sont limités par leur intelligence réduite, mais elles peuvent au moins vous renseigner sur les environs et les monstres aux alentours, ainsi que sur ce qu'elles perçoivent aujourd'hui ou ont perçu la veille. Si le MJ accepte, vous pouvez convaincre une bête de vous accorder une petite faveur.

Vous donnez un semblant de vie et d'intelligence à un cadavre de votre choix situé à portée. Il est alors en mesure de répondre à vos questions. Le cadavre doit encore disposer d'une bouche et ne doit pas être un mort-vivant. Le sort échoue si le cadavre choisi a déjà été la cible de ce sort au cours des 10 jours précédents.

Vous pouvez poser jusqu'à cinq questions avant la fin de la durée du sort. Les connaissances du cadavre se limitent à ce qu'il savait de son vivant, y compris au niveau des langues qu'il est capable de parler. Les réponses sont souvent brèves, cryptiques ou répétitives et le cadavre n'est absolument pas obligé de vous donner une réponse sincère si vous lui êtes hostile ou s'il vous reconnaît comme étant un ennemi. Ce sort ne ramène pas l'âme de la cible dans son corps, juste l'esprit qui l'animait ; le cadavre ne peut donc pas apprendre de nouvelles informations, ne comprend rien de ce qui s'est passé après sa mort et est incapable de faire des spéculations sur l'avenir.

Vous imprégnez la végétation située dans un rayon de 9 mètres autour de vous d'une conscience et d'une mobilité limitées, ce qui permet aux plantes de communiquer avec vous et de suivre des ordres simples. Vous pouvez interroger les végétaux sur les événements qui se sont déroulés la veille dans la zone du sort et ainsi obtenir des informations sur les créatures qui sont passées, sur les conditions météorologiques et autres.

Vous pouvez également transformer un terrain rendu difficile à cause de la végétation (comme des buissons ou d'épais taillis) en terrain ordinaire pendant toute la durée du sort. Vous pouvez également transformer un terrain ordinaire où poussent des plantes en terrain difficile pendant toute la durée du sort, par exemple de manière à ce que des plantes grimpantes et des branches gênent vos poursuivants.

Les plantes peuvent exécuter d'autres tâches pour vous, si le MJ donne son accord. Le sort ne leur permet pas de se déraciner ni de se déplacer, mais elles peuvent agiter leurs branches, leurs vrilles et leurs tiges.

Si une créature végétale se trouve dans la zone, vous pouvez communiquer avec elle comme si vous partagiez un même langage, mais vous ne gagnez pas de capacité magique permettant de l'influencer.

Ce sort permet de libérer une créature [entravée](hd_conditions_entrave.md) par les plantes nées d'un sort d'_[enchevêtrement](hd_spells_enchevetrement.md)_.

Vous entrez en contact avec votre divinité ou l'un de ses représentants et lui posez jusqu'à trois questions fermées auxquelles la réponse est soit oui, soit non. Vous devez les poser avant la fin du sort et vous recevez une réponse correcte à chacune d'entre elles.

Les êtres divins ne sont pas forcément omniscients, il se peut donc que vous obteniez « incertain » comme réponse si votre question porte sur des informations sortant du champ des connaissances de votre divinité. Si une réponse d'un seul mot risque de se révéler trompeuse ou contraire aux intérêts de la divinité, le MJ peut lui substituer une courte phrase.

Si vous lancez ce sort à deux reprises ou plus avant un long repos, il y a 25 % de chances (cumulables) que chaque incantation en sus de la première ne reçoive pas de réponse. Le MJ effectue ce jet en secret.

Pendant un court instant, vous ne faites plus qu'un avec la nature et obtenez des informations sur le territoire environnant.

En extérieur, ce sort vous transmet des informations sur le terrain qui vous entoure dans un rayon de 4,5 kilomètres. Dans une grotte ou un autre environnement naturel souterrain, le rayon d'action est de 90 mètres.

Ce sort ne fonctionne pas là où les constructions ont remplacé la nature, comme en ville ou dans un donjon.

Vous obtenez instantanément des informations sur un maximum de trois éléments de votre choix portant sur l'un des sujets suivants dans votre zone.

* Le terrain et les étendues d'eau.

* Les plantes, les minéraux, les animaux et les peuples majoritaires.

* Les célestes, les fées, les fiélons, les élémentaires ou les morts-vivants dotés d'une certaine puissance.

* L'influence émanant des autres plans d'existence.

* Les constructions.

Par exemple, vous pouvez apprendre où se trouve un puissant mort-vivant résidant dans la zone, savoir où se trouvent les points d'eau potable majeurs et où se trouvent les villages les plus proches.

Vous tentez de convaincre une bête à portée et dans votre champ de vision de devenir votre compagnon de route et d'aventure. L'animal ne doit pas être hostile au moment où vous lancez le sort et vous l'amadouez avec un peu de nourriture pendant l'incantation. Le succès du sort est automatique si l'indice de dangerosité de la bête ne dépasse pas 1/2 et que sa valeur d'intelligence est inférieure ou égal à 4. Dans le cas contraire, la bête n'est pas affectée par le sort.

Si le sort est un succès, vous pouvez communiquer de façon rudimentaire avec votre compagnon et lui donner des ordres simples comme attaquer une cible ou la suivre, rapporter un objet en vue, garder un lieu ou une créature, etc. Cela ne vous demande pas de dépenser une action. De plus, vous pouvez entendre et voir par l'intermédiaire des oreilles et des yeux de votre compagnon, comme si vous occupiez son emplacement.

À votre tour, vous pouvez dépenser une action bonus pour passer de l'utilisation de ses sens à celle des vôtres et inversement. Tant que vous utilisez ses sens, vous êtes aveugle et sourd à votre propre environnement.

Lorsque les points de vie d'un compagnon animal sont égaux à 0, il suit les mêmes règles qu'un personnage et il peut bénéficier de soins. Après chaque repos court, les points de vie du compagnon animal remontent à la moitié de son maximum s'ils sont inférieurs à cette valeur.

Après chaque repos long, le compagnon récupère l'intégralité des points de vie perdus.

Chaque jour, vous pouvez conserver le même compagnon animal sans devoir à nouveau lancer le sort, simplement en sacrifiant l'emplacement de sort correspondant et en utilisant une action bonus.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, vous pouvez choisir dans la liste ci-dessous un effet supplémentaire par niveau au-delà du niveau 2. Vous ne pouvez pas choisir le même effet plus d'une fois.

* Lancer le sort sur une bête dont l'indice de dangerosité est inférieur ou égal à 1.

* Accorder à votre compagnon dont l'indice de dangerosité est inférieur ou égal à 1/2 une résistance à tous les types de dégâts et un avantage en attaque et aux [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md)

* Communiquer par télépathie sans limite de distance avec votre compagnon et obtenir la capacité de le guérir d'un nombre de points de vie de votre choix en dépensant une action bonus et autant de vos propres points de vie, sans limite de distance.

* Affecter une bête identique supplémentaire.

Lorsque vous choisissez d'autres effets, ce second compagnon en bénéficie aussi.

Pendant toute la durée du sort, vous comprenez le sens littéral de tout langage parlé que vous entendez. Vous comprenez aussi les langues écrites que vous voyez, à condition de toucher la surface sur laquelle les mots ont été tracés. Il vous faut 1 minute pour lire une page de texte.

Ce sort ne décode pas les messages secrets compris dans un texte ni les glyphes qui ne correspondent pas à un langage écrit, comme un _[symbole](hd_spells_symbole.md)_ magique.

Les créatures de votre choix, situées à portée, dans votre champ de vision et en mesure de vous entendre, doivent réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) ou être affectées par le sort. Une cible qui ne peut être [charmée](hd_conditions_charme.md) réussit automatiquement ce jet. À chaque tour jusqu'à la fin du sort, vous pouvez utiliser une action bonus pour désigner une direction (vers laquelle la cible peut se diriger) par rapport à vous. Chaque cible affectée doit alors utiliser son déplacement au mieux pour se diriger dans cette direction à son prochain tour. De plus, elle ne peut pas effectuer d'action avant de se déplacer. Une fois qu'elle s'est ainsi déplacée, elle peut faire un nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) pour tenter de mettre un terme à l'effet du sort.

Une cible n'est pas obligée de se rendre au sein d'une zone à l'évidence dangereuse, comme un brasier ou une fosse béante, mais elle est prête à provoquer des attaques d'opportunité pour se déplacer dans la direction indiquée.

Une bouffée d'air froid jaillit de vos mains. Toutes les créatures présentes dans un cône de 18 mètres doivent effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). Celles qui le ratent subissent 8d8 dégâts de froid, les autres la moitié seulement.

Une créature qui succombe suite à ce sort se transforme en statue de glace jusqu'à ce qu'elle fonde.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, les dégâts augmentent de 1d8 par niveau au-delà du niveau 5.

Ce sort assaille et pervertit l'esprit des créatures, génère des hallucinations et provoque des réactions incontrôlées.

Toutes les créatures situées dans une sphère de 3 mètres de rayon autour d'un point de votre choix situé à portée doivent réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) ou être affectées par ce sort.

Une cible affectée ne peut pas utiliser de réaction et doit lancer 1d10 au début de chacun de ses tours pour déterminer comment elle se comporte pendant le tour.

|d10|Comportement|
|---|---|
|1|La créature utilise la totalité de son mouvement pour se déplacer dans une direction aléatoire. Pour déterminer cette dernière, lancez un d8 en assignant une direction à chaque face. La créature n'effectue aucune action pour ce tour.|
|2-6|La créature ne bouge pas et n'entreprend pas la moindre action pour ce tour.|
|7-8|La créature utilise son action pour porter une attaque au corps-à-corps contre une créature aléatoire à portée d'allonge. S'il n'y a pas de créature à portée, elle ne fait rien durant le tour.|
|9-10|La créature peut agir et se déplacer normalement.|

Une créature affectée peut faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) à la fin de chacun de ses tours. En cas de succès, l'effet se termine pour elle.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 5 ou supérieur, le rayon de la sphère augmente de 1,50 mètre par niveau au-delà du niveau 4.

Vous faites apparaître une main fantomatique et squelettique sur l'emplacement d'une créature située à portée.

Faites un jet d'attaque de sort à distance contre la créature pour la transir de froid. Si l'attaque touche, la victime reçoit 1d8 dégâts nécrotiques et ne peut pas récupérer de point de vie avant le début de votre prochain tour. Jusque-là, la main s'accroche à elle.

Si votre cible est un mort-vivant, il subit en plus un désavantage lors des jets d'attaque effectués contre vous jusqu'à la fin de votre prochain tour.

Les dégâts du sort augmentent de 1d8 quand vous atteignez les niveaux 5 (2d8), 11 (3d8) et 17 (4d8).

Vous contactez mentalement un demi-dieu, l'esprit d'un sage décédé depuis longtemps, ou une autre entité mystérieuse issue d'un autre plan. Le contact avec cette intelligence extraplanaire met votre esprit à rude épreuve et risque même de le briser. Quand vous lancez ce sort, vous devez effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) d'intelligence DD 15.

En cas d'échec, vous encaissez 6d6 dégâts psychiques et vous devenez fou jusqu'à ce que vous ayez bénéficié d'un repos long. Tant que vous êtes fou, vous ne pouvez pas entreprendre la moindre action, vous ne comprenez pas ce que disent les autres créatures, vous êtes incapable de lire et vous ne bredouillez que des paroles insensées. Une tierce personne peut mettre un terme à cet effet en vous ciblant avec un sort de _[restauration supérieure](hd_spells_restauration_superieure.md)_.

Si vous réussissez votre [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), vous pouvez poser jusqu'à cinq questions à l'entité. Vous devez les poser avant la fin du sort. C'est le MJ qui répond à chacune d'entre elles avec un mot, comme « oui », « non », « peutêtre », « jamais », « hors sujet » ou « incertain » (si l'entité ignore la réponse à votre question). Si une réponse limitée à un seul mot risque de se révéler trompeuse, le MJ peut la remplacer par une courte phrase.

Votre simple contact transmet des maladies. Faites une attaque de sort au corps-à-corps contre une créature à portée. Si vous touchez, vous lui inoculez une maladie de votre choix, à sélectionner parmi celles décrites ci-dessous.

La cible doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) à la fin de chacun de ses tours. Une fois qu'elle en a raté trois, la maladie fait effet pendant toute la durée du sort et la créature n'a plus à faire de [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md). Si elle réussit trois [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md), elle guérit de sa maladie et le sort se termine.

Comme le sort déclenche une maladie naturelle chez la cible, tout effet qui guérit une maladie ou améliore ses symptômes s'applique.

**_Bouille-crâne._** La créature a soudain l'esprit enfiévré. Elle souffre d'un désavantage lors des tests d'[Intelligence](hd_abilities_intelligence.md) et des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) d'[Intelligence](hd_abilities_intelligence.md). De plus, au combat, elle se comporte comme si elle était sous l'effet d'un sort de _[confusion](hd_spells_confusion.md)_.

**_Convulsions._** La créature est agitée de tremblements.

Elle subit un désavantage lors des tests de [Dextérité](hd_abilities_dexterity.md), des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md) et des jets d'attaque basés sur la [Dextérité](hd_abilities_dexterity.md).

**_Fièvre répugnante._** Une forte fièvre s'empare de la créature, qui est affectée par un désavantage lors des tests de [Force](hd_abilities_strength.md), des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md) et des jets d'attaque basés sur la [Force](hd_abilities_strength.md).

**_Mal aveuglant._** La créature est en proie à de violentes douleurs cérébrales et ses yeux deviennent d'un blanc laiteux.

Elle subit un désavantage lors des tests de [Sagesse](hd_abilities_wisdom.md) et des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) et elle est [aveuglée](hd_conditions_aveugle.md).

**_Mort poisseuse._** La créature est affligée de saignements incontrôlables. Elle souffre d'un désavantage lors des tests de [Constitution](hd_abilities_constitution.md) et des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). De plus, elle est [étourdie](hd_conditions_etourdi.md) jusqu'à la fin de son prochain tour à chaque fois qu'elle subit des dégâts.

**_Pourriture._** La chair de la créature se met à pourrir.

Elle subit un désavantage lors des tests de [Charisme](hd_abilities_charisma.md) et devient vulnérable à tous les dégâts.

Vous transmettez une maladie virulente à une créature située à portée et dans votre champ de vision. La cible doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). Si elle échoue, elle subit 14d6 dégâts nécrotiques, la moitié seulement si elle réussit. Ces dégâts ne peuvent pas faire passer les points de vie de la cible au-dessous de 1. Si la cible rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), son total de points de vie maximum est réduit, pendant 1 heure, d'un montant égal aux dégâts nécrotiques reçus. Tout effet qui guérit les maladies ramène le maximum de points de vie de la cible à la normale sans avoir besoin d'attendre 1 heure.

Choisissez un sort de niveau 5 ou moins que vous êtes en mesure de lancer, qui possède un temps d'incantation d'une action, et qui peut vous prendre pour cible. Vous lancez ce sort (que l'on appelle le sort contingent) lors de l'incantation de la contingence. Vous dépensez donc les emplacements des deux sorts, mais le contingent ne fait pas effet immédiatement. Il s'active lorsque certaines conditions sont remplies. Vous devez décrire ces dernières au moment où vous lancez les deux sorts. Par exemple, lors d'une contingence associée à une respiration aquatique, vous pouvez stipuler que la respiration aquatique doit se déclencher quand vous vous trouvez immergé dans l'eau ou dans un liquide similaire.

Le sort contingent prend effet dès que les circonstances sont remplies pour la première fois, que vous le vouliez ou non, ce qui met un terme à la contingence.

Le sort contingent affecte uniquement votre personne, même s'il peut normalement affecter d'autres créatures.

Vous ne pouvez utiliser qu'un seul sort de contingence à la fois. Si vous en lancez un second, les effets du précédent se dissipent. De plus, la contingence prend fin si sa composante matérielle n'est plus sur votre personne.

Vous tentez d'interrompre une créature en pleine incantation.

Si elle essayait de lancer un sort de niveau 3 ou moins, il échoue et reste sans effet. Si le sort est de niveau 4 ou plus, faites un test de caractéristique en utilisant votre caractéristique d'incantation. Le DD est de 10 + le niveau du sort. Si vous réussissez, le sort de la créature échoue et reste sans effet.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, le sort à interrompre est automatiquement sans effet s'il est d'un niveau égal ou inférieur à celui de l'emplacement de sort utilisé.

Jusqu'à la fin du sort, vous contrôlez toute étendue d'eau indépendante située dans la zone de votre choix, cette dernière devant tenir dans un cube d'au maximum 30 mètres d'arête. Quand vous lancez ce sort, vous pouvez choisir l'un des effets suivants. À votre tour, vous pouvez utiliser une action pour répéter l'effet ou en appliquer un nouveau.

**_Écarter les eaux._** Vous écartez les eaux de la zone pour y créer un passage. Il traverse toute la zone, les eaux formant une muraille de chaque côté. Le passage demeure jusqu'à la fin du sort ou jusqu'à ce que vous optiez pour un effet différent. Dans ces deux cas, l'eau remplit alors progressivement le passage, au fil du round suivant, jusqu'à ce que le niveau de l'eau revienne à la normale.

**_Inondation._** Vous faites monter le niveau d'une étendue d'eau isolée d'un maximum de 6 mètres. Si la zone comprend une rive, l'eau déborde et se répand sur la terre ferme.

Si vous avez lancé le sort sur une grande étendue d'eau, vous créez une vague de 6 mètres de haut qui traverse la zone affectée d'un bout à l'autre pour se briser une fois arrivée à la fin de la zone. Tous les véhicules de taille TG ou inférieure qui se trouvent sur le chemin de la vague sont emportés jusqu'au bout de la zone. Tous les véhicules ont 25 % de chances de chavirer.

Le niveau de l'eau reste plus élevé jusqu'à la fin du sort ou jusqu'à ce que vous choisissiez un autre effet. Si l'effet d'inondation produit une vague, elle se reforme au début de votre prochain tour tant que vous gardez cet effet actif.

**_Modifier le cours de l'eau._** Vous changez l'itinéraire de l'eau courante qui traverse la zone et l'envoyez dans la direction de votre choix, même si elle doit pour cela franchir des obstacles comme passer par-dessus un mur ou couler dans une direction improbable. L'eau suit vos instructions dans la zone affectée mais, dès qu'elle en sort, elle reprend un cours normal défini par le terrain qu'elle parcourt. L'eau continue de couler là où vous l'avez choisi jusqu'à la fin du sort ou jusqu'à ce que vous décidiez d'un autre effet.

**_Tourbillon._** Cet effet nécessite une étendue d'eau d'au moins 15 mètres carrés pour 7,50 mètres de fond et se traduit par la formation d'un tourbillon au centre de la zone. Il se présente sous forme d'un vortex de 1,50 mètre de large à sa base pour un maximum de 15 mètres de large au sommet et une hauteur de 7,50 mètres. Toutes les créatures et tous les objets qui se trouvent dans l'eau et dans un rayon de 7,50 mètres autour du tourbillon sont entraînés vers lui sur 3 mètres. Une créature peut s'éloigner à la nage si elle réussit un test de [Force (Athlétisme)](hd_abilities_strength_athletisme.md) contre le DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de votre sort.

Quand une créature entre dans le vortex pour la première fois de son tour ou qu'elle y commence son tour, elle doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md). Si elle échoue, elle reçoit 2d8 dégâts contondants et se fait emporter par le vortex jusqu'à la fin du sort. Si elle réussit son jet, elle subit seulement la moitié des dégâts et n'est pas prise dans le vortex. Une créature emportée par le vortex peut utiliser une action pour tenter de s'en éloigner comme décrit plus haut, mais elle est affectée par un désavantage lors de son test de [Force (Athlétisme)](hd_abilities_strength_athletisme.md). À chaque tour, la première fois qu'un objet entre dans le vortex, il subit 2d8 dégâts contondants. Ces dégâts se répètent à chaque round passé dans le vortex.

Vous prenez le contrôle de la météo dans un rayon de 7,5 kilomètres autour de vous pendant toute la durée du sort. Vous devez être en extérieur au moment de l'incantation.

Si vous vous rendez dans un endroit d'où vous ne voyez pas directement le ciel, le sort se termine prématurément.

Au moment de l'incantation, vous changez les conditions météorologiques actuelles déterminées par le MJ en fonction du climat et de la saison. Vous pouvez modifier les précipitations, la température et le vent. Il faut 1d4×10 minutes pour que les nouvelles conditions s'installent. Vous pouvez ensuite les modifier à nouveau. Le temps retourne progressivement à la normale une fois le sort terminé.

Quand vous modifiez les conditions météorologiques, cherchez les conditions actuelles dans les tables suivantes : vous pouvez les décaler d'un cran vers le haut ou le bas. Quand vous modifiez le vent, vous pouvez changer sa direction.

Précipitations

|Étape|Condition|
|---|---|
|1|Ciel dégagé|
|2|Quelques nuages|
|3|Ciel couvert ou brume au sol|
|4|Pluie, grêle ou neige|
|5|Pluies torrentielles, forte grêle ou blizzard|

Température

|Étape|Condition|
|---|---|
|1|Chaleur insoutenable|
|2|Forte chaleur|
|3|Tiède|
|4|Frais|
|5|Grand froid|
|6|Froid polaire|

Vent

|Étape|Condition|
|---|---|
|1|Temps calme|
|2|Vent modéré|
|3|Vent fort|
|4|Grand vent|
|5|Tempête|

Vous touchez un objet pesant 5 kilogrammes ou moins et dont la dimension la plus longue est de 1,80 mètre ou moins. Le sort laisse une marque [invisible](hd_conditions_invisible.md) sur la surface de l'objet et inscrit le nom de l'objet sur le saphir que vous utilisez comme composante matérielle. Chaque fois que vous lancez ce sort, vous devez utiliser un saphir différent.

Ensuite, vous pouvez utiliser une action quand vous le désirez pour prononcer le nom de l'objet et broyer le saphir.

L'objet apparaît immédiatement dans votre main, en dépit des distances physique et planaire, et le sort se termine.

Si l'objet est actuellement porté ou transporté par quelqu'un d'autre, il n'arrive pas jusqu'à vous quand vous broyez le saphir, mais vous apprenez qui est la créature qui détient l'objet et vous savez à peu près où elle se trouve à ce moment-là.

_[Dissipation de la magie](hd_spells_dissipation_de_la_magie.md)_ ou un effet similaire appliqué sur le saphir met un terme à l'effet du sort.

Une barrière scintillante se déploie depuis votre personne, jusqu'à englober une zone d'un rayon de 3 mètres. Elle se déplace avec vous, reste centrée sur vous et repousse les créatures autres que les morts-vivants et les créatures artificielles. Cette barrière persiste pendant toute la durée du sort.

La barrière empêche les créatures affectées de la franchir ou de passer un membre au travers. Une créature affectée peut lancer des sorts ou porter des attaques à distance ou via une arme à allonge, tout cela franchissant la barrière.

Si vous vous déplacez de telle manière qu'une créature affectée est contrainte de traverser la barrière, le sort se termine.

Vous touchez une longueur de corde d'au maximum 18 mètres. L'une de ses extrémités s'élève alors dans les airs, jusqu'à ce que toute la corde se dresse perpendiculairement au sol. Une entrée [invisible](hd_conditions_invisible.md) s'ouvre à l'extrémité supérieure de la corde et débouche sur un espace extradimensionnel qui persiste jusqu'à la fin du sort.

On peut atteindre cet espace extradimensionnel en grimpant jusqu'au sommet de la corde. Il peut accueillir un maximum de huit créatures de taille M ou inférieure.

On peut ensuite tirer la corde dans l'espace extradimensionnel, afin que personne ne la voie en dehors de l'abri.

Les attaques et les sorts ne peuvent traverser l'entrée de l'espace extradimensionnel ni depuis l'intérieur, ni depuis l'extérieur. En revanche, les créatures qui se trouvent à l'intérieur peuvent regarder dehors grâce à une fenêtre de 90 centimètres sur 1,50 mètre centrée sur la corde.

Tout ce qui se trouve dans l'espace extradimensionnel tombe à l'extérieur quand le sort se termine.

Un éventail de lumières colorées éblouissantes jaillit de votre main. Lancez 6d10. Le total représente le nombre de points de vie de créatures que le sort affecte. Les créatures situées dans un cône de 4,50 mètres, prenant votre personne comme point d'origine, sont affectées dans l'ordre croissant de leurs points de vie actuels (en ignorant les créatures [inconscientes](hd_conditions_inconscient.md) et les créatures [aveuglées](hd_conditions_aveugle.md)).

Chaque créature affectée, en commençant par celle qui possède actuellement le moins de points de vie, est [aveuglée](hd_conditions_aveugle.md) jusqu'à la fin du sort. Soustrayez du total obtenu le nombre de points de vie actuel de chaque créature affectée avant de passer à la suivante, en choisissant chaque fois celle qui possède le moins de points de vie. Pour qu'une créature soit affectée, elle doit posséder un nombre de points de vie actuels inférieur ou égal au total restant.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, lancez 2d10 supplémentaires par niveau au-delà du niveau 1.

Vous tirez des bribes de matière ombreuse du plan de l'ombre pour créer à portée des objets inertes en matière végétale : du tissu, de la corde, du bois ou des objets similaires. Ce sort permet aussi de créer des objets minéraux comme de la pierre, du cristal ou du métal.

L'objet créé ne doit pas être plus grand qu'un cube de 1,50 mètre d'arête et doit impérativement être d'une forme et d'un matériau que vous avez déjà vus.

La durée du sort dépend du matériau choisi pour façonner l'objet. S'il est fait de plusieurs matières, c'est la durée la plus courte qui s'applique.

|Matériau|Durée|
|---|---|
|Matière végétale|1 jour|
|Pierre ou cristal|12 heures|
|Métaux précieux|1 heure|
|Gemmes|10 minutes|
|Adamantium ou mithral|1 minute|

Si vous utilisez les matériaux créés via ce sort comme composantes matérielles pour un autre sort, ce dernier échoue.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, l'arête du cube augmente de 1,50 mètre par niveau au-delà du niveau 5.

Ce sort se lance uniquement de nuit. Choisissez jusqu'à trois cadavres de créatures humanoïdes de taille M ou P situés à portée. Chacun se change en goule placée sous votre contrôle. (Le MJ dispose du profil technique de ces créatures).

À chacun de vos tours, vous pouvez utiliser une action bonus pour contrôler mentalement les créatures que vous avez animées avec ce sort si elles se trouvent dans un rayon de 36 mètres (si vous en contrôlez plusieurs, vous pouvez en commander une ou plusieurs à la fois, à condition de donner le même ordre à toutes). Vous pouvez décider de l'action que la créature va entreprendre et de l'endroit où elle va se rendre lors de son prochain tour, ou donner des consignes plus génériques, comme de garder une salle ou un couloir. En l'absence d'ordre de votre part, la créature se contente de se défendre contre les créatures hostiles.

Dès qu'une créature a reçu un ordre, elle s'y conforme jusqu'à avoir accompli sa tâche.

La créature reste sous votre contrôle pendant 24 heures, après quoi elle cesse d'obéir aux ordres que vous lui avez donnés. Pour la maintenir sous votre contrôle pendant 24 heures de plus, vous devez lui relancer ce sort avant que les 24 heures de contrôle en cours ne se soient écoulées. Cette nouvelle utilisation du sort vous permet de réaffirmer votre contrôle sur un maximum de trois créatures que vous avez déjà animées via ce sort au lieu d'en animer de nouvelles.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, vous pouvez animer ou maintenir votre contrôle sur quatre goules.

Quand vous le lancez à partir d'un emplacement de niveau 8, vous pouvez animer ou maintenir votre contrôle sur cinq goules ou deux blêmes ou deux nécrophages.

Quand vous le lancez à partir d'un emplacement de niveau 9, vous pouvez animer ou maintenir votre contrôle sur six goules ou trois blêmes ou trois nécrophages ou deux momies.

Vous créez 25 kilogrammes de nourriture et 120 litres d'eau, soit par terre, soit dans des récipients installés à portée. Cela suffit à nourrir et abreuver un maximum de quinze humanoïdes ou de cinq montures pendant 24 heures. Les vivres sont fades mais nourrissants. Ils se gâtent si personne ne les a mangés dans les 24 heures suivant leur création. L'eau est claire et ne croupit pas.

Vous créez ou détruisez de l'eau.

**_Création d'eau._** Vous créez jusqu'à 40 litres d'eau potable qui apparaissent à portée, dans un récipient ouvert.

Sinon, l'eau peut tomber en pluie dans un cube de 9 mètres d'arête à portée, éteignant toutes les flammes à nu dans la zone.

**_Destruction d'eau._** Vous détruisez jusqu'à 40 litres d'eau situés à portée dans un récipient ouvert. Sinon, vous pouvez dissiper le brouillard dans un cube de 9 mètres d'arête situé à portée.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, vous créez ou détruisez 40 litres d'eau de plus, ou bien l'arête du cube affecté augmente de 1,50 mètre par niveau au-delà du niveau 1.

Dans une zone de 6 mètres de rayon centrée sur un point à portée, le sol se met à se déformer et donne naissance à un tapis de pointes et d'épines. La zone se mue en terrain difficile pendant toute la durée du sort. Quand une créature entre dans la zone ou s'y déplace, elle reçoit 2d4 dégâts perforants par tranche de 1,50 mètre parcouru.

La transformation du sol est camouflée, de manière à ce que le terrain ait l'air naturel. Une créature dans l'incapacité de voir la zone au moment de l'incantation doit réussir un test de [Sagesse (Perception)](hd_abilities_wisdom_perception.md) contre le DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de votre sort pour remarquer que le terrain est dangereux avant d'y entrer.

Ce sort décuple la vitalité des plantes d'une zone donnée.

Le sort a deux modes d'utilisation, l'un apportant des bénéfices immédiats, l'autre sur le long terme.

**_Si vous lancez ce sort en une action, choisissez un point à portée._** Toutes les plantes ordinaires situées dans un rayon de 30 mètres autour de ce point deviennent particulièrement touffues et la végétation s'épaissit. Une créature qui se déplace dans cette zone doit dépenser 1,20 mètre de déplacement pour parcourir 30 centimètres.

Vous pouvez exclure une ou plusieurs portions, de n'importe quelle taille, de la zone affectée par le sort.

**_Si vous lancez le sort sur une période de huit heures, vous enrichissez la terre._** Toute la végétation dans un rayon de 800 mètres autour d'un point de votre choix situé à portée devient luxuriante pendant un an. Elle donne deux fois plus de nourriture que la normale lors de la récolte.

Choisissez une créature située à portée et dans votre champ de vision. La cible entame une danse comique, se mettant à taper du pied et à caracoler sur place. Les créatures qui ne peuvent être [charmées](hd_conditions_charme.md) sont immunisées contre ce sort.

Une fois que la créature s'est mise à danser, elle doit dépenser la totalité de son déplacement pour danser sans quitter son espace. De plus, elle souffre d'un désavantage lors des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md) et des jets d'attaque.

Tant que la cible est affectée par ce sort, les autres créatures bénéficient d'un avantage lors de leurs jets d'attaque contre elle. Une créature en train de danser peut utiliser son action pour effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) et reprendre le contrôle de son corps. Si elle réussit, le sort se termine.

Choisissez un objet situé à portée et dans votre champ de vision. Ce peut être une porte, une boîte, un coffre, des menottes, un cadenas ou un autre objet disposant d'un système de fermeture ordinaire ou magique.

Une cible fermée par une serrure ordinaire, coincée ou bloquée par une barre se déverrouille ou se débloque. Si l'objet a plusieurs serrures, le sort en ouvre une seule. Si vous visez une cible fermée par un _[verrou magique](hd_spells_verrou_magique.md)_, ce dernier est supprimé pendant 10 minutes, au cours desquelles on peut ouvrir et fermer la cible normalement.

Quand vous lancez le sort, un cliquetis émane de l'objet et retentit si fort qu'on l'entend dans un rayon de 90 mètres.

Vous faites en sorte que votre personne (y compris vos vêtements, votre armure, vos armes et les autres objets en votre possession) prenne une apparence différente jusqu'à la fin du sort ou jusqu'à ce que vous utilisiez une action pour y mettre un terme. Vous pouvez passer pour une personne de 30 centimètres de plus ou de moins, sembler gros, maigre ou entre les deux. Vous ne pouvez pas changer de morphologie, vous devez choisir une forme possédant la même conformation que vous au niveau des membres. En dehors de cela, les détails de l'illusion sont laissés à votre imagination.

Les changements qu'apporte le sort ne résistent pas à un examen physique. Par exemple, si vous l'utilisez pour ajouter un chapeau à votre tenue, les objets passent au travers et toute personne qui essaie de le toucher ne sentira que de l'air, ou des cheveux et un crâne. Si vous utilisez le sort pour paraître plus mince qu'en réalité, la main de quelqu'un qui tente de vous toucher se heurtera à vous alors que, visuellement, elle semble encore dans le vide.

Pour percer votre déguisement à jour, une créature peut dépenser une action pour vous examiner. Elle doit alors réussir un test d'[Intelligence (Investigation)](hd_abilities_intelligence_investigation.md) contre le DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) du sort.

Vous créez une porte floue sur une surface plate et solide située à portée et dans votre champ de vision. Elle est assez large pour laisser passer sans mal des créatures de taille M. Quand quelqu'un ouvre la porte, elle donne sur un demi-plan ressemblant à une pièce vide de 9 mètres de côté (dans toutes les dimensions) faite de bois ou de pierre. La porte disparaît quand le sort se termine et les créatures et les objets encore dans le demi-plan y restent piégés, car elle s'efface aussi de leur côté.

Vous pouvez créer un nouveau demi-plan pour chaque incantation du sort ou relier la porte à un demi-plan que vous avez précédemment créé via ce sort. De plus, si vous connaissez la nature et le contenu d'un demi-plan qu'une autre créature a créé grâce à ce sort, vous pouvez lui relier votre propre porte.

Choisissez une zone de terrain à portée d'au maximum 12 mètres de côté. Vous pouvez remodeler la terre, le sable ou l'argile qu'elle comporte comme bon vous semble pendant toute la durée du sort. Vous pouvez augmenter ou diminuer l'altitude de la zone, creuser ou combler une tranchée, ériger ou abattre un mur, ou former un pilier. L'amplitude de ces modifications ne peut pas excéder la moitié de la dimension la plus importante de la zone affectée. Donc, si vous modifiez une zone de 12 mètres de côté, vous pouvez créer un pilier de 6 mètres de haut au maximum, modifier l'altitude de la zone de 6 mètres au plus, creuser une tranchée d'un maximum de 6 mètres de profondeur, etc. Il faut 10 minutes pour finaliser ces modifications.

Au bout de chaque période de 10 minutes passées à vous concentrer sur le sort, vous pouvez choisir une nouvelle zone de terrain à modifier. Comme les transformations se produisent lentement, il est bien rare qu'une créature se retrouve piégée ou blessée à cause des mouvements du terrain.

Ce sort est incapable de manipuler la pierre naturelle et les constructions de pierre. La roche et les structures s'adaptent au nouvel agencement du terrain. Si vos mo- difications déstabilisent une structure, elle peut très bien s'effondrer.

De même, le sort n'affecte pas directement la croissance des plantes. La terre déplacée emporte les végétaux avec elle.

Un mince rayon de lumière verte jaillit de votre doigt pointé vers une cible située dans votre champ de vision et à portée. La cible peut être une créature, un objet ou une création de force magique, comme une barrière issue d'un _[mur de force](hd_spells_mur_de_force.md)_.

Une créature visée par ce sort doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Si elle le rate, elle subit 10d6+40 dégâts de force. Si ces dégâts la réduisent à 0 point de vie, elle est désintégrée.

Une créature désintégrée est réduite à l'état de fine poussière grise, tout comme tous les objets qu'elle porte et transporte, à l'exception des objets magiques. Pour ressusciter une créature ainsi désintégrée, il faut impérativement recourir à une _[résurrection suprême](hd_spells_resurrection_supreme.md)_ ou un _[souhait](hd_spells_souhait.md)_.

Ce sort désintègre automatiquement les objets non magiques de taille G ou inférieure et les créations magiques de force. Si la cible est un objet de taille TG ou supérieure, le sort désintègre un cube de 3 mètres d'arête au sein de l'objet. Ce sort reste sans effet sur les objets magiques.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, les dégâts augmentent de 3d6 par niveau au-delà du niveau 6.

Vous désignez une cible vivante à portée du sort et tant que vous vous concentrez, l'eau contenue dans son corps s'écoule par ses yeux, sa bouche, ses oreilles ou les pores de sa peau. Au début de chacun de ses tours, la cible doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) ou subir 2d6 dégâts nécrotiques. Une sauvegarde réussie réduit ces dégâts de moitié.

Les morts-vivants, les créatures artificielles et les élémentaires sont immunisés à ce sort.

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de sort de niveau 3 ou supérieur, vous pouvez affecter une cible supplémentaire par niveau d'emplacement au-delà du niveau 2.

Pendant toute la durée du sort, vous percevez la présence de magie dans un rayon de 9 mètres autour de vous. Si vous percevez ainsi la magie, vous pouvez utiliser votre action pour discerner une faible aura autour d'une créature ou d'un objet visible dans la zone et imprégné de magie. Vous découvrez aussi à quelle école appartient cette magie, le cas échéant.

Le sort ignore la plupart des obstacles, mais il ne peut pas franchir 30 centimètres de pierre, 2,5 centimètres de métal ordinaire, une mince feuille de plomb, ni 1 mètre de bois ou de terre.

Pendant toute la durée du sort, vous parvenez à lire les pensées de certaines créatures. Quand vous lancez ce sort, puis en tant qu'action à votre tour jusqu'à la fin du sort, vous pouvez focaliser vos pensées sur une créature située à moins de 9 mètres dans votre champ de vision.

Si elle dispose d'une [Intelligence](hd_abilities_intelligence.md) de 3 ou moins ou ne parle aucune langue, elle n'est pas affectée.

Au départ, vous découvrez les pensées superficielles de la créature, c'est-à-dire ce qu'elle a à l'esprit à ce moment-là. Par une action, vous pouvez porter votre attention sur les pensées d'une autre créature ou tenter de vous enfoncer plus profondément dans l'esprit de celle que vous sondez actuellement. Dans ce cas, cette créature doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md).

Si elle réussit, le sort se termine. Sinon, vous avez un aperçu de son mode de raisonnement (le cas échéant), de son état émotionnel ou de ce qui occupe une place importante dans son esprit (par exemple, quelque chose qui l'inquiète fortement, qu'elle aime, qu'elle déteste…).

Dans les deux cas, la cible sait que vous sondez son esprit et, à moins que vous ne tourniez votre attention vers une autre créature, votre cible peut utiliser son action à son tour pour faire un test d'[Intelligence](hd_abilities_intelligence.md) opposé au vôtre. Si elle réussit, le sort se termine.

Les questions directement posées à l'oral à une cible orientent naturellement le cours de ses pensées, ce sort est donc particulièrement utile lors d'un interrogatoire.

Vous pouvez aussi utiliser ce sort pour détecter la présence de créatures intelligentes que vous ne voyez pas.

Vous pouvez chercher les pensées qui se trouvent dans un rayon de 9 mètres autour de vous au moment où vous lancez ce sort ou bien par une action tandis que le sort est actif. Le sort peut franchir des obstacles, mais il est arrêté par 60 centimètres de roche, 2,5 centimètres de métal autre que le plomb ou une mince feuille de plomb. Vous ne pouvez pas repérer les créatures dotées d'une [Intelligence](hd_abilities_intelligence.md) de 3 ou moins, ni celles qui ne parlent aucune langue.

Une fois que vous avez ainsi détecté la présence d'une créature, vous pouvez lire ses pensées pendant le reste de la durée du sort, comme expliqué plus haut, même si vous ne la voyez pas, mais elle doit tout de même se trouver à portée.

Pendant toute la durée du sort, vous savez s'il y a une aberration, un céleste, un élémentaire, une fée, un fiélon ou un mort-vivant dans un rayon de 9 mètres autour de vous et vous savez précisément où il se trouve. De même, vous savez si un lieu ou un objet situé dans un rayon de 9 mètres a été consacré ou profané.

Le sort ignore la plupart des obstacles, mais il ne peut pas franchir 30 centimètres de pierre, 2,5 centimètres de métal ordinaire, une mince feuille de plomb, ni 1 mètre de bois ou de terre.

Pendant toute la durée du sort, vous percevez la présence de poisons, de créatures venimeuses et de maladies dans un rayon de 9 mètres autour de vous. Vous déterminez également leur emplacement et identifiez à chaque fois le type de poison, de créature ou de maladie concerné.

Le sort ignore la plupart des obstacles, mais il ne peut pas franchir 30 centimètres de pierre, 2,5 centimètres de métal ordinaire, une mince feuille de plomb, ni 1 mètre de bois ou de terre.

Ce sort crée un plan de force circulaire horizontal d'un mètre de diamètre pour 2,5 centimètres d'épaisseur.

Il flotte à un mètre du sol dans un espace inoccupé de votre choix situé à portée et dans votre champ de vision. Le disque persiste pendant toute la durée du sort et peut accueillir jusqu'à 250 kilogrammes. Si on pose plus de poids dessus, le sort se termine et tout ce qui se trouvait sur le disque tombe au sol.

Le disque reste immobile tant que vous vous tenez à moins de 6 mètres. Si vous vous en éloignez, il vous suit de manière à rester dans un rayon de 6 mètres autour de vous. Il peut se déplacer sur un terrain irrégulier, monter ou descendre des escaliers, des pentes, etc. Mais il ne peut pas franchir une différence de niveau de 3 mètres ou plus. Par exemple, il ne peut pas passer au-dessus d'une fosse de 3 mètres de profondeur ni la quitter s'il a été formé au fond.

Si vous vous éloignez à plus de 30 mètres du disque (typiquement parce qu'il ne peut pas contourner un obstacle pour vous suivre), le sort se termine.

Choisissez une créature, un objet ou un effet magique à portée. Tout sort de niveau 3 ou inférieur qui l'affecte se termine. Si la cible est affectée par un sort de niveau 4 ou plus, faites un test de caractéristique en utilisant votre caractéristique d'incantation. Le DD est de 10 + niveau du sort. Ce dernier se termine si vous réussissez votre test.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, vous mettez automatiquement un terme à un sort affectant la cible quand le niveau de ce sort est égal ou inférieur au niveau de l'emplacement de sort que vous utilisez.

Une énergie scintillante vous entoure et vous protège contre les fées, les morts-vivants et les créatures originaires d'un autre plan que le plan matériel. Pendant toute la durée du sort, les célestes, les élémentaires, les fées, les fiélons et les morts-vivants subissent un désavantage lors de leurs attaques contre vous.

Vous pouvez terminer le sort plus tôt en utilisant l'une des fonctions spéciales suivantes.

**_Annulation d'enchantement._** Vous utilisez votre action pour toucher une créature à votre portée qui se trouve [charmée](hd_conditions_charme.md), [terrorisée](hd_conditions_terrorise.md) ou possédée par un céleste, un élémentaire, une fée, un fiélon ou un mort-vivant. Cette créature n'est alors plus [charmée](hd_conditions_charme.md), [terrorisée](hd_conditions_terrorise.md) ni possédée par ces créatures.

**_Renvoi._** Vous utilisez votre action pour faire une attaque de sort au corps-à-corps contre un céleste, un élémentaire, une fée, un fiélon ou un mort-vivant situé à une distance inférieure ou égale à votre allonge. Si vous touchez la créature, vous tentez de la renvoyer sur son plan natal. Elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md) ou retourner sur son plan natal (si elle ne s'y trouve pas déjà). Si un mort-vivant ne se trouve pas sur son plan natal, il est renvoyé dans les plans inférieurs, tandis qu'une fée sera expulsée sur son plan d'origine.

Grâce à votre magie et à une offrande, vous entrez en contact avec un dieu ou l'un de ses serviteurs. Vous lui posez une unique question à propos d'un objectif, d'un événement ou d'une activité qui doit se dérouler dans les 7 jours à venir. Le MJ vous donne une réponse sincère, pouvant être une courte phrase, des vers cryptiques ou un présage.

Le sort ne tient pas compte d'une éventuelle modification des circonstances susceptible de bouleverser l'issue des événements, comme l'incantation de sorts supplémentaires ou la perte ou l'arrivée d'un compagnon.

Si vous lancez ce sort à deux reprises ou plus avant un long repos, il y a 25 % de chances par incantation en sus de la première que vous obteniez une prémonition aléatoire au lieu d'une prémonition fiable. C'est au MJ de faire ce jet en secret.

Vous envoyez de l'énergie négative dans le corps d'une créature située à portée et dans votre champ de vision, ce qui lui inflige des douleurs déchirantes. La cible doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). Si elle échoue, elle subit 7d8+30 dégâts nécrotiques, la moitié seulement si elle réussit.

Si ce sort achève un humanoïde, ce dernier se relève au début de votre prochain tour sous forme de zombi à jamais sous votre contrôle. Il suit vos ordres verbaux au mieux de ses capacités.

Vous tentez d'envoûter un humanoïde situé à portée et dans votre champ de vision. Il doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md), sans quoi il est [charmé](hd_conditions_charme.md) par vous pendant toute la durée du sort. Il dispose d'un avantage lors du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) si vous ou des créatures amicales envers vous êtes en train de le combattre.

Tant que l'humanoïde est [charmé](hd_conditions_charme.md), vous entretenez un lien télépathique avec lui qui persiste tant que vous vous trouvez sur le même plan d'existence. Vous pouvez utiliser ce lien télépathique pour donner des ordres à cette créature tant que vous êtes conscient (ce qui ne vous demande pas d'action). Elle fait de son mieux pour vous obéir. Vous pouvez lui donner un ordre simple et générique, comme « attaque cette créature », « cours jusque là-bas » ou « va chercher cet objet ». Si elle ne reçoit pas de nouvelle instruction de votre part une fois l'ordre exécuté, elle se contente de se défendre et de se préserver au mieux.

Vous pouvez utiliser votre action pour prendre le contrôle total de votre cible et la diriger de façon précise.

Jusqu'à la fin de votre prochain tour, elle exécute seulement les actions que vous choisissez et ne fait rien que vous ne lui ayez autorisé. Pendant cette période, vous pouvez aussi lui faire exécuter une réaction, mais vous devez pour cela également dépenser votre propre réaction.

À chaque fois que la cible subit des dégâts, elle a droit à un nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) contre le sort.

Si elle le réussit, le sort prend fin.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 6, la durée devient « concentration, jusqu'à 10 minutes ». Si vous lancez ce sort en utilisant un emplacement de niveau 7, la durée devient « concentration, jusqu'à 1 heure ».

Si vous lancez ce sort en utilisant un emplacement de niveau 8, la durée devient « concentration, jusqu'à 8 heures ».

Vous tentez d'envoûter une créature située à portée et dans votre champ de vision. Elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md), sans quoi elle est [charmée](hd_conditions_charme.md) par vous pendant toute la durée du sort. Elle dispose d'un avantage lors du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) si vous ou des créatures amicales envers vous êtes en train de la combattre.

Tant que la créature est [charmée](hd_conditions_charme.md), vous entretenez un lien télépathique avec elle qui persiste tant que vous vous trouvez sur le même plan d'existence. Vous pouvez utiliser ce lien télépathique pour donner des ordres à cette créature tant que vous êtes conscient (ce qui ne vous demande pas d'action). Elle fait de son mieux pour vous obéir. Vous pouvez lui donner un ordre simple et générique, comme « attaque cette créature », « cours jusque là-bas » ou « va chercher cet objet ». Si elle ne reçoit pas de nouvelle instruction de votre part une fois l'ordre exécuté, elle se contente de se défendre et de se préserver au mieux.

Vous pouvez utiliser votre action pour prendre le contrôle total de votre cible et la diriger de façon précise.

Jusqu'à la fin de votre prochain tour, elle exécute seulement les actions que vous choisissez et ne fait rien que vous ne lui ayez autorisé. Pendant cette période, vous pouvez aussi lui faire exécuter une réaction, mais vous devez pour cela également dépenser votre propre réaction.

À chaque fois que la cible subit des dégâts, elle a droit à un nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) contre le sort.

Si elle le réussit, le sort prend fin.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 9, la durée devient « concentration, jusqu'à 8 heures ».

Vous tentez d'envoûter une bête située à portée et dans votre champ de vision. Elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md), sans quoi elle est [charmée](hd_conditions_charme.md) par vous pendant toute la durée du sort. Elle dispose d'un avantage lors du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) si vous ou des créatures amicales envers vous êtes en train de la combattre.

Tant que la bête est [charmée](hd_conditions_charme.md), vous entretenez un lien télépathique avec elle, qui persiste tant que vous vous trouvez sur le même plan d'existence. Vous pouvez utiliser ce lien télépathique pour donner des ordres à cette créature tant que vous êtes conscient (ce qui ne vous demande pas d'action). Elle fait de son mieux pour vous obéir. Vous pouvez lui donner un ordre simple et générique, comme « attaque cette créature », « cours jusque là-bas » ou « va chercher cet objet ». Si elle ne reçoit pas de nouvelle instruction de votre part une fois l'ordre exécuté, elle se contente de se défendre et de se préserver au mieux.

Vous pouvez utiliser votre action pour prendre le contrôle total de votre cible et la diriger de façon précise.

Jusqu'à la fin de votre prochain tour, elle exécute seulement les actions que vous choisissez et ne fait rien que vous ne lui ayez autorisé. Pendant cette période, vous pouvez aussi lui faire exécuter une réaction, mais vous devez pour cela également dépenser votre propre réaction.

À chaque fois que la cible subit des dégâts, elle a droit à un nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) contre le sort.

Si elle le réussit, le sort prend fin.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 5, la durée devient « concentration, jusqu'à 10 minutes ». Si vous lancez ce sort en utilisant un emplacement de niveau 6, la durée devient « concentration, jusqu'à 1 heure ». Si vous lancez ce sort en utilisant un emplacement de niveau 7, la durée devient « concentration, jusqu'à 8 heures ».

Vous touchez un cadavre ou des restes. Pendant toute la durée du sort, la cible est protégée contre la décomposition et ne peut pas se transformer en mort-vivant.

Le sort rallonge aussi la période pendant laquelle on peut rappeler la cible d'entre les morts, car les jours passés sous l'influence de ce sort ne sont pas décomptés de la période pendant laquelle on peut utiliser des sorts comme rappel à la vie.

Vous créez l'un des effets suivants à portée après quelques murmures adressés aux esprits de la nature.

* Vous créez un effet sensoriel réduit et inoffensif qui annonce le temps qu'il fera là où vous vous trouvez pendant les 24 heures à venir. Cet effet peut prendre la forme d'un orbe doré si le temps va rester dégagé, d'un nuage s'il va pleuvoir, de flocons pour une averse de neige etc. L'effet persiste pendant 1 round.

* Vous faites éclore une fleur ou un bourgeon ou germer une graine.

* Vous créez un effet sensoriel instantané, réduit et inoffensif, comme des feuilles qui tombent, une bourrasque, le bruit que ferait un petit animal ou une légère odeur de moufette. L'effet doit être contenu dans un cube d'au maximum 1,50 mètre d'arête.

* Vous allumez ou éteignez instantanément une chandelle, une torche ou un petit feu de camp.

Un éclair formant une ligne de 30 mètres de long pour 1,50 mètre de large jaillit de votre personne et file dans la direction de votre choix. Chaque créature située sur la ligne doit réaliser un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md).

Celles qui échouent subissent 8d6 dégâts de foudre, les autres la moitié seulement.

La foudre embrase les objets inflammables de la zone qui ne sont ni portés ni transportés par une créature.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, les dégâts augmentent de 1d6 par niveau au-delà du niveau 3.

Vous jetez un éclat de bois qui prend la forme d'une véritable javeline et part en direction de votre cible.

Vous devez réussir une attaque de sort à distance pour toucher votre cible. En cas de réussite, l'éclat de bois inflige 1d6 dégâts perforants. La zone de critique de l'attaque est de 18-20. L'éclat de bois est considéré comme une arme magique.

Vous pouvez lancer un éclat de bois supplémentaire lorsque vous atteignez les niveaux 5, 11 et 17. Ces éclats peuvent viser différentes cibles à portée du sort.

La chaude lumière du soleil illumine une zone de 18 mètres de rayon centrée sur un point de votre choix situé à portée. Chaque créature présente dans cette lumière doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md).

Celles qui échouent subissent 12d6 dégâts radiants et sont [aveuglées](hd_conditions_aveugle.md) pendant 1 minute. Les autres subissent seulement la moitié des dégâts et ne sont pas [aveuglées](hd_conditions_aveugle.md) par le sort. Les vases et les morts-vivants sont affectés par un désavantage lors de ce [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md).

Une créature [aveuglée](hd_conditions_aveugle.md) par le sort fait un autre jet de [Constitution](hd_abilities_constitution.md) à la fin de chacun de ses tours. Dès qu'elle réussit, sa cécité disparaît.

Ce sort dissipe toutes les ténèbres issues d'un sort présentes dans la zone.

Huit rayons de lumière multicolores jaillissent de votre main. Chacun a une couleur différente et possède des pouvoirs et objectifs distincts. Chaque créature présente dans un cône de 18 mètres doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Lancez 1d8 par cible pour savoir quelle couleur l'affecte.

**_1. Rouge._** La cible subit 10d6 dégâts de feu si elle rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), la moitié seulement si elle le réussit.

**_2. Orange._** La cible subit 10d6 dégâts d'acide si elle rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), la moitié seulement si elle le réussit.

**_3. Jaune._** La cible subit 10d6 dégâts de foudre si elle rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), la moitié seulement si elle le réussit.

**_4. Vert._** La cible subit 10d6 dégâts de poison si elle rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), la moitié seulement si elle le réussit.

**_5. Bleu._** La cible subit 10d6 dégâts de froid si elle rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), la moitié seulement si elle le réussit.

**_6. Indigo._** Si la cible rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), elle est [entravée](hd_conditions_entrave.md) et doit alors faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) à la fin de chacun de ses tours. Si elle en réussit trois, le sort se termine, si elle en rate trois, elle se change définitivement en pierre et est [pétrifiée](hd_conditions_petrifie.md). Les succès et les échecs n'ont pas à être consécutifs : tenez le compte dans chaque catégorie jusqu'à ce que l'une d'elles arrive à trois.

**_7. Violet._** La cible est [aveuglée](hd_conditions_aveugle.md) si elle rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md). Elle doit alors faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) au début de votre prochain tour. Si elle le réussit, elle recouvre la vue ; si elle le rate, elle est emportée sur un autre plan d'existence choisi par le MJ et recouvre aussi la vue. (En général, une créature qui ne se trouve pas sur son propre plan d'existence est bannie là-bas tandis que les autres créatures sont envoyées sur le plan astral ou éthéré.) 8. Spécial. Deux rayons viennent frapper la cible. Relancez deux fois le dé en le relançant à chaque fois que vous obtenez un 8.

Vous créez des entraves magiques pour immobiliser une créature située à portée et dans votre champ de vision.

La cible doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) ou se retrouver emprisonnée par le sort. Si elle réussit, elle est immunisée contre ce sort si vous le lancez de nouveau. Tant que la créature est affectée par le sort, elle n'a pas besoin de respirer, de manger, ni de boire et ne vieillit plus. Les sorts de divination ne parviennent plus à la localiser ni à la percevoir.

Vous devez opter pour l'une des formes d'emprisonnement suivantes quand vous lancez le sort.

**_Confinement minimal._** La cible rétrécit jusqu'à ne plus faire que 2,5 centimètres de haut et se retrouve emprisonnée dans une gemme ou un objet similaire. La lumière traverse la gemme normalement (ce qui permet à la cible de voir l'extérieur et aux autres créatures de regarder dedans) mais rien d'autre ne peut traverser sa paroi, pas même les méthodes de téléportation ni les voyages planaires. Il est impossible de tailler la gemme ou de la briser tant que le sort fait effet. La composante spéciale de cette version du sort est une grande gemme transparente comme un corindon, un diamant ou un rubis.

**_Enchaîné._** La cible est retenue par de lourdes chaînes fermement ancrées au sol. Elle est [entravée](hd_conditions_entrave.md) jusqu'à ce que le sort se termine et, jusque-là, elle ne peut pas se déplacer ni être déplacée par quelque moyen que ce soit.

La composante spéciale de cette version du sort est une fine chaîne faite de métal précieux.

**_Enseveli._** La cible est ensevelie dans les profondeurs de la terre, dans une sphère de force magique tout juste assez grande pour la contenir. Rien ne peut traverser cette sphère et les créatures ne peuvent pas recourir au voyage planaire pour y entrer ou en sortir. La composante spéciale de cette version du sort est un petit orbe en mithral.

**_Prison isolée._** Le sort transporte la cible dans un minuscule demi-plan protégé contre la téléportation et les voyages planaires. Ce demi-plan peut-être un labyrinthe, une cage, une tour ou une structure confinée similaire de votre choix. La composante spéciale de cette version du sort est une représentation miniature de la prison, faite de jade.

**_Sommeil._** La cible s'endort et il est impossible de la réveiller. La composante spéciale de cette version du sort est un bouquet d'herbes soporifiques très rares.

**_Mettre fin au sort._** Lors de l'incantation et quelle que soit la version du sort, vous pouvez préciser une condition spéciale qui met fin au sort et libère la cible. Cette condition peut être aussi spécifique ou aussi élaborée que vous le désirez, mais le MJ doit confirmer que cette condition est réalisable et a une chance d'être remplie.

Elle peut se baser sur le nom de la créature, son identité ou sa divinité, mais elle doit sinon reposer sur des actions ou des qualités observables et non sur des éléments intangibles comme le niveau, la classe ou les points de vie.

_[Dissipation de la magie](hd_spells_dissipation_de_la_magie.md)_ peut mettre fin au sort à condition d'être lancée depuis un emplacement de sort de niveau 9 en visant la prison ou la composante matérielle spéciale utilisée pour lancer le sort.

Vous pouvez utiliser une composante spéciale pour créer une prison à la fois seulement. Si vous relancez ce sort en utilisant la même composante, la cible de la première incantation est libérée sur-le-champ.

Des herbes et des lianes entremêlées jaillissent du sol dans un carré de 6 mètres de côté centré sur un point de votre choix à portée. Pendant toute la durée du sort, les végétaux transforment la zone en terrain difficile.

Une créature qui se trouve dans la zone affectée lorsque vous lancez le sort doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md), sans quoi elle reste [entravée](hd_conditions_entrave.md) dans les plantes jusqu'à ce que le sort se termine. Une créature [entravée](hd_conditions_entrave.md) peut utiliser une action pour faire un test de [Force](hd_abilities_strength.md) contre le DD du sort. Si elle réussit, elle se libère.

Quand le sort se termine, les plantes invoquées flétrissent.

Grâce à ce sort, vous vous attachez de force les services d'un céleste, d'un élémentaire, d'une fée ou d'un fiélon. La créature doit se trouver à portée pendant toute la durée du sort. (En général, elle est d'abord invoquée au centre d'un _[cercle magique](hd_spells_cercle_magique.md)_ inversé où elle reste piégée le temps de l'incantation.) La cible doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md) à la fin de l'incantation. Si elle échoue, elle est contrainte de vous servir pendant toute la durée du sort. Si elle a été invoquée ou créée via un autre sort, la durée de ce dernier se prolonge jusqu'à égaler celle de l'entrave planaire.

La créature liée doit suivre vos instructions au mieux de ses capacités. Vous pouvez lui demander de vous accompagner lors d'une aventure, de protéger un lieu ou de transmettre un message. La créature suit vos instructions à la lettre mais, si elle est hostile envers vous, elle peut tout à fait interpréter vos paroles de manière à satisfaire ses propres objectifs. Si la créature a exécuté vos instructions avant la fin du sort, elle revient vers vous pour vous en informer si elle se trouve sur le même plan d'existence que vous. Si vous êtes sur un autre plan, elle se rend là où vous l'avez liée et y reste jusqu'à la fin du sort.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau supérieur, la durée augmente : 10 jours au niveau 6, 30 au niveau 7, 180 au niveau 8 et 1 an et 1 jour au niveau 9.

Vous envoyez un court message d'au maximum vingtcinq mots à une créature qui vous est familière. Elle entend le message dans son esprit, sait que c'est vous qui le lui avez envoyé si elle vous connaît, et peut vous répondre immédiatement de la même manière. Le sort permet aux créatures dotées d'une [Intelligence](hd_abilities_intelligence.md) supérieure ou égale à 1 de comprendre le sens de votre message.

Vous pouvez envoyer votre message à n'importe quelle distance, et même sur un autre plan d'existence, mais il y a 5 % de chances, si la cible est sur un autre plan, que le message ne lui parvienne pas.

Vous entonnez une suite de paroles envoûtantes qui obligent les créatures de votre choix qui vous entendent et sont situées à portée et dans votre champ de vision à effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md). Une créature qui ne peut pas être [charmée](hd_conditions_charme.md) réussit automatiquement ce [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md). Si vous ou vos compagnons vous battez contre une de ces créatures, elle dispose d'un avantage lors du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md). Si la créature rate son jet, elle subit un désavantage lors des tests de [Sagesse (Perception)](hd_abilities_wisdom_perception.md) destinés à percevoir une créature autre que vous jusqu'à ce que le sort se termine ou jusqu'à ce qu'elle ne puisse plus vous entendre. Le sort se termine si vous êtes [neutralisé](hd_conditions_neutralise.md) ou dans l'incapacité de parler.

Vous touchez une créature vivante à 0 point de vie, ce qui la stabilise. Ce sort n'a aucun effet sur les morts-vivants et les créatures artificielles.

Votre épée devient une épée de justice pour toute la durée du sort. Elle bénéficie donc d'un bonus de +3 aux jets d'attaque et aux dégâts, inflige 2d10 dégâts radiants supplémentaires contre les fiélons et les morts-vivants, et crée une aura de 3 mètres de rayon octroyant à vos alliés qui s'y trouvent un avantage aux [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) contre les sorts et effets magiques. De plus, lorsque l'épée de justice blesse pour la première fois un fiélon ayant un nombre de DV inférieur ou égal au vôtre, celui-ci doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md) sous peine de disparaître aussitôt et d'être contraint de retourner à son plan d'origine.

Vous créez un plan de force en forme d'épée qui plane à portée et persiste pendant toute la durée du sort.

Dès que l'épée apparaît, vous faites une attaque de sort au corps-à-corps contre une cible de votre choix située dans un rayon de 1,50 mètre autour de l'épée. Si l'épée touche, la cible subit 3d10 dégâts de force. Tant que le sort n'est pas terminé, vous pouvez dépenser une action bonus à chacun de vos tours pour déplacer l'épée d'un maximum de 6 mètres afin de la conduire à un endroit situé dans votre champ de vision, puis répéter l'attaque contre la même cible ou une autre.

Vous vous attaquez à l'esprit d'une créature située à portée et dans votre champ de vision en essayant de briser son intellect et sa personnalité. La cible subit 4d6 dégâts psychiques et doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) d'[Intelligence](hd_abilities_intelligence.md).

Si la cible rate son jet, son [Intelligence](hd_abilities_intelligence.md) et son [Charisme](hd_abilities_charisma.md) tombent à 1. Elle ne peut plus lancer de sort, activer d'objet magique, comprendre une langue ni communiquer de manière intelligible. En revanche, elle est toujours capable de reconnaître ses amis, de les suivre et même de les protéger.

La créature peut refaire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) tous les 30 jours. Le sort se termine dès qu'elle réussit. On peut aussi mettre un terme à ce sort grâce à l'un des sorts suivants : _[restauration supérieure](hd_spells_restauration_superieure.md)_, _[guérison](hd_spells_guerison.md)_ ou _[souhait](hd_spells_souhait.md)_.

Vous touchez une créature consentante et, jusqu'à la fin du sort, vous l'immunisez contre les dégâts psychiques, les effets percevant les émotions ou révélant les pensées, les sorts de divination et l'état [charmé](hd_conditions_charme.md). Ce sort déjoue même les _[souhaits](hd_spells_souhait.md)_ et les sorts et effets de même puissance qui cherchent à affecter l'esprit de la cible ou à obtenir des informations à son propos.

Vous appelez des esprits qui vous protègent. Ils volettent autour de vous dans un rayon de 4,50 mètres pendant toute la durée du sort. Si vous êtes Bon ou Neutre, ils ont une apparence angélique ou féerique (à vous de choisir). Si vous êtes Mauvais, ils ont une apparence fiélone.

Quand vous lancez le sort, vous pouvez désigner autant de créatures que vous le voulez afin qu'il ne les affecte pas. Une créature affectée voit sa vitesse réduite de moitié dans la zone et, quand elle y entre pour la première fois de son tour ou quand elle y commence son tour, elle doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md).

Si elle échoue, elle subit 3d8 dégâts radiants (si vous êtes Bon ou Neutre) ou 3d8 dégâts nécrotiques (si vous êtes Mauvais). Si elle réussit son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), elle subit seulement la moitié de ces dégâts.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, les dégâts augmentent de 1d8 par niveau au-delà du niveau 3.

Vous puisez dans les peurs les plus profondes d'un groupe de créatures et créez des êtres illusoires dans leurs esprits, qu'elles sont les seules à voir. Chaque créature située dans une sphère de 9 mètres de rayon centrée sur un point de votre choix situé à portée doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) ou être [terrorisée](hd_conditions_terrorise.md) pendant toute la durée du sort. Les illusions se basent sur les peurs enfouies en chaque cible et transforment leurs pires cauchemars en menace implacable. À la fin de chacun de ses tours, une créature [terrorisée](hd_conditions_terrorise.md) doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md). Si elle échoue, elle subit 4d10 dégâts psychiques. Si elle réussit, le sort se termine pour elle.

Une fois que vous avez passé la durée de l'incantation à tracer des sentiers magiques dans une pierre précieuse, vous touchez un animal ou une plante de taille TG ou inférieure qui doivent être dépourvus de toute valeur d'[Intelligence](hd_abilities_intelligence.md) ou posséder une [Intelligence](hd_abilities_intelligence.md) de 3 ou moins. La cible reçoit alors une [Intelligence](hd_abilities_intelligence.md) de 10 et la possibilité de parler un langage que vous connaissez. Si la cible est une plante, elle peut se déplacer à l'aide de ses branches, de ses racines, de ses lianes, de ses vrilles ou autre et gagne des sens similaires à ceux d'un humain.

C'est au MJ de choisir les caractéristiques appropriées à la plante éveillée, en lui appliquant par exemple le profil d'un buisson ou d'un arbre éveillé.

La bête ou la plante éveillée est considérée [charmée](hd_conditions_charme.md) par vous pendant 30 jours ou jusqu'à ce que vous ou l'un de vos compagnons la blessiez. Une fois que cet effet se termine, la créature éveillée décide seule si elle reste amicale envers vous, selon la façon dont vous l'avez traitée lorsqu'elle était [charmée](hd_conditions_charme.md).

Vous créez un passage de 1,50 mètre de côté et de 15 mètres de profondeur dans la pierre ou la terre (de la roche ou un mur) et dans le bois, mais pas dans le métal. Le passage créé est permanent et l'effet du sort ne peut être dissipé. Plusieurs incantations du sort permettent de de former des tunnels souterrains ne nécessitant pas d'étaiement. Vous pouvez orienter le tunnel dans la direction de votre choix.

La prochaine fois que vous réussissez une attaque de corps-à-corps pendant la durée du sort, vous lancez un ordre de repentir sur la créature que vous frappez. Sur cette attaque, elle subit 3d8 dégâts psychiques, écrasée par le poids de ses péchés et la culpabilité. En outre, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) ou être [étourdie](hd_conditions_etourdi.md) jusqu'à la fin de son prochain tour et subir un désavantage à tous ses tests de [Sagesse](hd_abilities_wisdom.md) pour une minute.

Un éclair d'énergie crépitante file vers une créature à portée. Faites un jet d'attaque de sort à distance contre la cible. Si vous réussissez, elle subit 1d10 dégâts de force.

Le sort crée des rayons supplémentaires quand vous atteignez certains niveaux : deux rayons au niveau 5, trois au niveau 11 et quatre au niveau 17. Vous pouvez diriger tous les rayons sur une même cible ou les répartir entre plusieurs. Faites un jet d'attaque distinct pour chacun.

Vous convertissez des matériaux bruts en produits finis faits de la même matière. Par exemple, vous pouvez fabriquer un pont de bois à partir de souches d'arbres, une corde à base d'un tas de chanvre, et des habits à partir de lin ou de laine.

Choisissez des matériaux bruts situés à portée et dans votre champ de vision. Vous pouvez fabriquer un objet de taille G ou inférieure (contenu dans un cube de 3 mètres de côté ou dans huit cubes reliés de 1,50 mètre de côté), à condition d'avoir assez de matière première. Toutefois, si vous travaillez avec du métal, de la pierre ou une autre substance minérale, l'objet fabriqué ne doit pas dépasser la taille M (donc tenir dans un cube de 1,50 mètre de côté). La qualité de l'objet fabriqué dépend de celle des matières premières.

Il est impossible de créer ou de transmuter des créatures ou des objets magiques à l'aide de ce sort. Vous ne pouvez pas non plus y recourir pour fabriquer des objets demandant un haut degré d'expertise, comme des bijoux, des armes, du verre ou une armure, à moins que vous n'ayez la maîtrise des outils d'artisan nécessaires à l'élaboration de tels objets.

Vous touchez un objet de pierre de taille M ou inférieure ou une section de pierre d'un maximum de 1,50 mètre dans toutes les dimensions et lui donnez la forme que vous désirez. Vous pouvez, par exemple, façonner un gros caillou de manière à en faire une arme, une idole ou un coffre, ou bien creuser un étroit passage dans un mur, à condition que ce dernier ne fasse pas plus de 1,50 mètre d'épaisseur. Vous pouvez façonner une porte de pierre ou son chambranle pour la sceller. L'objet créé peut avoir au maximum deux charnières et un loquet, mais il est impossible de créer des mécanismes plus complexes.

Vos prières vous imprègnent d'une aura radieuse.

Jusqu'à la fin du sort, les attaques que vous portez avec une arme infligent 1d4 dégâts radiants supplémentaires en cas de coup au but.

Vous matérialisez un grand festin, comprenant des boissons et des mets de grande qualité. Il faut 1 heure pour terminer le festin, qui disparaît au bout de cette durée. Ses effets bénéfiques se manifestent uniquement une fois cette heure écoulée. Douze créatures au maximum peuvent se joindre à vous lors de ce repas.

Une créature qui participe au festin en retire plusieurs bénéfices. Elle est guérie de toutes les maladies et de tous les poisons qui l'affectaient, elle est immunisée contre le poison et l'état [terrorisé](hd_conditions_terrorise.md), et elle obtient un avantage lors de tous ses [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md).

Son maximum de points de vie augmente de 2d10 et elle gagne le même nombre de points de vie. Ces bénéfices persistent pendant 24 heures.

Une explosion de flammes noires jaillit de votre corps et blesse les créatures située à moins de 1,50 mètre de vous.

Chaque créature dans la zone doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md), ou subir 2d6 dégâts nécrotiques et être [aveuglée](hd_conditions_aveugle.md) jusqu'à votre prochain tour. En cas de réussite, elle ne subit que la moitié des dégâts et n'est pas [aveuglée](hd_conditions_aveugle.md).

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de sorts de niveau 2 ou supérieur, les dégâts augmentent de 1d6 pour chaque emplacement au-delà du niveau 1.

Une flamme à la luminosité égale à celle d'une torche embrase soudain l'objet que vous touchez. L'effet du sort ressemble à une flamme ordinaire, mais ne dégage pas de chaleur et ne consomme pas d'oxygène. On peut couvrir ou cacher la flamme éternelle, mais pas l'étouffer ni l'éteindre avec de l'eau.

Une lumière flamboyante s'abat sur une créature située à portée et dans votre champ de vision. La cible doit réussir un jet de [Dextérité](hd_abilities_dexterity.md) ou subir 1d8 dégâts radiants.

Même si elle se trouve derrière un abri, la cible ne bénéficie pas d'un avantage lors du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md).

Les dégâts du sort augmentent de 1d8 quand vous atteignez le niveau 5 (2d8), 11 (3d8) et 17 (4d8).

Trois créatures de votre choix au maximum, toutes situées à portée et dans votre champ de vision, sont contraintes d'effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md).

Dès qu'une cible qui a raté ce jet effectue un jet d'attaque ou de sauvegarde alors que le sort n'est pas terminé, elle doit lancer 1d4 et soustraire le résultat obtenu de son jet d'attaque ou de sauvegarde.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, vous pouvez viser une créature de plus par niveau au-delà du niveau 1.

Un essaim de sauterelles carnivores forme une sphère de 6 mètres de rayon centrée sur un point de votre choix situé à portée. La sphère s'étend en contournant les angles et persiste pendant toute la durée du sort. La visibilité est réduite dans la zone affectée. L'intérieur de la sphère devient un terrain difficile.

Quand la sphère d'insectes apparaît, chaque créature prise à l'intérieur doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). Une créature subit 4d10 dégâts perforants si elle rate son jet, la moitié seulement si elle le réussit.

Une créature doit effectuer le même jet quand elle entre dans la sphère pour la première fois de son tour ou quand elle y termine son tour.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, les dégâts augmentent de 1d10 par niveau au-delà du niveau 5.

Une flèche d'un vert chatoyant file vers une cible située à portée et explose en une gerbe d'acide. Faites une attaque de sort à distance contre la cible. Si vous touchez, la cible reçoit 4d4 dégâts d'acide immédiatement et 2d4 dégâts d'acide à la fin de son prochain tour. Si vous ne touchez pas, l'acide éclabousse la cible et lui inflige la moitié des dégâts initiaux, mais aucun à la fin de son prochain tour.

**_À plus haut niveau._** Quand vous utilisez ce sort via un emplacement de niveau 3 ou supérieur, les dégâts initiaux et secondaires augmentent de 1d4 par niveau au-delà du niveau 2.

L'énergie nécromantique inonde une créature de votre choix située à portée et dans votre champ de vision, et draine ses fluides corporels et sa vitalité. La cible doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). Si elle échoue, elle reçoit 8d8 dégâts nécrotiques, la moitié seulement si elle réussit son jet. Ce sort n'a aucun effet sur les morts-vivants ou les créatures artificielles.

Si vous visez une créature végétale ou une plante magique, elle subit un désavantage lors du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) et le sort lui inflige le maximum de dégâts possible. Si vous visez une plante non magique qui n'est pas une créature, comme un arbre ou un buisson, elle n'a pas droit au moindre [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), mais se flétrit et meurt.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 5 ou supérieur, les dégâts augmentent de 1d8 par niveau au-delà du niveau 4.

Votre corps devient flou, il ondule et vacille comme une flamme aux yeux d'autrui. Pendant toute la durée du sort, les créatures subissent un désavantage lorsqu'elles font un jet d'attaque contre vous. Un attaquant est immunisé contre cet effet s'il ne se repose pas sur sa vue, s'il dispose de vision aveugle, par exemple, ou s'il peut percer les illusions à jour avec vision parfaite.

Vous pénétrez dans la région frontalière du plan éthéré, dans une zone où il chevauche votre plan actuel. Vous restez sur la frontière éthérée pendant toute la durée du sort ou jusqu'à ce que vous utilisiez une action pour y mettre fin. Pendant cette période, vous pouvez vous déplacer dans n'importe quelle direction. Si vous optez pour un déplacement vers le haut ou le bas, le prix du mouvement est doublé, chaque mètre de déplacement vous coûtant 1 mètre supplémentaire. Vous voyez et entendez ce qui se passe sur le plan d'où vous venez, mais tout y est gris et vous ne voyez plus rien au-delà de 18 mètres.

Une fois sur le plan éthéré, vous pouvez affecter uniquement des créatures situées sur ce plan, et elles sont les seules à pouvoir vous affecter. Celles qui ne se trouvent pas sur ce plan ne vous perçoivent pas et sont incapables d'interagir avec vous, à moins qu'un pouvoir spécial ou magique ne le leur permette.

Les objets et effets qui ne se trouvent pas sur le plan éthéré n'ont aucune incidence sur vous, ce qui vous permet de traverser des objets que vous apercevez sur le plan d'où vous venez.

Quand le sort se termine, vous retournez immédiatement sur le plan d'où vous venez, à l'endroit que vous occupez actuellement. Si vous occupez le même emplacement qu'un objet solide ou une créature lorsque cela se produit, vous êtes immédiatement projeté dans l'espace inoccupé le plus proche susceptible de vous accueillir et subissez 6 points de dégâts de force par mètre de distance de cette projection.

Ce sort n'a aucun effet si vous le lancez alors que vous vous trouvez sur le plan éthéré ou sur un plan non limitrophe, comme les plans extérieurs.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 8 ou supérieur, vous pouvez affecter jusqu'à trois créatures consentantes (vous y compris) par niveau au-delà du niveau 7. Toutes ces créatures doivent se trouver dans un rayon de 3 mètres autour de vous quand vous lancez le sort.

Vous touchez une créature consentante et la transformez, ainsi que tous les objets qu'elle porte et qu'elle transporte, en nuage brumeux pour toute la durée du sort. Ce dernier se termine si la créature tombe à 0 point de vie. Le sort n'affecte pas les créatures intangibles.

Sous cette forme, la cible n'a plus qu'un seul mode de déplacement : le vol, à une vitesse de 3 mètres. Elle peut entrer dans l'espace d'une autre créature et l'occuper. Elle est résistante aux dégâts non magiques et elle bénéficie d'un avantage lors des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md), de [Dextérité](hd_abilities_dexterity.md) et de [Constitution](hd_abilities_constitution.md). Elle peut passer à travers de petits trous, de minces ouvertures et même de simples fissures.

En revanche, les liquides équivalent pour elle à des surfaces solides. Elle ne peut pas tomber et continue de flotter dans les airs même si elle est [étourdie](hd_conditions_etourdi.md) ou [neutralisée](hd_conditions_neutralise.md).

Sous forme de nuage brumeux, la cible ne peut pas parler ni manipuler d'objet. Il lui est impossible de lâcher les objets qu'elle portait et qu'elle transportait, et personne ne peut les utiliser ni interagir avec eux. Elle ne peut pas attaquer ni lancer de sort.

Votre magie transforme vos alliés en animaux. Choisissez autant de créatures consentantes à portée et dans votre champ de vision que vous désirez. Vous transformez chacune d'entre elles en bête de taille G ou inférieure dotée d'un indice de dangerosité inférieur ou égal à 4. Lors de vos tours suivants, vous pouvez dépenser votre action pour transformer les créatures affectées en d'autres bêtes.

La transformation persiste pour chaque cible pendant toute la durée du sort ou jusqu'à ce que la cible tombe à 0 point de vie ou meure. Vous pouvez attribuer une forme différente à chaque cible. La cible remplace son profil technique par celui de l'animal choisi, bien qu'elle conserve son alignement, son [Intelligence](hd_abilities_intelligence.md), sa [Sagesse](hd_abilities_wisdom.md) et son [Charisme](hd_abilities_charisma.md). La cible adopte les points de vie de sa nouvelle forme et, quand elle reprend son apparence normale, elle se retrouve avec le même nombre de points de vie que celui qu'elle avait avant sa transformation. Si elle recouvre sa forme initiale suite à un passage à 0 point de vie, les dégâts en excès sont reportés sur les points de vie de sa forme initiale. Tant que ces dégâts en excès ne réduisent pas les points de vie de la forme normale de la cible à 0, elle ne tombe pas [inconsciente](hd_conditions_inconscient.md). Les actions de la créature transformée sont limitées par la nature de sa nouvelle apparence, et elle ne peut ni parler ni lancer de sort.

L'équipement de la cible fusionne avec sa nouvelle forme, mais elle ne peut pas activer ni manier la moindre pièce d'équipement et n'obtient pas les bénéfices qui en découlent habituellement.

Une créature de votre choix située à portée et dans votre champ de vision trouve soudain tout ce qui l'entoure d'une drôlerie hilarante et succombe à un fou rire irrépressible dès que ce sort l'affecte. Elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) ou se retrouver [à terre](hd_conditions_a_terre.md), [neutralisée](hd_conditions_neutralise.md) et incapable de se relever pendant toute la durée du sort. Ce sort n'affecte pas les créatures dotées d'une [Intelligence](hd_abilities_intelligence.md) de 4 ou moins.

À la fin de chacun de ses tours et à chaque fois qu'elle subit des dégâts, la cible a droit à un nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md). Elle bénéficie d'un avantage lors de ce jet si ce sont des dégâts qui l'ont provoqué. Si le jet est réussi, le sort se termine.

La prochaine fois que vous réussissez une attaque de corps-à-corps pendant la durée du sort, votre arme frappe votre cible avec l'énergie de la justice sacrée. La cible subit 2d6 dégâts supplémentaires et un effet secondaire.

Le type de dégâts supplémentaires infligés et la nature de l'effet dépendent du type de dégâts infligés par votre arme (par exemple, tranchant pour une épée, contondant pour un marteau) :

* Contondant : dégâts de tonnerre et [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md) ou [assourdi](hd_conditions_assourdi.md) pendant 1 round et à terre.

* Perçant : dégâts psychiques et [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) ou effrayé pendant 1 round.

* Tranchant : dégâts radiants et [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md) ou [aveuglé](hd_conditions_aveugle.md) pendant 1 round.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, vous infligez 1d6 points de dégât par niveau d'emplacement de sort au-dessus du niveau 1.

La prochaine attaque avec une arme de corps-àcorps ou à distance qui vous permet de toucher une créature avant la fin de ce sort voit votre arme briller soudain d'une lumière astrale et infliger 2d6 dégâts radiants additionnels à votre cible, qui devient visible si elle était [invisible](hd_conditions_invisible.md) et se met à émettre une faible lumière dans un rayon de 1,50 mètre jusqu'à la fin du sort. Elle ne peut plus devenir [invisible](hd_conditions_invisible.md) pendant toute cette durée.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, les dégâts augmentent de 1d6 par emplacement de sort au-dessus du niveau 2.

Vous entrez dans un objet ou une surface de pierre assez grande pour contenir entièrement votre corps, votre personne et votre équipement fusionnant avec la pierre pendant toute la durée du sort. Vous utilisez votre déplacement pour entrer dans la pierre en un point que vous êtes en mesure de toucher. Il ne reste alors rien de visible ni de détectable indiquant votre présence pour des sens non-magiques.

Tant que vous êtes fusionné avec la pierre, vous ne voyez pas ce qui se passe à l'extérieur et vous êtes affecté par un désavantage lors des tests de [Sagesse (Perception)](hd_abilities_wisdom_perception.md) destinés à entendre les sons qui retentissent à l'extérieur de la pierre.

Vous restez conscient du temps qui passe et vous pouvez lancer des sorts à portée personnelle. Vous pouvez utiliser votre déplacement pour quitter la pierre par l'endroit par où vous y êtes entré, ce qui met fin au sort. En dehors de cela, vous êtes dans l'incapacité de vous déplacer.

Vous n'êtes pas blessé si la pierre subit des dégâts mineurs mais, si elle est partiellement détruite ou change de forme (au point que vous ne tenez plus entièrement à l'intérieur), elle vous expulse et vous subissez 6d6 dégâts contondants. Si la pierre est complètement détruite (ou transmutée en une substance différente), elle vous expulse et vous subissez 50 dégâts contondants. Si vous vous faites expulser de la pierre, vous vous retrouvez à terre dans l'emplacement inoccupé le plus proche de celui par lequel vous êtes entré dans la roche.

Durée d'incantation : 1 action Un gardien spectral de taille G apparaît et flotte dans un emplacement inoccupé de votre choix situé dans votre champ de vision et à portée. Il occupe alors cet emplacement, mais sa silhouette reste indistincte, à l'exception de son arme luisante et de son bouclier frappé du symbole de votre divinité.

Toute créature hostile envers vous qui entre dans un emplacement situé dans un rayon de 3 mètres autour du gardien pour la première fois de son tour doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Si elle échoue, elle subit 20 dégâts radiant, la moitié seulement si elle réussit. Le gardien disparaît dès qu'il a infligé un total de 60 dégâts.

Un geyser d'énergie jaillit du sol d'un endroit que vous spécifiez dans la portée du sort. Vous choisissez acide, foudre, feu, froid, poison ou tonnerre comme type d'énergie pour le geyser. Chaque créature située dans le cylindre de 1,50 mètre de diamètre et de 6 mètres de haut doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md), sans quoi elle subit 3d8 dégâts du type préalablement déterminé.

Si le jet est réussi, les dégâts sont réduits de moitié.

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de sort de niveau 2 ou supérieur, les dégâts sont augmentés de 1d8 par niveau au-delà du niveau 1.

Une barrière immobile scintille légèrement dans un rayon de 3 mètres autour de vous et persiste pendant toute la durée du sort.

Tout sort de niveau 5 ou inférieur lancé depuis l'extérieur de la barrière se trouve dans l'incapacité d'affecter les créatures et les objets se trouvant à l'intérieur, même si le lanceur de sort utilise un emplacement de niveau supérieur. Le sort peut très bien viser les créatures et les objets situés au sein de la barrière, mais il n'a aucun effet sur eux. De même, la zone protégée par la barrière est exclue de la zone affectée par les sorts de ces niveaux.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, la barrière bloque les sorts d'un niveau de plus par niveau au-delà du niveau 6.

Lorsque vous lancez ce sort, vous inscrivez un glyphe capable de blesser autrui, soit sur une surface quelconque comme une table, le sol ou un mur, soit dans un objet que l'on peut refermer pour dissimuler l'inscription, comme un livre, un parchemin ou un coffre au trésor. Si vous optez pour une surface, le glyphe peut couvrir une zone de 3 mètres de diamètre au maximum.

Si vous choisissez un objet, il ne faut plus le déplacer par la suite : si quelqu'un le déplace à plus de 3 mètres de l'endroit où vous avez jeté ce sort, le glyphe se brise et le sort se termine sans avoir été déclenché.

Le glyphe est presque [invisible](hd_conditions_invisible.md). Pour le discerner, il faut réussir un test d'[Intelligence (Investigation)](hd_abilities_intelligence_investigation.md) contre le DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de votre sort.

Lors de l'incantation, c'est à vous de décider de ce qui déclenchera le sort. Pour les glyphes tracés sur une surface quelconque, les déclencheurs les plus courants consistent à toucher le glyphe ou se tenir dessus, à déplacer un objet recouvrant le glyphe, à s'approcher à une certaine distance du glyphe ou encore à manipuler l'objet sur lequel le glyphe est tracé. Pour les glyphes inscrits dans un objet, on trouve parmi les déclencheurs les plus répandus le fait d'ouvrir l'objet, de s'en approcher à une certaine distance ou de voir ou de lire le glyphe. Le sort se termine dès que le glyphe se déclenche.

Vous pouvez affiner le déclencheur, de façon à ce que le sort s'active sous certaines conditions ou en fonction de certaines caractéristiques physiques (comme le poids ou la taille), selon un type de créatures (pour un glyphe destiné aux aberrations ou aux elfes noirs par exemple) ou selon l'alignement. Vous pouvez aussi définir des conditions pour que certaines créatures ne déclenchent pas le glyphe, en prononçant un mot de passe, par exemple.

Lorsque vous dessinez le glyphe, vous devez choisir entre des runes explosives ou un glyphe à sort.

**_Glyphe à sort._** Vous pouvez stocker un sort de niveau 3 ou inférieur dans le glyphe en le lançant lors de l'incantation du glyphe. Ce sort doit viser une créature unique ou une zone. Le sort stocké n'a aucun effet immédiat quand il est lancé ainsi. Il se lance quand quelqu'un déclenche le glyphe. Si le sort affecte une cible, il vise celle qui a déclenché le glyphe. S'il affecte une zone, cette dernière est centrée sur la créature qui a déclenché le glyphe. Si le sort invoque des créatures hostiles ou crée des objets néfastes ou des pièges, ils apparaissent aussi près de l'intrus que possible et s'en prennent à lui. Si le sort nécessite de la concentration, il persiste jusqu'à la fin de sa durée maximale.

**_Runes explosives._** Quand le glyphe se déclenche, il explose dans une sphère de 6 mètres de rayon centrée sur lui. La sphère s'étend en contournant les angles si besoin. Chaque créature de la zone doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Une créature reçoit 5d8 dégâts d'acide, de froid, de feu, de foudre ou de tonnerre si elle rate son jet (à vous de choisir le type de dégâts lors de l'incantation), la moitié seulement si elle le réussit.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, les dégâts des runes explosives augmentent de 1d8 par niveau au-delà du niveau 3. Si vous créez un glyphe à sort, vous pouvez stocker un sort d'un niveau égal ou inférieur à celui employé pour lancer le glyphe.

La puissance du monde naturel imprègne le bois du bâton ou du gourdin que vous tenez. Pendant toute la durée du sort, vous pouvez utiliser votre caractéristique d'incantation au lieu de votre [Force](hd_abilities_strength.md) pour effectuer les jets d'attaque et de dégâts au corps-à-corps avec cette arme. Le dé de dégâts de l'arme devient un d8. L'arme devient magique si elle ne l'était pas déjà. Le sort se termine si vous le lancez de nouveau ou si vous lâchez votre arme.

Une couche de graisse particulièrement glissante recouvre le sol dans une zone de 3 mètres de côté centrée sur un point situé à portée et le change en terrain difficile pour toute la durée du sort.

Lorsque la graisse apparaît, chaque créature qui se trouve dans la zone affectée doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md) ou tomber à terre. Une créature qui entre dans la zone ou y termine son tour doit aussi réussir ce jet sous peine de se retrouver à terre.

Vous touchez une créature dont la vitesse augmente de 3 mètres jusqu'à la fin du sort.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, vous pouvez affecter une créature de plus par niveau au-delà du niveau 1.

Choisissez une créature située à portée et dans votre champ de vision. Une bouffée d'énergie positive la traverse et lui rend 70 points de vie. Ce sort annule aussi les états [aveuglé](hd_conditions_aveugle.md) et [assourdi](hd_conditions_assourdi.md), ainsi que toutes les maladies qui l'affectent. Ce sort n'a aucun effet sur les créatures artificielles et les morts-vivants.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, la quantité de soins prodigués augmente de 10 points par niveau au-delà du niveau 6.

Un flot d'énergie curative émane de vous et enveloppe les créatures blessées qui vous entourent. Vous rendez jusqu'à 700 points de vie, divisés comme bon vous semble entre autant de créatures situées à portée et dans votre champ de vision que vous le souhaitez.

Le sort débarrasse aussi les créatures qu'il guérit de leurs maladies et des états [assourdi](hd_conditions_assourdi.md) ou [aveuglé](hd_conditions_aveugle.md). Ce sort n'a aucun effet sur les morts-vivants et sur les créatures artificielles.

Vous effleurez le bord d'un verre, et le corps de vos alliés à portée et capables entendre le son produit se met à résonner avec l'énergie positive. Vous-même et chaque créature affectée récupérez 10 points de vie et annulez un niveau d'épuisement au début de chacun de vos tours.

Enfin, le sort met un terme aux effets de réduction des points de vie maximum provoqué par certaines créatures (momie, spectre, vampire, etc.) ainsi qu'aux états [charmé](hd_conditions_charme.md) et [pétrifié](hd_conditions_petrifie.md).

Choisissez une créature consentante située à portée et dans votre champ de vision. Jusqu'à la fin du sort, la cible voit sa vitesse doubler, bénéficie d'un bonus de +2 à la CA, a l'avantage lors des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md) et dispose d'une action de plus par tour. Cette action est uniquement réservée aux actions suivantes : attaquer (permet seulement une unique attaque), se précipiter, se désengager, se cacher ou utiliser un objet.

Quand le sort se termine, la cible ne peut pas se déplacer ni effectuer une action avant que son prochain tour ne se soit écoulé, car une vague de léthargie déferle sur elle.

Vous imprégnez de courage une créature consentante que vous touchez. Jusqu'à la fin du sort, elle est immunisée contre l'état [terrorisé](hd_conditions_terrorise.md) et, au début de chacun de ses tours, elle gagne un nombre de points de vie temporaires égal à votre modificateur de caractéristique d'incantation. Quand le sort se termine, la cible perd les éventuels points de vie temporaires restants issus de ce sort.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, vous pouvez affecter une créature de plus par niveau au-delà du niveau 1.

Vous choisissez un objet avec lequel vous devez rester en contact pendant toute l'incantation du sort. Si c'est un objet magique ou un objet imprégné de magie, vous apprenez immédiatement quelles sont ses propriétés et comment vous en servir. Vous savez aussi s'il faut s'harmoniser avec lui pour l'utiliser et combien de charges il possède, le cas échéant. Vous savez si des sorts affectent l'objet et quel est leur nom. Si l'objet a été créé grâce à un sort, vous apprenez quel sort lui a donné naissance.

Si, à la place, vous touchez une créature pendant toute l'incantation, vous découvrez quels sorts l'affectent présentement, le cas échéant.

Vous créez à portée un son ou une image représentant un objet. L'illusion persiste pendant toute la durée du sort, et se dissipe si vous révoquez le sort par une action ou si vous lancez de nouveau ce sort.

Si vous créez un son, son volume peut aller du simple murmure au hurlement. Ce peut être votre voix, celle de quelqu'un d'autre, le rugissement d'un lion, un battement de tambours ou tout autre son de votre choix. Ce bruit persiste sans faiblir pendant toute la durée du sort, à moins que vous ne préfériez émettre des sons distincts à différents moments pendant la durée du sort.

Si vous créez une image (comme une chaise, des empreintes boueuses ou un petit coffre), elle doit tenir dans un cube de 1,50 mètre d'arête. L'image ne s'accompagne pas de son, de lumière, d'odeur, ni d'autre effet sensoriel. Une interaction physique avec l'image révèle immédiatement qu'elle n'est qu'une illusion, car les objets la traversent.

Si une créature utilise son action pour examiner le son ou l'image, elle comprend qu'il s'agit d'une illusion si elle réussit un test d'[Intelligence (Investigation)](hd_abilities_intelligence_investigation.md) opposé au DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de votre sort. Si une créature perce l'illusion à jour, celle-ci perd toute substance pour elle.

Vous créez une illusion représentant un objet, une créature ou un autre phénomène visible à portée. Elle s'active une fois les conditions spécifiques remplies ; en attendant, elle est imperceptible. L'illusion doit tenir dans un cube de 9 mètres d'arête. Vous décidez de son comportement et des sons qu'elle émet au moment où vous lancez le sort. Ce comportement programmé peut durer un maximum de 5 minutes.

Quand les conditions spécifiées se présentent, l'illusion apparaît et se comporte comme vous l'avez décidé. Sa représentation finie, elle disparaît et reste en hibernation pendant 10 minutes. Ensuite, elle peut se réactiver de nouveau.

Les conditions de déclenchement peuvent être aussi génériques ou détaillées que vous le souhaitez, mais elles doivent toujours se baser sur des éléments visuels ou audibles se produisant dans un rayon de 9 mètres autour de la zone du sort. Par exemple, vous pouvez créer une illusion de vous-même qui apparaît pour avertir d'autres gens quand ils tentent d'ouvrir une porte piégée, ou vous pouvez programmer votre illusion pour qu'elle se déclenche seulement quand une créature prononce le mot de passe correct.

Les interactions physiques révèlent que l'image n'est qu'une illusion, car les objets la traversent. Si une créature utilise son action pour examiner l'image, elle comprend que c'est une illusion, à condition de réussir un test d'[Intelligence (Investigation)](hd_abilities_intelligence_investigation.md) contre le DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de votre sort. Si une créature perce l'illusion à jour, elle voit à travers l'image et les sons produits par l'illusion sonnent creux à ses oreilles.

Vous créez l'image d'un objet, d'une créature ou d'un phénomène visible pas plus grand qu'un cube de 6 mètres d'arête. L'image apparaît en un point situé à portée et dans votre champ de vision et persiste pendant toute la durée du sort. Elle a l'air absolument réelle et s'accompagne des sons, des odeurs et de la température appropriés pour la chose qu'elle représente. En revanche, elle ne dégage pas assez de chaleur ou de froid pour blesser quelqu'un, ne génère pas de son assez puissant pour provoquer des dégâts de tonnerre pour qu'une créature soit [assourdie](hd_conditions_assourdi.md), et n'émet pas une odeur assez puissante pour écoeurer une créature (comme le fait la puanteur du troglodyte).

Tant que vous êtes à portée de l'illusion, vous pouvez utiliser votre action pour déplacer l'image vers un autre point situé à portée. Quand l'image bouge, vous pouvez modifier son apparence de manière à ce que ses mouvements paraissent naturels. Par exemple, si vous créez l'image d'une créature et la déplacez, vous pouvez modifier l'image pour donner l'impression que la créature marche. De même, vous pouvez modifier les sons que l'image émet, à tel point que vous pouvez lui faire tenir une conversation, par exemple.

Les interactions physiques avec l'image révèlent qu'elle n'est qu'une illusion, car les objets la traversent. Si une créature utilise son action pour examiner l'image, elle comprend que c'est une illusion à condition de réussir un test d'[Intelligence (Investigation)](hd_abilities_intelligence_investigation.md) contre le DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de votre sort. Si une créature perce l'illusion à jour, elle voit à travers l'image et ne perçoit plus que faiblement ses autres propriétés sensorielles.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, le sort persiste jusqu'à dissipation, sans que vous ayez besoin de vous concentrer.

Trois répliques illusoires de votre personne apparaissent dans votre emplacement. Jusqu'à la fin du sort, ces répliques se déplacent en même temps que vous et imitent toutes vos actions, changeant de position de manière à ce qu'il soit impossible de savoir quelles versions de vous sont des images et quelle version est réelle. Vous pouvez utiliser une action pour révoquer les répliques illusoires.

Pendant toute la durée du sort, chaque fois qu'une créature vous prend pour cible d'une attaque, vous devez lancer 1d20 pour savoir si l'attaque touche votre personne ou l'un de vos doubles. Si vous avez trois répliques, vous devez obtenir 6 ou plus pour que l'attaque touche une réplique.

Si vous n'en avez plus que deux, vous devez faire 8 ou plus, et si vous n'en avez plus qu'une, vous devez faire 11 ou plus.

Chaque réplique possède une CA de 10 + votre modificateur de [Dextérité](hd_abilities_dexterity.md). Si l'attaque touche une réplique, elle la détruit.

Le seul moyen de détruire une réplique est de l'atteindre avec une attaque, car elle ignore tous les autres effets et dégâts.

Le sort se termine si les trois répliques sont détruites.

Une créature n'est pas affectée par ce sort si elle ne voit pas, si elle se sert d'un mode de perception autre que la vue (comme la vision aveugle) ou encore si elle perçoit les illusions comme telles, avec vision parfaite, par exemple.

Vous créez un double illusoire de votre personne qui persiste pendant toute la durée du sort. Ce double peut apparaître à n'importe quel endroit à portée, peu importent les obstacles interposés, à condition que vous l'ayez déjà vu auparavant. D'un point de vue visuel et auditif, l'illusion vous est tout à fait semblable ; en revanche, elle est intangible. Si elle subit le moindre dégât, elle disparaît et le sort se termine.

Vous pouvez utiliser votre action pour déplacer votre illusion jusqu'au double de votre vitesse, lui faire exécuter des gestes, la faire parler et se comporter comme bon vous semble. Elle imite vos manières à la perfection.

Vous pouvez entendre et voir par l'intermédiaire des oreilles et des yeux de votre double, comme si vous occupiez son emplacement. À votre tour, vous pouvez dépenser une action bonus pour passer de l'utilisation de ses sens à celle des vôtres et inversement. Tant que vous utilisez ses sens, vous êtes aveugle et sourd à votre propre environnement.

Les interactions physiques révèlent que l'image n'est qu'une illusion, car les objets la traversent. Si une créature utilise son action pour examiner l'image, elle comprend que c'est une illusion, à condition de réussir un test d'[Intelligence (Investigation)](hd_abilities_intelligence_investigation.md) contre le DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de votre sort. Si une créature perce l'illusion à jour, elle voit à travers l'image et les sons produits par l'illusion sonnent creux à ses oreilles.

Vous créez l'image d'un objet, d'une créature ou d'un phénomène visible tenant dans un cube de 4,50 mètres de côté. L'image apparaît en un point situé à portée et persiste pendant toute la durée du sort. L'image comporte seulement des composantes visuelles, elle ne s'accompagne pas d'odeur, de son, ni d'autre effet sensoriel.

Vous pouvez utiliser votre action pour déplacer l'image vers un autre point à portée. Pendant qu'elle se déplace, vous pouvez modifier son apparence pour donner l'impression d'un mouvement naturel. Par exemple, si vous créez l'image d'une créature et que vous la déplacez, vous pouvez modifier l'image pour donner l'impression que la créature est en train de marcher.

Les interactions physiques révèlent que l'image n'est qu'une illusion, car les objets la traversent. Si une créature utilise son action pour examiner l'image, elle comprend que c'est une illusion à condition de réussir un test d'[Intelligence (Investigation)](hd_abilities_intelligence_investigation.md) contre le DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de votre sort. Si une créature perce l'illusion à jour, elle voit à travers l'image.

Choisissez un humanoïde situé à portée et dans votre champ de vision. Il doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md), sans quoi il est [paralysé](hd_conditions_paralyse.md) pour toute la durée du sort. À la fin de chacun de ses tours, la cible a droit à un nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md). Si elle le réussit, le sort se termine.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, vous pouvez viser un humanoïde de plus par niveau au-delà du niveau 2. Les humanoïdes visés doivent se trouver à 9 mètres ou moins les uns des autres au moment où vous lancez le sort.

Choisissez une créature située à portée et dans votre champ de vision. Elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md), sans quoi elle est [paralysée](hd_conditions_paralyse.md) pour toute la durée du sort. Ce sort est sans effet sur les morts-vivants. À la fin de chacun de ses tours, la cible a droit à un nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md). Si elle le réussit, le sort se termine.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, vous pouvez viser une créature de plus par niveau au-delà du niveau 5.

Les créatures visées doivent se trouver à 9 mètres ou moins les unes des autres au moment où vous lancez le sort.

Vous lancez un ordre d'un mot à une créature située à portée et dans votre champ de vision. Elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md), sans quoi elle exécute votre ordre à son prochain tour. Le sort reste sans effet si la cible est un mort-vivant, si elle ne comprend pas votre langue ou si votre ordre la met directement en danger.

Voici quelques ordres typiques et leurs effets. Vous pouvez donner un ordre différent de ceux présentés ici mais, dans ce cas, c'est au MJ de décider comment la victime se comporte. Le sort se termine si elle se trouve dans l'incapacité d'obéir à l'ordre reçu.

**_Approche._** La cible s'approche de vous en empruntant l'itinéraire le plus court et le plus direct. Elle termine son tour dès qu'elle arrive dans un rayon de 1,50 mètre autour de vous.

**_Arrête._** La cible ne bouge pas et n'entreprend aucune action. Une créature en vol reste dans les airs, à condition qu'elle soit en mesure de le faire. Si elle est obligée de se déplacer pour rester en vol, elle parcourt la distance minimum requise pour ce faire.

**_Fuis._** La cible passe son tour à s'éloigner de vous par la méthode la plus rapide à sa disposition.

**_Lâche._** La cible lâche ce qu'elle tient et son tour se termine.

**_Rampe._** La cible se laisse tomber à terre et termine son tour.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, vous pouvez affecter une créature de plus par niveau au-delà du niveau 1. Ces créatures doivent toutes se trouver à 9 mètres ou moins les unes des autres lorsque vous lancez le sort.

Vous transformez un maximum de dix mille-pattes, trois araignées, cinq guêpes ou un scorpion situés à portée en version géante de leur forme naturelle pendant toute la durée du sort. Un mille-pattes devient donc un mille-pattes géant, une araignée une araignée géante, une guêpe une guêpe géante et un scorpion un scorpion géant.

Chaque créature obéit à vos ordres verbaux et, lors d'un combat, agit à chaque round à votre tour. C'est le MJ qui dispose du profil technique de ces créatures et gère leurs actions et leurs déplacements.

Une créature reste sous sa forme géante pendant toute la durée du sort, jusqu'à ce qu'elle tombe à 0 point de vie ou jusqu'à ce que vous utilisiez une action pour révoquer l'effet du sort sur elle.

Le MJ peut vous autoriser à choisir une cible différente.

Par exemple, si vous transformez une abeille, sa version géante peut disposer du même profil technique qu'une guêpe géante.

Vous créez une manifestation illusoire d'un instrument de musique fantomatique près d'une créature de votre choix à portée. Cet instrument fantomatique est visible uniquement de cette créature et la suit dans tous ses déplacements, même si elle n'est plus visible ou plus à portée du sort. L'instrument produit une musique uniquement audible par la cible, qui provoque chez elle une peine et une douleur effroyables.

Au début de chacun de ses tours, la créature doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) ou subir 2d4 dégâts psychiques et être [étourdie](hd_conditions_etourdi.md) jusqu'à son prochain tour. En cas de réussite, les dégâts sont annulés et le sort prend fin. Les créatures dont l'[Intelligence](hd_abilities_intelligence.md) est inférieure à 3 sont immunisées à ce sort, celles autres qu'humanoïdes ou géants obtiennent un avantage à leur [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md).

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de sort de niveau 2 ou supérieur, vous pouvez cibler une créature de plus par niveau au-delà du niveau 1.

Vous créez un sceau empêchant les déplacements magiques dans une zone de 60 mètres de côté au sol et d'une hauteur de 9 mètres. Pendant toute la durée du sort, les créatures ne peuvent pas se téléporter dans la zone ni y entrer via un portail comme celui issu du sort du même nom.

Le sort protège la zone contre tous les modes de déplacement planaire et empêche donc les créatures d'y entrer en passant par le plan astral, le plan éthéré, la féerie, le plan de l'ombre ou en utilisant un sort de _[changement de plan](hd_spells_changement_de_plan.md)_.

De plus, le sort blesse les créatures des types choisis lors de son incantation. Choisissez un ou plusieurs de ces types : célestes, élémentaires, fées, fiélons, morts-vivants.

Quand une créature d'un type choisi pénètre dans la zone pour la première fois de son tour ou y débute son tour, elle subit 5d10 dégâts radiants ou nécrotiques (à vous de choisir quand vous lancez le sort).

Vous pouvez décider d'un mot de passe lors de l'incantation du sort. Si une créature le prononce en entrant dans la zone, elle ne subit pas de dégât.

La zone d'effet de ce sort ne peut pas se superposer à celle d'un autre sort d'interdiction. Si vous lancez interdiction tous les jours pendant 30 jours au même endroit, le sort persiste jusqu'à dissipation et les composantes matérielles sont consommées lors de la dernière incantation.

Ce sort inverse la gravité dans un cylindre de 15 mètres de rayon et de 30 mètres de haut centré sur un point de votre choix à portée. Toutes les créatures et tous les objets qui ne sont pas ancrés au sol, d'une manière ou d'une autre, tombent vers le haut jusqu'à atteindre le sommet de la zone affectée par le sort. Une créature peut faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md) pour s'accrocher à un objet fixe situé à sa portée, afin d'éviter la chute.

Si un objet solide (comme un plafond) se trouve sur la trajectoire de la chute, les créatures et les objets le percutent comme lors d'une chute ordinaire vers le bas. Si un objet ou une créature atteint le sommet de la zone affectée sans heurter quoi que ce soit, il reste là, à osciller légèrement, pendant toute la durée du sort.

Une fois la durée du sort écoulée, les objets et les créatures affectés retombent au sol.

La créature que vous touchez devient [invisible](hd_conditions_invisible.md) jusqu'à la fin du sort. Tout ce qu'elle porte et transporte reste [invisible](hd_conditions_invisible.md) tant qu'elle le garde sur elle. Le sort se termine si la cible attaque ou lance un sort.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, vous pouvez viser une créature de plus par niveau au-delà du niveau 2.

Vous devenez [invisible](hd_conditions_invisible.md) jusqu'à ce que le sort se termine, ou vous pouvez accorder cet effet à une créature consentante que vous touchez. Tout ce que porte la cible devient [invisible](hd_conditions_invisible.md) tant que les objets restent sur sa personne.

Vous invoquez des esprits féeriques qui prennent la forme d'animaux et apparaissent dans des espaces inoccupés situés à portée et dans votre champ de vision.

Choisissez l'une des options suivantes pour déterminer quelles créatures apparaissent.

* Une bête dont l'indice de dangerosité est inférieur ou égal à 2.

* Deux bêtes dont l'indice de dangerosité est inférieur ou égal à 1.

* Quatre bêtes dont l'indice de dangerosité est inférieur ou égal à 1/2.

* Huit bêtes dont l'indice de dangerosité est inférieur ou égal à 1/4.

Chacune de ces bêtes est aussi considérée comme une fée et disparaît dès qu'elle tombe à 0 point de vie ou quand le sort se termine.

Les créatures invoquées se montrent amicales envers vous et vos compagnons. Déterminez une initiative pour les créatures invoquées, elles forment un groupe qui dispose de ses propres tours de jeu. Les animaux obéissent aux ordres verbaux que vous leur donnez (sans que cela vous demande d'utiliser une action). En l'absence d'ordre, ils se défendent contre les créatures hostiles, mais n'entreprennent pas d'autre action.

C'est le MJ qui dispose du profil technique des créatures.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant certains emplacements de niveau supérieur, vous choisissez l'une des options d'invocation décrites précédemment et faites apparaître plus de créatures : deux fois plus pour un emplacement de niveau 5, trois fois plus pour un emplacement de niveau 7 et quatre fois plus pour un emplacement de niveau 9.

Vous invoquez des élémentaires qui apparaissent dans des espaces inoccupés situés à portée et dans votre champ de vision. Choisissez l'une des options suivantes pour déterminer quelles créatures apparaissent.

* Un élémentaire dont l'indice de dangerosité est inférieur ou égal à 2.

* Deux élémentaires dont l'indice de dangerosité est inférieur ou égal à 1.

* Quatre élémentaires dont l'indice de dangerosité est inférieur ou égal à 1/2.

* Huit élémentaires dont l'indice de dangerosité est inférieur ou égal à 1/4.

Un élémentaire ainsi invoqué disparaît dès qu'il tombe à 0 point de vie ou quand le sort se termine.

Les créatures invoquées se montrent amicales envers vous et vos compagnons. Déterminez une initiative pour les créatures invoquées, elles forment un groupe qui dispose de ses propres tours de jeu. Les élémentaires obéissent aux ordres verbaux que vous leur donnez (sans que cela vous demande d'utiliser une action). En l'absence d'ordre, ils se défendent contre les créatures hostiles, mais n'entreprennent pas d'autre action.

C'est le MJ qui dispose du profil technique des créatures.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant certains emplacements de niveau supérieur, vous choisissez l'une des options d'invocation décrites précédemment et faites apparaître plus de créatures : deux fois plus pour un emplacement de niveau 6 et trois fois plus pour un emplacement de niveau 8.

Vous invoquez des créatures féeriques qui apparaissent dans des cases inoccupées situées à portée et dans votre champ de vision. Choisissez l'une des options suivantes pour déterminer quelles créatures apparaissent.

* Une créature féerique dont l'indice de dangerosité est inférieur ou égal à 2.

* Deux créatures féeriques dont l'indice de dangerosité est inférieur ou égal à 1.

* Quatre créatures féeriques dont l'indice de dangerosité est inférieur ou égal à 1/2.

* Huit créatures féeriques dont l'indice de dangerosité est inférieur ou égal à 1/4.

Une créature invoquée disparaît dès qu'elle tombe à 0 point de vie ou quand le sort se termine.

Les créatures invoquées se montrent amicales envers vous et vos compagnons. Déterminez une initiative pour les créatures invoquées, elles forment un groupe qui dispose de ses propres tours de jeu.. Les créatures féeriques obéissent aux ordres verbaux que vous leur donnez (sans que cela vous demande d'utiliser une action). En l'absence d'ordre, elles se défendent contre les créatures hostiles, mais n'entreprennent pas d'autre action.

C'est le MJ qui dispose du profil technique des créatures.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant certains emplacements de niveau supérieur, vous choisissez l'une des options d'invocation décrites précédemment et faites apparaître plus de créatures : deux fois plus pour un emplacement de niveau 6, et trois fois plus pour un emplacement de niveau 8.

Vous invoquez un céleste doté d'un indice de dangerosité inférieur ou égal à 4. Il apparaît dans une case inoccupée située à portée et dans votre champ de vision.

Le céleste disparaît dès qu'il tombe à 0 point de vie ou quand le sort se termine.

Le céleste se montre amical envers vous et vos compagnons.

Déterminez son initiative, sachant qu'il dispose de ses propres tours de jeu. Il obéit aux ordres verbaux que vous lui donnez (sans que cela vous demande d'utiliser une action), tant qu'ils ne vont pas à l'encontre de son alignement. En l'absence d'ordre, il se défend contre les créatures hostiles, mais n'entreprend pas d'autre action.

C'est le MJ qui dispose du profil technique du céleste.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 9 ou supérieur, vous invoquez un céleste doté d'un indice de dangerosité inférieur ou égal à 5.

Vous invoquez un serviteur élémentaire. Choisissez une zone d'air, de terre, de feu ou d'eau occupant un cube de 3 mètres d'arête situé à portée. Un élémentaire doté d'un indice de dangerosité inférieur ou égal à 5 et adapté à la zone que vous avez choisie apparaît dans un espace inoccupé situé dans un rayon de 3 mètres autour d'elle. Par exemple, un élémentaire du feu jaillit d'un brasier tandis qu'un élémentaire de la terre sort du sol.

L'élémentaire disparaît dès qu'il tombe à 0 point de vie ou quand le sort se termine.

L'élémentaire se montre amical envers vous et vos compagnons. Déterminez son initiative, sachant qu'il dispose de ses propres tours de jeu. Il obéit aux ordres verbaux que vous lui donnez (sans que cela vous demande d'utiliser une action). En l'absence d'ordre, il se défend contre les créatures hostiles, mais n'entreprend pas d'autre action.

Si votre concentration se brise, l'élémentaire ne disparaît pas, mais il échappe à votre contrôle et devient hostile envers vous et vos compagnons. Il peut aller jusqu'à vous attaquer. Vous ne pouvez pas renvoyer un élémentaire qui est hors de contrôle, il disparaît simplement 1 heure après que vous l'avez invoqué.

C'est le MJ qui dispose du profil technique de l'élémentaire.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, l'indice de dangerosité de l'élémentaire augmente de 1 par niveau au-delà du niveau 5.

Vous invoquez une créature féerique, ou un esprit féerique qui revêt l'apparence d'une bête, dotée d'un indice de dangerosité inférieur ou égal à 6. La créature apparaît dans une case inoccupée située à portée et dans votre champ de vision. Elle disparaît dès qu'elle tombe à 0 point de vie ou quand le sort se termine.

La créature féerique se montre amicale envers vous et vos compagnons. Lancez l'initiative pour elle, sachant qu'elle dispose de ses propres tours de jeu. Elle obéit aux ordres verbaux que vous lui donnez (sans que cela vous demande d'utiliser une action), tant qu'ils ne vont pas à l'encontre de son alignement. En l'absence d'ordre, elle se défend contre les créatures hostiles, mais n'entreprend pas d'autre action.

Si votre concentration se brise, la créature féerique ne disparaît pas, mais elle échappe à votre contrôle et devient hostile envers vous et vos compagnons. Elle peut aller jusqu'à vous attaquer. Vous ne pouvez pas renvoyer une créature féerique qui est hors de contrôle, elle disparaît simplement 1 heure après que vous l'avez invoquée.

C'est le MJ qui dispose du profil technique de la créature féerique.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, l'indice de dangerosité de l'élémentaire augmente de 1 par niveau au-delà du niveau 6.

Vous touchez une créature qui doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md), sans quoi elle est maudite pour toute la durée du sort. À vous de choisir la nature de cette malédiction parmi les options suivantes au moment de l'incantation.

* Choisissez une caractéristique. Tant que la cible est maudite, elle est affectée par un désavantage lors des tests et des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) basés sur cette caractéristique.

* Tant que la cible est maudite, elle subit un désavantage lors de ses jets d'attaque contre vous.

* Tant que la cible est maudite, elle doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) au début de chacun de ses tours. Si elle le rate, elle gaspille son action du tour et ne fait rien.

* Tant que la cible est maudite, vos sorts et vos attaques à son encontre lui infligent 1d8 dégâts nécrotiques supplémentaires.

Le sort _[lever une malédiction](hd_spells_lever_une_malediction.md)_ met un terme à cet effet.

Si le MJ est d'accord, vous pouvez choisir un autre effet de malédiction, mais il ne doit pas être plus puissant que ceux proposés ici. C'est au MJ de décider s'il accepte ou non le nouvel effet de malédiction.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, le sort fait effet tant que vous vous concentrez, sans dépasser un maximum de 10 minutes. Si vous utilisez un emplacement de niveau 5 ou supérieur, la durée est de 8 heures, tandis qu'elle passe à 24 heures si vous utilisez un emplacement de sort de niveau 7 ou plus. Si vous utilisez un emplacement de niveau 9, le sort persiste jusqu'à ce qu'il soit dissipé. L'utilisation d'un emplacement de niveau 5 ou plus vous dispense de vous concentrer.

Vous créez une sphère de 9 mètres de rayon centrée sur un point visible de votre choix à portée. Toute créature située dans la sphère doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md) ou subir 4d8 points de dégâts radiants. Si la créature est une créature céleste, un fiélon ou un mort-vivant les dégâts sont doublées et la créature est [aveuglée](hd_conditions_aveugle.md) pour 1 round. En cas de réussite, la cible subit seulement la moitié des dégâts et n'est pas [aveuglée](hd_conditions_aveugle.md).

Vous bannissez une créature située à portée et dans votre champ de vision dans un demi-plan labyrinthique.

La cible y reste pendant toute la durée du sort, ou jusqu'à ce qu'elle s'échappe du dédale.

Elle peut utiliser une action pour tenter de s'évader.

Pour cela, elle effectue un test d'[Intelligence](hd_abilities_intelligence.md) DD 20. Si elle le réussit, elle s'échappe et le sort se termine (les minotaures et les démons goristros réussissent automatiquement).

Quand le sort se termine, la cible réapparaît à l'emplacement qu'elle a quitté ou, s'il est occupé, dans l'emplacement libre le plus proche.

Vous invoquez une lame enflammée dans votre main libre. Au niveau de la taille et de la forme, elle ressemble à un cimeterre et persiste pendant toute la durée du sort. Si vous la lâchez, elle disparaît, mais vous pouvez l'invoquer de nouveau par une action bonus.

Vous pouvez utiliser votre action pour faire une attaque de sort au corps-à-corps avec la lame enflammée. Si vous touchez la cible, cette dernière subit 3d6 dégâts de feu.

La lame enflammée émet une vive lumière dans un rayon de 3 mètres et une faible lumière dans un rayon de 3 mètres de plus.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, les dégâts augmentent de 1d6 tous les deux niveaux au-delà du niveau 2.

La lumière ambiante se concentre dans votre main et prend la forme d'un rayon en forme de lance. Vous devez réussir une attaque au corps-à-corps pour frapper la cible. La lance de lumière inflige 3d8 dégâts radiants.

De plus, la créature touchée se retrouve [aveuglée](hd_conditions_aveugle.md). Elle doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) à chacun de ses tours suivants jusqu'à réussite pour ne plus être [aveuglée](hd_conditions_aveugle.md).

Ce sort permet à la créature que vous touchez de comprendre toutes les langues parlées qu'elle entend.

De plus, quand elle parle, toute créature qui maîtrise au moins une langue et l'entend comprend ce qu'elle dit.

Nommez ou décrivez une personne, un lieu ou un objet. Le sort porte à votre connaissance un bref résumé des connaissances essentielles se rapportant à la chose nommée. Ces connaissances peuvent se présenter sous la forme d'histoires actuelles, de contes oubliés ou même d'un savoir secret qui n'a jamais été révélé.

Si la chose que vous nommez n'est pas digne de figurer dans une légende, vous n'obtenez aucune information.

Plus vous possédez d'informations sur cette chose, plus celles que vous recevez via le sort sont précises et détaillées.

Les informations obtenues sont exactes, mais susceptibles de se présenter dans un langage figuré. Par exemple, si vous avez une mystérieuse hache en main, le sort peut vous donner les renseignements suivants : « Malheur au malfaisant qui pose la main sur cette hache, car même son manche peut entailler la main des mécréants. Seul un véritable enfant de la pierre, un être qui aime Gorom et en est aimé en retour, pourra éveiller la véritable puissance de cette hache, à condition de prononcer le mot sacré Rudnogg. »

Choisissez jusqu'à cinq créatures à portée en train de chuter. La vitesse de chute de chacune passe à 18 mètres par round jusqu'à la fin du sort. Si une créature atterrit avant la fin du sort, elle ne subit pas de dégât de chute et se reçoit sur ses pieds, le sort se terminant alors pour elle.

Vous modifiez le cours du temps autour d'un maximum de six créatures de votre choix situées dans un cube de 12 mètres d'arête situé à portée. Chaque cible doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md), sans quoi le sort l'affecte pendant toute sa durée.

Une cible affectée voit sa vitesse réduite de moitié. De plus, elle subit un malus de -2 à la CA et aux [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md) et ne peut plus utiliser de réaction.

À son tour, elle peut utiliser une action ou une action bonus, mais pas les deux. Elle ne peut pas faire plus d'une attaque au corps-à-corps ou à distance à son tour, quels que soient ses aptitudes et ses objets magiques.

Si la créature affectée tente de lancer un sort doté d'un temps d'incantation de 1 action, lancez 1d20. Sur un résultat de 11 ou plus, le sort agit seulement au prochain tour de la créature, qui doit utiliser son action de ce tour pour terminer l'incantation. Si elle en est incapable, le sort est n'a aucun effet.

Une créature affectée par ce sort fait un nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) à la fin de chacun de ses tours. Si elle le réussit, le sort se termine pour elle.

À votre contact, toutes les malédictions qui affectent une créature ou un objet disparaissent. Si l'objet est un objet magique maudit, la malédiction persiste, mais le sort rompt l'harmonisation entre l'objet et son détenteur, ce qui permet à ce dernier de l'ôter ou de s'en débarrasser.

Une créature ou un objet situé à portée et dans votre champ de vision s'élève à la verticale à une hauteur de 6 mètres et reste suspendu là pendant toute la durée du sort. Ce dernier peut soulever une cible d'au maximum 250 kilogrammes. Si la créature visée n'est pas consentante, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) pour éviter d'être affectée par le sort.

La cible peut se déplacer uniquement en se propulsant ou en se tractant, en prenant appui sur un objet fixe ou une surface à proximité (comme un mur ou un plafond). Elle se meut alors comme si elle était en pleine escalade. Quand vient votre tour, vous pouvez modifier l'altitude de la cible d'un maximum de 6 mètres dans la direction de votre choix. Si vous êtes la cible, vous pouvez monter ou descendre lors de votre déplacement.

En dehors de cela, vous devez dépenser une action pour déplacer la cible qui doit rester à portée du sort.

Si la cible est encore en l'air quand le sort se termine, elle flotte délicatement jusqu'au sol.

Vous invoquez une liane mobile dotée de sarments flexibles et vous la contrôlez pendant toute la durée du sort. Sa vitesse de déplacement est de 1,50 mètre et son allonge est de 3 mètres. La liane se détend subitement lorsque qu'un adversaire passe à sa portée.

La victime doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md) ou subir 1d6+7 dégâts contondants et être [entravée](hd_conditions_entrave.md). À son tour, la cible peut effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md) pour se libérer en utilisant une action bonus.

La liane a le profil suivant : CA 15, points de vie 30, [Force](hd_abilities_strength.md) 20 (+5), résistance au feu et au froid, immunité à la foudre.

Vous touchez une créature consentante. Pendant toute la durée du sort, ses déplacements ne sont pas affectés par un terrain difficile, tandis que les sorts et autres effets magiques ne peuvent ni réduire sa vitesse, ni provoquer l'état [paralysé](hd_conditions_paralyse.md) ou [entravé](hd_conditions_entrave.md).

La cible peut également dépenser 1,50 mètre de déplacement pour échapper automatiquement à des liens non magiques, comme des menottes ou la prise d'une créature qui l'empoigne. Enfin, sous l'eau, elle ne subit pas de malus aux déplacements ni aux attaques.

Ce sort protège une créature consentante et crée un lien mystique entre vous et votre cible jusqu'à la fin du sort.

Tant que la cible se trouve dans un rayon de 18 mètres autour de vous, elle bénéficie d'un bonus de +1 à la CA et aux [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) et devient résistante à tous les types de dégâts. En revanche, à chaque fois qu'elle subit des dégâts, vous subissez exactement les mêmes.

Le sort se termine si vous tombez à 0 point de vie ou si votre cible et vous êtes séparés de plus 18 mètres. Il se termine aussi si vous le lancez de nouveau le sort. Vous pouvez également révoquer le sort par une action.

Vous forgez un lien télépathique entre un maximum de huit créatures consentantes situées à portée. Elles sont alors psychiquement liées les unes aux autres pendant la durée du sort. Ce sort n'affecte pas les créatures dotées d'une [Intelligence](hd_abilities_intelligence.md) de 2 ou moins.

Jusqu'à la fin du sort, les cibles peuvent communiquer entre elles par télépathie via le lien créé, qu'elles partagent un même langage ou non. Cette communication fonctionne quelle que soit la distance qui les sépare, mais ne s'étend pas aux autres plans d'existence.

**_À plus haut niveau._** Lorsque vous lancez ce sort en dépensant un emplacement de sort de niveau 6, la durée passe à 12 heures. Au niveau 7, vous pouvez transmettre des images, sons et autres perceptions sensorielles aux créatures ciblées. Enfin, au niveau 8, la portée devient illimitée tant que vous êtes sur le même plan et que vous connaissez les créatures ciblées.

Décrivez ou nommez un type spécifique de bêtes ou de plantes. Vous vous concentrez sur la voix de la nature qui vous entoure et découvrez dans quelle direction et à quelle distance se trouve le spécimen le plus proche, s'il y en a, dans un rayon de 7,5 kilomètres.

Décrivez ou nommez un objet qui vous est familier.

Vous sentez dans quelle direction il se trouve, à condition qu'il soit dans un rayon de 300 mètres. S'il se déplace, vous savez dans quelle direction.

Le sort permet de localiser un objet spécifique de votre connaissance à condition que vous l'ayez vu de près, c'est-à-dire vous être trouvé à moins de 9 mètres de lui une fois dans votre vie. Sinon, le sort peut localiser l'objet d'un type donné le plus proche, comme un type d'appareil, de bijou, de meuble, d'outil ou d'arme.

Le sort ne parvient pas à localiser l'objet si une couche de plomb, aussi mince soit-elle, bloque une trajectoire directe entre vous et l'objet.

Décrivez ou nommez une créature qui vous est familière.

Vous sentez dans quelle direction elle se trouve, à condition qu'elle soit dans un rayon de 300 mètres. Si elle se déplace, vous savez dans quelle direction.

Le sort permet de localiser une créature spécifique de votre connaissance ou la créature la plus proche du même type (comme un humain ou une licorne), mais pour cela, vous devez avoir déjà vu une telle créature de près, c'est-à-dire vous être trouvé à moins de 9 mètres d'elle au moins une fois dans votre vie. Si la créature que vous décrivez ou nommez se trouve actuellement sous une forme différente, sous l'effet d'un sort de métamorphose, par exemple, ce sort est incapable de la localiser.

Le sort ne parvient pas à localiser la créature si le chemin qui vous relie directement est coupé par une étendue d'eau courante d'au moins 3 mètres de large.

Ce sort offre espoir et robustesse. Choisissez autant de créatures consentantes à portée que vous le désirez.

Pendant toute la durée du sort, elles bénéficient d'un avantage lors des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) et des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) contre la mort. De plus, elles récupèrent le maximum de points de vie possible dès qu'elles reçoivent des soins.

Tous les objets contenus dans un cube de 6 mètres d'arête situé à portée sont auréolés d'une lumière bleue, verte ou violette (à vous de choisir). Les créatures qui se trouvent dans la zone au moment de l'incantation sont aussi entourées de lumière, à moins de réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Pendant toute la durée du sort, les créatures et les objets affectés émettent une faible luminosité dans un rayon de 3 mètres.

Un assaillant a l'avantage lors du jet d'attaque contre une cible affectée s'il peut la voir. Les créatures et les objets affectés ne peuvent pas bénéficier de l'état [invisible](hd_conditions_invisible.md).

Vous touchez un objet qui ne fait pas plus de 3 mètres dans chaque dimension. Jusqu'à la fin du sort, il émet une vive lumière dans un rayon de 6 mètres et une faible lumière dans un rayon additionnel de 6 mètres.

Vous pouvez colorer cette lumière comme vous le souhaitez.

Il suffit de recouvrir complètement l'objet avec quelque chose d'opaque pour bloquer la lumière. Le sort se termine si vous le lancez de nouveau ou si vous le révoquez en dépensant une action.

Si vous visez un objet porté ou transporté par une créature hostile, cette dernière doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md) pour éviter les effets du sort.

Une sphère de lumière de 18 mètres de rayon s'étend depuis un point de votre choix situé à portée. Elle émet une lumière vive dans ce rayon et une lumière faible dans un rayon additionnel de 18 mètres.

Si le point que vous avez choisi est un objet en votre possession ou un objet qui n'est ni porté ni transporté par autrui, la lumière irradie de l'objet et se déplace avec lui. Il suffit de recouvrir complètement l'objet affecté avec un objet opaque, comme un bol ou un heaume, pour bloquer la lumière.

Si une partie de la zone affectée par ce sort chevauche une zone de ténèbres issue d'un sort de niveau 3 ou moins, elle dissipe le sort en question.

Vous créez jusqu'à quatre lumières de la taille d'une torche qui apparaissent à portée. Elles ressemblent à des lanternes, des torches ou des orbes luisants qui flottent dans les airs pendant toute la durée du sort.

Vous pouvez aussi les combiner pour obtenir une forme brillante vaguement humanoïde de taille M.

Quelle que soit l'option choisie, chaque source lumineuse offre une lumière faible dans un rayon de 3 mètres.

À votre tour et par une action bonus, vous pouvez déplacer les lumières sur un maximum de 18 mètres pour les installer ailleurs, mais toujours à portée. Une lumière créée via ce sort doit toujours se trouver à 6 mètres ou moins d'une autre émanant du même sort.

Elle s'éteint si elle passe hors de portée.

Une main spectrale flottante apparaît à portée, en un point de votre choix. Elle persiste pendant toute la durée du sort ou jusqu'à ce que vous révoquiez le sort par une action. La main disparaît si elle s'éloigne à plus de 9 mètres de vous ou si vous relancez le sort.

Vous pouvez utiliser votre action pour contrôler la main et vous en servir pour manipuler un objet, ouvrir une porte ou un récipient qui ne sont pas verrouillés, placer un objet dans un récipient ouvert ou l'en sortir, ou bien verser le contenu d'une flasque. Vous pouvez déplacer la main d'un maximum de 9 mètres à chaque fois que vous l'utilisez.

La main ne peut pas attaquer, activer un objet magique, ni transporter plus de 5 kilogrammes.

Vous créez une main de force luisante et translucide, de taille G, dans un espace inoccupé situé à portée et dans votre champ de vision. La main existe pendant toute la durée du sort, se déplace sur votre ordre et imite les mouvements de votre propre main.

La main est un objet doté d'une CA de 20 et d'un nombre de points de vie égal à votre maximum de points de vie. Si elle tombe à 0 point de vie, le sort se dissipe. La main possède une [Force](hd_abilities_strength.md) de 26 (+8) et une [Dextérité](hd_abilities_dexterity.md) de 10 (+0). Elle n'occupe pas la case où elle se trouve.

Lorsque vous lancez le sort, puis via une action bonus lors de vos tours ultérieurs, vous pouvez déplacer la main sur une distance maximale de 18 mètres et lui faire appliquer l'un des effets suivants.

**_Main agrippeuse._** La main tente d'empoigner une créature de taille TG ou inférieure qui se trouve dans un rayon de 1,50 mètre. Utilisez la valeur de [Force](hd_abilities_strength.md) de la main pour résoudre le test d'empoignade. Si la cible est de taille M ou inférieure, vous bénéficiez d'un avantage lors du test. Tant que la cible est [empoignée](hd_conditions_empoigne.md) par la main, vous pouvez utiliser une action bonus pour que la main la broie. Dans ce cas, la cible subit un total de dégâts contondants égal à 2d6 + votre modificateur de caractéristique d'incantation.

**_Main interposée._** La main s'interpose entre vous et une créature de votre choix jusqu'à ce que vous lui donniez un autre ordre. Elle se déplace de manière à toujours rester entre vous et la cible désignée et vous offre un abri partiel contre elle. La cible ne peut pas franchir la zone occupée par la main si sa valeur de [Force](hd_abilities_strength.md) est inférieure ou égale à celle de la main. Si elle est supérieure, elle peut se déplacer dans votre direction en traversant la zone de la main, mais cette zone est considérée pour elle comme un terrain difficile.

**_Main percutante._** La main tente de bousculer une créature située dans un rayon de 1,50 mètre dans la direction de votre choix. Faites un test avec la [Force](hd_abilities_strength.md) de la main opposé au test de [Force (Athlétisme)](hd_abilities_strength_athletisme.md) de la cible.

Si cette dernière est de taille M ou inférieur, vous bénéficiez d'un avantage lors du test. Si vous l'emportez, la main pousse la cible sur 1,50 mètre plus 1,50 mètre multiplié par votre modificateur de caractéristique d'incantation. La main se déplace de manière à rester à moins de 1,50 mètre de la cible.

**_Poing serré._** La main frappe une créature ou un objet situé dans un rayon de 1,50 mètre autour d'elle.

Faites une attaque de sort de contact pour la main en utilisant vos propres bonus d'attaque. Si elle touche, la cible subit 4d8 dégâts de force.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, les dégâts de l'option poing serré augmentent de 2d8 et ceux de la main agrippeuse de 2d6 par niveau au-delà du niveau 5.

Alors que vous vous tenez les doigts écartés en éventail et les pouces l'un contre l'autre, une mince nappe de feu s'étend depuis vos mains tendues.

Chaque créature située dans un cône de 4,50 mètres doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Celles qui échouent reçoivent 3d6 dégâts de feu, les autres la moitié seulement.

Le feu embrase tous les objets inflammables de la zone, à moins que quelqu'un ne les porte ou ne les transporte.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, les dégâts augmentent de 1d6 par niveau au-delà du niveau 1.

Vous invoquez une demeure extraplanaire à portée qui persiste pendant toute la durée du sort. À vous de choisir où se situe sa seule entrée. Cette dernière scintille légèrement et mesure 1,50 mètre de large pour 3 mètres de haut. Vous et toutes les créatures que vous désignez lors de l'incantation êtes libres d'entrer et de sortir de cette demeure extraplanaire, tant que son portail reste ouvert. Vous pouvez l'ouvrir ou le fermer si vous vous tenez à 9 mètres ou moins de lui. Quand le portail est fermé, il est [invisible](hd_conditions_invisible.md).

Un splendide vestibule s'ouvre derrière le portail et dessert de nombreuses pièces. Les lieux sont propres et l'atmosphère tiède et agréable.

Vous pouvez disposer le plan des lieux comme bon vous semble, mais l'espace occupé ne peut pas excéder cinquante cubes mesurant chacun 3 mètres d'arête.

L'endroit est meublé et décoré selon vos souhaits et contient assez de nourriture pour un banquet de neuf plats destiné à une centaine de convives au maximum.

Une équipe de cent serviteurs translucides s'occupent de tous ceux qui pénètrent dans la demeure. À vous de décider de l'apparence visuelle de ces domestiques et de leur tenue. Ils obéissent aveuglément à tous vos ordres. Chacun est en mesure d'accomplir n'importe quelle tâche à la portée d'un serviteur humain ordinaire, mais les domestiques ne peuvent ni attaquer ni effectuer une action visant à nuire directement à une autre créature. Ils peuvent donc aller chercher des affaires, faire le ménage, raccommoder et plier les habits, allumer la cheminée, servir les plats et la boisson, etc.

Ils peuvent se rendre partout dans la demeure, mais sont incapables de la quitter. Les meubles et autres objets créés à l'aide de ce sort se dissipent en volutes de fumée s'ils sont amenés à l'extérieur de la demeure.

Quand le sort se termine, toutes les créatures qui se trouvent dans l'espace extradimensionnel sont expulsées dans les emplacements libres les plus proches de l'entrée.

Vous vous recouvrez d'une enveloppe de givre. Vous bénéficiez d'une résistance aux dégâts contre la prochaine attaque réussie contre vous, tandis que la créature qui vous a attaqué subit la moitié des dégâts de son attaque sous forme de dégâts de froid. Ensuite, le sort cesse de faire effet.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, le sort fait effet sur une attaque supplémentaire par niveau au-dessus du premier.

Ce sort permet de se déplacer sur n'importe quelle surface liquide (comme de l'eau, de l'acide, de la boue, de la neige, des sables mouvants ou de la lave) comme s'il s'agissait d'un sol ferme et inoffensif (ceci dit, les créatures qui marchent sur la lave subissent tout de même les dégâts liés à la chaleur dégagée). Vous pouvez accorder cette capacité pendant toute la durée du sort à un maximum de dix créatures consentantes situées à portée et dans votre champ de vision.

Si vous prenez pour cible une créature immergée dans un liquide, le sort la ramène à la surface du liquide à une vitesse de 18 mètres par round.

Vous et un maximum de dix créatures consentantes, situées à portée et dans votre champ de vision, prenez une forme gazeuse pendant toute la durée du sort et ressemblez à des volutes de nuages. Sous cette forme, une créature affectée a une vitesse de vol de 90 mètres et une résistance aux dégâts des armes non magiques. Elle est limitée dans ses actions : elle peut juste se précipiter ou reprendre sa forme normale. Il lui faut 1 minute pour reprendre sa forme normale et, pendant toute cette période, elle est [neutralisée](hd_conditions_neutralise.md) et incapable de bouger. Elle peut de nouveau se muer en nuage tant que le sort n'est pas terminé, cette nouvelle transformation lui demandant aussi 1 minute.

Si une créature est sous forme de nuage et en plein vol quand le sort se termine, elle descend de 18 mètres par round pendant 1 minute, jusqu'à ce qu'elle atterrisse, en parfaite sécurité. Si elle n'arrive pas à atterrir avant la fin de cette minute, elle tombe sur la distance qui lui reste à parcourir.

Vous choisissez une créature située dans votre champ de vision et à portée et lui apposez une marque mystique la désignant comme votre proie. Jusqu'à la fin du sort, vous lui infligez 1d6 dégâts supplémentaires à chaque fois que vous réussissez à lui infliger des dégâts avec une arme et vous avez l'avantage sur les éventuels tests de [Sagesse (Perception)](hd_abilities_wisdom_perception.md) ou [Sagesse (Survie)](hd_abilities_wisdom_survie.md) que vous faites pour la retrouver. Si la cible tombe à 0 point de vie avant que ce sort se termine, vous pouvez utiliser une action bonus lors d'un tour ultérieur pour marquer une nouvelle créature.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou 4, vous pouvez vous concentrer sur le sort pendant 8 heures. Si vous utilisez un emplacement de niveau 5 ou supérieur, vous pouvez maintenir votre concentration sur le sort jusqu'à 24 heures.

Pendant la durée du sort, vos yeux deviennent deux trous noirs regorgeant d'un pouvoir terrifiant. Une créature de votre choix, située dans votre champ de vision et dans un rayon de 18 mètres doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) ou se voir affectée par l'un des effets suivants, choisi par vos soins, pendant toute la durée du sort. À chacun de vos tours jusqu'à ce que le sort se termine, vous pouvez utiliser votre action pour viser une autre créature, mais vous ne pouvez pas reprendre pour cible une créature ayant déjà réussi un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) contre l'incantation de mauvais oeil en cours.

**_Nauséeux._** La cible est affectée par un désavantage lors des jets d'attaque et des tests de caractéristique. Elle a droit à un nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) à la fin de chacun de ses tours. L'effet se termine si elle le réussit.

**_Endormi._** La cible tombe [inconsciente](hd_conditions_inconscient.md). Elle se réveille si elle subit le moindre dégât ou si une tierce personne utilise une action pour la réveiller en la secouant.

**_Paniqué._** Vous terrorisez la cible. À chacun de ses tours, la cible [terrorisée](hd_conditions_terrorise.md) doit utiliser l'action se précipiter et s'éloigner de vous via l'itinéraire le plus rapide et le plus sûr, à moins qu'elle n'ait nulle part où aller. Cet effet se termine si la cible gagne un emplacement situé à au moins 18 mètres de vous et d'où elle ne vous voit plus.

Vous pointez du doigt une créature à portée et murmurez un message. La cible (et elle seule) l'entend et peut répondre dans un murmure que vous êtes le seul à entendre.

Vous pouvez lancer ce sort au travers d'un objet solide si vous connaissez bien la cible et savez qu'elle se trouve de l'autre côté de cet obstacle. Le sort est bloqué par un silence magique, 30 centimètres de pierre, 2,5 centimètres de métal ordinaire, une mince couche de plomb ou 90 centimètres de bois. Le sort n'a pas besoin de voyager en ligne directe, il peut contourner les angles et franchir les ouvertures.

Grâce à ce sort, vous chargez un animal de délivrer un message pour vous. Choisissez une bête de taille TP située à portée et dans votre champ de vision, comme un écureuil, un geai ou une chauve-souris. Vous lui précisez l'endroit où se rendre (où vous devez vous être déjà rendu vous-même auparavant) et donnez une description générale du destinataire, comme « un homme ou une femme vêtus de l'uniforme de la garde de la ville » ou « un nain roux avec un chapeau pointu ». Vous prononcez ensuite votre message, de vingt-cinq mots au maximum.

La bête chargée du message fait alors route vers la destination indiquée pendant toute la durée du sort.

Elle parcourt environ 75 kilomètres par 24 heures si elle vole, ou environ 35 kilomètres dans le cas contraire.

Quand elle arrive sur place, elle transmet votre message à la créature que vous avez décrite, imitant le son de votre voix. Le messager parle uniquement à une créature correspondant à la description que vous lui avez donnée. S'il n'atteint pas sa destination avant la fin du sort, le message est perdu et l'animal retourne là où vous avez lancé le sort.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, la durée du sort augmente de 48 heures par niveau au-delà du niveau 2.

Ce sort change la forme d'une créature située à portée et dans votre champ de vision. Une créature non consentante doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) pour éviter cet effet. Le sort n'a aucun effet sur un métamorphe ou une créature à 0 point de vie.

La transformation persiste pendant toute la durée du sort ou jusqu'à ce que la cible tombe à 0 point de vie ou meure. Vous pouvez donner comme nouvelle forme celle de n'importe quelle bête dont l'indice de dangerosité est égal ou inférieur à celui de la cible (ou à son niveau, si elle n'a pas d'indice de dangerosité). Le profil technique de la cible, y compris ses valeurs de caractéristique mentales, est remplacé par celui de la bête choisie. Elle conserve en revanche son alignement et sa personnalité.

La cible possède les points de vie correspondant à sa nouvelle forme. Quand elle reprend sa forme initiale, elle se retrouve avec le nombre de points de vie qui était le sien avant la transformation. Si elle reprend sa forme initiale parce qu'elle est tombée à 0 point de vie, les éventuels dégâts en excès sont déduits des points de vie de sa forme d'origine. Tant que les dégâts en excès ne réduisent pas les points de vie normaux de la créature à 0, elle n'est pas [inconsciente](hd_conditions_inconscient.md).

La nouvelle forme de la créature limite les actions qu'elle peut entreprendre et elle ne peut ni parler, ni lancer de sorts, ni effectuer une action qui nécessite de parler ou de se servir de ses mains.

L'équipement de la cible fusionne avec sa nouvelle forme, mais elle ne peut pas activer, utiliser ni manier la moindre pièce d'équipement et ne peut pas non plus bénéficier de ses effets.

Choisissez une créature ou un objet non magique situés à portée et dans votre champ de vision. Vous transformez la créature en une autre créature, la créature en un objet ou l'objet en une créature (cet objet ne doit pas être porté ni transporté par autrui). La transformation persiste pendant toute la durée du sort ou jusqu'à ce que la cible tombe à 0 point de vie ou meure. Si vous vous concentrez sur ce sort pendant toute sa durée, la transformation persiste jusqu'à dissipation.

Ce sort n'a aucun effet sur un métamorphe ou une créature tombée à 0 point de vie. Si la cible n'est pas consentante, elle peut faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md).

Si elle le réussit, le sort ne l'affecte pas.

**_Créature en créature._** Si vous changez une créature en créature d'un autre type, vous pouvez lui attribuer la forme de votre choix, à condition qu'elle corresponde à une créature dotée d'un indice de dangerosité égal ou inférieur au sien (ou à son niveau si la cible n'a pas d'indice de dangerosité). Le profil technique de la cible (y compris ses caractéristiques mentales) est remplacé par celui de sa nouvelle forme, mais elle conserve son alignement et sa personnalité.

La cible adopte les points de vie de sa nouvelle forme.

Quand elle reprend son apparence initiale, elle se retrouve avec le même nombre de points de vie que celui qui était le sien avant sa transformation. Si elle reprend sa véritable forme parce qu'elle est tombée à 0 point de vie, les dégâts en excès sont transférés sur sa forme initiale.

Tant que ces dégâts en excès ne font pas tomber sa forme d'origine à 0 point de vie, la cible n'est pas [inconsciente](hd_conditions_inconscient.md).

La nouvelle forme de la créature limite ses actions.

Elle ne peut pas parler, lancer de sorts, ni effectuer une action nécessitant des mains ou la parole, à moins que sa nouvelle forme ne soit à même d'accomplir ces actes.

L'équipement de la cible fusionne avec sa nouvelle forme. La créature est donc dans l'incapacité d'activer, utiliser, ou manier son équipement ou de bénéficier de ses effets.

**_Objet en créature._** Vous pouvez changer un objet en créature, à condition que la taille de la créature ne dépasse pas celle de l'objet et que son indice de dangerosité soit de 9 ou moins. La créature est amicale envers vous et vos compagnons. Elle agit à chacun de vos tours.

C'est à vous de décider des actions qu'elle entreprend et de ses déplacements, mais c'est le MJ qui dispose de son profil technique et résout ses actions et ses déplacements.

Si le sort devient permanent, vous ne contrôlez plus la créature, mais elle peut rester amicale envers vous selon la manière dont vous l'avez traitée.

**_Créature en objet._** Si vous transformez une créature en objet, tous les objets qu'elle porte et transporte se métamorphosent avec elle. Le profil technique de l'objet remplace celui de la créature qui, une fois revenue à sa forme d'origine à la fin du sort, n'a aucun souvenir de la période pendant laquelle elle a été métamorphosée.

Vous donnez à un terrain d'au maximum 2,5 kilomètres carrés la même apparence visuelle, sonore, olfactive et générale qu'un autre type de terrain. En revanche, sa forme globale ne change pas. Vous pouvez maquiller un champ ou une route pour lui donner l'air d'un marais, d'une colline, d'une crevasse ou d'un autre terrain difficile ou impraticable. Vous pouvez faire passer une mare pour une prairie herbeuse, un précipice pour une pente douce ou un goulet rocailleux pour une route aussi large que lisse. Vous pouvez aussi modifier l'apparence des structures ou en ajouter là où n'y en a pas. En revanche, le sort est incapable de déguiser, dissimuler ou ajouter des créatures.

L'illusion comprend des composantes auditives, visuelles, tactiles et olfactives, elle peut donc changer un sol dégagé en terrain difficile (ou inversement) ou gêner les déplacements dans la zone. Tout élément de terrain illusoire (comme une pierre ou une brindille) disparaît dès qu'il quitte la zone d'effet du sort.

Les créatures dotées de vision parfaite distinguent le véritable terrain derrière l'illusion, mais les autres composantes restent en place ; elles savent donc qu'elles ont affaire à une illusion, mais peuvent toujours interagir physiquement avec celle-ci.

Vous tentez de remodeler les souvenirs d'autrui. Une créature située dans votre champ de vision doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md). Si vous combattez cette créature, elle a l'avantage lors du jet. Si elle échoue, elle est [charmée](hd_conditions_charme.md) par vous pendant toute la durée du sort. Elle est alors [neutralisée](hd_conditions_neutralise.md) et n'a plus conscience de ce qui l'entoure, mais elle vous entend toujours. Le sort se termine si elle subit le moindre dégât ou si elle est la cible d'un autre sort, auquel cas ses souvenirs restent tous intacts.

Tant que le sort persiste, vous pouvez influer sur les souvenirs de la cible liés à un événement qui s'est déroulé dans les 24 heures précédentes et qui n'a pas duré plus de 10 minutes. Vous pouvez éliminer définitivement tout souvenir de cet événement, permettre à la cible de s'en souvenir parfaitement dans les moindres détails, modifier les détails dont elle se souvient ou créer un souvenir décrivant un tout autre événement.

Vous devez parler à votre cible pour décrire comment ses souvenirs sont affectés et, pour que les nouveaux souvenirs s'implantent dans sa mémoire, elle doit être à même de comprendre votre langue. Son esprit se charge de combler les manques dans votre description. Si le sort se termine avant que vous ayez fini de décrire les souvenirs modifiés, la mémoire de la cible ne subit aucune modification. Sinon, elle tient compte des modifications qui lui ont été apportées dès que le sort se termine.

Les souvenirs modifiés ne changent pas forcément l'attitude de la créature, surtout s'ils entrent en contradiction avec ses penchants naturels, son alignement ou ses croyances. Un souvenir modifié illogique sera ignoré : par exemple, si la cible se souvient combien elle a aimé se baigner dans de l'acide, elle prendra cela pour un mauvais rêve. Le MJ peut estimer qu'un souvenir est modifié de manière tellement insensée qu'il n'affecte pas la cible de manière significative.

Un sort _[lever une malédiction](hd_spells_lever_une_malediction.md)_ ou _[restauration supérieure](hd_spells_restauration_superieure.md)_ permet à la cible de retrouver ses véritables souvenirs.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, vous pouvez modifier les souvenirs d'un événement remontant à 7 jours (niveau 6), 30 jours (niveau 7), 1 an (niveau 8) ou issus de n'importe quelle période du passé de la cible (niveau 9).

Vous revêtez une forme différente. Quand vous lancez ce sort, choisissez l'une des options suivantes, dont les effets dureront aussi longtemps que le sort. Tant qu'il est actif, vous pouvez utiliser une action pour mettre un terme à une option afin de bénéficier d'une autre.

**_Adaptation aquatique._** Vous adaptez votre corps à un environnement aquatique, générant des branchies et des palmures entre vos doigts. Vous pouvez respirer sous l'eau et gagnez une vitesse de nage égale à votre vitesse de marche.

**_Armes naturelles._** Vous acquérez des griffes, des crocs, des épines, des cornes ou une autre arme naturelle de votre choix. Vos attaques à mains nues infligent 1d6 dégâts contondants, perforants ou tranchants, comme il sied à l'arme naturelle que vous avez choisie et vous maîtrisez automatiquement les attaques à mains nues. Enfin, votre arme naturelle est de nature magique et vous disposez d'un bonus de +1 aux jets d'attaque et de dégâts quand vous l'utilisez.

**_Changer d'apparence._** Vous modifiez votre apparence et choisissez votre taille, votre poids, vos traits, le son de votre voix, la longueur de vos cheveux, votre pigmentation, et toute caractéristique distinctive désirée. Vous pouvez vous faire passer pour un membre d'une autre race, mais vos caractéristiques ne changent pas. Vous ne pouvez pas vous faire passer pour une créature d'une catégorie de taille différente de la vôtre, et votre silhouette générale doit rester la même (par exemple, si vous êtes un bipède, vous ne pouvez pas utiliser ce sort pour prendre l'apparence d'un quadrupède). À tout moment lors de la durée du sort, vous pouvez dépenser une action pour modifier de nouveau votre apparence de cette manière.

Une créature équine de taille G quasi réelle apparaît dans un emplacement au sol de votre choix situé à portée.

À vous de décider de l'apparence de la créature, mais elle est systématiquement équipée d'une selle, d'un mors et d'une bride. Toutes les pièces d'équipement nées de ce sort disparaissent dans une volute de fumée si quelqu'un les emporte à plus de 3 mètres de la monture.

Pendant toute la durée du sort, vous et une créature de votre choix pouvez chevaucher la monture. Cette dernière possède le même profil technique qu'un cheval de selle, excepté sa vitesse, de 30 mètres. En 1 heure, elle peut parcourir 15 kilomètres, ou 20 kilomètres au galop. Quand le sort se termine, la monture s'estompe progressivement, ce qui laisse 1 minute au cavalier pour mettre pied à terre. Le sort se termine si vous utilisez une action pour le révoquer ou si la monture subit le moindre dégât.

Vous lancez une bordée d'insultes empreintes d'un subtil enchantement à une créature située à portée et dans votre champ de vision. Tant qu'elle vous entend (elle n'a pas besoin de vous comprendre), elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md), sans quoi elle subit 1d4 dégâts psychiques et subit un désavantage sur le prochain jet d'attaque qu'elle effectue avant la fin de son prochain tour.

Les dégâts du sort augmentent de 1d4 quand vous atteignez le niveau 5 (2d4), le niveau 11 (3d4) et le niveau 17 (4d4).

Une créature de votre choix située à portée et dans votre champ de vision récupère un nombre de points de vie égal à 1d4 + votre modificateur de caractéristique d'incantation. Ce sort n'a aucun effet sur les créatures artificielles et les morts-vivants.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, les soins augmentent de 1d4 par niveau au-delà du niveau 1.

Vous prononcez des paroles curatives qui rendent un nombre de points de vie égal à 1d4 + votre modificateur de caractéristique d'incantation à un maximum de six créatures de votre choix situées à portée et dans votre champ de vision. Ce sort reste sans effet sur les morts-vivants et les créatures artificielles.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, les soins augmentent de 1d4 par niveau au-delà du niveau 3.

Vous prononcez un mot de pouvoir capable de submerger l'esprit d'une créature située à portée et dans votre champ de vision. Elle en est abasourdie. Si elle possède 150 points de vie ou moins, elle est [étourdie](hd_conditions_etourdi.md), sinon le sort est sans effet.

Une cible [étourdie](hd_conditions_etourdi.md) a droit à un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) à la fin de chacun de ses tours. L'effet d'étourdissement se termine dès qu'elle en réussit un.

Vous prononcez un mot de pouvoir capable d'obliger une créature située à portée et dans votre champ de vision à mourir instantanément. Si la créature choisie a 100 points de vie ou moins, elle meurt, sinon le sort n'a aucun effet.

Vous et un maximum de cinq créatures consentantes situées dans un rayon de 1,50 mètre autour de vous vous téléportez immédiatement dans un sanctuaire précédemment choisi. Vous – et les créatures qui se téléportent éventuellement avec vous – apparaissez dans l'emplacement inoccupé le plus proche de l'endroit que vous avez désigné lorsque vous avez préparé votre sanctuaire (voir plus bas). Si vous lancez ce sort sans avoir préparé un sanctuaire au préalable, il n'a aucun effet.

Pour désigner un sanctuaire, vous devez lancer ce sort en un lieu dédié à votre divinité, comme un temple, ou entretenant des liens étroits avec elle. Si vous tentez de lancer ainsi le sort dans une zone qui n'est pas dédiée à votre divinité, il n'a aucun effet.

Vous tissez dans les airs un motif aux couleurs mouvantes dans un cube de 9 mètres d'arête situé à portée.

Le motif apparaît pendant un bref instant avant de s'évanouir. Chaque créature qui se trouve dans la zone et voit le motif doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md). Celles qui échouent sont [charmées](hd_conditions_charme.md) pendant la durée du sort. Tant qu'une créature est [charmée](hd_conditions_charme.md) par ce sort, elle est [neutralisée](hd_conditions_neutralise.md) et a une vitesse de 0.

Le sort se termine pour une créature donnée si elle subit le moindre dégât ou si quelqu'un d'autre utilise son action pour la secouer et la sortir de sa torpeur.

Vous créez un mur fait de buissons souples et robustes, enchevêtrés et hérissés d'épines acérées. Il apparaît à portée sur une surface solide et persiste pendant toute la durée du sort. Vous pouvez créer un mur de 18 mètres de long, 3 mètres de haut et 1,50 mètre d'épaisseur, ou le disposer en un cercle de 6 mètres de diamètre pour une hauteur maximum de 6 mètres et une épaisseur de 1,50 mètre. Le mur bloque le champ de vision.

Quand le mur apparaît, chaque créature située dans sa zone doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md).

Celles qui échouent subissent 7d8 dégâts perforants, les autres la moitié seulement.

Une créature peut traverser le mur, mais lentement et dans la douleur. Elle doit dépenser 1,20 mètre de déplacement pour avancer de 30 centimètres au sein du mur. De plus, quand elle entre dans le mur pour la première fois de son tour ou quand elle y termine son tour, elle doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Elle subit 7d8 dégâts perforants si elle rate son jet, la moitié si elle le réussit.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, les deux types de dégâts augmentent chacun de 1d8 par niveau au-delà du niveau 6.

Vous créez un mur de feu sur une surface solide située à portée. Il peut faire un maximum de 18 mètres de long, 6 mètres de haut et 30 centimètres d'épaisseur, ou prendre une forme circulaire de 6 mètres de diamètre pour 6 mètres de haut et 30 centimètres d'épaisseur. Le mur est opaque et persiste toute la durée du sort.

Quand le mur apparaît, chaque créature présente dans sa zone d'effet doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Celles qui échouent reçoivent 5d8 dégâts de feu, les autres la moitié seulement.

Une face du mur (celle de votre choix) inflige 5d8 dégâts de feu à chaque créature qui termine son tour à 3 mètres d'elle ou moins ou au sein du mur. Une créature qui pénètre dans le mur pour la première fois de son tour ou y termine son tour subit les mêmes dégâts.

L'autre face du mur n'inflige pas de dégâts.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 5 ou supérieur, les dégâts augmentent de 1d8 par niveau au-delà du niveau 4.

Un mur de force [invisible](hd_conditions_invisible.md) se matérialise soudain en un point de votre choix situé à portée. Il s'oriente comme bon vous semble, comme une barrière horizontale, verticale ou inclinée. Il peut flotter librement ou reposer sur une surface solide. Vous pouvez lui donner une forme de dôme hémisphérique ou de sphère d'un rayon maximal de 3 mètres ou en faire une surface plane composée de dix panneaux de 3 mètres sur 3. Chaque panneau doit être contigu à un autre. Quelle que soit sa forme, le mur fait 0,5 centimètre d'épaisseur et persiste pendant toute la durée du sort. Si le mur passe par l'emplacement d'une créature lorsqu'il apparaît, il l'expulse d'un côté ou de l'autre (à vous de choisir).

Aucun élément ne peut franchir physiquement le mur, qui est immunisé contre tous les dégâts et résiste à toute _[dissipation de la magie](hd_spells_dissipation_de_la_magie.md)_. En revanche, on peut le détruire instantanément avec une _[désintégration](hd_spells_desintegration.md)_. Le mur s'étend également sur le plan éthéré, ce qui empêche de le franchir sous forme éthérée.

Vous créez un mur de glace sur une surface solide à portée. Vous pouvez lui donner une forme de dôme hémisphérique ou de sphère d'un rayon maximal de 3 mètres ou en faire une surface plane composée de dix panneaux de 3 mètres d'arête. Chaque panneau doit être contigu à un autre. Quelle que soit sa forme, le mur fait 30 centimètres d'épaisseur et persiste pendant toute la durée du sort. Si le mur passe par l'emplacement d'une créature lorsqu'il apparaît, il l'expulse d'un côté ou de l'autre et elle doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Si elle échoue, elle subit 10d6 dégâts de froid, la moitié seulement si elle réussit.

Le mur est un objet que l'on peut endommager, et on peut donc y ouvrir des brèches. Il a une CA de 12 et 30 points de vie par section de 3 mètres de côté. Il est vulnérable aux dégâts de feu. Si une section de 3 mètres de côté tombe à 0 point de vie, elle est détruite et laisse juste une zone d'air glacé à l'emplacement où se trouvait le pan de mur. Quand une créature se déplace dans cette zone frigorifique pour la première fois de son tour, elle doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md).

Si elle échoue, elle subit 5d6 dégâts de froid, la moitié seulement si elle réussit.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, les dégâts que le mur inflige en apparaissant augmentent de 2d6 et les dégâts provoqués par un passage dans la zone d'air glacé augmentent de 1d6 par niveau au-delà du niveau 6.

Vous créez un mur de pierre non magique qui se matérialise en un point de votre choix à portée. Il fait 15 centimètres d'épaisseur et se compose de dix panneaux de 3 mètres sur 3. Chaque panneau doit être contigu à un autre. Sinon, vous pouvez opter pour des panneaux de 3 mètres sur 6 de seulement 7,5 centimètres d'épaisseur.

Si le mur passe par l'emplacement d'une créature lorsqu'il apparaît, il l'expulse d'un côté ou de l'autre (à vous de choisir). Si une créature est placée de telle manière qu'elle devrait se retrouver entourée de toutes parts par le mur (ou par le mur et une autre surface solide), elle doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Si elle le réussit, elle peut utiliser sa réaction pour se déplacer à sa vitesse au maximum afin de ne plus être encerclée par le mur.

Le mur peut prendre la forme que vous désirez, mais il ne peut pas occuper le même emplacement qu'une créature ou un objet. Il n'est pas forcément vertical et n'a pas besoin de reposer sur des fondations solides. En revanche, il doit impérativement fusionner avec de la pierre existante lui servant de soutien solide. Vous pouvez donc utiliser ce sort pour jeter un pont au-dessus d'un fossé ou créer une rampe.

Si vous créez une longueur de plus de 6 mètres, vous devez réduire de moitié la taille de chaque panneau pour créer des supports. Vous pouvez façonner la silhouette générale du mur pour le doter de créneaux, de remparts et autres.

Le mur est un objet de pierre que l'on peut endommager et on peut donc y ouvrir des brèches. Chaque panneau a une CA de 15 et 30 points de vie par section de 2,5 centimètres d'épaisseur. Si un panneau tombe à 0 point de vie, il est détruit, ce qui peut entraîner l'effondrement des panneaux adjacents, au choix du MJ.

Si vous restez concentré sur le sort pendant toute sa durée, le mur devient une structure permanente et ne peut plus être dissipé, sinon il disparaît à la fin du sort.

Un mur de vent fort se lève soudain depuis le sol en un point de votre choix à portée. Vous pouvez lui faire couvrir jusqu'à 15 mètres de long, 4,50 mètres de haut et 30 centimètres d'épaisseur. Vous pouvez lui donner la forme que vous voulez tant qu'il dessine un chemin continu au sol. Ce mur persiste pendant toute la durée du sort.

Quand le mur apparaît, chaque créature située dans sa zone doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md). Les créatures qui échouent subissent 3d8 dégâts contondants, les autres la moitié seulement.

Le vent fort maintient la brume, la fumée et les autres gaz à l'écart. Les créatures et objets volants de taille P ou inférieure ne peuvent pas traverser le mur. Les matériaux libres et légers s'envolent si on les apporte dans le mur. Les flèches, les carreaux et autres projectiles ordinaires visant une cible située derrière le mur sont systématiquement détournés vers le haut et ratent automatiquement leur cible. (Ce phénomène n'affecte pas les rochers que lancent les géants ou les engins de siège, ni les projectiles similaires.) Les créatures sous forme gazeuse ne peuvent pas franchir le mur.

Un plan de lumière scintillante multicolore forme un mur opaque vertical centré sur un point situé à portée et dans votre champ de vision. Ce mur fait au maximum 27 mètres de long, 9 mètres de haut et 2,5 centimètres d'épaisseur. Sinon, vous pouvez façonner le mur de manière à ce qu'il forme une sphère d'au maximum 9 mètres de diamètre centrée sur un point de votre choix situé à portée. Le mur reste en place pendant toute la durée du sort. Si vous positionnez le mur de manière à ce qu'il passe par un emplacement occupé par une créature, le sort échoue : votre action et l'emplacement du sort sont gaspillés.

Le mur émet une lumière vive dans un rayon de 30 mètres et une lumière faible dans un rayon de 30 mètres de plus. Vous et les créatures que vous désignez au moment de l'incantation pouvez traverser le mur et rester à côté sans conséquence. Si une créature qui voit le mur s'en approche à 6 mètres ou moins, ou qu'elle démarre son tour dans ce périmètre, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) ou être [aveuglée](hd_conditions_aveugle.md) pendant 1 minute.

Le mur se compose de sept couches, chacune d'une couleur différente. Quand une créature tente de franchir le mur ou d'y enfoncer la main, elle avance d'une couche à la fois, jusqu'à les franchir toutes. À chaque fois qu'elle traverse ou touche une couche, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md), sans quoi elle est affectée par les propriétés de la couche indiquées plus bas.

On peut détruire le mur, également couche par couche, du rouge au violet, en appliquant une méthode spécifique à chaque couche. Une fois une couche détruite, elle ne se répare pas jusqu'à la fin du sort. Un sceptre d'annulation détruit un mur prismatique, mais un champ d'antimagie en est incapable.

**_1. Rouge._** La cible subit 10d6 dégâts de feu si elle rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), la moitié seulement si elle le réussit.

Tant que cette couche est en place, les attaques à distance non magiques ne peuvent pas traverser le mur. On peut la détruire en lui infligeant 25 dégâts de froid.

**_2. Orange._** La cible subit 10d6 dégâts d'acide si elle rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), la moitié seulement si elle le réussit. Tant que cette couche est en place, les attaques à distance magiques ne peuvent pas traverser le mur. On peut détruire cette couche avec un vent fort.

**_3. Jaune._** La cible subit 10d6 dégâts de foudre si elle rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), la moitié seulement si elle le réussit. On peut détruire cette couche en lui infligeant au moins 60 dégâts de force.

**_4. Vert._** La cible subit 10d6 dégâts de poison si elle rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), la moitié seulement si elle le réussit. On peut détruire cette couche grâce à un sort de _[passe-muraille](hd_spells_passe_muraille.md)_ ou un autre sort d'un niveau égal ou supérieur capable d'ouvrir un portail dans une surface solide.

**_5. Bleu._** La cible subit 10d6 dégâts de froid si elle rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), la moitié seulement si elle le réussit. On peut détruire cette couche en lui infligeant 25 dégâts de feu.

**_6. Indigo._** Si la cible rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), elle est [entravée](hd_conditions_entrave.md) et doit alors faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) à la fin de chacun de ses tours. Si elle en réussit trois, cet effet se termine ; si elle en rate trois, elle se change définitivement en pierre et elle est [pétrifiée](hd_conditions_petrifie.md).

Les succès et les échecs n'ont pas à être consécutifs : tenez le compte dans chaque catégorie jusqu'à ce que l'une d'elles arrive à trois.

Tant que cette couche est en place, il est impossible de lancer un sort à travers le mur. On peut détruire la couche grâce à la vive lumière d'un sort de _[lumière du jour](hd_spells_lumiere_du_jour.md)_ ou d'un sort similaire de niveau égal ou supérieur.

**_7. Violet._** La cible est [aveuglée](hd_conditions_aveugle.md) si elle rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md). Elle doit alors faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) au début de votre prochain tour. Si elle le réussit, elle recouvre la vue, si elle le rate, elle est emportée sur un autre plan d'existence choisi par le MJ et recouvre aussi la vue. (En général, une créature qui ne se trouve pas sur son propre plan d'existence est bannie là-bas, tandis que les autres créatures sont envoyées sur le plan astral ou éthéré.) On peut détruire cette couche avec une _[dissipation de la magie](hd_spells_dissipation_de_la_magie.md)_ ou un sort similaire de niveau identique ou supérieur, capable de mettre un terme à un sort ou à un effet magique.

Vous créez une sphère de brouillard de 6 mètres de rayon centrée sur un point à portée. La sphère s'étend en contournant les angles et, dans la zone qu'elle occupe, la visibilité est nulle. Le brouillard persiste pendant toute la durée du sort ou jusqu'à ce qu'un vent modéré ou plus violent (soufflant au moins à 15 kilomètres par heure) le disperse.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, le rayon de la sphère augmente de 6 mètres par niveau au-delà du niveau 1.

Un nimbe blanc et scintillant d'énergie sacrée vous entoure pour la durée du sort. Au moment de l'incantation, les créatures vivantes situées à 3 mètres ou moins de vous récupèrent autant de points de vie que leur bonus de maîtrise, sans dépasser leur maximum. De plus, toutes bénéficient d'une résistance aux dégâts nécrotiques pour toute la durée du sort. Les morts-vivants présents dans cette zone au début de leur tour subissent 1d6 points de dégâts radiants.

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de sorts de niveau 5 ou supérieur, les dégâts augmentent de 1d6 par niveau au-delà du niveau 4.

Pour toute la durée du sort, vous dissimulez la cible que vous touchez aux yeux de la magie de divination.

Vous pouvez prendre pour cible une créature consentante, un endroit ou un objet ne mesurant pas plus de 3 mètres dans chaque dimension. La magie de divination ne peut plus viser votre cible et les organes de scrutation magiques ne la perçoivent plus.

Un nuage de fumée ondoyant constellé de braises rougeoyantes apparaît sous la forme d'une sphère de 6 mètres de rayon centrée sur un point à portée. Le nuage se répand en contournant les angles si nécessaire et la visibilité est nulle à l'intérieur. Le nuage persiste pendant toute la durée du sort ou jusqu'à ce qu'un vent fort ou modéré (au moins 15 km/h) le disperse.

Quand le nuage apparaît, chaque créature se trouvant à l'intérieur doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md).

Celles qui échouent subissent 10d8 dégâts de feu, les autres la moitié seulement. Une créature doit aussi effectuer ce jet quand elle entre dans la zone affectée pour la première fois du tour ou lorsqu'elle y finit son tour.

Le nuage s'éloigne de vous sur 3 mètres dans la direction de votre choix au début de chacun de vos tours.

Vous créez une sphère de 6 mètres de rayon faite d'un brouillard verdâtre toxique. Il est centré sur un point de votre choix situé à portée. Le brouillard s'étend en contournant les coins au besoin. Il persiste pendant toute la durée du sort ou jusqu'à ce qu'un vent fort le disperse et mette un terme au sort. La visibilité est nulle dans sa zone d'effet.

Quand une créature entre dans la zone du sort pour la première fois de son tour ou qu'elle y débute son tour, elle doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md).

Elle subit 5d8 dégâts de poison si elle rate son jet et seulement la moitié si elle le réussit. Le brouillard affecte même les créatures qui retiennent leur souffle ou qui n'ont pas besoin de respirer.

Le brouillard s'éloigne de vous sur une distance de 3 mètres au début de chacun de vos tours, rampant à la surface du sol. Comme ses vapeurs sont plus lourdes que l'air, il s'enfonce dans les replis du terrain et s'infiltre même dans les ouvertures.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, les dégâts augmentent de 1d8 par niveau au-delà du niveau 5.

Vous créez une sphère d'un gaz jaunâtre et nauséabond de 6 mètres de rayon centrée sur un point à portée. Le nuage se répand en contournant les angles et la visibilité est nulle dans toute sa zone. Le nuage persiste dans la zone affectée pendant toute la durée du sort.

Chaque créature entièrement englobée dans le nuage au début de son tour doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) contre le poison. Celles qui échouent passent toutes leurs actions du tour à vomir. Les créatures qui ne respirent pas et celles qui sont immunisées contre le poison réussissent automatiquement ce jet.

Un vent modéré (au moins 15 km/h) disperse le nuage après 4 rounds. Un vent fort (au moins 30 km/h) le disperse au bout de seulement 1 round.

Des orbes de feu flamboyants s'abattent au sol en quatre points de votre choix situés à portée et dans votre champ de vision. Chaque créature située dans la sphère de 12 mètres de rayon centrée sur chacun de ces points doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md).

Les sphères s'étendent en contournant les angles. Une créature qui rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) subit 20d6 dégâts de feu et 20d6 dégâts contondants, les autres la moitié seulement. Une créature qui se trouve prise dans deux sphères à la fois ne subit qu'une seule fois les dégâts des météores.

Le sort abîme et embrase les objets inflammables de la zone s'ils ne sont pas portés ou transportés.

Vous utilisez votre action pour lancer une arme ou tirer un projectile et une action bonus pour lancer le sort. Le projectile se dédouble de nombreuses fois et affecte toutes les créatures dans une zone de 6 mètres de rayon autour de votre cible initiale, dans la limite de la portée habituelle de l'arme utilisée. Faites un seul jet d'attaque à distance, chaque créature dans la zone subit automatiquement les dégâts habituels de l'arme. Celles dont votre attaque permet d'atteindre ou de dépasser la CA subissent le double des dégâts. Vous ajoutez normalement votre modificateur de [Dextérité](hd_abilities_dexterity.md) aux dégâts et de magie si votre arc ou vos flèches sont magiques. Dans tous les cas, les dégât sont magiques (du type approprié aux projectiles).

Vous créez un oeil magique [invisible](hd_conditions_invisible.md) à portée, qui flotte dans les airs pendant toute la durée du sort. Il vous envoie mentalement des informations visuelles grâce à sa vision normale et dans le noir dans un rayon de 9 mètres. Il peut regarder dans toutes les directions.

Par une action, vous pouvez déplacer l'oeil d'un maximum de 9 mètres dans la direction de votre choix. Il peut s'éloigner de vous sur une distance illimitée, mais il ne peut pas entrer dans un autre plan d'existence. Une barrière solide l'empêche de passer, mais il peut se glisser à travers une ouverture d'au minimum 2,5 centimètres de diamètre.

Une créature vivante à portée et dans votre champ de vision doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) sous peine de se sentir soudainement obligée de vous donner ce qu'elle tient au moment où vous lancez le sort. Dès son tour, la cible se rapproche aussi près que possible de vous et vous tend l'objet.

Pour toute la durée du sort, la cible fait en sorte de protéger l'objet qu'elle doit vous donner et ne peut donc pas s'en servir pour attaquer ni pour se défendre et subit par ailleurs d'un désavantage sur ses jets d'attaques Le sort prend fin si vous ou vos alliés blessez la cible ou lui lancez un sort néfaste, ou si vous vous trouvez au-delà de la portée du sort.

Vous désignez une cible à portée et dans votre champ de vision. Vous créez des images fantasmagoriques cauchemardesques dans son esprit. La victime doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) d'[Intelligence](hd_abilities_intelligence.md). En cas d'échec, elle perçoit des silhouettes d'ombres qui l'assaillent, ce qui lui inflige un désavantage à toutes ses actions pendant la durée du sort.

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de sort de niveau 5 ou supérieur, le sort persiste jusqu'à la fin de sa durée normale sans nécessiter de concentration.

Vous libérez une vague d'énergie purificatrice qui met instantanément fin aux maladies, poisons et états spéciaux suivants qui affectent vos alliés situés dans la zone : [assourdi](hd_conditions_assourdi.md), [aveuglé](hd_conditions_aveugle.md), [charmé](hd_conditions_charme.md), [empoisonné](hd_conditions_empoisonne.md), [étourdi](hd_conditions_etourdi.md), [neutralisé](hd_conditions_neutralise.md), [pétrifié](hd_conditions_petrifie.md) et [terrorisé](hd_conditions_terrorise.md). Elle annule également les effets de sommeil et les effets du sort esprit faible.

Vous prononcez une parole divine, empreinte de la puissance qui a façonné le monde à l'aube de la création.

Choisissez autant de créatures situées à portée et dans votre champ de vision que vous le désirez. Chacune de celles qui vous entendent doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md), ou souffrir d'un des effets suivants, selon son total actuel de points de vie.

* 50 points de vie ou moins : [assourdie](hd_conditions_assourdi.md) pour 1 minute.

* 40 points de vie ou moins : [aveuglée](hd_conditions_aveugle.md) et [assourdie](hd_conditions_assourdi.md) pour 10 minutes.

* 30 points de vie ou moins : [aveuglée](hd_conditions_aveugle.md), [assourdie](hd_conditions_assourdi.md) et [étourdie](hd_conditions_etourdi.md) pour 1 heure.

* 20 points de vie ou moins : morte sur-le-champ.

Quels que soient ses points de vie, si un céleste, un élémentaire, une fée ou un fiélon rate son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), il est immédiatement renvoyé sur son plan natal (s'il ne s'y trouve pas déjà). Il ne peut pas revenir sur votre propre plan pendant les 24 heures qui suivent, à moins d'user d'un _[souhait](hd_spells_souhait.md)_.

Vous êtes brièvement entouré d'une brume argentée et vous vous téléportez sur un maximum de 9 mètres jusqu'à un emplacement inoccupé situé dans votre champ de vision.

Vous désignez un point sur une surface à portée dans votre champ de vision et créez une ouverture circulaire de 1,50 mètre de diamètre entourée de runes rayonnantes.

Avant la fin du sort, par une action bonus, vous désignez un deuxième point sur une autre surface située à 150 mètres ou moins de la première pour créer une seconde ouverture faisant le lien avec la première et formant un passage extra-dimensionnelle bidirectionnel.

Les surfaces ne doivent pas forcément avoir la même inclinaison mais doivent être planes et solides (ex: sol, mur ou plafond) et ne pas comporter de métal.

Toute créature ou objet solide entrant par une ouverture ressort instantanément par l'autre, perpendiculairement à l'ouverture et en conservant sa vitesse. Il est ainsi possible de lancer un objet ou de tirer un projectile par l'ouverture, de ramasser un objet de l'autre côté, de laisser tomber un objet lourd par une ouverture dans le sol pour qu'il retombe de l'autre côté, de sauter au travers pour accéder de l'autre côté sur un passage en hauteur, etc.

Les ouvertures ne laissent pas passer les matières liquides ou gazeuses sauf si elles sont contenues (des flots d'eau ou de lave ne peuvent pas passer au travers, mais une bouteille, une fiole ou un seau d'eau oui). Les sorts et les énergies ne peuvent pas franchir le passage, toutefois la lumière non magique passe au travers ce qui permet de voir de l'autre côté. Si la surface désignée ne peut accueillir l'ouverture, le sort est perdu ou s'arrête. Chacune des ouvertures n'a pas d'épaisseur et n'a qu'une seule face correspondant avec l'autre.

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de sort de niveau 7 ou supérieur, le diamètre de l'ouverture augmente de 1,50 mètre par niveau au-delà du niveau 6.

Vous êtes soudain capable d'entrer dans un arbre et de passer de son sein à celui d'un autre arbre de la même espèce situé dans un rayon de 150 mètres. Ces deux arbres doivent être vivants et au moins de la même taille que vous. Vous devez dépenser 1,50 mètre de déplacement pour entrer dans un arbre. Vous apprenez alors instantanément où se trouvent tous les autres arbres de la même espèce dans un rayon de 150 mètres et vous pouvez gagner l'un d'eux ou ressortir par l'arbre dans lequel vous êtes entré, ce mouvement faisant partie de votre déplacement de 1,50 mètre. Vous apparaissez à l'endroit de votre choix dans un rayon de 1,50 mètre autour de l'arbre dans lequel vous êtes arrivé en dépensant de nouveau 1,50 mètre de déplacement. S'il ne vous reste pas de distance de déplacement à dépenser, vous apparaissez dans un rayon de 1,50 mètre autour de l'arbre par lequel vous êtes entré.

Vous pouvez utiliser cette capacité de transport une fois par round pendant toute la durée du sort. Vous devez terminer chaque tour en dehors d'un arbre.

Une aura d'ombre et de silence émane de vous et enveloppe vos compagnons, vous dissimulant aux sens d'autrui.

Pendant toute la durée du sort, chaque créature que vous choisissez et qui se trouve dans un rayon de 9 mètres (vous y compris) bénéficie d'un bonus de +10 aux tests de [Dextérité (Discrétion)](hd_abilities_dexterity_discretion.md) et il devient impossible de suivre sa piste à moins de recourir à des méthodes magiques.

Une créature qui profite de ce bonus ne laisse derrière elle aucune trace ni aucun autre indice de son passage.

Un passage apparaît en un point de votre choix situé à portée et dans votre champ de vision sur une surface de bois, de plâtre ou de pierre (comme un mur, un sol ou un plafond). Il persiste pendant toute la durée du sort. À vous de décider des dimensions de l'ouverture qui peut faire, au maximum, 1,50 mètre de large pour 2,50 mètres de haut et 6 mètres de profondeur. L'apparition du passage ne crée aucune faiblesse dans la structure qui l'entoure.

Quand l'ouverture disparaît, les créatures et les objets qui s'y trouvaient encore sont expulsés en toute sécurité dans l'emplacement inoccupé le plus proche de la surface sur laquelle vous avez lancé le sort.

Jusqu'à la fin du sort, une créature consentante que vous touchez devient capable de se déplacer sur les surfaces verticales, et même au plafond la tête en bas, tout en gardant les mains libres. La cible bénéficie aussi d'une vitesse d'escalade égale à sa vitesse de marche.

Vous touchez une créature consentante. Pendant toute la durée du sort, sa peau prend la consistance et l'apparence de l'écorce, et sa CA ne peut pas descendre au-dessous de 16, quelle que soit l'armure qu'elle porte.

Ce sort modifie la chair d'une créature consentante pour la rendre aussi dure que de la pierre. Jusqu'à la fin du sort, la cible est résistante aux dégâts non magiques contondants, perforants et tranchants.

Un dôme de force immobile, de 3 mètres de rayon, apparaît soudain autour et au-dessus de vous. Il reste stationnaire pendant toute la durée du sort. Ce dernier se termine si vous quittez sa zone.

Le dôme peut abriter un maximum de neuf créatures de taille M ou inférieure, en plus de vous. Le sort échoue si la zone comprend une créature de taille supérieure ou plus de dix créatures. Les créatures et les objets qui se trouvent à l'intérieur du dôme lors de l'incantation peuvent en sortir et y rentrer librement ; en revanche, les autres créatures sont incapables de franchir ses limites. Les sorts et autres effets magiques ne peuvent pas s'étendre au-delà de la limite du dôme ni être lancés à travers. L'atmosphère au sein du dôme est agréable et sèche, quelles que soient les conditions météorologiques à l'extérieur.

Tant que le sort n'est pas terminé, vous pouvez faire en sorte que l'intérieur du dôme soit faiblement éclairé ou plongé dans le noir. Vu de l'extérieur, le dôme est opaque, de la couleur que vous désirez, mais vu de l'intérieur, il est transparent.

Vous tentez de changer en pierre une créature située à portée et dans votre champ de vision. Si le corps de la cible est fait de chair, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) ou se retrouver [entravée](hd_conditions_entrave.md), car sa chair se met à durcir.

Une créature [entravée](hd_conditions_entrave.md) par ce sort doit effectuer un nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) à la fin de chacun de ses tours. Si elle en réussit trois, le sort se termine. Si elle en rate trois, elle se change en pierre et se retrouve [pétrifiée](hd_conditions_petrifie.md) pendant toute la durée du sort. Il est inutile que les succès et les échecs soient consécutifs, notez juste leur nombre jusqu'à ce que la cible arrive à en accumuler trois d'une sorte ou de l'autre.

Si quelqu'un brise le corps physique de la cible alors qu'elle est [pétrifiée](hd_conditions_petrifie.md), les difformités subies sont conservées par sa forme d'origine quand elle la retrouve.

Si vous maintenez votre concentration sur ce sort jusqu'à la fin de la durée maximale, la cible est définitivement changée en pierre jusqu'à ce que quelqu'un dissipe l'effet.

Vous projetez une image fantasmagorique des pires terreurs d'une créature. Chaque créature située dans un cône de 9 mètres doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) ou lâcher tout ce qu'elle tient en main et être [terrorisée](hd_conditions_terrorise.md) pendant toute la durée du sort.

Tant qu'une créature est [terrorisée](hd_conditions_terrorise.md) par ce sort, elle est obligée d'utiliser l'action se précipiter à chacun de ses tours et de s'éloigner de vous par l'itinéraire le plus sûr, à moins qu'elle n'ait nulle part où aller. Si elle termine son tour en un endroit où vous ne figurez plus dans son champ de vision, elle peut faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md). Si elle le réussit, le sort se termine pour elle.

Vous utilisez votre action pour lancer une arme ou tirer un projectile et une action bonus pour lancer le sort.

Le projectile se dédouble de nombreuses fois et affecte toutes les créatures dans une zone de 3 mètres de rayon autour de votre cible initiale, dans la limite de la portée habituelle de l'arme utilisée. Faites un seul test d'attaque à distance, chaque créature dans la zone subit les dégâts habituels de votre attaque, la moitié seulement si le résultat du test d'attaque n'a pas atteint la CA de la créature. Vous ajoutez normalement votre modificateur de [Dextérité](hd_abilities_dexterity.md) aux dégâts et de magie si votre arc ou vos flèches sont magiques. Dans tous les cas, les dégâts sont magiques (du type approprié aux projectiles).

La foudre jaillit de votre main et bondit sur la créature que vous tentez de toucher. Faites une attaque de sort au corps-à-corps contre la cible. Vous bénéficiez d'un avantage lors du jet d'attaque si votre cible porte une armure métallique. Si vous touchez la cible, elle subit 1d8 dégâts de foudre et ne peut pas effectuer de réaction avant le début de son prochain tour.

Les dégâts du sort augmentent de 1d8 quand vous atteignez le niveau 5 (2d8), 11 (3d8) et 17 (4d8).

Une arme de votre choix exsude une substance poisseuse et venimeuse. À la première attaque que vous réussissez avec cette arme, la victime doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) ou subir 2d6 dégât de poison et être [empoisonnée](hd_conditions_empoisonne.md). En cas de succès, elle subit seulement la moitié des dégâts et elle n'est pas [empoisonnée](hd_conditions_empoisonne.md).

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, les dégâts augmentent de 1d6 par niveau au-delà du niveau 1.

Vous invoquez un portail reliant un espace inoccupé, situé à portée et dans votre champ de vision, à un autre plan d'existence. Ce portail se présente sous la forme d'une ouverture circulaire de 1,50 à 6 mètres de diamètre, à votre guise. Vous pouvez orienter le portail dans la direction de votre choix et il persiste pendant toute la durée du sort.

Le portail a une face avant et une face arrière sur chaque plan où il apparaît. Pour voyager grâce au portail, il faut impérativement le franchir en passant par l'avant. Tout ce qui le traverse ainsi apparaît instantanément sur l'autre plan, dans l'espace inoccupé le plus proche du portail.

Les divinités et autres dirigeants planaires peuvent empêcher un portail né de ce sort de s'ouvrir en leur présence ou en n'importe quel point de leur domaine.

Quand vous lancez ce sort, vous pouvez prononcer le nom d'une créature spécifique (sachant que les pseudonymes, les titres et les surnoms ne fonctionnent pas). Si cette créature se trouve sur un autre plan que celui sur lequel vous vous trouvez, le portail s'ouvre dans ses environs immédiats et attire la créature en son sein. Elle réapparaît de votre côté du portail, dans l'espace inoccupé le plus proche. Cela ne vous donne aucun contrôle sur la créature, qui agit librement, comme le MJ le désire. Elle peut s'en aller, vous attaquer ou vous aider.

Vous vous téléportez depuis votre position actuelle vers n'importe quel emplacement désiré situé à portée.

Vous arrivez exactement à l'endroit voulu. Ce peut être un endroit que vous voyez, que vous visualisez ou que vous pouvez décrire en donnant sa distance et sa direction, par exemple « 60 mètres plus bas en ligne droite » ou « en montant au nord-ouest à un angle de 45 degrés sur 90 mètres ».

Vous pouvez amener des objets avec vous, tant que leur poids ne dépasse pas la charge que vous êtes capable de porter. Vous pouvez également emmener avec vous une créature consentante de votre taille ou d'une taille inférieure, qui peut transporter du matériel dans la limite de ses capacités. Elle doit se trouver dans un rayon de 1,50 mètre autour de vous quand vous lancez le sort.

Si vous deviez arriver dans un emplacement déjà occupé par un objet ou une créature, vous et la créature qui voyage avec vous subissez chacun 4d6 dégâts de force tandis que le sort s'avère incapable de vous téléporter.

Vous agrippez votre objet porte-bonheur (gri-gri, talisman, amulette, etc.) et, jusqu'à la fin de votre prochain tour, vous bénéficiez d'une résistance aux dégâts élémentaires (acide, feu, froid, foudre).

Votre corps tombe en catatonie tandis que votre âme le quitte et pénètre dans le réceptacle utilisé comme composante de sort. Tant qu'elle se trouve là, vous percevez votre environnement comme si votre corps occupait le même espace que le réceptacle. En revanche, vous ne pouvez pas bouger ni utiliser de réaction. Vous ne pouvez accomplir qu'une action : projeter votre âme dans un rayon de 30 mètres au maximum autour du réceptacle, soit pour retourner dans votre corps (ce qui met fin au sort), soit pour prendre possession d'un autre corps humanoïde.

Vous pouvez tenter de prendre possession de n'importe quel humanoïde situé dans votre champ de vision et dans un rayon de 30 mètres (sachant que les créatures protégées par une _[protection contre le mal et le bien](hd_spells_protection_contre_le_mal_et_le_bien.md)_ ou par un _[cercle magique](hd_spells_cercle_magique.md)_ sont immunisées contre la possession). La cible doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md). Si elle échoue, votre âme s'installe dans son corps et la sienne est prisonnière du réceptacle.

Si elle réussit son test, elle résiste à votre tentative de possession et vous ne pouvez plus essayer de la posséder pendant 24 heures.

Une fois que vous avez pris possession du corps d'une autre créature, vous le contrôlez totalement.

Votre profil technique est remplacé par celui de cette créature, bien que vous conserviez votre alignement et vos valeurs d'[Intelligence](hd_abilities_intelligence.md), de [Sagesse](hd_abilities_wisdom.md) et de [Charisme](hd_abilities_charisma.md).

Vous conservez aussi vos aptitudes de classe. Si votre cible possède des niveaux de classe, vous n'avez pas accès aux aptitudes correspondantes.

Pendant ce temps, l'âme de la créature possédée perçoit ce qui se passe autour du réceptacle grâce à ses propres sens, mais elle ne peut pas se déplacer ni effectuer la moindre action.

Tant que vous possédez le corps d'autrui, vous pouvez utiliser votre action pour le quitter et regagner le réceptacle s'il se trouve à 30 mètres de vous ou moins.

L'âme de votre hôte retourne alors dans son propre corps. Si le corps de l'hôte périt alors que vous l'occupez, l'hôte meurt et vous devez faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md) contre votre propre DD d'incantation.

Si vous réussissez, vous regagnez le réceptacle, à condition qu'il se trouve dans un rayon de 30 mètres.

Sinon, vous mourez.

Si le réceptacle est détruit ou que le sort se termine, votre âme regagne immédiatement votre corps, à moins qu'il ne se trouve à plus de 30 mètres d'elle ou qu'il ait succombé, auquel cas vous périssez. Si l'âme d'une autre créature occupe le réceptacle au moment où il est détruit, cette âme retourne immédiatement dans son corps, à condition qu'il se trouve dans un rayon de 30 mètres et soit encore en vie. Sinon, elle meurt.

Le réceptacle est détruit quand le sort se termine.

Vous touchez une créature consentante et lui conférez une aptitude limitée à voir dans le futur immédiat. Pendant toute la durée du sort, elle ne peut pas être surprise et elle a l'avantage sur les jets d'attaque, les tests de caractéristique et les [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md). De plus, les autres créatures sont affectées par un désavantage lors de leurs jets d'attaque contre elle pendant toute la durée du sort.

Le sort se termine immédiatement si vous le lancez de nouveau avant la fin de sa durée.

Ce sort est un tour de magie basique que les novices utilisent pour s'entraîner. Vous l'utilisez pour créer à portée l'un des effets magiques suivants :

* Vous créez un effet sensoriel immédiat et inoffensif, comme une pluie d'étincelles, un coup de vent, de faibles notes de musique ou une odeur étrange.

* Vous allumez ou éteignez instantanément une chandelle, une torche ou un petit feu de camp.

* Vous nettoyez ou salissez instantanément un objet ne faisant pas plus de 30 décimètres cubes.

* Vous refroidissez, réchauffez ou aromatisez jusqu'à 30 décimètres cubes de matière non vivante pendant 1 heure.

* Vous faites apparaître une couleur, une petite marque ou un symbole sur un objet ou une surface pendant 1 heure.

* Vous créez un colifichet non magique ou une image illusoire tenant dans votre main, qui persiste jusqu'à la fin de votre prochain tour.

Si vous lancez le sort à plusieurs reprises, vous ne pouvez pas avoir plus de trois effets non instantanés actifs à la fois. Vous pouvez révoquer un tel effet par une action.

Un maximum de six créatures de votre choix, situées à portée et dans votre champ de vision, récupèrent chacune un nombre de points de vie égal à 2d8 + votre modificateur de caractéristique d'incantation. Ce sort n'a aucun effet sur les morts-vivants et les créatures artificielles.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, les soins augmentent de 1d8 par niveau au-delà du niveau 2.

Une flamme vacillante apparaît dans votre main. Elle y reste pendant toute la durée du sort et ne vous blesse pas, pas plus qu'elle n'endommage votre équipement.

La flamme émet une lumière vive dans un rayon de 3 mètres et une lumière faible dans un rayon additionnel de 3 mètres. Le sort se termine si vous le révoquez par une action ou si vous le lancez de nouveau.

Vous pouvez attaquer avec la flamme, mais cela met fin au sort. Pour cela, quand vous lancez le sort, ou par une action lors d'un tour ultérieur, vous lancez la flamme sur une créature située dans un rayon de 9 mètres. Faites une attaque de sort à distance. Si vous touchez, la cible subit 1d8 dégâts de feu.

Les dégâts de ce sort augmentent de 1d8 quand vous atteignez le niveau 5 (2d8), le niveau 11 (3d8) et le niveau 17 (4d8).

Vous créez trois fléchettes faites d'énergie magique brillante. Chacune touche une créature de votre choix, située à portée et dans votre champ de vision. Une fléchette inflige 1d4+1 dégâts de force à la cible. Toutes les fléchettes frappent leur cible en même temps, sachant que vous pouvez toutes les diriger contre une seule et même créature ou les répartir entre plusieurs.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, le sort crée une fléchette de plus par niveau au-delà du niveau 1.

Vous utilisez votre action pour lancer une arme ou tirer un projectile et une action bonus pour lancer le sort.

À son impact, le projectile explose en un nuage toxique de 3 mètres de diamètre, centré sur votre cible. Si vous touchez votre cible, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) ou subir 4d6 dégâts de poison (en remplacement des dégâts habituels) et être [empoisonnée](hd_conditions_empoisonne.md) pendant 1 minute. En cas de réussite, elle divise les dégâts par deux et n'est pas [empoisonnée](hd_conditions_empoisonne.md). Toutes les créatures dans la zone d'effet, y compris la cible initiale si vous l'avez manquée, subissent 2d6 dégâts de poison (la moitié si la sauvegarde est réussie) et, en cas de [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) raté, elles sont [empoisonnées](hd_conditions_empoisonne.md) pendant seulement 1 round.

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de sort de niveau 4 ou supérieur, les dégâts augmentent de 1d6 par niveau au-delà du niveau 3.

Vous et un maximum de huit créatures consentantes à portée projetez vos corps astraux sur le plan astral (si vous vous trouvez déjà sur ce plan, le sort échoue et l'incantation est gâchée). Les corps physiques que vous laissez derrière vous sont [inconscients](hd_conditions_inconscient.md), en état d'animation suspendue. Ils n'ont pas besoin de nourriture ni d'air et ne vieillissent pas.

Votre corps astral ressemble fort à votre corps physique, jusqu'à reproduire son profil technique et dupliquer ses possessions. La principale différence, c'est le cordon argenté qui sort entre vos omoplates et se prolonge derrière vous, disparaissant du champ de vision après une trentaine de centimètres. C'est lui qui vous relie à votre corps physique. Tant que ce lien est intact, vous pourrez rentrer chez vous, mais s'il est coupé (ce qui se produit seulement si un effet le précise), votre âme est soudain séparée de votre corps et vous mourez sur-le-champ.

Votre forme astrale se déplace librement sur le plan astral et peut traverser les portails menant à d'autres plans. Si vous pénétrez sur un nouveau plan ou si vous retournez sur le plan où vous étiez lorsque vous avez lancé ce sort, votre corps et vos possessions physiques sont transportés le long du cordon argenté, ce qui vous permet de réintégrer votre corps dès que vous arrivez sur le nouveau plan. Votre forme astrale est une incarnation distincte : les dégâts et autres effets s'appliquant sur elle n'ont aucun effet sur votre corps physique et ne vous affectent plus dès que vous le regagnez.

Le sort se termine pour vous et vos compagnons dès que vous utilisez une action pour y mettre fin. À ce moment, les créatures affectées regagnent leurs corps physiques, qui se réveillent.

Le sort peut se terminer plus tôt pour vous ou pour l'un de vos camarades. Si quelqu'un réussit une _[dissipation de la magie](hd_spells_dissipation_de_la_magie.md)_ contre le corps astral ou physique d'une créature affectée, le sort se termine pour elle seule. Il en va de même si la forme astrale ou le corps physique d'une créature affectée tombe à 0 point de vie. Si le sort se termine alors que le cordon argenté est intact, celui-ci ramène la forme astrale dans le corps physique, mettant un terme à l'état d'animation suspendue.

Si vous êtes prématurément renvoyé dans votre corps physique, vos compagnons restent sous forme astrale et doivent se débrouiller seuls pour regagner leur corps physique, en général en se laissant tomber à 0 point de vie.

Vous touchez une créature et lui donnez une protection relative contre la mort. Quand elle devrait tomber à 0 point de vie pour la première fois suite à des dégâts, elle tombe à la place à 1 point de vie et le sort se termine.

Si le sort est encore actif quand la cible est soumise à un effet qui devrait la tuer sur-le-champ sans lui infliger de dégâts, l'effet est annulé contre cette cible et le sort se termine.

Jusqu'à la fin du sort, une créature consentante que vous touchez est protégée contre certains types de créatures : les aberrations, les célestes, les élémentaires, les fées, les fiélons et les morts-vivants.

Cette protection se traduit par plusieurs bénéfices.

Les créatures des types précédemment nommés subissent un désavantage lors des jets d'attaque contre la cible, et cette dernière ne peut être [charmée](hd_conditions_charme.md), [terrorisée](hd_conditions_terrorise.md) ou possédée par elles. Si la cible est déjà sous l'effet d'un tel état spécial émanant d'une telle créature, elle obtient un avantage lors d'un éventuel nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) contre l'effet en question.

Vous touchez une créature. Si elle est [empoisonnée](hd_conditions_empoisonne.md), vous neutralisez ce poison. Si elle est victime de plusieurs poisons, vous en neutralisez un dont vous avez détecté la présence ou un au hasard.

Pendant toute la durée du sort, la cible bénéficie d'un avantage lors des [jets de sauvegarde](hd_abilities_jets_de_sauvegarde.md) contre le poison et se montre résistante aux dégâts de poison.

Pendant toute la durée du sort, la créature consentante que vous touchez devient résistante à un type de dégâts de votre choix : acide, feu, froid, foudre ou tonnerre.

Vous créez un sceau protégeant une zone au sol de 225 mètres carrés (soit une zone de 15 mètres de côté, soit une centaine de zones de 1,50 mètre de côté, soit vingt-cinq zones de 3 mètres de côté). La zone protégée fait au maximum 6 mètres de haut et prend la forme de votre choix. Vous pouvez protéger ainsi plusieurs étages d'une place forte en répartissant la zone affectée entre eux tant que vous pouvez relier toutes les zones contiguës en marchant lorsque vous lancez le sort.

Lors de l'incantation, vous pouvez définir quels individus ne seront pas affectés par un ou tous les effets du sort. Vous pouvez aussi choisir un mot de passe qui immunise celui qui le prononce à haute voix contre ces effets.

Protections et sceaux produit les effets suivants dans la zone protégée.

**_Couloirs._** Le brouillard envahit tous les couloirs, où la visibilité est alors nulle. De plus, à chaque intersection ou embranchement laissant un choix de direction, il y a 50 % de chances que les créatures autres que vous soient persuadées d'aller dans la direction opposée à celle qu'elles ont choisie.

**_Escaliers._** Des _[toiles d'araignées](hd_spells_toile_daraignee.md)_, comme le sort du même nom, emplissent tous les escaliers de la zone protégée, du sol au plafond. Tant que protections et sceaux persiste, ces fils réapparaissent en 10 minutes si quelqu'un les brûle ou les arrache.

**_Portes._** Toutes les portes de la zone protégée sont fermées par magie, comme scellées avec un _[verrou magique](hd_spells_verrou_magique.md)_. De plus, vous pouvez recouvrir jusqu'à dix portes d'une illusion (comme la fonction d'objet illusoire du sort _[illusion mineure](hd_spells_illusion_mineure.md)_), afin de les faire passer pour une section de mur ordinaire.

**_Autres effets de sort._** Vous pouvez placer l'un des effets suivants, au choix, dans la zone protégée par le sort.

* Placer _[lumières dansantes](hd_spells_lumieres_dansantes.md)_ dans quatre couloirs.

Vous pouvez choisir un programme très simple que les lumières suivront pendant toute la durée de protections et sceaux.

* Placer une bouche magique en deux endroits.

* Placer un _[nuage puant](hd_spells_nuage_puant.md)_ en deux endroits. Les vapeurs apparaissent à l'endroit de votre choix. Tant que protections et sceaux persiste, elles réapparaissent au bout de 10 minutes si le vent les disperse.

* Placer une bourrasque constante dans un couloir ou une pièce.

* Placer une _[suggestion](hd_spells_suggestion.md)_ en un endroit. Choisissez une zone d'au maximum 1,50 mètre de côté : toute créature qui y pénètre ou la traverse reçoit une suggestion mentale.

Toute la zone protégée émet une aura magique. Si quelqu'un lance avec succès une _[dissipation de la magie](hd_spells_dissipation_de_la_magie.md)_ sur un effet spécifique, il élimine seulement cet effet.

Vous pouvez protéger une structure en permanence si vous lancez ce sort tous les jours pendant un an.

Toute la nourriture et les boissons non magiques présentes dans une sphère d'un rayon de 1,50 mètre centrée autour d'un point de votre choix situé à portée sont purifiées et débarrassées de tout poison et maladie.

Une créature à portée et que vous pouvez voir subit votre malédiction. Dès que vous lui infligez une blessure, cette plaie se répand petit à petit à l'ensemble de son corps, qui prend une teinte violacée. Les plaies s'infectent et suppurent. Jusqu'à la fin du sort, la cible subit 1d4 points de dégâts nécrotique au début de son tour et obtient un désavantage sur ses jets de [Constitution](hd_abilities_constitution.md).

Les dégâts cessent si la cible quitte la portée du sort.

Si la cible décède pendant qu'elle est sous l'effet du sort, son corps éclate et affecte les créatures situées à 1,50 mètre ou moins d'elle. Les nouvelles cibles affectées doivent réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) ou de [Dextérité](hd_abilities_dexterity.md) pour éviter d'être affecté par le sort.

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de niveau 3, les victimes subissent 2d4 dégâts. Les dégâts passent à 3d4 au niveau 5, 4d4 au niveau 6 et 5d4 au niveau 9.

Vous touchez une créature décédée et la ramenez à la vie, à condition que son trépas ne remonte pas à plus de 10 jours. Si l'âme de la créature est désireuse de rejoindre son corps et libre de le faire, le défunt revient à la vie avec 1 point de vie.

Ce sort neutralise également les poisons et soigne les maladies non-magiques qui affectaient la créature au moment de sa mort. En revanche, il ne la débarrasse pas des maladies magiques, des malédictions et des effets similaires. Si on ne supprime pas ces effets sur le cadavre avant de lancer le sort, ils affectent de nouveau la créature ressuscitée. Ce sort est incapable de ramener un mort-vivant à la vie.

Ce sort referme les plaies mortelles, mais ne restaure pas les parties manquantes du corps. Si la créature est privée d'un organe ou d'un morceau indispensable à sa survie, comme sa tête, le sort échoue automatiquement.

Le retour d'entre les morts est une rude épreuve qui se traduit par un malus de -4 aux jets d'attaque et de sauvegarde ainsi qu'aux tests de caractéristique. À chaque fois que la cible termine un repos long, ce malus se réduit de 1 jusqu'à disparaître.

Un rayon noir fait d'énergie débilitante jaillit de votre doigt en direction d'une créature à portée. Faites une attaque de sort à distance contre la cible. Si vous la touchez, la créature inflige seulement la moitié des dégâts habituels lorsqu'elle attaque avec une arme basée sur la [Force](hd_abilities_strength.md).

La cible a droit à un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) contre le sort à la fin de chacun de ses tours. Le sort se termine si elle réussit.

Vous créez trois rayons de feu et les projetez sur des cibles à portée. Vous pouvez les diriger contre une même cible ou contre des cibles différentes. Faites une attaque de sort à distance pour chaque rayon. Si vous touchez, la cible reçoit 2d6 dégâts.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, vous créez un rayon de plus par niveau au-delà du niveau 2.

Un rayon de lumière d'un blanc bleuté file vers une créature à portée. Faites une attaque de sort à distance contre la cible. Si vous la touchez, elle subit 1d8 dégâts de froid et sa vitesse est réduite de 3 mètres jusqu'au début de votre prochain tour.

Les dégâts du sort augmentent de 1d8 quand vous atteignez le niveau 5 (2d8),11 (3d8) et 17 (4d8).

Un pâle rayon de lune brille dans un cylindre de 1,50 mètre de rayon pour 12 mètres de haut centré sur un point à portée. Une faible lumière emplit le cylindre jusqu'à la fin du sort.

Quand une créature entre dans la zone du sort pour la première fois de son tour ou qu'elle y commence son tour, elle est enveloppée de flammes fantomatiques qui provoquent de violentes douleurs, et doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). Si elle échoue, elle subit 2d10 dégâts radiants, la moitié seulement si elle réussit.

Les métamorphes subissent un désavantage lors de ce jet. Si l'un d'eux le rate, il reprend aussitôt son apparence d'origine et ne peut plus changer de forme tant qu'il n'a pas quitté la zone de lumière du sort.

Une fois que vous avez lancé ce sort, à chacun de vos tours, vous pouvez utiliser une action pour déplacer le rayon de lumière de 18 mètres au maximum dans la direction de votre choix.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, les dégâts augmentent de 1d10 par niveau au-delà du niveau 2.

Un rayon de vive lumière jaillit de votre main sur une ligne de 18 mètres de long pour 1,50 mètre de large.

Chaque créature située sur cette ligne doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). Celles qui échouent subissent 6d8 dégâts radiants et sont [aveuglées](hd_conditions_aveugle.md) jusqu'à la fin de votre prochain tour. Les autres subissent seulement la moitié des dégâts et ne sont pas [aveuglées](hd_conditions_aveugle.md). Les vases et les morts-vivants sont affectés par un désavantage lors de ce [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md).

Vous pouvez créer une nouvelle ligne de lumière en dépensant votre action à n'importe quel tour jusqu'à la fin du sort.

Pendant toute la durée du sort, une boule de lumière brille dans votre main. Elle émet une lumière vive dans un rayon de 9 mètres et une lumière faible dans un rayon de 9 mètres supplémentaires. Cette lumière est de la même nature que la lumière du soleil.

Vous touchez une créature et stimulez ses capacités de guérison naturelle. La cible récupère 4d8+15 points de vie. Pendant toute la durée du sort, elle récupère en plus 1 point de vie au début de chacun de ses tours (c'est-àdire 10 points de vie par minute).

Si la cible a des membres sectionnés (des doigts, des jambes, une queue, etc.), ils repoussent au bout de 2 minutes.

Si vous disposez de la partie amputée et la maintenez contre le moignon, le sort ressoude instantanément le membre au moignon.

Vous touchez un humanoïde mort ou un morceau du cadavre d'une telle créature. Si la créature est morte depuis 10 jours ou moins, le sort lui fabrique un nouveau corps adulte et y appelle son âme. Le sort échoue si l'âme n'est pas libre de gagner ce corps ou si elle ne le désire pas.

La magie façonne un nouveau corps pour accueillir l'âme, ce qui risque de modifier la race de la créature. Le MJ lance 1d100 et consulte la table suivante pour déterminer quel sera le corps de la créature ramenée à la vie ou il en choisit un.

|d100|Race|
|---|---|
|01-03|sangdragon|
|04-09|nain des collines|
|10-15|nain des montagnes|
|16-19|nain des profondeurs|
|20-24|elfe de sang|
|25-28|elfe d'aether|
|29-32|elfe de fer|
|33-39|elfe de bois|
|40-44|gnome des roches|
|45-47|demi-elfe|
|48-49|demi-ogre|
|50-52|demi-orc|
|53-59|halfelin pied-léger|
|60-66|halfelin grand sabot|
|67-86|humain|
|87-89|homme serpent|
|90-92|félys|
|93-96|aasimar|
|97-100|tieffelin|

La créature réincarnée se souvient de son ancienne vie et de ses expériences passées. Elle conserve les capacités dont elle disposait sous sa forme d'origine, mais échange sa race précédente contre la nouvelle et modifie ses traits raciaux en conséquence.

Ce sort répare un objet cassé ou déchiré en un seul point, comme un maillon de chaîne cassé, deux moitiés d'une clef brisée, une cape déchirée ou une outre de vin qui fuit.

Pour cela, vous devez toucher l'objet et la cassure ou la déchirure ne doit pas mesurer plus de 30 centimètres dans chaque dimension. Le problème se répare et il n'en reste plus trace.

Le sort permet de réparer un objet magique ou une créature artificielle, mais pas de restaurer sa magie.

Ce sort vous permet de vous déplacer à une vitesse incroyable. Vous pouvez utiliser l'action se précipiter quand vous le lancez, puis par une action bonus à chacun de vos tours jusqu'à ce que le sort se termine.

Durée d'incantation : 1 réaction en réponse aux dégâts que vous inflige une créature située dans votre champ de vision et dans un rayon de 18 mètres autour de vous Il vous suffit de pointer le doigt vers la créature qui vient de vous blesser pour qu'elle soit un instant enveloppée d'un linceul de flammes infernales. Elle doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Si elle échoue, elle subit 2d10 dégâts de feu, sinon la moitié seulement.

**_À plus haut niveau._**Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, les dégâts augmentent de 1d10 par emplacement de sort au-dessus du 1er.

Ce sort attire ou refoule les créatures de votre choix.

Vous choisissez un objet ou une créature de taille TG ou inférieure situés à portée ou une zone pas plus grande qu'un cube de 60 mètres de côté. Ensuite, vous décrivez une catégorie de créatures intelligentes, comme les dragons rouges, les gobelins ou les vampires. La cible est alors baignée d'une aura qui attire ou refoule ces créatures pendant toute la durée du sort. Vous devez choisir la répulsion ou l'attirance comme effet de l'aura.

**_Attirance._** L'enchantement génère chez la créature une envie irrépressible de s'approcher de la cible dès qu'elle se trouve à 18 mètres ou moins d'elle ou dès qu'elle la voit. Quand la créature voit la cible ou se trouve dans un rayon de 18 mètres autour d'elle, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md), sans quoi, à chacun de ses tours, elle se déplace de manière à entrer dans la zone désirée ou à arriver à portée de la cible. Une fois là, la créature ne peut plus s'éloigner de sa propre initiative.

Si la cible blesse ou fait du mal à la créature affectée, cette dernière a droit à un nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) pour mettre un terme à l'effet, comme décrit plus bas.

**_Répulsion._** L'enchantement génère chez les créatures de la catégorie choisie un intense besoin de quitter les lieux et d'éviter la cible. Quand une telle créature voit la cible ou se trouve dans un rayon de 18 mètres autour d'elle, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) ou se retrouver [terrorisée](hd_conditions_terrorise.md). Elle reste dans cet état tant qu'elle voit la cible ou se trouve à 18 mètres ou moins d'elle.

Tant que la cible l'effraie, la créature doit impérativement utiliser son déplacement pour gagner l'endroit sûr le plus proche, c'est-à-dire un endroit d'où elle ne verra plus la cible. Si la créature s'éloigne à plus de 18 mètres de la cible et ne la voit plus, elle n'est plus [terrorisée](hd_conditions_terrorise.md), mais elle le redevient si la cible apparaît de nouveau en vue ou si elle s'approche à 18 mètres ou moins d'elle.

**_Mettre un terme à l'effet._** Si une créature affectée termine son tour alors qu'elle ne se trouve pas à 18 mètres ou moins de la cible ou qu'elle ne peut pas la voir, elle a droit à un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md). Si elle le réussit, la cible n'exerce plus d'effet sur elle et elle comprend que le sentiment d'attirance ou de répulsion qu'elle ressentait était d'origine magique. De plus, une créature affectée par le sort a droit à un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) toutes les 24 heures tant que le sort persiste.

Une créature qui réussit son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) contre l'effet est immunisée contre lui pendant 1 minute, après quoi, il peut de nouveau l'affecter.

Vous touchez une créature consentante. Une fois avant la fin du sort, elle peut lancer 1d4 et ajouter le résultat obtenu à un unique [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de son choix. Elle peut lancer le dé avant ou après avoir fait son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md).

Le sort se termine alors.

Grâce à ce sort, un maximum de dix créatures situées à portée et dans votre champ de vision deviennent capables de respirer sous l'eau jusqu'à la fin du sort. Les créatures affectées conservent en plus leur mode de respiration normal.

Vous touchez une créature et mettez fin à une maladie ou à un état spécial qui l'affectait, parmi [aveuglé](hd_conditions_aveugle.md), [assourdi](hd_conditions_assourdi.md), [paralysé](hd_conditions_paralyse.md) ou [empoisonné](hd_conditions_empoisonne.md).

Vous imprégnez la créature que vous touchez d'énergie positive, afin de la débarrasser d'un effet débilitant. Vous pouvez ainsi réduire le niveau d'épuisement de la cible d'un cran ou mettre un terme à l'un des effets suivants l'affectant.

* L'état [charmé](hd_conditions_charme.md) ou [pétrifié](hd_conditions_petrifie.md).

* Une malédiction, y compris l'harmonisation entre la cible et un objet magique maudit.

* Une réduction sur l'une des valeurs de caractéristique de la cible.

* Un effet réduisant le maximum de points de vie de la cible.

Vous touchez le cadavre d'une créature décédée depuis 100 ans au maximum, qui n'est pas morte de vieillesse et qui n'est pas un mort-vivant. Si son âme est libre et consentante, la cible ressuscite avec tous ses points de vie.

Ce sort neutralise les poisons et maladies ordinaires qui affectaient éventuellement la cible à sa mort, mais il ne guérit pas les maladies magiques, les malédictions et autres effets de même type. Il faut en débarrasser la cible avant de la ressusciter, sans quoi ils l'affligent de nouveau dès qu'elle revient à la vie.

Ce sort referme les blessures mortelles et restaure les parties de corps éventuellement manquantes.

Le retour d'entre les morts est une rude épreuve qui se traduit par un malus de -4 aux jets d'attaque et de sauvegarde ainsi qu'aux tests de caractéristique. À chaque fois que la cible termine un repos long, ce malus se réduit de 1 jusqu'à disparaître.

Si ce sort est destiné à une créature décédée depuis un an ou plus, son incantation est extrêmement éprouvante.

Après cela, vous ne pouvez plus lancer de sort et vous souffrez d'un désavantage lors des jets d'attaque et de sauvegarde et des tests de caractéristique jusqu'à ce que vous ayez terminé un repos long.

Vous touchez une créature décédée depuis 200 ans au maximum, de n'importe quelle cause sauf de vieillesse.

Si son âme est libre et consentante, elle revient à la vie avec tous ses points de vie.

Le sort referme toutes les plaies, neutralise tous les poisons, guérit toutes les maladies et lève toutes les malédictions qui affectaient éventuellement la cible à sa mort. Il remplace les organes et les membres abîmés ou manquants. Il peut même fournir un nouveau corps à la cible si l'original n'existe plus, mais dans ce cas, vous devez prononcer le nom de la créature à ressusciter. Elle apparaît alors dans un emplacement inoccupé de votre choix dans un rayon de 3 mètres autour de vous.

Ce sort façonne les rêves d'une créature. Choisissez comme cible une créature de votre connaissance. Elle doit se trouver sur le même plan d'existence que vous. Il est impossible de contacter via ce sort une créature qui ne dort pas, tel un elfe. Vous entrez dans un état de transe et servez de messager, à moins que vous ne confiiez ce rôle à une autre créature consentante. Pendant la transe, le messager est conscient de son environnement, mais il ne peut pas entreprendre d'action ni se déplacer.

Si la cible est endormie, le messager apparaît dans son rêve et peut discuter avec elle tant qu'elle est endormie, pendant toute la durée du sort. Le messager peut aussi modeler l'environnement onirique, en créant des objets, un paysage et d'autres images. Il peut sortir de sa transe quand bon lui semble, mettant alors un terme prématuré au sort. La cible se souvient parfaitement de son rêve quand elle se réveille. Si la cible est éveillée quand vous lancez le sort, le messager le sait et peut sortir de sa transe (et mettre un terme au sort) ou attendre qu'elle s'endorme, car il apparaîtra dans ses rêves à ce moment.

Vous pouvez affubler le messager d'une apparence que la cible trouvera monstrueuse et terrifiante. Dans ce cas, le message qu'il transmet ne peut excéder dix mots et la cible est obligée d'effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md). Si elle échoue, les échos de cette monstruosité fantasmagorique génèrent un cauchemar qui dure pendant tout le sommeil de la cible et l'empêche de bénéficier de sa période de repos. De plus, quand elle se réveille, elle subit 3d6 dégâts psychiques.

Si vous êtes en possession d'un élément corporel de la cible, comme une mèche de cheveux, des rognures d'ongles ou autre, elle subit un désavantage lors de son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md).

Vous touchez une créature morte au cours de la minute précédente. Elle revient à la vie avec 1 point de vie. Ce sort ne ramène pas à la vie les créatures mortes de vieillesse et ne restaure pas les parties manquantes du corps.

Vous touchez un point et imprégnez la zone qui l'entoure de puissance bénie (ou impie). Cette zone possède un rayon maximal de 18 mètres, sachant que le sort échoue si cette zone chevauche une autre zone déjà sous l'effet d'un sort de sanctification. La zone affectée est soumise aux effets suivants.

Premièrement, les célestes, les élémentaires, les fées, les fiélons et les morts-vivants ne peuvent entrer dans la zone. Les créatures qui se trouvent dans la zone ne peuvent être [charmées](hd_conditions_charme.md), [terrorisées](hd_conditions_terrorise.md) ou possédées par l'une de ces créatures. Une créature déjà [charmée](hd_conditions_charme.md), [terrorisée](hd_conditions_terrorise.md) ou possédée par l'une de ces créatures ne l'est plus dès qu'elle pénètre dans la zone. Vous pouvez décider qu'un ou plusieurs des types de créatures mentionnés ne seront pas affectés par cet effet.

Deuxièmement, vous pouvez apposer un effet supplémentaire sur la zone. Choisissez l'un des effets de la liste suivante ou optez pour un autre que propose votre MJ. Certains effets s'appliquent aux créatures de la zone. Dans ce cas, vous pouvez préciser s'ils affectent toutes les créatures, uniquement celles qui obéissent à une divinité ou à un chef particulier, ou seulement celles d'un type donné, comme les orcs ou les trolls.

Quand une créature susceptible d'être affectée pénètre dans la zone d'effet du sort pour la première fois de son tour ou quand elle y commence son tour, elle peut effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md). Si elle le réussit, elle ignore l'effet supplémentaire jusqu'à ce qu'elle quitte la zone.

**_Courage._** Les créatures affectées ne peuvent être [terrorisées](hd_conditions_terrorise.md) tant qu'elles se trouvent dans la zone.

**_Interférence extradimensionnelle._** Les créatures affectées ne peuvent pas se déplacer ni voyager en usant de téléportation, ni de moyens extradimensionnels ou interplanaires.

**_Langues._** Les créatures affectées peuvent communiquer avec n'importe quelle créature de la zone, même si elles ne partagent pas le même langage.

**_Lumière du jour._** Une vive lumière emplit la zone.

Les ténèbres magiques issues d'un sort de niveau inférieur à celui de l'emplacement que vous avez utilisé pour lancer sanctification ne peuvent étouffer cette lumière.

**_Protection contres les énergies._** Les créatures affectées situées dans la zone gagnent une résistance contre un type de dégâts de votre choix, à l'exception des dégâts contondants, perforants et tranchants.

**_Repos éternel._** Les cadavres inhumés dans la zone ne peuvent pas se changer en morts-vivants.

**_Ténèbres._** Les ténèbres s'abattent sur la zone. La lumière normale est incapable d'illuminer les lieux, tout comme les lumières magiques issues d'un sort de niveau inférieur à celui de l'emplacement que vous avez utilisé pour lancer sanctification.

**_Vulnérabilité à l'énergie._** Les créatures affectées situées dans la zone sont affligées d'une vulnérabilité à un type de dégâts de votre choix, à l'exception des dégâts contondants, perforants et tranchants.

**_Silence._** Aucun son n'émane de l'intérieur de la zone et aucun son ne peut y pénétrer.

**_Terreur._** Les créatures affectées sont [terrorisées](hd_conditions_terrorise.md) tant qu'elles se trouvent dans la zone.

Vous protégez une créature à portée contre les attaques.

Jusqu'à la fin du sort, toute créature qui vise la cible avec une attaque ou un sort néfaste doit d'abord effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md). Si elle le rate, elle doit choisir une nouvelle cible, sans quoi l'attaque ou le sort est perdu. Ce sort ne protège pas la cible contre les effets de zone, comme l'explosion d'une _[boule de feu](hd_spells_boule_de_feu.md)_.

Ce sort se termine si la créature protégée attaque ou lance un sort affectant une créature ennemie.

Vous sécurisez par magie une zone à portée. Il s'agit d'un cube de 1,50 mètre à 30 mètres d'arête. Le sort persiste pendant toute sa durée ou jusqu'à ce que vous utilisiez une action pour le révoquer.

Vous décidez de la sécurité offerte par le sort au moment de l'incantation en choisissant une ou plusieurs propriétés parmi les suivantes.

* Les sons ne peuvent pas franchir la barrière qui délimite la zone protégée.

* La barrière délimitant la zone protégée est sombre et brumeuse, ce qui empêche de voir au travers (même avec la vision dans le noir).

* Les organes sensoriels créés via un sort de divination ne peuvent pas apparaître au sein de la zone protégée ni traverser la barrière qui délimite son périmètre.

* Les sorts de divination ne peuvent pas prendre les créatures de la zone pour cible.

* Rien ne peut se téléporter à l'intérieur ou à l'extérieur de la zone protégée.

* Les voyages planaires sont bloqués au sein de la zone protégée.

Si on lance ce sort tous les jours au même endroit pendant un an, ses effets deviennent permanents.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 5 ou supérieur, vous pouvez augmenter la taille du cube de 30 mètres par niveau au-delà du niveau 4. Ainsi, avec un emplacement de niveau 5, vous pouvez protéger une zone de 60 mètres de côté.

Vous contaminez le sang d'une créature vivante que vous touchez. Vous effectuez une attaque de sort au contact. Si elle est réussie, le sang de la cible devient corrosif, lui infligeant 1d6 dégâts d'acide à chacun de vos tours. Si la cible réussit un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md), les dégâts sont ignorés pour ce tour.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de sort de niveau 2 ou supérieur, les dégâts augmentent de 1d6 pour chaque niveau au-delà du niveau 1.

Vous touchez une créature et triplez sa distance de saut jusqu'à ce que le sort se termine.

Vous voyez et entendez une créature donnée de votre choix, à condition qu'elle se trouve sur le même plan d'existence que vous. La cible doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md), modifié par le degré de connaissance que vous avez d'elle et le type de lien physique que vous avez établi avec elle. Si la cible sait que vous lancez ce sort, elle peut rater volontairement son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) si elle veut que vous l'observiez.

|Connaissance|Modificateur du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md)|
|---|---|
|Deuxième main (vous avez entendu parler de la cible)|+5|
|Première main (vous avez rencontré la cible)|+0|
|Familière (vous connaissez bien la cible)|-5|

|Lien|Modificateur du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md)|
|---|---|
|Représentation ou portrait|-2|
|Possession ou vêtement|-4|
|Partie du corps, cheveux, ongles, etc.|-10|

Si la cible réussit son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), elle n'est pas affectée et vous ne pouvez plus utiliser ce sort sur elle pendant 24 heures.

Si elle rate son jet, le sort crée un organe sensoriel [invisible](hd_conditions_invisible.md) dans un rayon de 3 mètres autour d'elle. Vous voyez et entendez à travers cet organe comme si vous vous trouviez à sa place. L'organe sensoriel se déplace avec la cible et reste dans un rayon de 3 mètres autour d'elle pendant toute la durée du sort. Une créature capable de voir les objets [invisibles](hd_conditions_invisible.md) perçoit l'organe sensoriel comme un orbe lumineux de la taille de votre poing.

Au lieu de prendre une créature pour cible, vous pouvez choisir un lieu que vous avez déjà vu. L'organe sensoriel apparaît alors à cet endroit et n'en bouge pas.

Grâce à ce sort, vous pouvez dissimuler une créature consentante ou un objet qui sera [invisible](hd_conditions_invisible.md) à tout moyen de détection pendant toute la durée du sort. Quand vous lancez le sort et touchez la cible, elle devient [invisible](hd_conditions_invisible.md) et ne peut plus être la cible de sorts de divination. De plus, les organes sensoriels de scrutation issus d'un sort de divination ne la perçoivent plus.

Si la cible est une créature, elle entre en état d'animation suspendue. Le temps ne s'écoule plus pour elle et elle ne vieillit plus.

Vous pouvez décider d'une condition qui mettra un terme prématuré au sort. Ce peut être ce que vous voulez, mais ce doit être visible ou se produire dans un rayon de 1,5 kilomètre autour de la cible. Par exemple, « au bout de 1 000 ans » ou « quand la tarasque se réveillera ». Ce sort se termine également si la cible subit le moindre dégât.

Ce sort crée une force [invisible](hd_conditions_invisible.md), dépourvue de forme et d'intellect, mais capable d'accomplir des tâches simples sur votre ordre jusqu'à la fin du sort. Le serviteur se matérialise au sol, dans un emplacement inoccupé situé à portée. Il a une CA de 10, 1 pv, une [Force](hd_abilities_strength.md) de 2 et il est incapable d'attaquer. S'il tombe à 0 point de vie, le sort se termine.

Une fois à chacun de vos tours, vous pouvez utiliser une action bonus pour ordonner mentalement à votre serviteur de se déplacer d'un maximum de 4,50 mètres et d'interagir avec un objet. Le serviteur peut accomplir des tâches simples à la portée d'un domestique humain, comme aller chercher des affaires, faire le ménage, repriser, plier les habits, allumer la cheminée, servir les plats et la boisson, etc. Une fois que vous avez donné votre ordre, il fait de son mieux pour y obéir jusqu'à ce qu'il ait terminé. Il attend alors l'ordre suivant.

Si vous ordonnez à votre serviteur d'accomplir une tâche qui l'éloigne à plus de 18 mètres de vous, le sort se termine.

Pendant toute la durée du sort, aucun son ne peut se créer au sein d'une sphère de 6 mètres de rayon centrée sur un point de votre choix à portée, ni la traverser.

Une créature ou un objet entièrement contenu dans la sphère sont immunisés contre les dégâts de tonnerre, et les créatures entièrement contenues dans la sphère sont [assourdies](hd_conditions_assourdi.md). Il est impossible de lancer un sort à composante verbale depuis la sphère.

Vous façonnez un double illusoire d'une bête ou d'un humanoïde à portée pendant toute la durée de l'incantation.

Le double est une créature partiellement réelle, faite de neige ou de glace, qui peut accomplir des actions et qui est affectée par les éléments extérieurs comme une créature normale. Il ressemble en tout point à l'original, mais il n'a que la moitié de son maximum de points de vie et n'a pas d'équipement lors de sa création. En dehors de cela, il utilise le profil technique de la créature qu'il représente.

Le simulacre se montre amical envers vous et les créatures que vous désignez. Il obéit à vos ordres vocaux, se déplace et agit comme vous le souhaitez et agit à votre tour lors des combats. Le simulacre est incapable d'apprendre et de gagner en puissance, il ne monte donc jamais de niveau et ne développe jamais ses pouvoirs. Il ne peut pas non plus récupérer un emplacement de sort dépensé.

Si le simulacre est endommagé, vous pouvez le réparer dans un laboratoire d'alchimie en utilisant des herbes rares et des minéraux d'une valeur de 100 po par point de vie à régénérer. Le simulacre persiste jusqu'à ce qu'il tombe à 0 point de vie, il se transforme alors en neige et fond instantanément.

Si vous lancez de nouveau ce sort, l'éventuel double que vous maintenez déjà en activité est détruit sur-lechamp.

Vous renforcez votre corps avec un ersatz de vie et gagnez 1d4+4 points de vie temporaires pendant la durée du sort.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, vous gagnez 5 points de vie temporaires supplémentaires par niveau au-delà du niveau 1.

La créature que vous touchez récupère un nombre de points de vie égal à 1d8 + votre modificateur de caractéristique d'incantation. Ce sort n'a aucun effet sur les morts-vivants et les créatures artificielles.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, les soins augmentent de 1d8 par niveau au-delà du niveau 1.

Une vague d'énergie curative s'étend depuis un point de votre choix situé à portée. Choisissez un maximum de six créatures présentes dans une sphère de 9 mètres de rayon centrée sur ce point. Chacune d'entre elles récupère un nombre de points de vie égal à 3d8 + votre modificateur de caractéristique d'incantation. Ce sort n'a aucun effet sur les morts-vivants ni sur les créatures artificielles.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 6 ou supérieur, les soins augmentent de 1d8 par niveau au-delà du niveau 5.

Ce sort plonge quelques créatures dans un sommeil magique. Lancez 5d8. Le total indique le nombre de points de vie de créatures que le sort affecte. Les créatures qui se trouvent dans un rayon de 6 mètres autour d'un point de votre choix situé à portée sont affectées dans l'ordre croissant de leur total actuel de points de vie (en ignorant les créatures [inconscientes](hd_conditions_inconscient.md)).

Chaque créature affectée par le sort tombe [inconsciente](hd_conditions_inconscient.md), en commençant par celle qui possède actuellement le moins de vie. Elle reste ainsi jusqu'à la fin de la durée du sort, jusqu'à ce qu'elle subisse des dégâts ou jusqu'à ce que quelqu'un utilise son action pour la réveiller en la secouant ou en la giflant. Soustrayez le nombre de points de vie de la créature endormie du total auquel vous avez droit avant de passer à la suivante, c'est-à-dire celle qui a le moins de points de vie après elle. Le nombre de points de vie de la créature doit être égal ou inférieur au total vous restant, sinon le sort n'affecte pas la créature.

Ce sort reste sans effet sur les morts-vivants et les créatures qui ne peuvent être [charmées](hd_conditions_charme.md).

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, lancez 2d8 de plus par niveau au-delà du niveau 1.

Le souhait est le plus puissant des sorts qu'une créature mortelle puisse lancer. Vous pouvez modifier les fondements de la réalité selon vos désirs, simplement en prononçant quelques mots.

L'utilisation basique de ce sort consiste à dupliquer les effets de n'importe quel sort de niveau 8 ou moins.

Vous n'avez alors pas besoin de remplir les conditions requises, pas même de fournir les composantes matérielles onéreuses, le sort fait tout simplement effet.

Sinon, vous pouvez créer l'un des effets suivants, au choix.

* Vous créez un objet d'une valeur maximale de 25 000 po qui n'a rien de magique. Il doit mesurer au maximum 90 mètres dans chaque dimension et apparaît en un emplacement inoccupé situé au sol et dans votre champ de vision.

* Vous permettez à un maximum de vingt créatures situées dans votre champ de vision de récupérer la totalité de leurs points de vie et vous mettez fin à tous les effets les affectant, tel que décrit dans le sort de _[restauration supérieure](hd_spells_restauration_superieure.md)_.

* Vous conférez à un maximum de dix créatures situées dans votre champ de vision une résistance à un type de dégâts de votre choix.

* Vous conférez à un maximum de dix créatures situées dans votre champ de vision l'immunité contre un unique sort ou un autre effet magique pendant 8 heures. Par exemple, vous pouvez vous immuniser, ainsi que tous vos compagnons, contre l'attaque absorption de vie des liches.

* Vous défaites un unique événement récent en faisant relancer un jet de dé effectué au cours du round précédent (y compris lors de votre dernier tour). La réalité se modifie pour s'adapter au nouveau résultat. Par exemple, un souhait peut obliger un adversaire à relancer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) réussi, un ennemi à refaire son jet de critique ou un ami à rejouer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) raté. Vous pouvez attribuer un avantage ou un désavantage à la créature qui relance le dé et vous êtes libre d'appliquer le résultat du premier jet ou de la relance.

Ce sort peut également vous permettre d'accomplir des exploits dépassant le cadre des exemples précédents.

Formulez votre souhait à votre MJ de la manière la plus précise possible. Le MJ dispose d'une grande liberté pour gérer ce genre de cas. Plus le souhait est important, plus il y a de chances que quelque chose tourne mal. Le sort peut tout simplement échouer, avoir des effets partiels seulement ou s'accompagner de conséquences inattendues en raison de la manière dont vous l'avez formulé. Par exemple, si vous souhaitez qu'un adversaire soit mort, vous pouvez très bien être projeté en avant dans le temps, à une période où il est décédé, ce qui, en pratique, vous élimine de la partie en cours de jeu. Et si vous souhaitez obtenir un objet magique légendaire ou un artefact mythique, vous pourriez très bien être instantanément transporté en sa présence, et en celle de son propriétaire actuel.

Le stress lié à l'incantation d'un souhait pour faire autre chose que répliquer un autre sort vous affaiblit grandement. À tel point que vous subissez 1d10 dégâts nécrotiques par niveau de sort à chaque fois que vous lancez un autre sort par la suite, et ce jusqu'à ce que vous ayez terminé un repos long. Il est absolument impossible de réduire ces dégâts ou de les empêcher, de quelque manière que ce soit. De plus, votre [Force](hd_abilities_strength.md) tombe à 3 (si elle n'est pas déjà de 3 ou moins) pendant 2d4 jours. À chaque fois que vous passez une de ces journées à vous reposer et ne rien faire de plus que des activités légères, le temps de récupération qui vous reste diminue de 2 jours. Enfin, suite à ce stress, il y a 33 % de chances que vous ne puissiez plus jamais lancer souhait.

Une sphère de feu de 1,50 mètre de diamètre apparaît dans un espace inoccupé de votre choix situé à portée et subsiste pendant toute la durée du sort. Chaque créature qui termine son tour dans un rayon de 1,50 mètre autour de la sphère doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Celles qui échouent subissent 2d6 dégâts de feu, les autres la moitié seulement.

Vous pouvez déplacer la sphère sur un maximum de 9 mètres par une action bonus. Si vous lui faites heurter une créature, cette dernière doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) ou subir les dégâts de la sphère, qui arrête de se déplacer pour ce tour.

Quand vous déplacez la sphère, vous pouvez lui faire franchir des obstacles de 1,50 mètre de haut et la faire sauter par-dessus des fosses de 3 mètres de large. Elle embrase les objets inflammables qui ne sont ni portés ni transportés. Elle émet une lumière vive dans un rayon de 6 mètres et une lumière faible dans un rayon de 6 mètres supplémentaires.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, les dégâts augmentent de 1d6 par niveau au-delà du niveau 2.

Un globe d'énergie gelée jaillit de la pointe de votre doigt tendu et file vers un point de votre choix situé à portée. Là, il explose en une sphère de 18 mètres de rayon. Chaque créature dans la zone doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). Celles qui échouent subissent 10d6 dégâts de froid, les autres la moitié seulement.

Si le globe frappe une surface aqueuse ou un liquide principalement constitué d'eau (ce qui n'inclut pas les créatures majoritairement composées d'eau), il gèle le liquide sur une épaisseur de 15 centimètres dans une zone de 9 mètres de côté. La glace subsiste une minute.

Les créatures qui nageaient à la surface de l'étendue d'eau se retrouvent prises dans la glace. Une telle créature peut utiliser une action pour faire un test de [Force](hd_abilities_strength.md) contre le DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de votre sort afin de se libérer.

Une fois que vous avez terminé l'incantation, vous pouvez attendre avant de lancer le globe. Dans ce cas, il ressemble à une bille de fronde glacée qui reste dans votre main. Vous pouvez alors le lancer à la main (à une portée de 12 mètres), avec une fronde (selon la portée habituelle de cette fronde) ou le donner à une créature qui peut faire de même. Le globe se brise à l'impact, explosant comme décrit dans la version normale du sort.

Vous pouvez également poser le globe au sol sans le briser.

Il explose au bout de 1 minute s'il n'a pas été brisé auparavant.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, les dégâts augmentent de 1d6 par niveau au-delà du niveau 6.

Une sphère de force scintillante englobe une créature ou un objet de taille G ou inférieure situés à portée. Si la cible n'est pas consentante, elle a droit à un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Si elle le rate, elle est enfermée dans la sphère pour toute la durée du sort.

Rien ne peut franchir la barrière que forme la sphère : ni les objets physiques, ni l'énergie, ni les effets des autres sorts. En revanche, une créature qui se trouve au sein de la sphère y respire sans mal. La sphère est immunisée contre tous les types de dégâts. De plus, les attaques et les effets originaires de l'extérieur de la sphère ne peuvent pas blesser la créature ou l'objet qu'elle abrite. De même, une créature au sein de la sphère est incapable d'endommager ce qui se trouve à l'extérieur.

La sphère ne pèse rien et elle est tout juste assez grande pour contenir la créature ou l'objet qu'elle renferme.

Une créature enfermée dans la sphère peut utiliser son action pour exercer une poussée sur la paroi de la sphère et la faire rouler à la moitié de sa vitesse habituelle. De même, une tierce personne peut ramasser la sphère ou la déplacer.

Un sort de _[désintégration](hd_spells_desintegration.md)_ visant la sphère la détruit sans endommager ce qu'elle contient.

Vous faites jaillir du sol des stalagmites de pierre d'une hauteur de 3 mètres dans une zone carrée de 3 mètres d'arête à portée du sort. Si elles atteignent le plafond avant d'atteindre leur taille maximale, les stalagmites cessent de grandir. Chaque créature dans la zone doit effectuer une sauvegarde de [Dextérité](hd_abilities_dexterity.md). Une créature volant à moins de 3 mètres du sol bénéficie d'un avantage sur ce jet. En cas d'échec, les stalagmites infligent 4d4 dégâts perforants et la cible se retrouve [entravée](hd_conditions_entrave.md) entre les stalagmites jusqu'à la fin du sort. En cas de succès, elle ne subit que la moitié des dégâts et est libre ses mouvements. Une cible [entravée](hd_conditions_entrave.md) par les stalagmites peut utiliser une action pour effectuer une sauvegarde de [Force](hd_abilities_strength.md). En cas de réussite, la créature se libère, mais subit 1d6 dégâts contondants. Pour la durée du sort, le terrain où se trouvent les stalagmites est considéré comme difficile.

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de niveau 3 ou supérieur, les dégâts perforants augmentent de 2d4 pour chaque niveau au-delà du niveau 2.

Vous tendez le bras en direction de votre cible et, de votre main, vous mimez son étranglement. Faites une attaque de sort à distance. En cas de réussite, la cible subit 1d6 points de dégâts contondants et elle doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md) ou être [entravée](hd_conditions_entrave.md). Si le jet d'attaque initial était un succès, à chacun de vos tours pendant la durée du sort, vous pouvez utiliser votre action pour lui infliger automatiquement les mêmes dégâts et l'obliger à faire un nouveau [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md). Si vous faites quoi que ce soit d'autre (vous pouvez toutefois parler), le sort prend fin. Le sort prend aussi fin si la cible passe hors de portée ou en dehors de votre champ de vision.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 3, vous infligez 2d6 points de dégât par round. Vous augmentez les dégâts de 1d6 supplémentaires par tranche de 2 niveaux de plus (jusqu'à 5d6 au niveau 9).

Vous visez une créature située à portée et dans votre champ de vision et à même de vous entendre et de vous comprendre. Vous l'influencez par magie de façon à ce qu'elle suive la conduite que vous lui proposez (en seulement une phrase ou deux). Les créatures qui ne peuvent être [charmées](hd_conditions_charme.md) sont immunisées contre ce sort.

Vous devez formuler votre suggestion de manière à ce que la conduite à tenir semble tout à fait raisonnable.

Si vous demandez à une créature de se poignarder, de se laisser tomber sur une lance, de s'immoler ou d'accomplir n'importe quelle action à l'évidence néfaste, le sort se termine automatiquement.

La cible doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md), sans quoi elle fait de son mieux pour suivre la conduite que vous lui avez suggérée et cela peut continuer pendant toute la durée du sort. Si l'action suggérée peut se finir plus rapidement, le sort se termine quand la cible a accompli ce que vous lui aviez demandé.

Vous pouvez spécifier des conditions qui déclenchent une conduite spéciale pendant la durée du sort. Par exemple, vous pouvez suggérer à un chevalier de donner son cheval de guerre au premier mendiant qu'il rencontre. Si les conditions ne sont pas remplies avant la fin du sort, la cible n'accomplit pas l'action.

Si vous (ou l'un de vos compagnons) blessez une créature affectée par ce sort, le sort se termine.

Vous visez un maximum de douze créatures de votre choix, situées à portée et dans votre champ de vision et à même de vous entendre et de vous comprendre. Vous les influencez par magie de façon à ce qu'elles suivent la conduite que vous leur proposez (en seulement une phrase ou deux). Les créatures qui ne peuvent être [charmées](hd_conditions_charme.md) sont immunisées contre ce sort. Vous devez formuler votre suggestion de manière à ce que la conduite à tenir semble tout à fait raisonnable. Si vous demandez à une créature de se poignarder, de se laisser tomber sur une lance, de s'immoler ou d'accomplir n'importe quelle action à l'évidence néfaste, l'effet du sort s'annule automatiquement.

Chaque cible doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md), sans quoi elle fait de son mieux pour suivre la conduite que vous lui avez suggérée et cela peut occuper toute la durée du sort. Si l'action suggérée peut se finir plus rapidement, le sort se termine quand la cible a accompli ce que vous lui aviez demandé.

Vous pouvez spécifier des conditions qui déclenchent une conduite spéciale pendant la durée du sort. Par exemple, vous pouvez suggérer à un groupe de soldats de donner tout leur argent au premier mendiant qu'ils rencontrent. Si les conditions ne sont pas remplies avant la fin du sort, la cible n'accomplit pas l'action.

Si vous (ou l'un de vos compagnons) blessez une créature affectée par ce sort, le sort se termine pour elle.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 7 ou supérieur, la durée du sort est de 10 jours. Si vous utilisez un emplacement de niveau 8, elle est de 30 jours et si vous utilisez un emplacement de niveau 9, elle est de 1 an et 1 jour.

Quand vous lancez ce sort, vous inscrivez un glyphe néfaste sur une surface (comme une partie du sol, un pan de mur ou une table) ou dans un objet que l'on peut refermer pour le dissimuler, comme un livre, un parchemin ou un coffre au trésor. Si vous optez pour une surface, le glyphe peut couvrir une zone de 3 mètres de diamètre au maximum. Si vous choisissez un objet, il ne faut plus le déplacer par la suite : si quelqu'un le déplace à plus de 3 mètres de l'endroit où vous avez jeté ce sort, le glyphe se brise et le sort se termine sans avoir été déclenché.

Le glyphe est presque [invisible](hd_conditions_invisible.md). Pour le discerner, il faut réussir un test d'[Intelligence (Investigation)](hd_abilities_intelligence_investigation.md) contre le DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de votre sort.

C'est lors de l'incantation que vous décidez de ce qui déclenchera le sort. Pour les glyphes tracés sur une surface quelconque, les déclencheurs les plus courants consistent à toucher le glyphe ou à se tenir dessus, à déplacer un objet recouvrant le glyphe, à s'approcher à une certaine distance du glyphe ou encore à manipuler l'objet sur lequel le glyphe est tracé. Pour les glyphes inscrits dans un objet, on trouve parmi les déclencheurs les plus répandus le fait d'ouvrir l'objet, de s'en approcher à une certaine distance, ou de voir ou de lire le glyphe.

Vous pouvez affiner le déclencheur, de façon à ce que le sort s'active sous certaines conditions ou en fonction de certaines caractéristiques physiques (comme le poids ou la taille), ou selon un type de créature (pour un glyphe destiné aux guenaudes ou aux métamorphes, par exemple). Vous pouvez aussi définir des conditions pour que certaines créatures ne déclenchent pas le glyphe, en prononçant un mot de passe, par exemple.

Lorsque vous dessinez le glyphe, vous devez choisir l'une des options suivantes. Une fois le glyphe déclenché, il se met à luire et emplit une sphère de 18 mètres de rayon avec une faible lumière pendant 10 minutes, après quoi le sort se termine. Chaque créature présente dans la sphère quand le glyphe s'active est visée par ses effets, tout comme une créature qui entre dans la sphère pour la première fois de son tour ou qui y termine son tour.

**_Démence._** Chaque cible doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) d'[Intelligence](hd_abilities_intelligence.md). Celles qui échouent deviennent folles pendant 1 minute. Une créature démente ne peut pas entreprendre la moindre action, ne comprend pas ce que disent les autres créatures, ne peut pas lire et ne parle que dans un charabia incompréhensible. C'est le MJ qui contrôle ses déplacements qui deviennent complètement erratiques.

**_Désespoir._** Chaque cible doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md) ou être submergée par le désespoir pendant 1 minute. Pendant tout ce temps, elles ne peuvent pas attaquer ni viser une créature avec une capacité, un sort ou un autre effet magique hostile.

**_Discorde._** Chaque cible doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). Celles qui le ratent se mettent à se quereller avec les autres créatures pendant 1 minute.

Pendant tout ce temps, elles sont incapables de tenir une conversation sensée et subissent un désavantage lors des jets d'attaque et des tests de caractéristique.

**_Douleur._** Chaque cible doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) ou être [neutralisée](hd_conditions_neutralise.md) par une douleur insoutenable pendant 1 minute.

**_Étourdissement._** Chaque cible doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) ou être [étourdie](hd_conditions_etourdi.md) pendant 1 minute.

**_Frayeur._** Chaque cible doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md). Celles qui échouent sont [terrorisées](hd_conditions_terrorise.md) pendant 1 minute. Une cible [terrorisée](hd_conditions_terrorise.md) lâche tout ce qu'elle tient et doit s'éloigner du glyphe de 9 mètres au minimum à chacun de ses tours, dans la mesure du possible.

**_Mort._** Chaque cible doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). Celles qui échouent subissent 10d10 dégâts nécrotiques, les autres la moitié seulement.

**_Sommeil._** Chaque cible doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Sagesse](hd_abilities_wisdom.md) ou tomber [inconsciente](hd_conditions_inconscient.md) pendant 10 minutes.

Une telle créature se réveille si elle subit des dégâts ou si quelqu'un utilise son action pour la réveiller en la secouant ou la giflant.

Vous devenez capable de déplacer ou de manipuler des créatures ou des objets par la pensée. Lorsque vous lancez ce sort, puis en tant qu'action à chaque round pendant toute la durée du sort, vous pouvez exercer votre force de volonté sur une créature ou un objet situés à portée et dans votre champ de vision, ce qui provoque l'effet approprié indiqué plus bas. Vous pouvez affecter la même cible, round après round, ou en choisir une nouvelle quand vous le désirez. Si vous changez de cible, la précédente n'est plus affectée.

**_Créatures._** Vous pouvez essayer de déplacer une créature de taille TG ou inférieure. Faites un test de caractéristique avec votre caractéristique d'incantation, opposé à un test de [Force](hd_abilities_strength.md) de la cible. Si vous l'emportez, vous déplacez la créature d'un maximum de 9 mètres dans la direction de votre choix, y compris en hauteur, mais pas hors de portée du sort. Jusqu'à la fin de votre prochain tour, la créature est [entravée](hd_conditions_entrave.md) dans votre étreinte télékinétique. Une créature soulevée dans les airs reste suspendue dans le vide.

Lors des rounds suivants, vous pouvez utiliser votre action pour maintenir votre prise télékinétique sur la cible en répétant les tests opposés.

**_Objets._** Vous pouvez essayer de déplacer un objet pesant au maximum 500 kilogrammes. Si cet objet n'est ni porté ni transporté, vous le déplacez automatiquement d'un maximum de 9 mètres dans la direction de votre choix, mais pas hors de portée du sort.

Si l'objet est porté ou transporté par une créature, faites un test de caractéristique avec votre caractéristique d'incantation, opposé à un test de [Force](hd_abilities_strength.md) de cette créature. Si vous l'emportez, vous éloignez l'objet de cette créature sur un maximum de 9 mètres dans la direction de votre choix, mais pas hors de portée du sort.

Vous exercez un contrôle précis sur les objets pris dans votre étreinte télékinétique, vous pouvez donc manipuler un outil basique, ouvrir une porte ou un récipient, déposer un objet dans un récipient ou en retirer un, ou encore verser le contenu d'une fiole.

Ce sort vous transporte instantanément à la destination de votre choix, ainsi qu'un maximum de huit créatures consentantes de votre choix situées à portée et dans votre champ de vision ou bien ainsi qu'un unique objet situé à portée et dans votre champ de vision. Si vous prenez un objet pour cible, il doit tenir dans un cube de 3 mètres de côté et il ne doit pas être porté ni transporté par une créature non consentante.

Vous devez choisir une destination connue, située sur le même plan d'existence que vous. C'est votre degré de familiarité avec la destination qui détermine vos chances d'arriver sur place. Le MJ lance 1d100 et consulte la table ci-dessous.

Téléportation - degré de familiarité

|Familiarité|Incident|Zone similaire|À proximité|Sur place|
|---|---|---|---|---|
|Cercle permanent|—|—|—|01-100|
|Objet associé|—|—|—|01-100|
|Très familier|01-05|06-13|14-24|25-100|
|Vu à quelques reprises|01-33|34-43|44-53|54-100|
|Vu une seule fois|01-43|44-53|54-73|74-100|
|Description|01-43|44-53|54-73|74-100|
|Destination factice|01-50|51-100|—|—|

**_Familiarité._** « Cercle permanent » désigne un cercle de téléportation dont vous connaissez la séquence de symboles. « Objet associé » indique que vous possédez un objet prélevé à la destination choisie au cours des 6 derniers mois, comme un livre sorti de l'étagère de la bibliothèque d'un magicien, les draps d'une suite royale ou un éclat de marbre arraché au tombeau secret d'une liche. « Très familier » désigne un endroit où vous êtes souvent rendu, un lieu que vous avez soigneusement étudié ou un endroit que vous voyez au moment de l'incantation.

« Vu à quelques reprises » correspond aux endroits que vous avez vus plus d'une fois, mais avec lesquels vous n'êtes pourtant pas très familiers. « Vu une fois » représente un lieu vu une seule fois, éventuellement par magie. « Description » correspond à un endroit que vous connaissez seulement via la description d'autrui, aussi bien au niveau de son emplacement que de son apparence, éventuellement grâce à une carte. « Destination factice » désigne les endroits qui n'existent pas, si par exemple vous avez tenté de scruter le sanctuaire d'un ennemi mais n'avez vu qu'une illusion ou si vous essayez de vous téléporter en un endroit familier qui n'existe plus.

**_Sur place._** Vous et vos compagnons (ou l'objet téléporté) apparaissez exactement où vous le souhaitiez.

**_À proximité._** Vous et vos compagnons (ou l'objet téléporté) apparaissez à une distance aléatoire de votre destination, éloignés dans une direction tout aussi aléatoire.

La distance qui vous sépare de votre destination est de 1d10 × 1d10 % de la distance que le sort vous a fait parcourir. Par exemple, si vous essayez de vous téléporter à une destination située à 180 kilomètres de votre position, que vous arrivez à proximité, et que vous obtenez 5 et 3, vous allez arriver à 15 % de distance de votre destination, c'est-à-dire à 27 kilomètres. Le MJ détermine la direction dans laquelle vous vous êtes éloignés de la cible en lançant 1d8, le 1 représentant le Nord, le 2 le Nord-Est, le 3 l'Est, etc., jusqu'à faire le tour de la rose des vents. Si vous comptiez vous téléporter dans une cité portuaire et arrivez à 27 kilomètres au large de ses côtes, en pleine mer, vous pourriez bien avoir quelques ennuis.

**_Zone similaire._** Vous et vos compagnons (ou l'objet téléporté) arrivez dans une zone différente de celle prévue, mais dotée de caractéristiques visuelles ou thématiques similaires. Par exemple, si vous comptiez regagner votre laboratoire, vous pourriez arriver dans celui d'un autre magicien ou dans une boutique d'alchimie qui possède nombre d'outils et d'appareils présents dans votre laboratoire. En général, vous apparaissez dans l'endroit ressemblant à votre destination le plus proche de celle-ci, mais comme le sort n'a pas de limite de portée, vous pouvez tout à fait arriver n'importe où sur votre plan d'existence.

**_Incident._** La magie imprévisible du sort complique le voyage. Chaque créature téléportée (ou l'objet téléporté) subit 3d10 dégâts de force tandis que le MJ relance le dé pour savoir où vous arrivez (sachant qu'il peut se produire plusieurs incidents, chacun infligeant ses propres dégâts).

Une tempête faite de nuages de feu ronflant se forme à l'endroit que vous avez choisi, à portée. La tempête occupe une zone composée d'un maximum de dix cubes de 3 mètres d'arête, que vous pouvez disposer comme bon vous semble. Chaque cube doit avoir au moins une face adjacente à celle d'un autre cube. Chaque créature de la zone doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md).

Celles qui échouent subissent 7d10 dégâts de feu, les autres la moitié seulement.

Le feu endommage les objets présents dans la zone et embrase les objets inflammables de la zone que personne ne porte ou ne transporte. Si vous le désirez, les flammes peuvent épargner la végétation présente dans la zone.

Des grêlons durs comme de la pierre s'abattent dans un cylindre de 6 mètres de rayon pour 12 mètres de haut, centré sur un point de votre choix à portée.

Chaque créature présente dans le cylindre doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Celles qui échouent subissent 2d8 dégâts contondants et 4d6 dégâts de froid tandis que les autres en subissent la moitié seulement.

Les grêlons transforment la zone en terrain difficile jusqu'à la fin de votre prochain tour.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 5 ou supérieur, les dégâts contondants augmentent de 1d8 par niveau au-delà du niveau 4.

Jusqu'à la fin du sort, une averse de flocons et de neige fondue s'abat dans un cylindre de 6 mètres de haut pour un rayon de 12 mètres centré sur un point de votre choix situé à portée. Dans la zone, la visibilité est nulle et les flammes à nu s'éteignent.

Le sol de la zone est couvert d'une couche de verglas si glissante que le terrain devient difficile. Quand une créature entre dans la zone d'effet pour la première fois de son tour ou y débute son tour, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md) ou tomber à terre.

Si une créature se concentre dans la zone d'effet du sort, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) contre le DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de votre sort, ou perdre sa concentration.

Vous créez une gigantesque tempête de sable qui balaye tout sur son passage. La vague de sable mesure 150 mètres de large, 24 mètres de long et 24 mètres de haut. Elle débute au point désigné situé à portée puis se déplace à une vitesse de 24 mètres par round dans la direction de votre choix.

Une fois la direction fixée, il n'est plus possible d'en modifier la course. La vague inflige 8d6 dégâts contondants à toute créature qui se trouve sur son passage. Chaque créature affectée a droit à un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md) pour réduire les dégâts de moitié. Les créatures de taille G ou inférieure qui le ratent sont emportées dans les airs et subissent 3d6 dégâts supplémentaires (non affectés par le résultat du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md)), tandis que les créatures de taille TG ou supérieure tombent à terre. Tant qu'une créature se trouve dans la zone d'effet de la tempête, elle est [aveuglée](hd_conditions_aveugle.md) et elle bénéficie d'un abri important.

Si ce sort est lancé dans un désert de sable ou de pierre, il inflige 4d6 dégâts supplémentaires (qui sont divisés par deux en cas de [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Force](hd_abilities_strength.md) réussi).

De menaçantes nuées orageuses se forment en un point situé dans votre champ de vision et s'étendent dans un rayon de 110 mètres. Des éclairs strient la zone, le tonnerre gronde et un vent fort se lève. Chaque créature située sous le nuage lors de son apparition (mais pas à plus de 1 500 mètres au-dessous) doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md). Celles qui échouent subissent 2d6 dégâts de tonnerre et sont [assourdies](hd_conditions_assourdi.md) pendant 5 minutes.

À chaque round où vous continuez à vous concentrer sur ce sort, il génère des effets supplémentaires à votre tour.

**_Round 2._** Une pluie acide se met à tomber. Les créatures et les objets situés sous le nuage subissent 1d6 dégâts d'acide.

**_Round 3._** Vous appelez six éclairs qui s'abattent du nuage sur six créatures ou objets de votre choix situés sous la nuée. Une même créature ou un même objet ne peut pas être la cible de plusieurs éclairs. Une créature frappée par la foudre doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Si elle échoue, elle subit 10d6 dégâts de foudre, la moitié seulement si elle réussit.

**_Round 4._** La grêle se met à tomber. Chaque créature située sous le nuage subit 2d6 dégâts contondants.

**_Rounds 5 à 10._** Des bourrasques et une pluie glacée balaient la zone sous le nuage et la transforment en terrain difficile où la visibilité est nulle. Chaque créature qui s'y trouve subit 1d6 dégâts de froid. Il est impossible d'effectuer une attaque avec une arme à distance dans la zone.

Le vent et la pluie fonctionnent comme une distraction sévère quand il s'agit de se concentrer sur un sort. Enfin, des bourrasques de vent fort (de 30 à 75 kilomètres par heure) dispersent automatiquement le brouillard, la brume et les phénomènes similaires stagnant dans la zone, qu'ils soient d'origine ordinaire ou magique.

Des ténèbres magiques se répandent depuis un point de votre choix situé à portée, jusqu'à englober une sphère de 4,50 mètres de rayon. Les ténèbres s'étendent en franchissant tout angle éventuel. La vision dans le noir d'une créature ne suffit pas à percer ces ténèbres et les lumières non-magiques se révèlent incapables de les éclairer.

Si le point que vous avez choisi est un objet en votre possession ou un objet qui n'est ni porté ni transporté par autrui, les ténèbres émanent de l'objet et se déplacent avec lui. Il suffit de recouvrir complètement l'objet affecté avec un objet opaque, comme un bol ou un heaume, pour bloquer les ténèbres.

Si une partie de la zone affectée par ce sort chevauche une zone de lumière issue d'un sort de niveau 2 ou moins, elle dissipe le sort de lumière.

Des tentacules noirs grouillants envahissent le sol d'un emplacement de 6 mètres de côté situé à portée et dans votre champ de vision. Pendant toute la durée du sort, ils transforment la zone en terrain difficile.

Quand une créature pénètre dans la zone affectée pour la première fois au cours d'un tour, ou quand elle débute son tour dans cette zone, elle doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md), sans quoi elle reçoit 3d6 dégâts contondants et se retrouve [entravée](hd_conditions_entrave.md) par les tentacules jusqu'à la fin du sort. Une créature qui commence son tour déjà [entravée](hd_conditions_entrave.md) dans la zone subit 3d6 dégâts contondants.

Une créature [entravée](hd_conditions_entrave.md) par les tentacules peut utiliser son action pour effectuer un test de [Force](hd_abilities_strength.md) ou de [Dextérité](hd_abilities_dexterity.md) (à elle de choisir) contre le DD de sauvegarde de votre sort. Si elle le réussit, elle parvient à se libérer.

Vous maquillez le terrain naturel dans un cube de 45 mètres d'arête situé à portée et lui attribuez l'apparence, les bruits et les odeurs d'un autre type de terrain naturel.

Ainsi, vous pouvez faire passer un champ ou une route pour un marais, une colline, une crevasse ou un autre terrain difficile voire impossible à traverser. Vous pouvez aussi déguiser une mare en prairie, un précipice en pente douce ou un goulet semé de rocaille en route large et aplanie. Les structures manufacturées, l'équipement et les créatures de la zone ne changent pas d'apparence.

Les caractéristiques tactiles de la zone ne changent pas, les créatures qui y pénètrent risquent donc fort de percer l'illusion à jour. Si la différence entre le terrain réel et l'illusion n'est pas évidente au toucher, une créature qui examine soigneusement la zone a droit à un test d'[Intelligence (Investigation)](hd_abilities_intelligence_investigation.md) contre le DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de votre sort pour percer l'illusion à jour.

Une fois qu'une créature a compris l'illusion, elle la voit comme une image floue superposée au terrain réel.

Vous écrivez sur un papier, un parchemin ou un autre matériau adapté à l'écriture et l'imprégnez d'une puissante illusion qui persiste pendant toute la durée du sort.

À vos yeux et à ceux de toutes les créatures que vous désignez lors de l'incantation, l'écriture semble normale, de votre main, et transmet le message que vous aviez en tête en rédigeant le texte. Pour les autres personnes, vos écrits semblent appartenir à une langue inconnue ou magique complètement inintelligible, ou alors ils transmettent un message complètement différent de la réalité, rédigé d'une main qui n'est pas la vôtre et dans une autre langue de votre connaissance.

Si quelqu'un dissipe le sort, l'illusion disparaît, mais le message original aussi. Une créature dotée de vision parfaite est capable de lire le message original.

Vous créez une manifestation merveilleuse mineure ou un signe de puissance surnaturelle à portée, ce qui génère l'un des effets magiques suivants à portée.

* Votre voix retentit jusqu'à trois fois plus fort que la normale pendant 1 minute.

* Les flammes vacillent, se ravivent, se réduisent ou changent de couleur pendant une minute.

* Vous provoquez des secousses inoffensives qui agitent le sol pendant 1 minute.

* Vous émettez un son instantané qui émane d'un point de votre choix situé à portée, comme un roulement de tonnerre, le croassement d'un corbeau ou des murmures inquiétants.

* Vous provoquez la fermeture ou l'ouverture violente et immédiate d'une porte ou d'une fenêtre non verrouillée.

* Vous modifiez l'apparence de vos yeux pendant 1 minute.

Si vous lancez ce sort à plusieurs reprises, vous ne pouvez avoir que trois effets d'une minute actifs à la fois.

Vous pouvez révoquer un tel effet par une action.

Vous invoquez une masse de toiles d'araignées épaisses et collantes en un point de votre choix situé à portée.

Pendant toute la durée du sort, les toiles occupent un cube de 6 mètres d'arête centré sur le point choisi. Elles forment un terrain difficile à la visibilité réduite.

Si les toiles ne sont pas ancrées entre deux éléments solides, comme des murs ou des arbres, ou disposées en couches sur le sol, le plafond ou un mur, elles s'effondrent sur elles-mêmes et le sort se termine au début de votre prochain tour. Des toiles disposées en couches superposées sur une surface plane s'accumulent sur une épaisseur de 1,50 mètre.

Chaque créature qui commence son tour dans les toiles ou qui y pénètre lors de son tour doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md), ou être [entravée](hd_conditions_entrave.md) tant qu'elle reste dans les toiles ou jusqu'à ce qu'elle se libère.

Une créature [entravée](hd_conditions_entrave.md) par les toiles peut utiliser son action pour effectuer un test de [Force](hd_abilities_strength.md) contre le DD du [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de votre sort. Si elle le réussit, elle n'est plus [entravée](hd_conditions_entrave.md).

Les toiles sont inflammables. Un cube de toiles de 1,50 mètre d'arête exposé au feu brûle en 1 round, infligeant 2d4 dégâts de feu à toute créature qui commence son tour dans les flammes.

Vous lancez un trait enflammé sur une créature ou un objet à portée. Faites une attaque de sort à distance contre la cible. Si vous touchez, elle subit 1d10 dégâts de feu. Si le sort touche un objet inflammable qui n'est ni porté ni transporté, il s'embrase.

Les dégâts du sort augmentent de 1d10 quand vous atteignez le niveau 5 (2d10), le niveau 11 (3d10) et le niveau 17 (4d10).

La prochaine fois que vous blessez une créature avec une arme à distance qui inflige des dégâts perçants ou tranchants, l'arme reste fichée dans le corps de votre cible. Elle lui inflige 1d4 dégâts supplémentaires à chacun de vos tours suivants jusqu'à la fin du sort, ou jusqu'à ce qu'elle utilise son action pour retirer l'arme.

Retirer l'arme lui inflige 2d4 dégâts, ou la moitié si elle réussit un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md).

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de sort de niveau 2, remplacez les d4 par des d6. Pour chaque niveau de sort supérieur augmentez le dé utilisé, jusqu'au d12 pour un emplacement de niveau 5.

Ce sort crée un lien magique entre une plante inanimée de taille G ou supérieure située à portée et une autre plante de mêmes dimensions, située à n'importe quelle distance mais sur le même plan d'existence. Vous devez impérativement avoir vu ou touché la plante de destination au moins une fois auparavant. Pendant toute la durée du sort, n'importe quelle créature peut entrer par la plante de départ et ressortir par celle d'arrivée en dépensant 1,50 mètre de déplacement.

Vous créez une perturbation sismique en un point situé au niveau du sol, dans votre champ de vision et à portée. Pendant toute la durée du sort, d'intenses secousses agitent le sol dans un cercle de 30 mètres de rayon centré sur le point choisi. Elles ébranlent toutes les créatures et structures en contact avec le sol de cette zone.

Le sol affecté devient un terrain difficile. Toute créature qui se trouve en contact avec le sol et en pleine concentration doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md) sous peine de voir sa concentration brisée.

Quand vous lancez ce sort, et à la fin de chacun de vos tours passés à vous concentrer dessus, toutes les créatures en contact avec le sol de la zone affectée doivent réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md) ou tomber à terre.

Le sort a des effets supplémentaires selon le terrain affecté.

C'est au MJ de déterminer cela.

**_Fissures._** Une fois que vous avez lancé le sort, des fissures s'ouvrent dans toute la zone affectée au début de votre tour suivant. 1d6 fissures s'ouvrent en des points choisis par le MJ. Chacune fait 1d10×3 mètres de profondeur pour 3 mètres de large et s'étend d'un bout de la zone sismique à l'autre. Une créature qui se tient sur l'emplacement d'une fissure en train de s'ouvrir doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Si elle le rate, elle tombe dedans, sinon elle réussit à s'écarter à temps.

Une structure s'effondre automatiquement si une fissure s'ouvre sous elle (voir plus loin).

**_Structures._** Les secousses infligent 50 dégâts contondants à toute structure en contact avec le sol au moment où vous lancez le sort et au début de chacun de vos tours jusqu'à la fin du sort. Si l'une d'elles tombe à 0 point de vie, elle s'effondre et blesse peut-être les créatures voisines.

Une créature qui se trouve près d'un bâtiment en train de s'effondrer, à une distance égale ou inférieure à la moitié de la hauteur de ce bâtiment, doit effectuer un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Dextérité](hd_abilities_dexterity.md). Si elle échoue, elle subit 5d6 dégâts contondants, elle tombe à terre et elle est ensevelie sous les décombres. Il faut réussir un test de [Force (Athlétisme)](hd_abilities_strength_athletisme.md) DD 20 via une action pour y échapper. Le MJ peut modifier le DD en fonction de la nature des décombres. Si la créature réussit son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md), elle subit seulement la moitié des dégâts, ne tombe pas à terre et n'est pas ensevelie.

Vous devenez [invisible](hd_conditions_invisible.md) à l'instant même où un double illusoire de votre personne apparaît là où vous vous trouvez. Ce double persiste pendant toute la durée du sort, mais votre invisibilité se termine dès que vous lancez un sort ou attaquez.

Vous pouvez utiliser votre action pour déplacer votre double d'un maximum de deux fois votre vitesse et le faire bouger, parler et se comporter comme bon vous semble.

Vous pouvez voir par les yeux et entendre par les oreilles de votre double comme si vous vous trouviez à son emplacement. À chacun de vos tours, vous pouvez utiliser une action bonus pour passer d'une perception via ses sens à une perception via les vôtres ou inversement.

Tant que vous utilisez les sens de votre double, vous êtes sourd et aveugle à ce qui se passe directement autour de vous.

Vous percevez la présence de tout piège se trouvant à portée et dans votre champ de vision. Concernant ce sort, le terme de piège désigne toute chose qui inflige soudainement ou de façon inattendue un effet considéré comme néfaste ou indésirable et que son créateur a conçu dans ce but. Ainsi, le sort prévient si une zone est affectée par une alarme, un glyphe de garde ou une fosse piégée mécanique, mais il ne révèle pas une faiblesse naturelle dans un plancher, un plafond instable ou une doline cachée.

Le sort indique simplement qu'il y a un piège ; il ne précise pas où, mais vous donne une idée générale de la nature du danger qu'il représente.

Ce sort vous permet de trouver le chemin physique le plus direct et le plus court vers un endroit fixe spécifique avec lequel vous êtes familier et qui se trouve sur le même plan d'existence que vous. Le sort échoue si vous choisissez une destination située sur un autre plan d'existence, une destination mouvante (comme une forteresse mobile) ou une destination n'ayant rien de spécifique (comme l'antre d'un dragon vert).

Tant que le sort persiste et que vous êtes sur le même plan d'existence que votre destination, vous savez dans quelle direction et à quelle distance elle se trouve. Tant que vous faites route vers votre destination, à chaque fois que vous avez le choix entre plusieurs itinéraires, vous déterminez automatiquement celui qui sera le plus court et le plus direct (mais pas forcément le plus sûr).

Vous invoquez un esprit qui prend la forme d'une monture dotée d'une intelligence, d'une puissance et d'une loyauté hors du commun, et créez un lien durable avec lui. La monture apparaît dans un emplacement inoccupé à portée et prend l'apparence de votre choix : un cheval de guerre, un poney, un chameau, un élan ou un mastiff. (Votre MJ peut autoriser d'autres formes animales.) La monture possède le profil technique de la forme choisie mais, au lieu d'être de type normal, elle est céleste, féerique ou fiélone (à vous de choisir).

De plus, si elle a d'ordinaire une [Intelligence](hd_abilities_intelligence.md) de 5 ou moins, cette caractéristique passe à 6 et elle comprend un langage de votre choix que vous maîtrisez.

Vous pouvez chevaucher votre monture au combat ou en dehors des affrontements, et le lien instinctif que vous partagez avec elle vous permet de vous battre ensemble comme si vous étiez une seule et même entité.

Tant que vous la chevauchez, les sorts qui vous visent exclusivement l'affectent aussi si vous le désirez.

Quand la monture tombe à 0 point de vie, elle disparaît sans laisser de cadavre physique. Vous pouvez la renvoyer quand vous le désirez par une action qui la fait disparaître. Si vous lancez de nouveau ce sort, c'est la même monture qui apparaît, disposant à nouveau de tous ses points de vie.

Vous pouvez communiquer par télépathie avec votre monture tant qu'elle se trouve dans un rayon de 1,50 kilomètre.

Vous ne pouvez vous lier qu'à une seule monture issue de ce sort à la fois. Vous pouvez libérer la monture du lien quand vous le désirez, par une action qui la fait disparaître.

Une vague de force tonnante émane de vous. Chaque créature située dans un cube de 4,50 mètres d'arête partant de vous doit faire un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Constitution](hd_abilities_constitution.md).

Les créatures qui échouent subissent 2d8 dégâts de tonnerre et sont bousculées de 3 mètres en face de vous.

Les autres subissent seulement la moitié des dégâts et ne sont pas bousculées.

De plus, les objets qui ne sont pas arrimés et se trouvent entièrement englobés dans la zone affectée sont automatiquement éloignés de 3 mètres à l'opposé de vous. Le sort émet un grondement de tonnerre qui s'entend dans un rayon de 90 mètres.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 2 ou supérieur, les dégâts augmentent de 1d8 par niveau au-delà du premier.

Vous touchez une ouverture fermée, comme une porte, une fenêtre, un portail, un coffre ou autre. Elle se verrouille alors pour toute la durée du sort. Vous et toutes les créatures désignées lors de l'incantation du sort pouvez ouvrir l'ouverture normalement. Vous pouvez aussi définir un mot de passe qui, une fois prononcé dans un rayon de 1,50 mètre autour de l'objet fermé, dissipe le sort pendant 1 minute. Sinon, impossible d'ouvrir l'objet à moins de le briser ou de dissiper ou supprimer le sort. Un sort de _[déblocage](hd_spells_deblocage.md)_ supprime le verrou magique pendant 10 minutes.

Tant que l'objet est affecté par ce sort, il est bien plus difficile à briser ou à ouvrir de force : le DD pour le briser ou crocheter ses éventuelles serrures augmente de 10.

Vous tendez la main et pointez du doigt une cible à portée. Votre magie vous donne un bref aperçu de ses défenses. À votre prochain tour, vous avez l'avantage lors de votre premier jet d'attaque contre elle, à condition que le sort ne se soit pas terminé avant.

Vous touchez une créature consentante pour lui permettre de voir dans le noir. Pendant toute la durée du sort, elle bénéficie de la vision dans le noir à une distance de 18 mètres.

Grâce à ce sort, la créature consentante que vous touchez est capable de voir les choses telles qu'elles sont réellement.

Pendant toute la durée du sort, la cible bénéficie de vision parfaite, repère les portes dérobées cachées par magie et voit le plan éthéré, tout cela dans un rayon de 36 mètres.

Jusqu'à six créatures vivantes de votre choix, à portée et dans votre champ de vision, récupèrent 1 point de vie par round jusqu'à la fin du sort.

**_À plus haut niveau._** Lorsque vous lancez ce sort en utilisant un emplacement de sorts de niveau 4 ou supérieur, vous augmentez le nombre de points de vie récupéré par round de 1 point par niveau au-delà du niveau 3.

Pendant toute la durée du sort, vous voyez les créatures et les objets [invisibles](hd_conditions_invisible.md) comme s'ils étaient bien visibles et vous pouvez aussi observer le plan éthéré. Les créatures et les objets éthérés vous apparaissent comme des silhouettes translucides et fantomatiques.

Vous touchez une créature consentante et lui conférez la capacité de voler à une vitesse de 18 mètres pendant toute la durée du sort. Si la cible se trouve dans les airs quand le sort se termine, elle tombe, à moins de pouvoir arrêter sa chute.

**_À plus haut niveau._** Si vous lancez ce sort en utilisant un emplacement de niveau 4 ou supérieur, vous pouvez viser une créature de plus par niveau au-delà du niveau 3.

Vous créez une zone magique capable de protéger contre la duplicité, de la forme d'une sphère de 4,50 mètres de rayon centrée sur un point de votre choix situé à portée. Jusqu'à la fin du sort, une créature qui pénètre dans la sphère pour la première fois de son tour ou y commence son tour doit réussir un [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md) de [Charisme](hd_abilities_charisma.md). Si elle échoue, elle ne peut pas mentir délibérément tant qu'elle reste dans la zone du sort. Vous savez si chaque créature présente a réussi ou raté son [jet de sauvegarde](hd_abilities_jets_de_sauvegarde.md).

Une créature affectée est consciente du sort qui la limite et peut donc soigneusement éviter de répondre aux questions qui susciteraient normalement un mensonge de sa part. Une telle créature peut rester évasive dans ses réponses, tant qu'elle reste dans les limites de la vérité.

