# Porcha Design website prototype

Local, static HTML prototype in the spirit of katieharbison.co: quiet type, full-bleed photography, short navigation. It uses Porcha's own words and Squarespace image URLs.

This folder does not touch the live site. [porchadesign.com](https://www.porchadesign.com) stays as it is.

## Open it

From this folder:

```bash
cd /workspace/porcha-website/prototype
python -m http.server 8765
```

Then open http://127.0.0.1:8765/ (or the box desktop browser). Opening `index.html` as a file also works. A local server is better if you add anything later that cares about paths.

## Pages

| File | What it is |
|------|------------|
| `index.html` | Home |
| `projects.html` | Project index |
| `projects/kenilworth-square.html` | Kenilworth |
| `projects/coastal-treetop-house.html` | Coastal Treetop House |
| `projects/the-georgian-pavilion.html` | The Georgian Pavilion |
| `studio.html` | About Sorcha, how she works, full-service design (the Dublin services page) |
| `contact.html` | Enquiry |
| `power-hour.html` | Interiors Power Hour, €300 / 60 minutes |
| `press.html` | Press |
| `css/styles.css` | Shared styles |
| `js/site.js` | Menu open and close |

Navigation is Projects, Studio and Contact, with a menu that also holds Instagram, Power Hour and Press. Instagram is in the menu, the footer of every page, and as a follow link on Studio and Contact. Booking goes to https://calendly.com/sorcha-porchadesign/60 with no month parameter.

Images are hotlinked from `images.squarespace-cdn.com`. They need a network connection.

Pages send `noindex` so this prototype is not a second public site if it is ever uploaded by mistake.

## Language

Irish English. No em dashes in the prototype copy.
