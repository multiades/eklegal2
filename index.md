---
layout: default
---

<!DOCTYPE html>
<html lang="el">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="./assets/css/styles.css" rel="stylesheet" type="text/css">
    <title>Παρουσίαση | eklegal</title>
  </head>
  <body>
    <div class="scrollbox"> <!-- It glides in relation with the body -->
      <header>
        <picture class="background">
          <source srcset="./assets/images/library_2_3.jpg" media="(max-width: 42rem)"> 
          <img src="./assets/images/library_16_9.jpg" class="background">
        </picture>
        <picture class="foreground"> 
          <source srcset="./assets/images/desk_2_3.png" media="(max-width: 42rem)">
          <img src="./assets/images/desk_16_9.png" class="foreground">
        </picture>
        <p>
          <span class="name">Καραμπάτσου Ελισάβετ</span><br>
          Νομικός Σύμβουλος, <abbr lang="en" title="Master of Science">M.Sc.</abbr>
      </p>
      <div class="bar">
        <!-- <img src="./assets/images/whale.png" alt="The logo, a cute whale"> -->
        <button><span class="material-symbols-outlined">menu</span></button>
        <input type="checkbox" id="toggler" unchecked> <!-- Invisible checkbox -->
      </div>
      <nav> <!-- We put it here, so as not to be a flex item. It also places it above the top bar -->
      <ul>
        <li><a href="#">Αρχική</a></li>
        <li><a href="#">Σχετικά</a></li>
        <li><a href="#">Τομείς</a></li>
        <li><a href="#">Νέα</a></li>
        <li><a href="#">Παρουσίαση</a></li>
      </ul>
    </nav>
      </header>
      <main>
      <h1>Κύρια επικεφαλίδα σελίδας</h1>
      <p> 
          Σε αυτήν την ενδεικτική σελίδα παρουσιάζονται ορισμένα δομικά στοιχεία πού δύνανται να περιέχουν οι ιστοσελίδες του ιστοτόπου,
          ώστε να διακρίνουμε και την εμφάνισή τους διαμέσω στυλιστικών μεταβολών. Τα βασικά στοιχεία οργάνωσης περιεχομένου είναι οι επικεφαλίδες 
          και οι παράγραφοι. Οι παράγραφοι οργανώνονται λογικά μέσω των επικεφαλίδων. Yπάρχουν 6 επίπεδα επικεφαλίδων. Κάθε επικεφαλίδα 
          επιπέδου ν υπάγεται εντός του περιεχομένου της επικεφαλίδας ν - 1, με ν μεγαλύτερο του 1.
          Κάθε σελίδα του ιστοτόπου δύναται να περιέχει έως μία κύρια επικεφαλίδα (επικεφαλίδα επιπέδου 1), διότι εκείνη, αν υπάρχει, συνοψίζει το περιεχόμενο
          ολόκληρης της σελίδας. 
       </p>
        <h2>Επικεφαλίδα επιπέδου 2</h2>
        <h3>Επικεφαλίδα επιπέδου 3</h3>
        <h4>Επικεφαλίδα επιπέδου 4</h4>
        <h5>Επικεφαλίδα επιπέδου 5</h5>
        <h6>Επικεφαλίδα επιπέδου 6</h6>
        <p>
          Κάθε παράγραφος υπάγεται στην αμέσως προηγούμενη επικεφαλίδα (η συγκεκριμένη, αλλά και η επόμενη ανήκουν στην επικεφαλίδα επιπέδου 6). Ακολουθεί αλλαγή
          γραμμής.<br>
          Αλλάξαμε γραμμή αλλά όχι παράγραφο. Ακολουθεί αλλαγή παραγράφου.
        </p>   
        <p>
          Αυτή είναι μι' άλλη παράγραφος. Το κείμενο δύναται να είναι <span class="bold">έντονο</span>, <span class="oblique">πλάγιο</span>,
          <span class="underlined">υπογραμμισμένο</span>, <span class="strikethrough">διαγραμμισμένο</span> ή <span class="overlined">υπεργραμμισμένο</span>,
          καθώς και κάθε δυνατός <span class="combo">συνδυασμός</span> των παραπάνω, σε διάφορα χρώματα. Ακολουθεί ένας οριζόντιος κανόνα
          που σηματοδοτεί κάποια αλλαγή στο περιεχόμενο.
        </p>
        <hr>
        <h2>Εικόνα</h2>
        <figure>
          <img src="assets/images/justice.png" alt="Η δικαιοσύνη ως γυναίκα, με το ξίφος και τον ζυγό">
          <figcaption>Λεζάντα: δικαιοσύνη</figcaption>
        </figure>
        <h2>Μη διατεταγμένη λίστα</h2>
        <ul>
          <li>Πρώτο μέλος της λίστας</li>
          <li>Δεύτερο μέλος της λίστας, εμφωλευμένη λίστα<br>
            <ul>
              <li>Πρώτο μέλος της εμφωλευμένης λίστας</li>
              <li>Δεύτερο μέλος της εμφωλευμένης λίστας</li>
            </ul>
          </li>
          <li>Τρίτο μέλος της λίστας</li>
        </ul>
        <h2>Διατεταγμένη λίστα</h2>
        <ol>
          <li>Πρώτο μέλος της λίστας</li>
          <li>Δεύτερο μέλος της λίστας</li>
          <li>Τρίτο μέλος της λίστας</li>
        </ol>
        <h2>Περιγραφική λίστα</h2>
        <dl>
          <dt>Πατρώνυμο</dt>
          <dd>Frankenstein</dd>
          <dt>Τόπος γέννησης</dt>
          <dd>Ίνγκολστατ</dd>
          <dd>Βαυαρία</dd>
          <dt>Σφυγμοί ανά λεπτό</dt>
          <dd>0</dd>
        </dl>
        <h2>Απόφθεγμα</h2>
        <blockquote>Αυτό είναι ένα απόφθεγμα, Κάποιος</blockquote>
        <h2>Άλλη μια εικόνα</h2>
        <figure>
          <img src="assets/images/whale.png" alt="Γλυκιά φάλαινα">
          <figcaption>Λεζάντα: το προσωρινό λογότυπο, φαίνεται και στην καρτέλα</figcaption>
        </figure>
        <h2>Πίνακας</h2>
        <table>
          <tbody>
            <tr>
              <th>Κυνοειδή</th>
              <th>Αιλουροειδή</th>
            </tr>
            <tr>
              <td>Κογιότ</td>
              <td>Λύγγας</td>
            </tr>
            <tr>
              <td>Λύκος</td>
              <td>Τίγρης</td>
            </tr>
            <tr>
              <td>Ύαινα</td>
              <td>Γατόπαρδος</td>
            </tr>
          </tbody>
        </table>
        <p>Ακολουθεί το υποσέλιδο και τερματίζεται η παρούσα σελίδα.</p>
      </main>
      <footer>        
        <p>
          <span class="name">Καραμπάτσου Ελισάβετ</span><br>
          Νομικός Σύμβουλος, <abbr lang="en" title="Master of Science">M.Sc.</abbr>
        </p>
         <p>
            Επικοινωνία:<br>
            τηλέφωνο: ...<br>
            email: ...
         </p>
         <p>
           Διεύθυνση:<br>
           ..., ...
         </p>
         <hr> 
         <p>Δικαιώματα</p>
      </footer>
    </div> <!-- scrollbox ends here -->
  </body>
</html>
