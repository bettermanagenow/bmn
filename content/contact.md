---
title: 'Contact Us'
date: 2018-02-22T17:01:34+07:00
intro_image: "images/illustrations/pointing.svg"
intro_image_absolute: true
intro_image_hide_on_mobile: false
layout: contact
---

<span class="typewriter-cycle">We help small businesses in <typewritten-text>Better Management</typewritten-text> of their Finances, Accounts, Investments, and Taxes <mark>(FAIT)</mark>. Be positive and keep doing better things. Be better than the best, and be better than the rest!! Please <mark>CONTACT</mark> us.</span>

| <u>Day</u>       | <u>Opening Hours</u>   |
| --------- | --------------- |
| Monday    | 9:30am - 6:00pm |
| Tuesday   | 9:30am - 6:00pm |
| Wednesday | 9:30am - 6:00pm |
| Thursday  | 9:30am - 6:00pm |
| Friday    | 9:30am - 6:00pm |
| Saturday  | <mark>Closed</mark> |

<style>
.tableRow {background-color:rgb(246, 253, 253);} 
tr {background-color:rgb(246, 253, 253);} 
tr:hover {background-color: rgba(233, 235, 154, 0.76) !important;}
.selectedTableRow {background-color: rgba(141, 186, 238, 0.76) !important;}
typewritten-text {
  font-weight: bold;
  color: #f24088;  
}
</style>

<script>
document.querySelectorAll('.typewriter-cycle').forEach(cycle => {
  const items = cycle.querySelectorAll('typewritten-text')
  for (let i = 0; i < items.length; ++i) {
    const cur = items[i]
    const next = items[i === items.length - 1 ? 0 : i + 1]
    
    cur.addEventListener('typewritten-text:phrasetyped', () => setTimeout(cur.start, cur.phraseInterval))
    cur.addEventListener('typewritten-text:phraseremoved', () => {
      cur.classList.remove('active')
      next.classList.add('active')
      setTimeout(next.start, next.phraseInterval)
    })
  }
})
</script>