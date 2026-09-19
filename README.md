# PhonePe UPI Payment Card — DZ0 Project

> **Project Goal:** Learn CSS by styling a PhonePe payment confirmation card — colours, typography, the box model, display flow, and everyday CSS properties.

---

## 📌 Progression Across Tickets (#1 – #4)

Here is a step-by-step breakdown of how the card was built across all four tickets:

### 1. Ticket #1: Semantic HTML Structure (The Unstyled Card)
- Set up a clean HTML5 boilerplate with descriptive tags.
- Built the logical card skeleton:
  - **Header:** Brand name & UPI payment tag.
  - **Body:** Success icon container, status heading, payment amount, recipient details.
  - **Bank Details:** Payment source card (bank name, masked account number).
  - **Dashed Perforation:** Visual receipt divider.
  - **Transaction Details:** Key-value pairs for UPI Reference ID (UTR), Transaction ID, and Date & Time.
  - **Actions:** Secondary ("Share Receipt") and primary ("Done") action buttons.
  - **Footer:** Security badge and "Powered by UPI" accreditation.

### 2. Ticket #2: Colours, Typography & Brand Styling
- Applied PhonePe's signature brand palette:
  - **Primary Purple:** `#5f259f` (header, brand accents, primary buttons)
  - **Dark Purple:** `#4b1b80` (button hover, headings)
  - **Success Green:** `#1da862` (success checkmark badge & status text)
  - **Background Tint:** `#f1ecf9` and card background `#faf7fd`
  - **Neutral Greys:** `#212121`, `#666666`, `#7b7b7b` for clear visual hierarchy.
- Established typography scales (font weights from 400 to 800, clear currency symbol styling).

### 3. Ticket #3: The Box Model (Margin, Padding, Borders & Sizing)
- Configured universal `box-sizing: border-box` to ensure predictable element dimensions.
- Styled inner containers with consistent padding (`padding: 24px 20px`).
- Formatted spacing using targeted `margin` values to create breathable rhythm between sections.
- Created the ticket-notch effect using pseudo-elements (`::before` & `::after`) over a dashed border line (`border-top: 1.5px dashed`).

### 4. Ticket #4: Display, Layout & Interactive Polish
- Used **Flexbox** (`display: flex`, `justify-content: space-between`, `align-items: center`, `gap`) for aligned headers, detail rows, and action button groups.
- Added modern card aesthetics:
  - `border-radius: 18px` for smooth rounded edges.
  - Layered `box-shadow` (`0 10px 28px rgba(95, 37, 159, 0.15)`).
  - Smooth interactive transitions on buttons (`:hover` state with colour shifts).
  - Responsive layout with `max-width: 380px` and `width: 100%` ensuring perfect rendering across mobile and desktop viewports.

---

## 🚀 How to Submit via GitHub Pull Request

### Step 1: Push Your Code to a New Branch
Run the following commands in your terminal:

```bash
# 1. Navigate to the repository
cd tiwaripawankumar217-cmd-learn-css-by-styling-a-p-2dfd6423

# 2. Create and switch to a new branch
git checkout -b feat/phonepe-payment-card

# 3. Stage the files (index.html and README.md)
git add index.html README.md

# 4. Commit your work
git commit -m "Complete PhonePe payment card (Tickets #1 - #4)"

# 5. Push the branch to GitHub
git push -u origin feat/phonepe-payment-card
```

---

### Step 2: Open a Pull Request
1. Open your repository on GitHub:
   👉 **[dayzero-hub/tiwaripawankumar217-cmd-learn-css-by-styling-a-p-2dfd6423](https://github.com/dayzero-hub/tiwaripawankumar217-cmd-learn-css-by-styling-a-p-2dfd6423)**
2. Click **"Compare & pull request"** (or go to the **Pull requests** tab and click **"New pull request"**).
3. Set **base: `main`** and **compare: `feat/phonepe-payment-card`**.

---

### Step 3: Fill Out the PR Description
Paste the following into your Pull Request description (replace `#N` with your actual issue/ticket number from your Issues tab):

```markdown
Closes #N

## What I did
Completed the PhonePe UPI payment confirmation card across all 4 project tickets:
- **Ticket #1 (Unstyled Card):** Built the complete semantic HTML skeleton containing brand header, payment status, amount, bank source box, transaction metadata, action buttons, and security footer.
- **Ticket #2 (Colours & Text):** Implemented PhonePe brand identity (signature `#5f259f` purple, `#1da862` success green, and subtle background tints) with typography hierarchy.
- **Ticket #3 (Box Model):** Structured spacing with padding, margins, borders, and a perforated ticket-style dashed separator with notch cutouts.
- **Ticket #4 (Display, Flow & Polish):** Utilized Flexbox for responsive alignment, added border radii, box-shadows, button hover micro-interactions, and responsive container constraints.
```

4. Click **"Create pull request"**.
