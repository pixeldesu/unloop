# loops-api-v0

Documentation and dumps for https://loops.video API v0

## Table of Contents

* `loops.video/`
  * `api/`
    * `v0/`
      * `client/`
        * `feed/`
          * [`for-you`](/loops.video/api/v0/client/feed/for-you.md)
        * [`onboarding`](/loops.video/api/v0/client/onboarding.md)
      * `comments/`
        * `delete/`
          * [`{{ id }}`](/loops.video/api/v0/comments/delete/{{%20id%20}}.md)
        * `id/`
          * [`{{ id }}`](/loops.video/api/v0/comments/id/{{%20id%20}}.md)
        * [`store`](/loops.video/api/v0/comments/store.md)
      * `follow/`
        * [`{{ id }}`](/loops.video/api/v0/follow/{{%20id%20}}.md)
      * `like/`
        * `video/`
          * [`{{ id }}`](/loops.video/api/v0/like/video/{{%20id%20}}.md)
      * `meta-app/`
        * `feedback/`
          * [`submit`](/loops.video/api/v0/meta-app/feedback/submit.md)
      * `unfollow/`
        * [`{{ id }}`](/loops.video/api/v0/unfollow/{{%20id%20}}.md)
      * `unlike/`
        * `video/`
          * [`{{ id }}`](/loops.video/api/v0/unlike/video/{{%20id%20}}.md)
      * `upload/`
        * [`video`](/loops.video/api/v0/upload/video.md)
      * `user/`
        * `id/`
          * [`{{ id }}`](/loops.video/api/v0/user/id/{{%20id%20}}.md)
        * [`self(/)`](/loops.video/api/v0/user/self.md)
          * [`update-bio`](/loops.video/api/v0/user/self/update-bio.md)
          * [`update-password`](/loops.video/api/v0/user/self/update-password.md)
        * `videos/`
          * [`{{ id }}`](/loops.video/api/v0/user/videos/{{%20id%20}}.md)
  * `auth/`
    * [`start`](/loops.video/auth/start.md)

## Contributing

Pull Requests and Issues are welcome!

Some things to look out for:
* Please follow the existing folder structure if you add a new endpoint documentation
* You can use the `.template/path.md` example file as a base for new endpoints
* Please remove any sensitive information from the requests and responses, like your bearer token, email or password.

## License

The Unlicense