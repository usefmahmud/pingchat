## PingChat

PingChat is a web-based real-time chat application that allows multiple users to communicate through text messages in a simple and reliable way. It supports core chat interactions such as replying to messages and reacting to them, with the system designed to evolve later to handle richer communication like attachments and voice calls.

## MVP Functional Requirements

### Authentication & Profile

- Users can authenticate using a third-party provider (Google)
- Users can choose a **unique username**
- Users can update basic profile information (e.g., avatar)

### User Discovery

- Users can search for other users using an **exact username**

### Messaging

- Users can start a **1-to-1 private chat** with another user
- Users can send and receive **text messages** in real time
- Users can **reply** to specific messages
- Users can **react** to messages

### Presence & Safety

- Users can see another user’s **online / last seen** status
- Users can **block** other users

---

## Future Considerations

These features are intentionally excluded from the MVP but considered in system design decisions:

- Attachments (images, files)
- Voice calls
- Group conversations
