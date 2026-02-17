# GitHub Pages Deployment Checklist

## ✅ After Your Site Goes Live

### 1. Test the URL (2 minutes)
Visit: https://lauranormie.github.io/home-ed-directory/

Check:
- [ ] Page loads correctly
- [ ] Search function works
- [ ] All tabs switch properly
- [ ] Mobile view looks good (test on phone)
- [ ] No broken links

### 2. Update Documentation (5 minutes)

Add your live URL to:
- README.md (replace `[YOUR URL]` placeholders)
- DISTRIBUTION.md (update Facebook post template)
- QUICK-START.md (update examples)

### 3. Add Custom Domain (Optional - 10 minutes)

If you want something like `mayohomeed.ie`:

**Option A: Buy domain from GitHub**
- Settings → Pages → Custom domain
- Click "Buy a domain"
- ~€12/year

**Option B: Use existing domain**
- Settings → Pages → Custom domain
- Enter your domain
- Add CNAME record at your domain provider

### 4. Set Up Analytics (5 minutes)

Add Google Analytics to track visitors:

1. Go to https://analytics.google.com
2. Create account → Create property
3. Get tracking ID (G-XXXXXXXXXX)
4. Edit `index.html`:

```html
<!-- Add before </head> tag -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

5. Commit and push:
```bash
cd ~/projects/home-ed-directory
git add index.html
git commit -m "Add Google Analytics"
git push
```

### 5. First Social Media Post (10 minutes)

**Copy this post for Facebook groups:**

```
📚 Free Mayo & Connacht Home Ed Directory! 📚

I've created a free searchable directory of 150+ home ed activities,
support groups, and resources across Mayo, Galway, Sligo, Roscommon & Leitrim.

Includes:
✅ Museum & heritage sites
✅ Nature activities & forest schools
✅ Indoor play centres
✅ Home ed meetups
✅ Support groups & contacts
✅ FREE activities
✅ Mobile-friendly search

Check it out: https://lauranormie.github.io/home-ed-directory/

Found it useful? Please share with other home ed families!

Know of activities I've missed? Let me know and I'll add them.
```

**Post to:**
- Mayo Sligo Home Educators: facebook.com/groups/381383792030224
- Mayo Home Educators: facebook.com/groups/1724660887809542
- Galway Home Ed (Under 8s): facebook.com/groups/132100874262478

### 6. Email HEN Contacts (5 minutes)

**To:** sarahmc92@hotmail.com (Sarah Mc Loughlin - Connemara)
**CC:** anna_sergeenko@yahoo.com (Anna - Sligo)

**Subject:** Free Home Ed Directory for Mayo & Connacht

```
Hi Sarah and Anna,

I've created a free searchable directory of home education resources
for Mayo and the wider Connacht region:

https://lauranormie.github.io/home-ed-directory/

It includes 150+ activities, meetups, support groups, and venues -
all in one searchable, mobile-friendly site.

As HEN local contacts, I thought you might find this useful to share
with families who reach out to you.

The directory covers:
- Mayo, Galway, Sligo, Roscommon & Leitrim
- Museums, nature centers, indoor activities
- Home ed meetups and support groups
- Free activities highlighted
- Mobile-friendly with search

I'd love your feedback! If you know of resources I've missed, please
let me know and I'll add them.

Would you be willing to share this with your local home ed networks?

Thanks,
Laura
laura@supernormal.com
```

---

## 🔄 How to Update Your Site

Whenever you make changes:

```bash
cd ~/projects/home-ed-directory

# Make your edits to index.html or other files

git add .
git commit -m "Describe your changes"
git push

# GitHub Pages will auto-deploy in 1-2 minutes
```

---

## 📊 Success Metrics - Week 1

Track in Google Analytics:
- Target: 500+ visitors
- 50+ email signups (once you add the form)
- 5+ testimonials/positive comments
- Shares in Facebook groups

---

## 🆘 Troubleshooting

**Site not loading?**
- Wait 2-3 minutes after enabling Pages
- Check Settings → Pages for "Your site is live" message
- Clear browser cache

**Changes not showing?**
- GitHub Pages can take 1-2 minutes to rebuild
- Hard refresh: Cmd+Shift+R (Mac) or Ctrl+Shift+R (Windows)

**404 error?**
- Make sure file is named `index.html` (not `Index.html`)
- Check main branch is selected in Pages settings

---

## 🎯 Next Steps (This Week)

Follow QUICK-START.md for your first 7 days:

**Day 1 (Today):**
- [x] Deploy to GitHub Pages ✅
- [ ] Post in Mayo Sligo Home Educators group
- [ ] Email Sarah & Anna

**Day 2:**
- [ ] Add Google Analytics
- [ ] Post in remaining FB groups
- [ ] Create Facebook page

**Day 3-7:**
- [ ] Respond to feedback
- [ ] Email 5 venues about their listings
- [ ] Plan first newsletter

---

Good luck with the launch! 🚀
