# MSC Documentation

<<<<<<< HEAD
<!-- ดาวน์โหลดไฟล์ด้วยวิธีหรือขั้นตอนที่ชอบ แนะนำให้ทำโดยการ Clone จาก Git หรือ Github CLI แต่ถ้าหากมี Github Desktop แนะนำให้ Clone โดยใช้ Github Desktop
ให้ Clone จาก Branch **999s** เท่านั้น -->
=======
ดาวน์โหลดไฟล์ด้วยวิธีหรือขั้นตอนที่ชอบ แนะนำให้ทำโดยการ Clone จาก Git หรือ Github CLI แต่ถ้าหากมี Github Desktop แนะนำให้ Clone โดยใช้ Github Desktop
ให้ Clone จาก Branch **999s** เท่านั้น
>>>>>>> cb3c72bd510283936c54106477b60b9e50a0c97d

### Development

ดาวน์โหลด [Mintlify CLI](https://www.npmjs.com/package/mintlify) โดยใช้คำสั่งข้างล่าง

```
npm i -g mintlify
```

ให้ทำการ `cd` ไปที่ Project Path แล้วทำการรันคำสั่งข้างล่างนี้

```
mintlify dev
```

### Publishing Changes

เมื่อต้องการเปลี่ยนแปลงข้อมูลให้ทำการ Push, Pull Request

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `docs.json`
