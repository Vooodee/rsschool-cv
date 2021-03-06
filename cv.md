# Welcom my profile
![Photo for my profile](https://github.com/Vooodee/rsschool-cv/blob/gh-pages/my-last-photo.png?raw=true)
---
* ## My contact information:
 * ### Sochial links 
    * ✉ **VK** -> [Write me a hot hi](https://vk.com/i_ac.dc_i)
    * 🔎 **Instagram** -> [It's me](https://www.instagram.com/rock_n_roll_la/)
    * ☎ **Discord(RS-school)** -> Egor Mironov (@Vooodee)
 * ### Other contacts
    * **mail** -> [wooodee@mail.ru](mailto:wooodee@mail.ru)
    * **Phone** -> [+375(25) 948-80-19](tel:375259488019)
* ## Let me introduce myself
*  My full name () {
  * [Last name] => '*Mironov*'
  * [First name] =>'*Egor*'
  * [Patronymic]=> '*Vitalievich*'
* }
1. ### My skills
   1. Base `HTML`
   2. Base `CSS` (+ `LESS`) 
   3. Base functions `PHP`
   4. I used *`Query` and `JS` sometimes
1. #### Other skills
2. #### Experience with the next CMS
   1. Wordpress ( + *Woocommerce* )
   2. CS-Cart
   3. Wix (~~do not judge strictly~~)  
4. #### Evaluation and **optimization** of the **download speed** according to the requirements of the *GooglePageSpeed* service
5. #### Experience working with different **hosting services** (*cPanel*, *domains*, etc.)
---
##### Will give an example of the code for the *Markdown* markup:
-- Don't know who selected this task and i thanks to you

```
# The first century spans from the year 1 up to and including the year 100, The second - from the year 101 up to and including the year 200, etc.
# Task:
# Given a year, return the century it is in.

function century(year) {
   return (year%100 >= 1)? Math.ceil(year/100): Math.trunc(year/100); 
}
```
---
##### _The code task is taken from **Codewars**.This task is cool_

```
while ($ic < $countM) {

    $categotia = get_terms(array(
        'taxonomy' => 'product_cat',
        'hide_empty' => true,
        'pad_counts' => true,
        'orderby' => 'menu_order',
        'parent' => $mas__id_cat[$ic]
   )); 
   $mid_cat = get_term($mas__id_cat[$ic])->name;
   foreach ($categotia as $cat) {

    $identificator = $cat->term_id;
    $full__name = 'Category description '. $mid_cat;
    $full__name_two = 'For a subcategory: '. $cat->name;

    $id_cat_id = 'ID_cat'.$identificator;

    $customizer->add_setting($id_cat_id, 
    array('default' => '')
    );
    
    $customizer->add_control($id_cat_id, array(
        'label' => $full__name,
        'description' => $full__name_two,
        'section' => 'settings_category',
        'type' => 'textarea',
    )
    );

}
$ic++;
}
```
##### _The code from my project is also for **example**_

##### I have 2 years of web development experience.

##### I don't have much English but I'm working on it.

###### When i ending this kurs, i will have next skills:
1. Experience basic language text markup  Markdown
2. Experience works in  system controls version git
3. And more `<!-- this list will be more-->` 

>
> *In theory, theory and practice are inseparable. In practice, this is not the case.*
>
> Yoggi Berra
