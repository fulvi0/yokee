# Yokee

**Youtube playlist keeper**

The best way to **keep**, **stream** and **share** the music that you *love* from playlist of youtube.

___

**Setup connection with bucket on AWS S3**

```ruby
class Application < Rails::Applicatio
  s3 = AWS::S3.new(
      :access_key_id     => 'access key',
      :secret_access_key => 'secret key'
      )

  BUCKET = 'music-storage'
end
```
___

Power by [PerkHand](http://perkhand.com)
