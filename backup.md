# Types of Backup: Full, Incremental and Differential Backup

Data loss always sneaks up on you.

One successful breach is all it takes for businesses to lose their fortunes. A recent study found that 29% of businesses that face a data breach end up losing revenue. Among those businesses, 38% experienced a revenue loss of 20% or more.

That’s why businesses back up critical data in order to have a fail-safe, so as to restore systems should a data loss incident occur. Assessing which type of backup fits certain business needs is a smart move, especially since data lives in more places now than ever before.

## Types of Backups

There are three main backup types used to back up all digital assets:

- **Full backup:** The most basic and comprehensive backup method, where all data is sent to another location.
- **Incremental backup:** Backs up all files that have changed since the last backup occurred.
- **Differential backup:** Backs up only copies of all files that have changed since the last full backup.

Not all IT organizations can support all backup types since network capability may vary from organization to organization. Choosing the right backup method requires a tactical approach — one that can help organizations get the best level of data protection without demanding too much from the network. However, before determining which backup method best suits the needs of your business, you need to understand the ins and outs of the three main backup types mentioned above.

## Full Backup

A full backup involves the creation of a complete copy of an organization’s files, folders, SaaS data, and hard drives. Essentially, all the data is backed up into a single version and moved to a storage device. It’s the perfect protection against data loss when you factor in recovery speed and simplicity. However, the time and expense required to copy all the data (all the time) may make it an undesirable option for many IT professionals.

### How does full backup work?

Let’s say you have to back up photos from Monday to Friday.

- Monday: You perform a full backup for 100 photos. You get an image file of 100 photos.
- Tuesday: You add another 100 photos and perform a full backup. You get an image file of 200 photos.
- Wednesday: You delete 100 photos and then perform a full backup. You get an image file of 100 photos.
- Thursday: You make no changes to your photos and perform a full backup. You get an image file of 100 photos.
- Friday: You add 200 photos and perform a full backup. You get an image file of 300 photos.

You get five backup files containing 800 photos. Should a data loss incident occur and you need to recover all the photos, simply restore the last version to get all 800 photos.

### Full Backup: Pros and Cons

Here are the advantages and disadvantages of running a full backup method:

#### Pros
- Quick restore time
- Storage management is easy since all the data is stored on a single version
- Easy version control allows you to maintain and restore different versions without breaking a sweat
- File search is easy as it gets

#### Cons
- Demands the most storage space comparatively
- Depending on their size, it takes a long time to back up files
- The need for additional storage space makes it the most expensive backup method
- The risk of data loss is high since all the data is stored in one place

### When should you use full backup?

Small businesses that deal consistently with a small amount of data may find full backup a good fit since it won’t eat up their storage space or take too much time to back up.

## Incremental Backup

Incremental backup involves backing up all the files, folders, SaaS data, and hard drives that have changed since the last backup activity. This could be the most recent full backup in the chain or the last incremental backup. Only the recent changes (increments) are backed up, consuming less storage space and resulting in a speedy backup. However, the recovery time is longer since more backup files will need to be accessed.

### How does incremental backup work?

Let’s say you have to back up photos from Monday to Thursday.

- Monday: You add 100 photos and perform a full backup. You get an image file of 100 photos.
- Tuesday: You add another 100 photos (now you have 200 photos) and perform an incremental backup. You get an image file of 100 photos.
- Wednesday: You make no changes and perform an incremental backup. You get an empty image file.
- Thursday: You delete 100 photos and edit the other 100 photos there and perform an incremental backup. You get an image file of only the edited 100 photos.

You get three image files containing 300 photos in total. In case you need to recover all the photos, restore all the image files since the last full backup, including the last full backup and the later incremental backups, to get your 200 photos (including the deleted 100 photos).

### Incremental Backup: Pros and Cons

Here are the advantages and disadvantages of running an incremental backup method:

#### Pros
- Efficient use of storage space since files are not duplicated in their entirety
- Lightning-fast backups
- Can be run as often as desired, with each increment being an individual recovery point

#### Cons
- Time-consuming restoration since data must be pieced together from multiple backups
- Successful recovery is only possible if all the backup files are damage-proof
- File search is cumbersome – you need to scout more than one backup set to restore a specific file

### When should you use incremental backup?

Businesses that deal with large volumes of data and cannot dedicate time to the backup process will find incremental backup methods effective since they take up less storage space and encourage fast backups.

## Differential Backup

Differential backup falls between full backup and incremental backup. It involves backing up files, folders, and hard drives that were created or changed since the last full backup (compared to just the changes since the last incremental backup). Only a small volume of data is backed up between the time interval of the last backup and the current one, consuming less storage space and requiring less time and investment.

### How does differential backup work?

Let’s say you have to back up photos from Monday to Thursday.

- Monday: You have 200 photos and perform a full backup. You get an image file of 200 photos.
- Tuesday: You add another 200 photos (a total of 400 photos) and perform a differential backup. You get an image file of the newly added 200 photos.
- Wednesday: You make no changes and perform a differential backup on the existing 400 photos. You get an image file of the newly added 200 photos on Tuesday.
- Thursday: You delete 100 photos and edit another 100 photos (total of 300 photos) and perform a differential backup. You get image files of 100 photos, 200 photos, and 300 photos.

Recovering 100 photos: Both deletion and editing happen to the added 200 photos. The differential backup will back up the edited 100 photos.

Recovering 200 photos: If you delete 100 photos from the added photos and edit 100 photos from the original photos, the differential backup will back up the edited 100 photos and the 100 added photos (left after deletion).

Recovering 300 photos: In the case of recovering 300 photos, the differential backup will include the edited 100 photos and the added 200 photos.

### Differential Backup: Pros and Cons

#### Pros:
- Takes less space than full backups.
- Faster restoration than incremental backups.
- Much faster backups than full backups.

#### Cons:
- Potential for failed recovery if any of the backup sets are incomplete.
- Compared to incremental backups, the backup takes longer and requires more storage space.
- Compared to full backups, restoration is slow and complex.

#### When should you use differential backup?
Small and medium-sized organizations that want to process large volumes of valuable data but cannot perform constant backups will find the differential backup method useful.
