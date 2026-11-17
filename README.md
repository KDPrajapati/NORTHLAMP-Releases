<h1>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="media/northlamp_lockup_dark.png">
    <img src="media/northlamp_lockup.png" alt="NORTHLAMP" width="338">
  </picture>
</h1>

### The daily report nobody has to make.

A lamp for your books.

NORTHLAMP is a 64-bit Windows app for the people who run a business. It reads the books you already keep and shows what they mean: what is owed to you and what you owe, who buys and who is slipping, what is short and what is sitting dead, selling price and cost.

It never writes to your accounting software. Every request it sends there is a read, the same kind made when you print a report.

Works with: Tally. More accounting software to follow.

## What you see

Home opens with what needs you today: the urgent items first, then the rest to act on. Across the top: Money, Clients, Inventory, Prices and, on Enterprise and above, Team. Each place is a set of cards. Once your books are read, each card is one figure in one sentence. Open any card and the page behind it is there.

## How it treats your books

- It runs on your own PC. Your sales, clients, prices and stock live in a file on that PC.
- Nothing from your books leaves your PC unless you use a feature that sends it, such as off-site backup to a cloud you choose, the optional AI assistant, sharing with your other laptops, or web search. WhatsApp order collection only reads orders in.
- On a paid plan or a trial the internet features stay shut until you switch them on. On the Free plan, installed for one user, they normally start on. You can shut them under Settings, Internet access. The WhatsApp message buttons are on for every plan; they only open a chat you send yourself.
- Off-site backup runs only after you choose a folder or storage address, and stops when you remove it. Sharing runs only after you choose a folder and start it.
- Apart from features you set up, it sends on its own only a weekly version check and, once a licence key is in (not a trial), a licence check-in: once a day, and every 10 minutes on the main PC or any PC not approved. None of these carries figures from your books. The app's About page describes the version check and the daily check-in, and Airplane mode blocks them all.
- After every live read it checks its figures against your accounting software's own totals. The full list of things to act on says in one line which match, which do not and which were not checked.

## Download and install

Each update is published under [Releases](../../releases). Download the `NORTHLAMP-Setup` file from the newest one and run it. If an earlier version is installed, run the new installer over the top: your book, your backups and everything you have taught the app are kept. **Do not uninstall first.**

The installer is not code-signed yet, so Windows may warn about an unrecognised publisher (choose **More info, then Run anyway**), and your browser may ask you to keep the file.

**Check your download.** Each release carries a signed `manifest.json` with the installer's SHA-256. If you download the installer yourself, compare its SHA-256 with the one in the manifest. When the app updates itself, it refuses any download that does not match the signed file.

## Plans

Four plans: Free, Pro, Enterprise and Tycoon. Free reads a file you export from your accounting software; the paid plans read it live over your network, with no manual export. The app's About page, under Your plan, lists what your plan includes. Enter your licence key when the app first opens, or later in Settings, under Plan.

To get a licence, e-mail krupeshdprajapati@gmail.com.

## Coming next

- Stock and delivery planning.
- Versions for Mac, iPhone and Android.

## If something looks wrong

Open Help and support, then Report a problem, and write what happened. The app packs the details into one file for you to send.

## What is in this repository

Built installers and their signed manifests. The source code is private.

Built by Krupesh Prajapati, with the help of AI tools.
