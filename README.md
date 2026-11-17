# FAHASA Layout Studio — User Guide

This guide explains how to use the **FAHASA Layout Studio**, the tool for planning the FAHASA Heritage Passage bookstore (Nguyễn Huệ Walking Street).

With it you can:

- Arrange shelves, tables, counters and other items on each floor.
- Choose what each shelf or table displays (books, coffee, tea, ceramics…).
- Change floors, the building size and colours.
- Write the points of interest (hotspots) shown to visitors.
- Present the store in 3D, with a guided customer journey.

---

## Contents

1. [Before you start](#1-before-you-start)
2. [The screen at a glance](#2-the-screen-at-a-glance)
3. [Working with items](#3-working-with-items)
4. [Floors and building](#4-floors-and-building)
5. [Hotspots and the customer journey](#5-hotspots-and-the-customer-journey)
6. [Colours](#6-colours)
7. [Presenting to clients](#7-presenting-to-clients)
8. [Saving, sharing and images](#8-saving-sharing-and-images)
9. [Keyboard shortcuts](#9-keyboard-shortcuts)
10. [Problems and solutions](#10-problems-and-solutions)
11. [Item library reference](#11-item-library-reference)

---

## 1. Before you start

### What you need

- A computer with **Google Chrome** or **Microsoft Edge**.
- An **internet connection**. The 3D engine loads from the internet each time you open the file.
- The file `fahasa-layout-studio.html`.

### How to open the studio

1. Double-click `fahasa-layout-studio.html`.
2. It opens in your browser. Wait for "Loading layout studio…" to disappear.
3. The first time, you see the original FAHASA layout: 3 floors, all items and 18 hotspots.

> **Tip:** Use the same browser on the same computer each time. Your work auto-saves there (see [Section 8](#8-saving-sharing-and-images)).

---

## 2. The screen at a glance

| Area | Where | What it does |
|---|---|---|
| **Top bar** | Top | Project name, Edit / Present switch, Undo, Redo, Import, Export, Reset, save status |
| **Left panel** | Left | Four tabs: **Library** (add items), **Floors** (building and floors), **Hotspots**, **Colours** |
| **Plan** | Centre-left | Top-down drawing of the current floor. This is where you arrange items. |
| **3D view** | Centre-right | Live 3D model. It updates as you edit. |
| **Right panel** | Right | Settings of whatever you selected |

### Reading the plan

- **The street is at the bottom** of the plan, marked "FRONT · STREET SIDE".
- The grid has a faint line every **1 metre** and a stronger line every **5 metres**.
- Each item has one **bold edge**: that is its **front**, the side customers face.
- The floor below is shown faded, so you can line things up between floors. Untick **Floor below** to hide it.

### Plan / Split / 3D

Use the **Plan · Split · 3D** buttons to choose your view:

- **Plan**: only the plan, best for precise layout work.
- **Split**: plan and 3D side by side (default).
- **3D**: only the 3D view, best for checking the look.

### Moving around

| To… | On the plan | In 3D |
|---|---|---|
| Zoom | Mouse wheel | Mouse wheel |
| Move the view | Right-click and drag, or hold **Space** and drag | Right-click and drag |
| Turn the view | — | Left-click and drag |
| Fit the whole building | **Fit** button or **F** key | **Focus floor** button |

### Switching floors

Click a floor name above the plan: **Tầng Trệt** (ground), **Tầng Lửng** (mezzanine) or **Lầu 1** (first floor). You can also press **Page Up / Page Down**.

You always edit **one floor at a time**. New items go on the floor you are viewing.

---

## 3. Working with items

### Add an item

1. Open the **Library** tab on the left.
2. Do one of the following:
   - **Click** an item: it appears in the middle of the plan.
   - **Drag** an item onto the plan: it appears where you drop it.
3. Move it into place (see below).

### Select an item

- **Click** it on the plan, **or**
- **Click** it in the 3D view.

The selected item turns orange and its settings appear in the right panel.

Selecting several items:

- **Shift + click** adds or removes items from the selection.
- **Drag on an empty area** of the floor draws a box and selects everything inside it.
- **Ctrl + A** selects all items on the floor.

### Move an item

- **Drag** it on the plan, **or**
- Press the **arrow keys** for small steps (hold **Shift** for 10× bigger steps), **or**
- Type exact values in the right panel: **x** (left–right) and **z** (front–back).

> **Snap:** Items move in steps (10 cm by default) so they line up neatly. Change the step size next to **Snap**, untick **Snap** to turn it off, or hold **Alt** while dragging to ignore snap once.

### Rotate an item

- Drag the **round handle** on the selected item (15° steps; hold **Shift** for 1° steps), **or**
- Press **R** (+15°) or **Shift + R** (−15°), **or**
- Use the **⟲ 90° / −15° / +15° / ⟳ 90°** buttons in the right panel, **or**
- Type the angle in **Rotation °**.

### Resize an item

- Drag a **white square** on the edge or corner of the selected item. The opposite side stays in place.
- Or type **Width**, **Depth** and **Height** in the right panel.

Some items only change in certain ways. For example, round tables keep their round shape, and paintings only change width.

### Change what an item displays (merchandise)

1. Select a shelf, gondola, table, plinth, counter or cabinet.
2. In the right panel, under **Settings**:
   - **Merchandise**: books, gourmet mix, Robusta coffee, Shan Tuyết tea, Bát Tràng ceramics, Mỹ Xuyên lacquerware, nón lá, stationery, postcards, and more.
   - **Fill level**: how full the item looks (slide left for more empty space).
   - **Accent goods** (wall shelving only): adds coffee, tea, ceramics etc. between the books every ~3 m.
   - **Item spacing**: distance between products (0 = automatic).

> To change the merchandise of many items at once, select them all. The right panel then shows one **Merchandise** setting that applies to every selected item.

### Name an item

Type in **Name on plan** (right panel), for example "Gourmet gondola". The name shows on the plan so the team knows what each item is.

### Change the colour of one item

1. Select the item.
2. Under **Colour override**, click the colour box and pick a colour.
3. To go back, click **Store colour**.

### Duplicate, copy and paste

- **Duplicate**: **Ctrl + D**, or the **Duplicate** button. The copy appears slightly offset.
- **Copy and paste**: **Ctrl + C**, then **Ctrl + V**.
- **Copy to another floor**: select the items, press **Ctrl + C**, switch floor, press **Ctrl + V**. They are pasted at exactly the same position.

### Move items to another floor

Select the items, then choose the floor in **Move to floor** (right panel).

### Line items up

Select two or more items. The right panel then shows:

- **Align left / Centre / Align right**
- **Align rear / Middle / Align front**
- **Space evenly ↔ / ↕** (needs three or more items)

### Delete an item

Select it and press **Delete**, or click **Delete** in the right panel.

### Undo a mistake

- **Undo**: **Ctrl + Z**, or the **↶ Undo** button.
- **Redo**: **Ctrl + Y**, or the **↷ Redo** button.

The studio remembers your last 150 changes.

### See an item in 3D

**Double-click** it on the plan, or click **Show in 3D** in the right panel. The 3D camera flies to it.

---

## 4. Floors and building

Open the **Floors** tab on the left.

### Project title and subtitle

- **Title**: shown in the top bar and in Present mode. Use " · " to split it over two lines in Present mode.
- **Subtitle**: shown under the title in Present mode. Write **{size}** where you want the building size to appear (for example "37.5 m × 25 m").

### Building size and entrance

| Setting | Meaning |
|---|---|
| **Street frontage** | Width of the building along Nguyễn Huệ (metres) |
| **Depth** | Distance from the street facade to the back wall (metres) |
| **Entrance centre x** | Where the entrance door is (0 = middle of the facade) |
| **Entrance width** | Width of the door opening |
| **Show street, trees and neighbours** | Turns the surroundings on or off |

> **Important:** Changing the building size does **not** move the items. Check the items near the walls afterwards.

### Floor settings

Each floor has a card with:

| Setting | Meaning |
|---|---|
| **Name / English name** | For example "Lầu 1" / "First Floor" |
| **3D label** | The short text shown next to the floor in 3D |
| **Floor level** | Height of the floor surface above the street (metres) |
| **Ceiling height** | Height from this floor to its ceiling |
| **Slab** | Thickness of the floor slab |
| **Floor colour** | Colour of the floor |
| **Covers the whole footprint** | Ticked = a full floor. Unticked = a partial floor (like the mezzanine), with its own position and size. |
| **Street facade** | Glass with entrance, glass only, or none |
| **Side and rear walls** | Show or hide the outer walls |
| **Mullion spacing** | Distance between the metal frames of the glass facade |

### Add or remove a floor

- **+ Floor above**: adds a full floor on top of the building.
- **+ Mezzanine**: adds a partial floor. Set its position and size on its card.
- **Delete floor**: removes the floor with all its items and hotspots. You can still undo this.

### Stairs between floors

To connect two floors:

1. On the **lower** floor, add a **Stair flight** (Library › Building).
2. Set its **Height** to the height it must climb. The stair rises in the direction of the arrow on the plan.
3. On the **upper** floor, add a **Floor opening** at the same place. It cuts a hole in the slab so the stair can pass through.
4. Add **Glass railings** around the opening if needed.

---

## 5. Hotspots and the customer journey

Hotspots are the **numbered markers** that visitors click in Present mode to read about an area. The numbers also set the order of the **customer journey** (the automatic tour).

### Add a hotspot

1. Go to the floor where you want it.
2. Open the **Hotspots** tab and click **+ Add hotspot on this floor**.
3. Drag the numbered circle on the plan to the right spot.

### Edit a hotspot

Click a hotspot (in the Hotspots list, on the plan, or in 3D). The right panel shows:

| Field | What to write |
|---|---|
| **Title** | Name of the area, for example "Analog Music Corner" |
| **Vietnamese subtitle** | For example "Góc nghe đĩa than" |
| **Description** | One or two sentences about what visitors find there |
| **List items** | One item per line, for example "Trịnh Công Sơn songs" |
| **Floor** | The floor the hotspot belongs to |
| **x / z / Marker height** | Exact position and height of the marker |
| **Show all floors when opened** | Ticked = all floors stay visible when this hotspot opens |
| **Include in the customer journey** | Unticked = the tour skips this hotspot |

> **Text changes apply when you leave the field.** Press **Enter** or click elsewhere.

### Set what the camera shows

By default, the camera chooses a view automatically. To choose it yourself:

1. Move the 3D view until it shows the area the way you want.
2. Click **Save current 3D view**.
3. Click **Preview** to check.
4. Click **Use automatic** to go back to the automatic view.

### Change the order of the journey

Use **▲ / ▼** in the Hotspots list, or **▲ Earlier / ▼ Later** in the right panel.

---

## 6. Colours

Open the **Colours** tab to change colours for the **whole store**. This covers dark and light wood, walls, glass tint, fabrics, lacquer, gold, plants, and LED light colour.

- Click a colour box to change it.
- Click **↺** next to a colour to return it to the default.
- Click **Reset all colours** to return everything to the defaults.

To change **one item only**, use **Colour override** on that item instead (see [Section 3](#3-working-with-items)).

---

## 7. Presenting to clients

Click **Present** in the top bar. The editing tools disappear and the 3D view fills the screen.

| Control | What it does |
|---|---|
| **Camera** | Jump to Overview, Street view, or a single floor |
| **Show floors** | Show or hide each floor |
| **Walls** | Solid, Cutaway (see-through) or Hidden |
| **Lighting** | Switch between day and evening (warm 3000K lighting) |
| **▶ Walk the customer journey** | Automatic tour of all hotspots, 6 seconds per stop |
| **Points of interest** | Click any hotspot to open it |

To go back to editing, click **← Back to editing**, or press **Esc** (press it twice if a hotspot panel is open).

> **Before a client meeting:** open Present mode, run the journey once, and check that each camera view shows the right area.

---

## 8. Saving, sharing and images

### Auto-save

Every change is saved automatically **in this browser on this computer**. The top bar shows "Auto-saved in this browser" with the time.

> **Auto-save is not a backup.** Clearing the browser history, using a private window, or switching computer or browser loses it. Use **Export** regularly.

### Export (keep a copy or share)

Click **Export**. A file is downloaded, for example `fahasa-heritage-passage-sai-gon-cultural-hub-2026-11-17.json`.

Use this file to:

- Keep a backup.
- Send the layout to a colleague.
- Continue on another computer.

### Import (open a saved layout)

Click **Import** and choose a `.json` file exported from the studio. It replaces the current layout. **Undo** brings the previous one back.

### Reset to the original layout

Click **Reset** to return to the original FAHASA layout. **Export** first if you want to keep your current work; **Undo** also brings it back.

### Save images

- **PNG** button above the plan: downloads the plan of the current floor.
- **PNG** button in the 3D view: downloads the current 3D view. Hotspot markers and floor labels are not included.

---

## 9. Keyboard shortcuts

Shortcuts work in Edit mode when you are not typing in a field.

| Keys | Action |
|---|---|
| **Ctrl + Z** | Undo |
| **Ctrl + Y** or **Ctrl + Shift + Z** | Redo |
| **Ctrl + D** | Duplicate |
| **Ctrl + C / Ctrl + V** | Copy / paste (also between floors) |
| **Ctrl + A** | Select all items on this floor |
| **Delete** or **Backspace** | Delete the selection |
| **Arrow keys** | Move the selection (Shift = 10× bigger steps) |
| **R / Shift + R** | Rotate +15° / −15° |
| **F** | Fit the plan to the screen |
| **Page Up / Page Down** | Go to the floor above / below |
| **Esc** | Clear the selection |
| **Space + drag** | Move the plan view |
| **Shift + click** | Add or remove an item from the selection |
| **Alt + drag** | Move or resize without snapping |
| **Double-click** an item | Show it in 3D |

On a Mac, use **Cmd** instead of **Ctrl**.

---

## 10. Problems and solutions

| Problem | Solution |
|---|---|
| **The screen stays on "Loading…" or is blank** | Check the internet connection. Use Chrome or Edge. Press **F12** and look at the Console tab for errors; the file may be incomplete. |
| **My work is gone** | Auto-save only works in the same browser on the same computer, and not in private windows. Open your last **Exported** file with **Import**. |
| **I can't click an item** | Check you are on the right floor. Floor finish zones are selected by clicking their **edge**. |
| **I can't see an upper floor in 3D** | Set the 3D view menu to **All floors**, or switch to that floor. |
| **A stair goes through the ceiling** | Add a **Floor opening** on the floor above (see [Stairs between floors](#stairs-between-floors)). |
| **My typed change did nothing** | Press **Enter** or click outside the field. Changes apply when you leave the field. |
| **Items moved in big jumps** | Snap is on. Choose a smaller step next to **Snap**, or hold **Alt** while dragging. |
| **The studio is slow** | Switch to **Plan** view while arranging, hide floors you don't need, and close other browser tabs. |
| **Hotspot numbers changed** | Numbers follow the order in the Hotspots list. Use ▲ / ▼ to reorder. |

---

## 11. Item library reference

| Group | Items | Typical use |
|---|---|---|
| **Shelving** | Wall shelving (books, gourmet & tea, craft & art), curved low shelf, gondolas, glass cabinets, stationery cabinet | Main book and product display |
| **Display** | Culture island, round photo-book table, display tables (incl. window tables with nón lá tier), plinth, glass display case, postcard spinner | Feature displays and souvenirs |
| **Service** | Cashier counter, café bar, gift-wrap station, back bar with jar shelves, listening counter (vinyl), stamp station | Checkout, café, activities |
| **Seating** | Café tables (2 or 4 seats), chair rows, window seats, workshop table and stools, bench, floor cushions | Reading, café, events, workshops |
| **Feature** | Check-in arch (nón lá vault), event stage, vintage mailbox, planter, facade sign | Photo spots and signature elements |
| **Wall art** | Painting, lacquer panel, heritage photo wall | Wall decoration |
| **Lighting** | Pendant lamps, interior light (3000K) | Atmosphere, mostly visible in evening mode |
| **Building** | Wall / partition, glass railing, stair flight, room, lift, floor opening, floor finish zone, custom block | Structure and back-of-house |

> **Facade sign:** select it and change the text under **Settings › Sign text**.
>
> **Interior light:** invisible in 3D. It lights its area, mainly in evening mode. Adjust **Brightness** and **Reach**.
