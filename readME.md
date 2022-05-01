##README
This application is meant to serve as motivation to practice healthy habits and further one's goals. We designated tasks to get points; these points can then be traded in for prizes. Similar to buying prizes with earned tickets at an arcade. My partner and I are also using this application to save money, because we are not allowed to buy another outside of these prizes. Adjusting tasks and prizes on a monthly basis will allow us to focus on what furthers our goals and focuses our attention on spending money on what we really want.

How is this going to work? What functions will be in this application?
It should have an inviting look that makes you want to be sedulous in your attempt to earn prizes.
Prizes will be display in circle (later iteration is to have different sized circles based on prize tiers), when you hover over the prize image it will fade in a black backgroun with white text (prize point cost).
In the upper left we want an entry field with a searchable drop list (i.e. user types "read" and in the drop down list you should see tasks like "read a book chosen by partner = 30 points", "read a book you own = 20 points", or "read a library book = 17 points"). When you find your task that you completed you can submit and display a confirmation window in which you choose which user to add the points to. Each user will have a sum of points, or tickets, when you want to buy a prize you can click on that prize and it will pop up a confirmation to see which user is buying the prize then it will subtract the points from your point total. If you don't have enough points return error message. Next to entry field there should be a question mark that the user can click to display point charts for both tasks and prizes.Should also have access for user to see what their personal point total is.

Rough list of prizes and tasks.
let prizes = {
  sticker: 5;
  comicBook: 20:
  pastryCandy: 25;
  coffee: 35;
  funkoPop: 60;
  preroll: 70;
  comicBookVolume: 90;
  book: 100;
  tattooTwenty: 100;
  edibles: 125;
  eighthConcentratePrerollPack: 200;
  pointsForCashTwenty:  200;
  clothingItemShoesOrTwoUnderFifty: 350;//was the item 75 and under?
  highEndFunko: 350;
  boardGame: 400;
  dateNight: 750;
  gPenConnect: 800;
}

let tasks = {
  hydration: .5; //how should i note it is up to three points a week
  dentalRoutine: 1; //morning and night routine equals 1 point combined up 5 points a week
  showerThree: 1;
  workoutFive: 1;
  bikeRide: 1;
  journalFive: 1;
  dogParkHour: 1;
  orderFood: 2;
  orderCustomFood: 5;
  codingTwoHours: 5; //this is outside of schoolwork
  readLibraryBook: 10;
  cookNewRecipeRob: 10;
  readPersonalBook: 20;
  walk: 20;
  readPartnerBook: 25;
  cookNewRecipeTia: 30;
  bathingDogs: 30;
  startNewHobby: 40;
  hike: 100;
  deepCleanBathroom: 100;
  finishCurrentOrSmallProject: 150;
  finishNewProject: 300;
  finishWritingNovel: 500;


RECOGNITION/SOURCES
Sites
  https://imagecompressor.com/

Images
    Yosep Sugiarto, cinnamonroll.jpg    https://unsplash.com/photos/1PEqqv4i2iM?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
    Jon Tyson, sticker.jpg   https://unsplash.com/photos/rW854PQU3ts?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
    Erik Mclean, comicbook.jpg     https://unsplash.com/photos/5pTPknX_Gzw?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
    preroll.jpg    https://wcp2018.org/why-you-should-use-pre-roll-joints.html
    Mikolaj, book.jpg    https://unsplash.com/photos/LV6wQnJfNRo?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
    Allef Vinicius, tattoo.jpg    https://unsplash.com/photos/hxNiXP498UI?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
    Plant For Persephone, edible.jpg    https://unsplash.com/photos/M5WX9Xr36N8?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
    Sharon McCutcheon, cash.jpg    https://unsplash.com/photos/8lnbXtxFGZw?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
    József Koller, boardgame.jpg    https://unsplash.com/photos/vrvKnqlPwzI?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
    Hitesh Dewasi, datenight.jpg    https://unsplash.com/photos/5JwBbnyZzfc?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
