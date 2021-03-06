# Τίτλος Εργασίας: Οπτικοποίηση Δεδομένων
#### Ονοματεπώνυμο: Αλεξίου Ελευθέριος
#### Αριθμός μητρώου: Π2017143
#### Προφίλ στο Github: https://github.com/leuteris99

### Παραδοτέο 1:
#### Εκτελέσιμο link: https://leuteris99.github.io/D3js-US-educational-attainment/
#### link Προς κώδικα: https://github.com/leuteris99/D3js-US-educational-attainment/tree/paradoteoA (Branch: paradoteoA)

### Παραδοτέο 2:
#### Εκτελέσιμο link: https://leuteris99.github.io/D3js-US-educational-attainment/ (Ζητούμενα 1 και 2)
#### https://leuteris99.github.io/D3-Charts/ (Ζητούμενο 3)
 
#### link Προς κώδικα: https://github.com/leuteris99/D3js-US-educational-attainment/tree/paradoteoB (Ζητούμενα 1 και 2)(Branch: paradoteoB)
#### https://github.com/leuteris99/D3-Charts (Ζητούμενο 3)

## Στόχοι
Όλα τα ζητούμενα και τον δύο παραδοτέων ολοκληρώθηκαν με επιτυχία.
Μοναδικό πρόβλημα που προέκυψε ήταν ότι ο chrome 66 ή νεότερη έκδοση του απαγορεύει την αναπαραγωγή ήχων χώρις ο χρήστης να έχει
αλληλεπιδράσει με την σελίδα.
 
Πιο συγκεκριμένα τα ζητούμενα που ολοκληρώθηκαν είναι:

- Αλλαγή των χρωμάτων στα 3 γραφήματα.
- Αντικατάσταση των διεπαφών στα διαγράμματα 2 και 3.
- Αναπαραγωγή ήχου όταν το ποντίκι διέρχεται πάνω από μια επιλογή στο menu
- Λειτουργία text to speach όταν το ποντίκι διέρχεται πάνω από κείμενο.
- Εφαρμογή responsive design στην σελίδα.
- Τροποποίηση του κώδικα ώστε να είναι εμφανές μονο το επιλεγμένο απο το menu διάγραμμα.
- Αντικατάσταση των 3 διαγραμμάτων με 3 νέα.
- Δημιουργεία 3 νέων διαγραμμάτων με δεδομένα από μια επίσημη αρχή.

## Διαδικασία Ανάπτυξης
Για την συγγραφή της αναφοράς και του κώδικα χρησιμοποιείθηκε το Visual Studio Code σε συνδιασμό, για την εκτέλεση του κώδικα το
Google Chrome.
Για την ανάπτυξη του κώδικα χρειάστηκε αρχικά η εκμάθηση των γλωσσών html, css και javascript.
Βοηθητικά link που χρησημοποιείθηκαν:

- https://www.udacity.com/course/intro-to-javascript--ud803
- https://www.youtube.com/playlist?list=PL081AC329706B2953
- https://developer.mozilla.org/en-US/

Για την ολοκλήρωση του πρότου παραδοτέου ακόμη χρειάστηκε η εκμάθηση βασικών
λειτουργίων με jQuery καθώς και η εφαρμογή του responsive design:

- https://jquery.com/
- https://developers.google.com/web/fundamentals/design-and-ux/responsive/

Ενώ για την ολοκλήρωση του δεύτερου παραδοτέου χρειάστηκε η εκμάθηση της βιβλιοθήκης D3 και η χρήση του εργαλείου mapshaper για την
δημιουργία του χάρτη των ΗΠΑ:
 
- https://www.youtube.com/watch?v=n5NcCoa9dDU&list=PL6il2r9i3BqH9PmbOf5wA5E1wOG3FT22p
- https://mapshaper.org/
- https://www.youtube.com/watch?v=lPr60pexvEM

Άλλα εργαλεία που χρησιμοποιείθηκαν:

- Adobe Photoshop (γισ την επεξεργασία εικόνων)

## Παραδοτέο 1

- [x] Αλλάξτε τα χρώματα στα 3 γραφήματα.
![default](https://github.com/leuteris99/Final-Report/blob/master/images/colors.png)
- [x] Αντικαταστήστε τις διεπαφές στα "κουμπιά" του 2ου και 3ου γραφήματος με άλλες της επιλογής σας.
![default](https://github.com/leuteris99/Final-Report/blob/master/images/buttons.png)
- [x] Όταν το ποντίκι διέρχεται επάνω από κάθε επιλογή του menu στην κορυφή της σελίδας, να ακούγεται κάποιος ήχος της επιλογής σας.
- [x] Όταν το ποντίκι διέρχεται πάνω από κάποια πρόταση/κείμενο της σελίδας ή περιοχή που περιλαμβάνει γραπτή πληροφορία
(π.χ. κάποιο τμήμα γραφήματος), να ακούγεται αυτόματα η αφήγηση του κειμένου (text-to-speech).
- [x] Εφαρμόστε responsive design στη σελίδα και κυρίως στο αρχικό menu έτσι ώστε να προσαρμόζεται σε οθόνες διαφορετικών διαστάσεων.
![default](https://github.com/leuteris99/Final-Report/blob/master/images/responsive-design.jpg)
 
### Υποσημειώση (προβλήματα)
1. Στο Chrome 66 ή νεότερο ο browser απαγορεύει στην σελίδα να παιζεί media files πριν ο χρήστης αλληλεπιδράση με την σελίδα(π.χ. να
κάνει κλίκ οπουδίποτε μέσα στην σελίδα). Εξαιτίας του παραπάνω προβλήματος έγραψα κώδικα όπου αν ο χρηστης χρησιμοποιεί chrome να
ενημερόνεται με ενα alert.(στους υπολοιπους browser λειτουργεί κανονικά)
2. Το text-to-speach στο διάγραμα 2 λειτουργεί μέχρι να πατήσεις πάνω σε μια περιοχή.(μετά ο κώδικας text-to-speach δεν εκτελείται)
3. Το text-to-speach στο διάγραμα 3 λειτουργεί μόνο πάνω άπο τον πίνακα αντιστοίχισης χρώματος με κατηγορία.
 
## Παραδοτέο 2

- [x]  **Τροποποιήστε** τον **κώδικα** και το **μενού** της εφαρμογής έτσι ώστε κάθε στιγμή να είναι εμφανές **μόνο ένα** από τα 3
γραφήματα, **παραμένοντας** πάντα στη σελίδα **index.html**.
- [x]  **Αντικαταστήστε** το κάθε ένα από τα 3 γραφήματα με κάποιο άλλο διαδραστικό γράφημα της **D3js**.

### Horizontal Bar Chart

![default](https://github.com/leuteris99/Final-Report/blob/master/images/new_chart_1.png)

Έφτιαξα ένα διάγραμμα με οριζόντιες μπάρες όπου όταν ο χρήστη βάζει το ποντίκι πάνω από μια μπάρα,
η μπάρα μεγαλώνει και αναγράφονται τα δεδομένα μέσα σε αυτή.

### US Map Chart

Στο δεύτερο διάγραμμα έφτιαξα τον χάρτη των ΗΠΑ , όπου ο χρήστης μπορεί να βάλει το ποντίκι πάνω
από μια πολιτεία και δίπλα να εμφανιστούν τα στατιστικά για την πολιτεία αυτή.

![default](https://github.com/leuteris99/Final-Report/blob/master/images/new_chart_2.png)

### Triple Pie Chart

![default](https://github.com/leuteris99/Final-Report/blob/master/images/new_chart_3.png)

Στης 2 πρώτες "πίτες" περιέχονται τα ποσοστά κάθε πολιτείας (στην πρώτη για τις πολιτείες από A εώς M, στην δεύτερη για τις πολιτείες
από N εώς W),
αν ο χρήστης βάλει το ποντίκι σε ένα κομμάτι της πίτας τότε δημιουργείτε μια τρίτη πίτα
όπου περιέχει τα πιο αναλυτικά ποσοστά για την επιλεγμένη πολιτεία.

- [x]  Σε μια καινούργια σελίδα, να τοποθετήσετε αντίστοιχα 3 **νέα** διαδραστικά γραφήματα **D3js** της επιλογής σας, τα οποία
θα οπτικοποιούν **καινούργια** στατιστικά **δεδομένα** που θα βρείτε από κάποια επίσημη στατιστική αρχή.

### Points Chart

Ένα διάγραμμα με 2 άξονες, ένα για την χρονιά και ένα για την ποσότητα.
Το διάγραμμα αναπαρηστά το ΑΕΠ της Ελλάδας από το 1995 εώς το 2017 (σύμφωνα με στατιτικά από την ΕΛΣΤΑ 
(http://www.statistics.gr/el/statistics/-/publication/SEL15/-)).
Το κάθε σημείο στην κάθε χρονιά δείχνει το ΑΕΠ σε εκατομμύρια ευρό.
 
![default](https://github.com/leuteris99/Final-Report/blob/master/images/gdp-gr.png)

### Vertical Bar Chart

Διάγραμμα επίσης με 2 άξονες, ένα για την χρονιά και ένα για τα ποσοστά.
Το διάγραμμα δείχνει τα ποσοστά ανεργίας της Ελλάδας ετησίος από το 2004 εώς το 2017 (σύμφωνα με στατιστικά από την ΕΛΣΤΑ
(http://www.statistics.gr/el/statistics/-/publication/SJO02/-)).
Η κάθε μπάρα δείχνεί το ποσοστό ανεργίας στην αναφερόμενη χρονιά.

![default](https://github.com/leuteris99/Final-Report/blob/master/images/unemployment-gr.png)

### Bubble Chart

Διάγραμμα με φούσκες όπου η κάθε φούσκα αναπαριστά μια χώρα της ευρώπης ή ένα σύνολο χωρών.
Το διάγραμμα δείχνει το ΑΕΠ της κάθε ευρώπαϊκης χώρας ή ομάδας χωρών ανά έτως (σύμφωνα με στατιστικά από την
Eurostat(http://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=nama_10_gdp&lang=en)).
Το μέγεθος και το χρώμα της φούσκας είναι ανάλογο με το ΑΕΠ της χώρας (ή ομάδας χωρών) που αναπαριστά.
Στο αριστερό μέρος του διαγράμματος υπάρχει η χρονιά που αναπαριστά το διάγραμμα αυτή τη στιγμή και 2 κουμπιά για την αλλαγή 
της χρονιάς (και την ενημέροση του υπόλοιπου διαγράμματος με τα νέα δεδομένα).
Όταν ο χρήστης βάζει το ποντίκι πάνω από μια φούσκα τότε εμφανίζονται πληροφορίες με το όνομα το κράτους (ή ομάδας κρατών) 
και το ΑΕΠ του.
 
![default](https://github.com/leuteris99/Final-Report/blob/master/images/gdp-eu.png)
 
