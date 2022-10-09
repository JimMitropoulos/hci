# Μάθημα: Επικοινωνία Ανθρώπου Υπολογιστή

### Ονοματεπώνυμο: ΑΡΓΥΡΩ ΜΑΡΙΟΛΗ
### Αριθμός Μητρώου: Π2017089
### GitHub Profile: [p17mari](https://github.com/p17mari)
<br />

## Πίνακας με σύνοψη των παραδοτέων

| Εβδομάδα* | Παραδοτέο |
| --- | --- |
| 1 | [Φορκ του αποθετηρίου και δημιουργία της σελίδας της αναφοράς με τα προσωπικά στοιχεία σας, της σύνοψης με αυτόν τον πίνακα περιεχομένων, και συγγραφή της εισαγωγής με περιγραφή των αναγκών και των στόχων σας για το μάθημα :Εισαγωγή](Πρώτες---Βδομάδες,---εγκατάσταση---ArchLinux---σε---Dual---Boot)|
| 2 | [Άσκηση γραμμής εντολών: Dual Boot and Troubleshooting](Dual---Boot---and---Troubleshooting)|
| 3 | [Άσκηση γραμμής εντολών: Virtual Box και tutorials](Virtual---Box---και---tutorials)|
| 4 | [Συμμετοχικό περιεχόμενο: Α1 και Α2](Συμμετοχικό---περιεχόμενο:---Α1---και---Α2)|
| 5 | [Άσκηση γραμμής εντολών: Warmup Youtube Download](Άσκηση---γραμμής---εντολών:---Warmup---Youtube---Download)|
| 6 | [Συμμετοχικό περιεχόμενο 2A](Συμμετοχικό---περιεχόμενο:---Β1---και---Β2) |
| 7 | [Άσκηση γραμμής εντολών: Warmup Check the Weather](Άσκηση---γραμμής---εντολών:---Warmup---Check---the---Weather)|
| 8 | [Άσκηση γραμμής εντολών: Warmup fetch information](Άσκηση---γραμμής---εντολών:---Warmup---fetch---information)|
| --- | --- |

# Πρώτες Βδομάδες, εγκατάσταση ArchLinux σε Dual Boot
## Προσδοκίες για το μάθημα
Σε αυτό το μάθημα ευελπιστούσα να κατανοήσω καλύτερα τις διαφορές μεταξύ των λειτουργικών συστημάτων και την διεπαφή που μου προσφέρουν και κατα την χρήση των Arch να καταλάβω τι μου είναι όντως αναγκαίο από τον υπολογιστή και τι είναι περιττό και έχω απλά συνηθίσει. Στόχος είναι να αναγνωρίσω τι απαιτήσεις θα είχα εαν μεταφερόμουν από τα συστήματα που έχω δεί ως τωρα σε customised OS.
Για αυτούς τους λόγους ήθελα το σύστημα ArchLinux στο οποίο θα εργαζόμουν σε αυτό το εξάμηνο να το είχα σε DualBoot με τα Windows 10 έτσι ώστε να κάνω μια καθαρή σύγκριση.

# Dual Boot and Troubleshooting
Στην αρχή του εξαμήνου ήθελα να εγκαταστήσω το ArchLinux σε Dual Boot όπως είχα κάνει στο παρελθόν με Ubuntu περιβάλλον. Η εγκατάσταση γινόταν επιτυχώς αλλά συνάντησα πολλές δυσκολίες λειτουργικότητας και για αυτό μετέφερα το περιβάλλον σε Virtual Box. Συγκεκριμένα τα προβλήματα που συνάντησα αφορούσαν τον bootloader και την αναγνώριση δικτύο με netctl. Ο Bootloader που χρησιμοποίησα είναι ο Grub και δεν αναγνώριζε το σύστημα των windows. Για να μεταφερθώ κατα την εκκίνηση στα windows έπρεπε να μπώ χειροκίνητα από τον πίνακα ελέγχου με esc f11. Δεν είχε διαγραφεί ο bootloader των windows απλά θεωρούταν δευτερεύων σύστημα και για αυτό άνοιγε το grub στην αρχή το οποίο και Pre και post-install δεν αναγνωριζε τα windows. Οπότε απεγκατέστησα τα Arch και έκανα resize το πρώτο partition που είχα φτάξει.

# Virtual Box και tutorials
Μετά από την παραπάνω προσπάθεια μεταφέρθηκα σε vm συγκεκριμένα το Oracle Virtual Box. Σε αυτό έφτιαξα ένα partition Arch Linux των 64GB στο οποίο έκανα install χρησιμοποιόντας το python script archinstall. Επιπλέον πακέτα που ζήτησα κατα την εγκατάσταση ήταν sudo, nano, vim, neofetch, NetworkManager, netctl. Στην αρχή δούλεψα με GNOME περιβάλλον αλλά θεώρησα ότι η διεπαφή με γραφικό περιβάλλον για τις απαιτήσεις του μαθήματος δεν είναι αναγκαστικές οπότε το αφαίρεσα από το σύστημα μου. Για προσωπική χρήση σίγουρα θα ήθελα να χρησιμοποιήσω κάποιο γραφικό περιβάλλον διότι στον ελεύθερο μου χρόνο ασχολούμε με το digital art. Αλλά θα ήθελα να μελετήσω καλύτερα τα διαθέσιμα γραφικά περιβάλλοντα για να καταλήξω σε ένα το οποίο θα ταιριάζει με τα προγράμματα που χρησιμοποιώ συνήθως.

[Neofetch](https://asciinema.org/a/463566)

# Συμμετοχικό περιεχόμενο: Α1 και Α2
Το RamKid για το εκπαιδευτικό παιχνίδι Πέρης και Κάτια ένα λογισμικό παθητικής διάδρασης για την εξοικίωση παιδιών δημοτικού με τον ηλεκτρονικό υπολογιστή. Επέλεξα αυτή την εφαρμογή διότι θυμάμαι να την χρησιμοποιώ εγώ όταν είχαν πρωτοβγεί και ήταν μια από τις πρώτες επαφές που είχα εγώ με εκπαιδευτικά προγράμματα. Επιπλέον επέλεξα αυτό το πρόγραμμα διότι είναι από τα λίγα και πρώτα εκπαιδευτικά προγράμματα για υπολογιστές που είναι όλο στο ελληνικά. Λόγω του περιεχομένου της εφαρμογής το κατέταξα στο χρονολόγιο βιντεοπαιχνίδια.

![330px-Kidepedia_τόμος_1](https://user-images.githubusercontent.com/43947917/144871199-b6eb8644-9932-485d-94a4-68a8c4371079.png)
| --- |
[md link](https://github.com/p17mari/_gallery/blob/master/ramkid.md)
| --- |
Για την δεύτερη εικόνα επιλέχθηκε το Leafpad το text editor Leafpad λογισμικό επεξεργασίας κειμένου για Linux.
Το Leafpad είναι ένα πρόγραμμα επεξεργασίας κειμένου ανοιχτού κώδικα για Linux, δημιουργήθηκε με στόχο να είναι ελαφρύ με ελάχιστα dependencies. 

![Leafpad](https://user-images.githubusercontent.com/43947917/144891270-dc3aca5c-567a-4187-abaa-7dfee82a82f1.png)
| --- |
[md link](https://github.com/p17mari/_gallery/blob/master/Leafpad.md)
| --- |


# Άσκηση γραμμής εντολών: Warmup Youtube Download
Aναζητήστε, κατεβάστε και παίξτε (με το τερματικό) το αγαπημένο σας τραγούδι του μήνα από το youtube. Κατέβασα το πακέτο του youtbe-dtl και το mpv player με την εντολή pacman youtube-dtl mpv. Η λήψη του αρχείου με την αναζήτηση ytsearch και την λέξη κλειδί που επιλέγεις ήταν εύκολη. Είχα μια μικρή δυσκολία με το format του αρχείου δεν είχα συνηδειτοποιήσει ότι το mpv δεν δέχεται mp4 αρχεία. Όταν το διόρθωσα το αρχείο έπαιζε κανονικά.
![image](https://user-images.githubusercontent.com/43947917/151203784-d2bc0055-5ebd-44d6-8d4d-f18614a282d3.png)

[download mp3](https://asciinema.org/a/463720)


# Συμμετοχικό περιεχόμενο: Β1 και Β2
## Β1 Βιβλιογραφία Seymour Papert

![Seymour_Papert](https://user-images.githubusercontent.com/43947917/151183355-a2331a2f-a925-4d7b-9751-72fc4ccbb6a5.jpg)

"Ο Seymour Papert ταν ένας από τους κύριους της πρωτοβουλίας One Laptop Per Child για την κατασκευή και τη διανομή του The Children's Machine σε αναπτυσσόμενες χώρες. Πάνω στην ανάλυση της θεωρίας του εποικοδομιτισμού βασίστηκε ο Alan Kay κατασκευάζοντας το Dynabook"

categories:
  - Βιογραφία 
  - Ορισμός 
tags:
  - Seymour Papert
  - Alan Kay
  - Dynabook

[md link](https://github.com/p17mari/site/blob/master/_biography/seymour-papert.md)

## Β2 Μελέτη Περίπτωσης: Lego Mindstorms
![lego-mindstorms](https://user-images.githubusercontent.com/43947917/151206662-1154cf40-01a0-4284-9d38-af6bb8afacc3.jpg)

Το Lego Mindstorms είναι μια δομή υλικού και λογισμικού που παράγεται από τη Lego για την ανάπτυξη προγραμματιζόμενων ρομπότ βασισμένων σε Lego blocks. Κάθε έκδοση του συστήματος περιλαμβάνει ένα τούβλο Lego υπολογιστή που ελέγχει το σύστημα, ένα σύνολο αρθρωτών αισθητήρων και κινητήρων και εξαρτήματα Lego από τη σειρά Technic για τη δημιουργία των μηχανικών συστημάτων.

categories:
  - Μελέτη Περίπτωσης
  - Εργαλεία

[md link](https://github.com/p17mari/site/blob/master/_case-study/lego-mindstorms.md)

# Άσκηση γραμμής εντολών: Warmup check the weather
Λάβετε την πρόγνωση του καιρού για την πόλη σας και μια ακόμη πόλη στην οποία θέλετε να πάτε. Έλενξα τον καιρό στην Αθήνα και την Κέρκυρα. Είδα επίσης τον αριθμό της σεληνιακής φάσης, ποσοστά υγρασίας και ημερίσια πρόγνωση πέρα απο την εβδομαδιαία. 
![image](https://user-images.githubusercontent.com/43947917/151201790-4d91de92-1446-40b8-8508-d962dbfd93b2.png)
[check the weather](https://asciinema.org/a/463741)

# Άσκηση γραμμής εντολών: Warmup fetch information
Διαβάστε τα business news. Πέρα από άρθρα επιχειρηματικά έκανα και έλεγχο για άρθρα σχετικά με covid καθώς και κάποιες επιπλέον εντολές που είχε στο αντίστοιχο άρθρο στο github. Έλενξα να δώ αν έχει διαθέσιμα άρθρα και σε άλλες θεματικές περιοχές με άλλες λέξεις κλειδιά.

![image](https://user-images.githubusercontent.com/43947917/151202835-bc9f4c91-c5b0-494a-aeeb-37c454cbb8c9.png)

Fetch Information[part one](https://asciinema.org/a/463738), [part two](https://asciinema.org/a/463742)

# Ομαδικότητα και Συνεργασία
https://github.com/courses-ionio/hci/discussions/1738
https://github.com/courses-ionio/hci/discussions/1739
https://github.com/courses-ionio/hci/discussions/1631