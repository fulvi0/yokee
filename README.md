# Yokee

**Youtube playlist keeper**

The best way to **keep**, **stream** and **share** the music that you *love* from playlist of youtube.

Power by [PerkHand](http://perkhand.com)

___

**Setup connection with bucket on AWS S3**

```ruby
class Application < Rails::Applicatio
    AWS::S3::Base.establish_connection!(
        :access_key_id     => 'access key',
        :secret_access_key => 'secret key'
        )

    BUCKET = 'music-storage'
end
```
