# Example: Edit + Off/On Shelf
User: 把这条改价到99，然后下架再重新上架

Expected flow:
1. Open edit page via `publish?itemId=<ID>`
2. Update price and publish
3. Off-shelf from list
4. Relist via list button or edit-page publish fallback
