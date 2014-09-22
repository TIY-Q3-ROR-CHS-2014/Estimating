# User authentication

# Theme

### Resources

- Who is making resources?
- Are they ready yet?

### Bootstrap

# Tech Specifications

## Home page

When someone visits my home (www.twitterclone.come) page,
They should see the marketing link, logo, login, etc.. IE: home page.

- Welcome controller
- Index action
- Template
- 24 hours

## User Authentication

When someone visits my page,
I want the user to be able to register for my website. They need to register before they can view any tweets.

- Devise
  - username instead of email
- 12 hours

## Tweet

As a user,
I want to be able to create a tweet.
Maximum of 145 characters.

- CRUD
- Relationship with the user
  - user has_many tweets
  - tweet belongs_to user  
- Styling
- AJAX form
- 12-16 hours

## Followers/Following

As a user,
I want to be able to follow and/or be followed.

- User
  - followers joins
  - following joins
- Following
  - followers joins
- Following Joins
  - belong to user
  - belong to following
- User experience for following a user should populate the corresponding tables
- 8 hours

# Infinite Tweet Loading

- https://github.com/amatsuda/kaminari/wiki/How-To:-Create-Infinite-Scrolling-with-jQuery
- 4 hours

# Search Functionality

- Styling
- Autocompletion (If you want that 'real-time' mess)

As a user,
I want to be able to search for other users, tweet content

- Custom controller route
  - Search through users
    - Limit it to 10
  - Search through tweet content
    - Limit it to 10
- Click "Search" to redirect
- Style a page to display the users and content that matches
- 12 hours

- 72 hours total
- Assuming we're working 12 hour days
- 6 days total
- With padding - 12 days total
- Clones are OK
- GIT CLONES ARE NOT

