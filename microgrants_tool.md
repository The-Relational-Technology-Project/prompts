# Microgrants Tool

A site to help streamline microgrants for neighbors to host gatherings, cover small costs, and spark connection. This tool provides an end-to-end flow: from applying, reviewing, and approving, to reflecting and sustaining momentum.  

---

## Core Principles
- **Small is powerful**: Keep grants low-dollar (e.g. $50) to encourage action over perfection.  
- **Ease of access**: Short, human-friendly applications that don’t require professional grant-writing.  
- **Trust before bureaucracy**: Generous design that minimizes reporting burden.  
- **Momentum, not transactions**: Each grant is a seed for continued connection and care.  
- **Commons-oriented**: Microgrants are onramps to the broader relational infrastructure.  

---

## Site Identity & Tone
- **Branding**: Friendly, civic, and trust-building. Warm typography (Inter, Nunito, Source Sans) and grounded palette (blues, oranges, neutrals).  
- **Tone of Copy**: Encouraging, straightforward, neighbor-to-neighbor.  
- **Logo Space**: Allow organizers to upload their own logo.  

---

## Homepage
- **Hero Section**:  
  - Headline: *“Gather your neighbors. Get support.”*  
  - Sub-headline: *“Apply for a $50 microgrant to bring people together in your shared place.”*  
  - Prominent CTA: **Get Support**.  
  - Secondary CTA: **Donate** (to fund more microgrants).  
- **How It Works**: 3-step flow with icons.  
  1. **Apply** – “Tell us your idea for bringing neighbors together.”  
  2. **Get Support** – “We’ll select hosts and send $50 microgrants.”  
  3. **Gather** – “Host your event and share back what happened.”  
- **Timeline**: Rolling or fixed windows (Applications open → Selection → Gatherings → Reflections).  
- **Stories/Reflections Carousel**: Photos, pull quotes.  
- **Footer**: Partner logos, mission note, remix link (“Remix this tool to run your own microgrants program”).  

---

## Application Flow (Public)
Multi-step form with progress bar.  
1. **Basic Info**: Name, email, ZIP, optional phone.  
2. **Your Gathering**:  
   - Date (calendar picker).  
   - Short description (prompt: *“In a few sentences, describe your gathering and how it helps neighbors imagine what’s possible together.”*).  
   - Expected attendees.  
   - How funds will be used (checkboxes: food, supplies, space, other).  
3. **Commitment**: Checkbox agreeing to reflection afterward.  
4. **Confirmation Page**: *“Thanks! You’ll hear from us soon.”*  

**Automations**:  
- Email to applicant confirming receipt with copy of submission.  
- Email to admin notifying of new application.  

---

## Admin Dashboard
Password-protected with tabs:  
- **Applications Table**: Columns for name, email, event date, funding request, status.  
- **Qualification**: Mark as qualified/unqualified.  
- **Selection**: Randomized or manual approval.  
- **Bulk Email Copy**: One-click to copy all emails in a status view for BCC.  
- **Notes Field**: Add steward notes.  
- **Reflections Tracking**: Mark received; link to reflections.  
- **Payment Tracking**: Manage disbursements.  
- **Export**: Applications and reflections exportable as CSV.  

---

## Reflections Page (Public Form)
- Headline: *“Share your gathering story”*.  
- Fields: Name, email, # attendees, short narrative (“What happened? What was most meaningful?”), optional photo upload.  
- Submit triggers:  
  - Confirmation screen + thank-you email.  
  - Admin notification.  

---

## Resource Library
- Tips for hosting gatherings.  
- Sample invitations.  
- Example event ideas (block clean-up, potluck, story circle).  
- Budget template.  

---

## Copy Suggestions
- Application: *“Don’t overthink it — simple ideas are welcome!”*  
- Reflection: *“Even a short note helps future neighbors imagine their own gatherings.”*  
- Admin: *“These tools are here to make it easy for you to support connection.”*  
- Success/thank-you: include encouragement to keep connecting.  

---

## Design Guidance
- **CTA Buttons**: Contrasting colors (blue for support, orange for donate).  
- **Forms**: Progress bars, plainspoken language.  
- **Icons**: Party popper, handshake, coffee cup.  
- **Photos**: Real neighborhood gatherings.  
- **Accessibility**: Mobile-first, high contrast, large touch targets.  

---

## Automated Emails
Email automations are sent for:  
1. **Application Received** – recap submission.  
2. **Grant Decision** – approval or decline with warm copy.  
3. **Reminders** –  
   - 1 week before event,  
   - 1 day before event,  
   - 1 day after event (prompt to submit reflection).  
4. **Reflection Confirmation** – thank-you with encouragement to keep building.  

---

## Example User Stories
- *As a parent, I want $50 for snacks and art supplies to host a sidewalk playdate that sparks conversations about reclaiming the park.*  
- *As a renter, I want to host tea for my apartment neighbors to break the ice after years of not knowing each other.*  
- *As a student, I want to co-host an intergenerational storytelling night with an elder in my neighborhood.*  
- *As a steward, I want a dashboard to track applications, approvals, and reflections in one place.*  
