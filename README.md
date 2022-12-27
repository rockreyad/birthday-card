# Happy Birthday Card

A Customizable Web based birthday card to wish your friends and family in a unique way.

If you liked it, please consider giving it star a 🤩⭐.

---

## How to setup

### For Local Building

1. Clone the repository

   ```sh
   git clone https://github.com/rockreyad/birthday-card
   ```

2. Install dependencies

   ```sh
   npm install
   ```

3. Add a pic of the receiver, in the `./local` directory. Ensure that the image is of 1:1 ratio or it might get cropped and squished.

4. Create a `.env` file in root directory, and add the following lines.

   ```env
    NAME='Name of the Receiever'
    PIC='name-of-image.extension'
   ```

5. Execute the following commands in order.

   ```sh
    npm run init-index-local
    npm run build:parcel
   ```

6. Upon Successful execution, your built files will be ready in the `./dist` directory. Open `./dist/index.html` to see the card.

For further customization, checkout [here](./docs/customizations.md).

---

## References

- [Environment Variables](./docs/variables.md)

- [Attributions](./docs/attributions.md)

---

## Support

If you have any queries or need some help in deployment, you may contact me here
