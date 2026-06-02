# Kemah Storage Units Website

A professional storage unit rental website with admin panel for **Kemah Storage Units** located at **1250 Winfield Ln, Kemah, Texas**.

## Features

### Public Website (index.html)
- ✅ Professional branding and layout
- ✅ 11 storage units displayed (Units 1-10 are 50x40 ft, Unit 11 is 150x40 ft)
- ✅ Each unit has a 30-40 ft container
- ✅ Privacy fence and access code mentioned for each unit
- ✅ Responsive design (mobile-friendly)
- ✅ Contact information section
- ✅ Admin panel access link

### Admin Panel (admin.html)
- 🔐 Password-protected login
- 📊 Dashboard with statistics
- 🏢 Manage storage units (view all units)
- ✏️ Edit unit details (name, size, container size, features, status)
- 💰 Set and update pricing per unit
- 📸 Upload and manage unit photos
- ⚙️ Admin settings (password management)

## Storage Unit Details

### Standard Units (1-10)
- **Size:** 50 x 40 ft
- **Container:** 30-40 ft
- **Features:** Private Fence, Access Code, Ground Level, Easy Loading
- **Status:** Available

### Premium Unit (11)
- **Size:** 150 x 40 ft
- **Container:** 30-40 ft
- **Features:** Private Fence, Access Code, Extra Large, Premium Space
- **Status:** Available

## How to Use

### For Customers
1. Open `index.html` in your web browser
2. Browse available storage units
3. View unit specifications and features
4. Contact via the provided information

### For Admin

#### First Login
1. Click "Admin Panel" button on the website
2. Enter the default password: **admin123** (You can change this in admin.html)

#### Managing Units
1. **Dashboard:** View overview statistics
2. **Manage Units:** See all units in a table view
3. **Edit Unit:** 
   - Select a unit
   - Modify name, size, features, or status
4. **Pricing & Photos:**
   - Set monthly rental prices
   - Upload unit photos (stored as base64 in browser storage)
5. **Settings:** Change admin password

## Technical Details

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Storage:** Browser LocalStorage (no server required)
- **Authentication:** Simple password protection
- **Data:** Stored locally in browser - persists across sessions

## Installation

1. Save both `index.html` and `admin.html` files
2. Open `index.html` in a web browser
3. Click "Admin Panel" to access admin features

## File Structure
```
storage-units-website/
├── index.html          (Public website)
├── admin.html          (Admin panel)
└── README.md          (This file)
```

## Security Notes

⚠️ **Important:** This is a client-side application using browser storage. For production use:
- Implement server-side authentication
- Use a proper database (MySQL, PostgreSQL, MongoDB, etc.)
- Use HTTPS for data transmission
- Implement proper access controls
- Add user authentication and session management

## Default Admin Credentials

- **Username:** Not required (password only)
- **Password:** `admin123`

To change: Edit line in admin.html where it says `const DEFAULT_PASSWORD = "admin123";`

## Features Not Yet Implemented

- Online booking system
- Payment processing
- Email notifications
- Multi-admin accounts
- Server-side data persistence

## Support

For issues or questions about the website, contact the administrator.

---

**Location:** 1250 Winfield Ln, Kemah, TX  
**Website Updated:** 2024