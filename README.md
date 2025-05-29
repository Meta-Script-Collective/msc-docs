# MSC Documentation

ดาวน์โหลดไฟล์ด้วยวิธีหรือขั้นตอนที่ชอบ แนะนำให้ทำโดยการ Clone จาก Git หรือ Github CLI แต่ถ้าหากมี Github Desktop แนะนำให้ Clone โดยใช้ Github Desktop

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
