# twitter_data_servers
# 推特大数据推送
twitter数据采集推特数据采集
twitter数据服务解决风控限制，次数限制， 账号管理问题, 可提供日数据2亿推送 
#### 服务地址 联系 飞机 https://t.me/dada123api   
##### 一、  twitter搜索 列表 （可采全）

* Post:/twitter_api/search

| 名称  | 类型   | 含义                                   |
| ----- | ------ | -------------------------------------- |
| q   | String | 搜索内容,eg:lang:zh,北京         |

| token | String | 用户标识                               |
* 返回：

```json
```

##### 二、twitter用户列表（可采全）

* Post:/twitter_api/user_timeline

| 名称  | 类型   | 含义                                   |
| ----- | ------ | -------------------------------------- |
| id   | String | 用户标识,eg:1454736746621521928         |
| max_id  | String    | 从0起 ，获取最小id |
| token | String | 用户标识                               |
* 返回：

```json
[
    {
        "created_at": "Tue Jul 11 07:07:02 +0000 2023",
        "id": 1678662164708741120,
        "id_str": "1678662164708741120",
        "text": "please tell him in a wise way in a kind way, i won't defend him. he should know his mistakes, if talking and commen… https://t.co/TaR6svq7Ds",
        "truncated": true,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [],
            "urls": [
                {
                    "url": "https://t.co/TaR6svq7Ds",
                    "expanded_url": "https://twitter.com/i/web/status/1678662164708741120",
                    "display_url": "twitter.com/i/web/status/1…",
                    "indices": [
                        117,
                        140
                    ]
                }
            ]
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "is_quote_status": false,
        "retweet_count": 86,
        "favorite_count": 128,
        "conversation_id": 1678662164708741120,
        "conversation_id_str": "1678662164708741120",
        "conversation_control": {
            "policy": "by_invitation",
            "conversation_owner": {
                "screen_name": "LHCMILD"
            }
        },
        "favorited": false,
        "retweeted": false,
        "limited_actions": "limited_replies",
        "lang": "en",
        "supplemental_language": null
    },
    {
        "created_at": "Mon Jul 10 23:00:16 +0000 2023",
        "id": 1678539664276221954,
        "id_str": "1678539664276221954",
        "text": "haechan who is both cute &amp; cool 🫤🥺 https://t.co/3wybppdM4S… https://t.co/3wybppdM4S",
        "truncated": true,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [],
            "urls": [
                {
                    "url": "https://t.co/3wybppdM4S",
                    "expanded_url": "https://twitter.com/i/web/status/1678539664276221954",
                    "display_url": "twitter.com/i/web/status/1…",
                    "indices": [
                        39,
                        62
                    ]
                },
                {
                    "url": "https://t.co/3wybppdM4S",
                    "expanded_url": "https://twitter.com/i/web/status/1678539664276221954",
                    "display_url": "twitter.com/i/web/status/1…",
                    "indices": [
                        64,
                        87
                    ]
                }
            ]
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "is_quote_status": false,
        "retweet_count": 847,
        "favorite_count": 4103,
        "conversation_id": 1678539664276221954,
        "conversation_id_str": "1678539664276221954",
        "conversation_control": {
            "policy": "community",
            "conversation_owner": {
                "screen_name": "LHCMILD"
            }
        },
        "favorited": false,
        "retweeted": false,
        "possibly_sensitive": false,
        "possibly_sensitive_editable": true,
        "limited_actions": "limited_replies",
        "lang": "en",
        "supplemental_language": null
    },
    {
        "created_at": "Mon Jul 10 22:51:38 +0000 2023",
        "id": 1678537494063661058,
        "id_str": "1678537494063661058",
        "text": "RT @HugoGloss: Exclusivo: Fenômeno do K-Pop, @NCTsmtown_DREAM  fala sobre passagem pelo Brasil e responde sobre possível spoiler de novo ál…",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [
                {
                    "screen_name": "HugoGloss",
                    "name": "Hugo Gloss",
                    "id": 15292534,
                    "id_str": "15292534",
                    "indices": [
                        3,
                        13
                    ]
                },
                {
                    "screen_name": "NCTsmtown_DREAM",
                    "name": "NCT DREAM",
                    "id": 870188817537355776,
                    "id_str": "870188817537355776",
                    "indices": [
                        45,
                        61
                    ]
                }
            ],
            "urls": []
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "retweeted_status": {
            "created_at": "Mon Jul 10 21:59:14 +0000 2023",
            "id": 1678524304424665089,
            "id_str": "1678524304424665089",
            "text": "Exclusivo: Fenômeno do K-Pop, @NCTsmtown_DREAM  fala sobre passagem pelo Brasil e responde sobre possível spoiler d… https://t.co/vz7lhNt6eZ",
            "truncated": true,
            "entities": {
                "hashtags": [],
                "symbols": [],
                "user_mentions": [
                    {
                        "screen_name": "NCTsmtown_DREAM",
                        "name": "NCT DREAM",
                        "id": 870188817537355776,
                        "id_str": "870188817537355776",
                        "indices": [
                            30,
                            46
                        ]
                    }
                ],
                "urls": [
                    {
                        "url": "https://t.co/vz7lhNt6eZ",
                        "expanded_url": "https://twitter.com/i/web/status/1678524304424665089",
                        "display_url": "twitter.com/i/web/status/1…",
                        "indices": [
                            117,
                            140
                        ]
                    }
                ]
            },
            "source": "<a href=\"https://mobile.twitter.com\" rel=\"nofollow\">Twitter Web App</a>",
            "in_reply_to_status_id": null,
            "in_reply_to_status_id_str": null,
            "in_reply_to_user_id": null,
            "in_reply_to_user_id_str": null,
            "in_reply_to_screen_name": null,
            "user": {
                "id": 15292534,
                "id_str": "15292534",
                "name": "Hugo Gloss",
                "screen_name": "HugoGloss",
                "location": "Brazil",
                "description": "Brazilian Entertainment Website. In Beyoncé we trust!",
                "url": "https://t.co/KLNu7LZZdC",
                "entities": {
                    "url": {
                        "urls": [
                            {
                                "url": "https://t.co/KLNu7LZZdC",
                                "expanded_url": "https://hugogloss.uol.com.br/",
                                "display_url": "hugogloss.uol.com.br",
                                "indices": [
                                    0,
                                    23
                                ]
                            }
                        ]
                    },
                    "description": {
                        "urls": []
                    }
                },
                "protected": false,
                "followers_count": 5383471,
                "fast_followers_count": 0,
                "normal_followers_count": 5383471,
                "friends_count": 4253,
                "listed_count": 7906,
                "created_at": "Tue Jul 01 22:17:25 +0000 2008",
                "favourites_count": 4458,
                "utc_offset": null,
                "time_zone": null,
                "geo_enabled": true,
                "verified": false,
                "statuses_count": 84557,
                "media_count": 50886,
                "lang": null,
                "contributors_enabled": false,
                "is_translator": false,
                "is_translation_enabled": false,
                "profile_background_color": "1A1B1F",
                "profile_background_image_url": "http://abs.twimg.com/images/themes/theme9/bg.gif",
                "profile_background_image_url_https": "https://abs.twimg.com/images/themes/theme9/bg.gif",
                "profile_background_tile": true,
                "profile_image_url": "http://pbs.twimg.com/profile_images/1253448789924462593/OeG6MbcO_normal.jpg",
                "profile_image_url_https": "https://pbs.twimg.com/profile_images/1253448789924462593/OeG6MbcO_normal.jpg",
                "profile_banner_url": "https://pbs.twimg.com/profile_banners/15292534/1683651747",
                "profile_link_color": "ABB8C2",
                "profile_sidebar_border_color": "FFFFFF",
                "profile_sidebar_fill_color": "252429",
                "profile_text_color": "666666",
                "profile_use_background_image": true,
                "has_extended_profile": true,
                "default_profile": false,
                "default_profile_image": false,
                "pinned_tweet_ids": [
                    1676730535069007875
                ],
                "pinned_tweet_ids_str": [
                    "1676730535069007875"
                ],
                "has_custom_timelines": true,
                "can_media_tag": true,
                "followed_by": false,
                "following": false,
                "follow_request_sent": false,
                "notifications": false,
                "advertiser_account_type": "promotable_user",
                "advertiser_account_service_levels": [],
                "analytics_type": "enabled",
                "business_profile_state": "none",
                "translator_type": "regular",
                "withheld_in_countries": [],
                "require_some_consent": false
            },
            "geo": null,
            "coordinates": null,
            "place": null,
            "contributors": null,
            "is_quote_status": false,
            "retweet_count": 3237,
            "favorite_count": 10382,
            "conversation_id": 1678524304424665089,
            "conversation_id_str": "1678524304424665089",
            "favorited": false,
            "retweeted": false,
            "possibly_sensitive": false,
            "possibly_sensitive_editable": true,
            "lang": "pt",
            "supplemental_language": null,
            "self_thread": {
                "id": 1678524304424665089,
                "id_str": "1678524304424665089"
            }
        },
        "is_quote_status": false,
        "retweet_count": 3237,
        "favorite_count": 0,
        "conversation_id": 1678537494063661058,
        "conversation_id_str": "1678537494063661058",
        "favorited": false,
        "retweeted": false,
        "lang": "pt",
        "supplemental_language": null
    },
    {
        "created_at": "Mon Jul 10 22:51:05 +0000 2023",
        "id": 1678537355286970370,
        "id_str": "1678537355286970370",
        "text": "RT @HugoGloss: Eles também gravaram um recado bem especial para os Czennies. 💚 Yo, Dream! https://t.co/9xm2CRlIC9",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [
                {
                    "screen_name": "HugoGloss",
                    "name": "Hugo Gloss",
                    "id": 15292534,
                    "id_str": "15292534",
                    "indices": [
                        3,
                        13
                    ]
                }
            ],
            "urls": [],
            "media": [
                {
                    "id": 1678522899815186434,
                    "id_str": "1678522899815186434",
                    "indices": [
                        90,
                        113
                    ],
                    "media_url": "http://pbs.twimg.com/ext_tw_video_thumb/1678522899815186434/pu/img/hIJG5K34Y2XJP22d.jpg",
                    "media_url_https": "https://pbs.twimg.com/ext_tw_video_thumb/1678522899815186434/pu/img/hIJG5K34Y2XJP22d.jpg",
                    "url": "https://t.co/9xm2CRlIC9",
                    "display_url": "pic.twitter.com/9xm2CRlIC9",
                    "expanded_url": "https://twitter.com/HugoGloss/status/1678524307541053440/video/1",
                    "type": "photo",
                    "original_info": {
                        "width": 1920,
                        "height": 1080
                    },
                    "sizes": {
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "large": {
                            "w": 1920,
                            "h": 1080,
                            "resize": "fit"
                        },
                        "medium": {
                            "w": 1200,
                            "h": 675,
                            "resize": "fit"
                        },
                        "small": {
                            "w": 680,
                            "h": 383,
                            "resize": "fit"
                        }
                    },
                    "source_status_id": 1678524307541053440,
                    "source_status_id_str": "1678524307541053440",
                    "source_user_id": 15292534,
                    "source_user_id_str": "15292534",
                    "features": {}
                }
            ]
        },
        "extended_entities": {
            "media": [
                {
                    "id": 1678522899815186434,
                    "id_str": "1678522899815186434",
                    "indices": [
                        90,
                        113
                    ],
                    "media_url": "http://pbs.twimg.com/ext_tw_video_thumb/1678522899815186434/pu/img/hIJG5K34Y2XJP22d.jpg",
                    "media_url_https": "https://pbs.twimg.com/ext_tw_video_thumb/1678522899815186434/pu/img/hIJG5K34Y2XJP22d.jpg",
                    "url": "https://t.co/9xm2CRlIC9",
                    "display_url": "pic.twitter.com/9xm2CRlIC9",
                    "expanded_url": "https://twitter.com/HugoGloss/status/1678524307541053440/video/1",
                    "type": "video",
                    "original_info": {
                        "width": 1920,
                        "height": 1080
                    },
                    "sizes": {
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "large": {
                            "w": 1920,
                            "h": 1080,
                            "resize": "fit"
                        },
                        "medium": {
                            "w": 1200,
                            "h": 675,
                            "resize": "fit"
                        },
                        "small": {
                            "w": 680,
                            "h": 383,
                            "resize": "fit"
                        }
                    },
                    "source_status_id": 1678524307541053440,
                    "source_status_id_str": "1678524307541053440",
                    "source_user_id": 15292534,
                    "source_user_id_str": "15292534",
                    "video_info": {
                        "aspect_ratio": [
                            16,
                            9
                        ],
                        "duration_millis": 23301,
                        "variants": [
                            {
                                "content_type": "application/x-mpegURL",
                                "url": "https://video.twimg.com/ext_tw_video/1678522899815186434/pu/pl/m7v8SpRLDq2UiUjQ.m3u8?tag=12&container=fmp4"
                            },
                            {
                                "bitrate": 2176000,
                                "content_type": "video/mp4",
                                "url": "https://video.twimg.com/ext_tw_video/1678522899815186434/pu/vid/1280x720/oYvNf0bBP5jBHnwF.mp4?tag=12"
                            },
                            {
                                "bitrate": 256000,
                                "content_type": "video/mp4",
                                "url": "https://video.twimg.com/ext_tw_video/1678522899815186434/pu/vid/480x270/pezscaLRRBZQXe2V.mp4?tag=12"
                            },
                            {
                                "bitrate": 832000,
                                "content_type": "video/mp4",
                                "url": "https://video.twimg.com/ext_tw_video/1678522899815186434/pu/vid/640x360/VLoqXuiUpjUvRHs-.mp4?tag=12"
                            }
                        ]
                    },
                    "features": {},
                    "media_key": "7_1678522899815186434",
                    "additional_media_info": {
                        "monetizable": false,
                        "source_user": {
                            "id": 15292534,
                            "id_str": "15292534",
                            "name": "Hugo Gloss",
                            "screen_name": "HugoGloss",
                            "location": "Brazil",
                            "description": "Brazilian Entertainment Website. In Beyoncé we trust!",
                            "url": "https://t.co/KLNu7LZZdC",
                            "entities": {
                                "url": {
                                    "urls": [
                                        {
                                            "url": "https://t.co/KLNu7LZZdC",
                                            "expanded_url": "https://hugogloss.uol.com.br/",
                                            "display_url": "hugogloss.uol.com.br",
                                            "indices": [
                                                0,
                                                23
                                            ]
                                        }
                                    ]
                                },
                                "description": {
                                    "urls": []
                                }
                            },
                            "protected": false,
                            "followers_count": 5383471,
                            "fast_followers_count": 0,
                            "normal_followers_count": 5383471,
                            "friends_count": 4253,
                            "listed_count": 7906,
                            "created_at": "Tue Jul 01 22:17:25 +0000 2008",
                            "favourites_count": 4458,
                            "utc_offset": null,
                            "time_zone": null,
                            "geo_enabled": true,
                            "verified": false,
                            "statuses_count": 84557,
                            "media_count": 50886,
                            "lang": null,
                            "contributors_enabled": false,
                            "is_translator": false,
                            "is_translation_enabled": false,
                            "profile_background_color": "1A1B1F",
                            "profile_background_image_url": "http://abs.twimg.com/images/themes/theme9/bg.gif",
                            "profile_background_image_url_https": "https://abs.twimg.com/images/themes/theme9/bg.gif",
                            "profile_background_tile": true,
                            "profile_image_url": "http://pbs.twimg.com/profile_images/1253448789924462593/OeG6MbcO_normal.jpg",
                            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1253448789924462593/OeG6MbcO_normal.jpg",
                            "profile_banner_url": "https://pbs.twimg.com/profile_banners/15292534/1683651747",
                            "profile_link_color": "ABB8C2",
                            "profile_sidebar_border_color": "FFFFFF",
                            "profile_sidebar_fill_color": "252429",
                            "profile_text_color": "666666",
                            "profile_use_background_image": true,
                            "has_extended_profile": true,
                            "default_profile": false,
                            "default_profile_image": false,
                            "pinned_tweet_ids": [
                                1676730535069007875
                            ],
                            "pinned_tweet_ids_str": [
                                "1676730535069007875"
                            ],
                            "has_custom_timelines": true,
                            "can_media_tag": true,
                            "followed_by": false,
                            "following": false,
                            "follow_request_sent": false,
                            "notifications": false,
                            "advertiser_account_type": "promotable_user",
                            "advertiser_account_service_levels": [],
                            "analytics_type": "enabled",
                            "business_profile_state": "none",
                            "translator_type": "regular",
                            "withheld_in_countries": [],
                            "require_some_consent": false
                        }
                    }
                }
            ]
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "retweeted_status": {
            "created_at": "Mon Jul 10 21:59:15 +0000 2023",
            "id": 1678524307541053440,
            "id_str": "1678524307541053440",
            "text": "Eles também gravaram um recado bem especial para os Czennies. 💚 Yo, Dream! https://t.co/9xm2CRlIC9",
            "truncated": false,
            "entities": {
                "hashtags": [],
                "symbols": [],
                "user_mentions": [],
                "urls": [],
                "media": [
                    {
                        "id": 1678522899815186434,
                        "id_str": "1678522899815186434",
                        "indices": [
                            75,
                            98
                        ],
                        "media_url": "http://pbs.twimg.com/ext_tw_video_thumb/1678522899815186434/pu/img/hIJG5K34Y2XJP22d.jpg",
                        "media_url_https": "https://pbs.twimg.com/ext_tw_video_thumb/1678522899815186434/pu/img/hIJG5K34Y2XJP22d.jpg",
                        "url": "https://t.co/9xm2CRlIC9",
                        "display_url": "pic.twitter.com/9xm2CRlIC9",
                        "expanded_url": "https://twitter.com/HugoGloss/status/1678524307541053440/video/1",
                        "type": "photo",
                        "original_info": {
                            "width": 1920,
                            "height": 1080
                        },
                        "sizes": {
                            "thumb": {
                                "w": 150,
                                "h": 150,
                                "resize": "crop"
                            },
                            "large": {
                                "w": 1920,
                                "h": 1080,
                                "resize": "fit"
                            },
                            "medium": {
                                "w": 1200,
                                "h": 675,
                                "resize": "fit"
                            },
                            "small": {
                                "w": 680,
                                "h": 383,
                                "resize": "fit"
                            }
                        },
                        "features": {}
                    }
                ]
            },
            "extended_entities": {
                "media": [
                    {
                        "id": 1678522899815186434,
                        "id_str": "1678522899815186434",
                        "indices": [
                            75,
                            98
                        ],
                        "media_url": "http://pbs.twimg.com/ext_tw_video_thumb/1678522899815186434/pu/img/hIJG5K34Y2XJP22d.jpg",
                        "media_url_https": "https://pbs.twimg.com/ext_tw_video_thumb/1678522899815186434/pu/img/hIJG5K34Y2XJP22d.jpg",
                        "url": "https://t.co/9xm2CRlIC9",
                        "display_url": "pic.twitter.com/9xm2CRlIC9",
                        "expanded_url": "https://twitter.com/HugoGloss/status/1678524307541053440/video/1",
                        "type": "video",
                        "original_info": {
                            "width": 1920,
                            "height": 1080
                        },
                        "sizes": {
                            "thumb": {
                                "w": 150,
                                "h": 150,
                                "resize": "crop"
                            },
                            "large": {
                                "w": 1920,
                                "h": 1080,
                                "resize": "fit"
                            },
                            "medium": {
                                "w": 1200,
                                "h": 675,
                                "resize": "fit"
                            },
                            "small": {
                                "w": 680,
                                "h": 383,
                                "resize": "fit"
                            }
                        },
                        "video_info": {
                            "aspect_ratio": [
                                16,
                                9
                            ],
                            "duration_millis": 23301,
                            "variants": [
                                {
                                    "content_type": "application/x-mpegURL",
                                    "url": "https://video.twimg.com/ext_tw_video/1678522899815186434/pu/pl/m7v8SpRLDq2UiUjQ.m3u8?tag=12&container=fmp4"
                                },
                                {
                                    "bitrate": 2176000,
                                    "content_type": "video/mp4",
                                    "url": "https://video.twimg.com/ext_tw_video/1678522899815186434/pu/vid/1280x720/oYvNf0bBP5jBHnwF.mp4?tag=12"
                                },
                                {
                                    "bitrate": 256000,
                                    "content_type": "video/mp4",
                                    "url": "https://video.twimg.com/ext_tw_video/1678522899815186434/pu/vid/480x270/pezscaLRRBZQXe2V.mp4?tag=12"
                                },
                                {
                                    "bitrate": 832000,
                                    "content_type": "video/mp4",
                                    "url": "https://video.twimg.com/ext_tw_video/1678522899815186434/pu/vid/640x360/VLoqXuiUpjUvRHs-.mp4?tag=12"
                                }
                            ]
                        },
                        "features": {},
                        "media_key": "7_1678522899815186434",
                        "additional_media_info": {
                            "monetizable": false
                        }
                    }
                ]
            },
            "source": "<a href=\"https://mobile.twitter.com\" rel=\"nofollow\">Twitter Web App</a>",
            "in_reply_to_status_id": 1678524304424665089,
            "in_reply_to_status_id_str": "1678524304424665089",
            "in_reply_to_user_id": 15292534,
            "in_reply_to_user_id_str": "15292534",
            "in_reply_to_screen_name": "HugoGloss",
            "user": {
                "id": 15292534,
                "id_str": "15292534",
                "name": "Hugo Gloss",
                "screen_name": "HugoGloss",
                "location": "Brazil",
                "description": "Brazilian Entertainment Website. In Beyoncé we trust!",
                "url": "https://t.co/KLNu7LZZdC",
                "entities": {
                    "url": {
                        "urls": [
                            {
                                "url": "https://t.co/KLNu7LZZdC",
                                "expanded_url": "https://hugogloss.uol.com.br/",
                                "display_url": "hugogloss.uol.com.br",
                                "indices": [
                                    0,
                                    23
                                ]
                            }
                        ]
                    },
                    "description": {
                        "urls": []
                    }
                },
                "protected": false,
                "followers_count": 5383471,
                "fast_followers_count": 0,
                "normal_followers_count": 5383471,
                "friends_count": 4253,
                "listed_count": 7906,
                "created_at": "Tue Jul 01 22:17:25 +0000 2008",
                "favourites_count": 4458,
                "utc_offset": null,
                "time_zone": null,
                "geo_enabled": true,
                "verified": false,
                "statuses_count": 84557,
                "media_count": 50886,
                "lang": null,
                "contributors_enabled": false,
                "is_translator": false,
                "is_translation_enabled": false,
                "profile_background_color": "1A1B1F",
                "profile_background_image_url": "http://abs.twimg.com/images/themes/theme9/bg.gif",
                "profile_background_image_url_https": "https://abs.twimg.com/images/themes/theme9/bg.gif",
                "profile_background_tile": true,
                "profile_image_url": "http://pbs.twimg.com/profile_images/1253448789924462593/OeG6MbcO_normal.jpg",
                "profile_image_url_https": "https://pbs.twimg.com/profile_images/1253448789924462593/OeG6MbcO_normal.jpg",
                "profile_banner_url": "https://pbs.twimg.com/profile_banners/15292534/1683651747",
                "profile_link_color": "ABB8C2",
                "profile_sidebar_border_color": "FFFFFF",
                "profile_sidebar_fill_color": "252429",
                "profile_text_color": "666666",
                "profile_use_background_image": true,
                "has_extended_profile": true,
                "default_profile": false,
                "default_profile_image": false,
                "pinned_tweet_ids": [
                    1676730535069007875
                ],
                "pinned_tweet_ids_str": [
                    "1676730535069007875"
                ],
                "has_custom_timelines": true,
                "can_media_tag": true,
                "followed_by": false,
                "following": false,
                "follow_request_sent": false,
                "notifications": false,
                "advertiser_account_type": "promotable_user",
                "advertiser_account_service_levels": [],
                "analytics_type": "enabled",
                "business_profile_state": "none",
                "translator_type": "regular",
                "withheld_in_countries": [],
                "require_some_consent": false
            },
            "geo": null,
            "coordinates": null,
            "place": null,
            "contributors": null,
            "is_quote_status": false,
            "retweet_count": 2033,
            "favorite_count": 4198,
            "conversation_id": 1678524304424665089,
            "conversation_id_str": "1678524304424665089",
            "favorited": false,
            "retweeted": false,
            "possibly_sensitive": false,
            "possibly_sensitive_editable": true,
            "lang": "pt",
            "supplemental_language": null,
            "self_thread": {
                "id": 1678524304424665089,
                "id_str": "1678524304424665089"
            }
        },
        "is_quote_status": false,
        "retweet_count": 2033,
        "favorite_count": 0,
        "conversation_id": 1678537355286970370,
        "conversation_id_str": "1678537355286970370",
        "favorited": false,
        "retweeted": false,
        "possibly_sensitive": false,
        "possibly_sensitive_editable": true,
        "lang": "pt",
        "supplemental_language": null
    },
    {
        "created_at": "Mon Jul 10 13:42:08 +0000 2023",
        "id": 1678399207990804482,
        "id_str": "1678399207990804482",
        "text": "haechannie is everything 🥺💗\nhttps://t.co/owWXREOVDs",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [],
            "urls": [],
            "media": [
                {
                    "id": 1445344352738295809,
                    "id_str": "1445344352738295809",
                    "indices": [
                        28,
                        51
                    ],
                    "media_url": "http://pbs.twimg.com/ext_tw_video_thumb/1445344352738295809/pu/img/HisZVYAE5g5-94Jg.jpg",
                    "media_url_https": "https://pbs.twimg.com/ext_tw_video_thumb/1445344352738295809/pu/img/HisZVYAE5g5-94Jg.jpg",
                    "url": "https://t.co/owWXREOVDs",
                    "display_url": "pic.twitter.com/owWXREOVDs",
                    "expanded_url": "https://twitter.com/HaechanTube/status/1445344371461689346/video/1",
                    "type": "photo",
                    "original_info": {
                        "width": 640,
                        "height": 480
                    },
                    "sizes": {
                        "medium": {
                            "w": 640,
                            "h": 480,
                            "resize": "fit"
                        },
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "small": {
                            "w": 640,
                            "h": 480,
                            "resize": "fit"
                        },
                        "large": {
                            "w": 640,
                            "h": 480,
                            "resize": "fit"
                        }
                    },
                    "source_status_id": 1445344371461689346,
                    "source_status_id_str": "1445344371461689346",
                    "source_user_id": 1169249320517820417,
                    "source_user_id_str": "1169249320517820417",
                    "features": {}
                }
            ]
        },
        "extended_entities": {
            "media": [
                {
                    "id": 1445344352738295809,
                    "id_str": "1445344352738295809",
                    "indices": [
                        28,
                        51
                    ],
                    "media_url": "http://pbs.twimg.com/ext_tw_video_thumb/1445344352738295809/pu/img/HisZVYAE5g5-94Jg.jpg",
                    "media_url_https": "https://pbs.twimg.com/ext_tw_video_thumb/1445344352738295809/pu/img/HisZVYAE5g5-94Jg.jpg",
                    "url": "https://t.co/owWXREOVDs",
                    "display_url": "pic.twitter.com/owWXREOVDs",
                    "expanded_url": "https://twitter.com/HaechanTube/status/1445344371461689346/video/1",
                    "type": "video",
                    "original_info": {
                        "width": 640,
                        "height": 480
                    },
                    "sizes": {
                        "medium": {
                            "w": 640,
                            "h": 480,
                            "resize": "fit"
                        },
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "small": {
                            "w": 640,
                            "h": 480,
                            "resize": "fit"
                        },
                        "large": {
                            "w": 640,
                            "h": 480,
                            "resize": "fit"
                        }
                    },
                    "source_status_id": 1445344371461689346,
                    "source_status_id_str": "1445344371461689346",
                    "source_user_id": 1169249320517820417,
                    "source_user_id_str": "1169249320517820417",
                    "video_info": {
                        "aspect_ratio": [
                            4,
                            3
                        ],
                        "duration_millis": 1550,
                        "variants": [
                            {
                                "bitrate": 256000,
                                "content_type": "video/mp4",
                                "url": "https://video.twimg.com/ext_tw_video/1445344352738295809/pu/vid/360x270/ZXLFYAWhfewW1rRj.mp4?tag=12"
                            },
                            {
                                "bitrate": 2176000,
                                "content_type": "video/mp4",
                                "url": "https://video.twimg.com/ext_tw_video/1445344352738295809/pu/vid/640x480/JPHhL4HAvbxjR17L.mp4?tag=12"
                            },
                            {
                                "content_type": "application/x-mpegURL",
                                "url": "https://video.twimg.com/ext_tw_video/1445344352738295809/pu/pl/97g3-pBSiQbseGK5.m3u8?tag=12&container=fmp4"
                            },
                            {
                                "bitrate": 832000,
                                "content_type": "video/mp4",
                                "url": "https://video.twimg.com/ext_tw_video/1445344352738295809/pu/vid/480x360/SzqOZohd5_4nRR-C.mp4?tag=12"
                            }
                        ]
                    },
                    "features": {},
                    "media_key": "7_1445344352738295809",
                    "additional_media_info": {
                        "monetizable": false,
                        "source_user": {
                            "id": 1169249320517820417,
                            "id_str": "1169249320517820417",
                            "name": "해찬튜브",
                            "screen_name": "HaechanTube",
                            "location": "해찬귀여워봇 ..",
                            "description": "#해찬🖤 좋은 사람 ♪ https://t.co/pOW7vToULb",
                            "url": "https://t.co/ZhhUhEl6CR",
                            "entities": {
                                "url": {
                                    "urls": [
                                        {
                                            "url": "https://t.co/ZhhUhEl6CR",
                                            "expanded_url": "https://asked.kr/HaechanTube",
                                            "display_url": "asked.kr/HaechanTube",
                                            "indices": [
                                                0,
                                                23
                                            ]
                                        }
                                    ]
                                },
                                "description": {
                                    "urls": [
                                        {
                                            "url": "https://t.co/pOW7vToULb",
                                            "expanded_url": "http://kko.to/9JX9p4mQY",
                                            "display_url": "kko.to/9JX9p4mQY",
                                            "indices": [
                                                13,
                                                36
                                            ]
                                        }
                                    ]
                                }
                            },
                            "protected": false,
                            "followers_count": 161676,
                            "fast_followers_count": 0,
                            "normal_followers_count": 161676,
                            "friends_count": 1,
                            "listed_count": 2907,
                            "created_at": "Wed Sep 04 14:02:23 +0000 2019",
                            "favourites_count": 158,
                            "utc_offset": null,
                            "time_zone": null,
                            "geo_enabled": true,
                            "verified": false,
                            "statuses_count": 16752,
                            "media_count": 15080,
                            "lang": null,
                            "contributors_enabled": false,
                            "is_translator": false,
                            "is_translation_enabled": false,
                            "profile_background_color": "F5F8FA",
                            "profile_background_image_url": null,
                            "profile_background_image_url_https": null,
                            "profile_background_tile": false,
                            "profile_image_url": "http://pbs.twimg.com/profile_images/1675528395055321089/Ox5UDgoz_normal.jpg",
                            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1675528395055321089/Ox5UDgoz_normal.jpg",
                            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1169249320517820417/1688311115",
                            "profile_link_color": "1DA1F2",
                            "profile_sidebar_border_color": "C0DEED",
                            "profile_sidebar_fill_color": "DDEEF6",
                            "profile_text_color": "333333",
                            "profile_use_background_image": true,
                            "has_extended_profile": false,
                            "default_profile": true,
                            "default_profile_image": false,
                            "pinned_tweet_ids": [
                                1641550967257829377
                            ],
                            "pinned_tweet_ids_str": [
                                "1641550967257829377"
                            ],
                            "has_custom_timelines": true,
                            "can_media_tag": false,
                            "followed_by": false,
                            "following": false,
                            "follow_request_sent": false,
                            "notifications": false,
                            "advertiser_account_type": "none",
                            "advertiser_account_service_levels": [],
                            "analytics_type": "disabled",
                            "business_profile_state": "none",
                            "translator_type": "none",
                            "withheld_in_countries": [],
                            "require_some_consent": false
                        }
                    }
                }
            ]
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "is_quote_status": false,
        "retweet_count": 452,
        "favorite_count": 2024,
        "conversation_id": 1678399207990804482,
        "conversation_id_str": "1678399207990804482",
        "conversation_control": {
            "policy": "community",
            "conversation_owner": {
                "screen_name": "LHCMILD"
            }
        },
        "favorited": false,
        "retweeted": false,
        "possibly_sensitive": false,
        "possibly_sensitive_editable": true,
        "limited_actions": "limited_replies",
        "lang": "en",
        "supplemental_language": null
    },
    {
        "created_at": "Mon Jul 10 13:21:56 +0000 2023",
        "id": 1678394123248893952,
        "id_str": "1678394123248893952",
        "text": "haechan who is round like a chocoball 😔🤏\nhttps://t.co/rRWQ0x0FFU",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [],
            "urls": [],
            "media": [
                {
                    "id": 1476902710288867331,
                    "id_str": "1476902710288867331",
                    "indices": [
                        41,
                        64
                    ],
                    "media_url": "http://pbs.twimg.com/ext_tw_video_thumb/1476902710288867331/pu/img/4_56QUqb3qunT_iz.jpg",
                    "media_url_https": "https://pbs.twimg.com/ext_tw_video_thumb/1476902710288867331/pu/img/4_56QUqb3qunT_iz.jpg",
                    "url": "https://t.co/rRWQ0x0FFU",
                    "display_url": "pic.twitter.com/rRWQ0x0FFU",
                    "expanded_url": "https://twitter.com/puduyam/status/1476902734641377287/video/1",
                    "type": "photo",
                    "original_info": {
                        "width": 462,
                        "height": 462
                    },
                    "sizes": {
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "large": {
                            "w": 462,
                            "h": 462,
                            "resize": "fit"
                        },
                        "medium": {
                            "w": 462,
                            "h": 462,
                            "resize": "fit"
                        },
                        "small": {
                            "w": 462,
                            "h": 462,
                            "resize": "fit"
                        }
                    },
                    "source_status_id": 1476902734641377287,
                    "source_status_id_str": "1476902734641377287",
                    "source_user_id": 1260805463148388353,
                    "source_user_id_str": "1260805463148388353",
                    "features": {}
                }
            ]
        },
        "extended_entities": {
            "media": [
                {
                    "id": 1476902710288867331,
                    "id_str": "1476902710288867331",
                    "indices": [
                        41,
                        64
                    ],
                    "media_url": "http://pbs.twimg.com/ext_tw_video_thumb/1476902710288867331/pu/img/4_56QUqb3qunT_iz.jpg",
                    "media_url_https": "https://pbs.twimg.com/ext_tw_video_thumb/1476902710288867331/pu/img/4_56QUqb3qunT_iz.jpg",
                    "url": "https://t.co/rRWQ0x0FFU",
                    "display_url": "pic.twitter.com/rRWQ0x0FFU",
                    "expanded_url": "https://twitter.com/puduyam/status/1476902734641377287/video/1",
                    "type": "video",
                    "original_info": {
                        "width": 462,
                        "height": 462
                    },
                    "sizes": {
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "large": {
                            "w": 462,
                            "h": 462,
                            "resize": "fit"
                        },
                        "medium": {
                            "w": 462,
                            "h": 462,
                            "resize": "fit"
                        },
                        "small": {
                            "w": 462,
                            "h": 462,
                            "resize": "fit"
                        }
                    },
                    "source_status_id": 1476902734641377287,
                    "source_status_id_str": "1476902734641377287",
                    "source_user_id": 1260805463148388353,
                    "source_user_id_str": "1260805463148388353",
                    "video_info": {
                        "aspect_ratio": [
                            1,
                            1
                        ],
                        "duration_millis": 6841,
                        "variants": [
                            {
                                "bitrate": 432000,
                                "content_type": "video/mp4",
                                "url": "https://video.twimg.com/ext_tw_video/1476902710288867331/pu/vid/320x320/1J63IRGZOMremnDB.mp4?tag=12"
                            },
                            {
                                "content_type": "application/x-mpegURL",
                                "url": "https://video.twimg.com/ext_tw_video/1476902710288867331/pu/pl/YkrWZ6Glr_GgRy2I.m3u8?tag=12&container=fmp4"
                            },
                            {
                                "bitrate": 832000,
                                "content_type": "video/mp4",
                                "url": "https://video.twimg.com/ext_tw_video/1476902710288867331/pu/vid/462x462/i0LDmQo0lB9TMxeL.mp4?tag=12"
                            }
                        ]
                    },
                    "features": {},
                    "media_key": "7_1476902710288867331",
                    "additional_media_info": {
                        "monetizable": false,
                        "source_user": {
                            "id": 1260805463148388353,
                            "id_str": "1260805463148388353",
                            "name": "ㅍㄷ",
                            "screen_name": "puduyam",
                            "location": "haechan",
                            "description": "",
                            "url": null,
                            "entities": {
                                "description": {
                                    "urls": []
                                }
                            },
                            "protected": false,
                            "followers_count": 23940,
                            "fast_followers_count": 0,
                            "normal_followers_count": 23940,
                            "friends_count": 89,
                            "listed_count": 604,
                            "created_at": "Thu May 14 05:33:50 +0000 2020",
                            "favourites_count": 18,
                            "utc_offset": null,
                            "time_zone": null,
                            "geo_enabled": false,
                            "verified": false,
                            "statuses_count": 25243,
                            "media_count": 11194,
                            "lang": null,
                            "contributors_enabled": false,
                            "is_translator": false,
                            "is_translation_enabled": false,
                            "profile_background_color": "F5F8FA",
                            "profile_background_image_url": null,
                            "profile_background_image_url_https": null,
                            "profile_background_tile": false,
                            "profile_image_url": "http://pbs.twimg.com/profile_images/1676831894162530304/LGkXcb8H_normal.jpg",
                            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1676831894162530304/LGkXcb8H_normal.jpg",
                            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1260805463148388353/1688622882",
                            "profile_link_color": "1DA1F2",
                            "profile_sidebar_border_color": "C0DEED",
                            "profile_sidebar_fill_color": "DDEEF6",
                            "profile_text_color": "333333",
                            "profile_use_background_image": true,
                            "has_extended_profile": false,
                            "default_profile": true,
                            "default_profile_image": false,
                            "pinned_tweet_ids": [],
                            "pinned_tweet_ids_str": [],
                            "has_custom_timelines": true,
                            "can_media_tag": true,
                            "followed_by": false,
                            "following": false,
                            "follow_request_sent": false,
                            "notifications": false,
                            "advertiser_account_type": "none",
                            "advertiser_account_service_levels": [],
                            "analytics_type": "disabled",
                            "business_profile_state": "none",
                            "translator_type": "none",
                            "withheld_in_countries": [],
                            "require_some_consent": false
                        }
                    }
                }
            ]
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "is_quote_status": false,
        "retweet_count": 1743,
        "favorite_count": 7056,
        "conversation_id": 1678394123248893952,
        "conversation_id_str": "1678394123248893952",
        "conversation_control": {
            "policy": "community",
            "conversation_owner": {
                "screen_name": "LHCMILD"
            }
        },
        "favorited": false,
        "retweeted": false,
        "possibly_sensitive": false,
        "possibly_sensitive_editable": true,
        "limited_actions": "limited_replies",
        "lang": "en",
        "supplemental_language": null
    },
    {
        "created_at": "Mon Jul 10 12:55:11 +0000 2023",
        "id": 1678387390640181249,
        "id_str": "1678387390640181249",
        "text": "RT @fs_sf_fs: The Evolution of Haechan’s “You want it babe~!” in Hot Sauce part 2!\n\nThe new high note Haechan mentioned on his 🫧- sustained…",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [
                {
                    "screen_name": "fs_sf_fs",
                    "name": "SUNSPOT📍 NCT LAB! ☀️🌙",
                    "id": 1369499623824318467,
                    "id_str": "1369499623824318467",
                    "indices": [
                        3,
                        12
                    ]
                }
            ],
            "urls": []
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "retweeted_status": {
            "created_at": "Mon Jul 10 12:31:40 +0000 2023",
            "id": 1678381473844322304,
            "id_str": "1678381473844322304",
            "text": "The Evolution of Haechan’s “You want it babe~!” in Hot Sauce part 2!\n\nThe new high note Haechan mentioned on his 🫧-… https://t.co/Cu17b9J09S",
            "truncated": true,
            "entities": {
                "hashtags": [],
                "symbols": [],
                "user_mentions": [],
                "urls": [
                    {
                        "url": "https://t.co/Cu17b9J09S",
                        "expanded_url": "https://twitter.com/i/web/status/1678381473844322304",
                        "display_url": "twitter.com/i/web/status/1…",
                        "indices": [
                            117,
                            140
                        ]
                    }
                ]
            },
            "source": "<a href=\"http://twitter.com/download/iphone\" rel=\"nofollow\">Twitter for iPhone</a>",
            "in_reply_to_status_id": null,
            "in_reply_to_status_id_str": null,
            "in_reply_to_user_id": null,
            "in_reply_to_user_id_str": null,
            "in_reply_to_screen_name": null,
            "user": {
                "id": 1369499623824318467,
                "id_str": "1369499623824318467",
                "name": "SUNSPOT📍 NCT LAB! ☀️🌙",
                "screen_name": "fs_sf_fs",
                "location": "eng/한 • kindly give credits ",
                "description": "CAN’T SPELL ACE WITHOUT #HAECHAN ☀️ sunspotopsnus on IG ☀️ #375Hours_Haechan_Vlog",
                "url": null,
                "entities": {
                    "description": {
                        "urls": []
                    }
                },
                "protected": false,
                "followers_count": 27231,
                "fast_followers_count": 0,
                "normal_followers_count": 27231,
                "friends_count": 4,
                "listed_count": 730,
                "created_at": "Wed Mar 10 04:05:55 +0000 2021",
                "favourites_count": 259,
                "utc_offset": null,
                "time_zone": null,
                "geo_enabled": false,
                "verified": false,
                "statuses_count": 8673,
                "media_count": 4032,
                "lang": null,
                "contributors_enabled": false,
                "is_translator": false,
                "is_translation_enabled": false,
                "profile_background_color": "F5F8FA",
                "profile_background_image_url": null,
                "profile_background_image_url_https": null,
                "profile_background_tile": false,
                "profile_image_url": "http://pbs.twimg.com/profile_images/1664985710653317122/sfFTiQTC_normal.jpg",
                "profile_image_url_https": "https://pbs.twimg.com/profile_images/1664985710653317122/sfFTiQTC_normal.jpg",
                "profile_banner_url": "https://pbs.twimg.com/profile_banners/1369499623824318467/1688171541",
                "profile_link_color": "1DA1F2",
                "profile_sidebar_border_color": "C0DEED",
                "profile_sidebar_fill_color": "DDEEF6",
                "profile_text_color": "333333",
                "profile_use_background_image": true,
                "has_extended_profile": true,
                "default_profile": true,
                "default_profile_image": false,
                "pinned_tweet_ids": [
                    1638171222931300352
                ],
                "pinned_tweet_ids_str": [
                    "1638171222931300352"
                ],
                "has_custom_timelines": true,
                "can_media_tag": true,
                "followed_by": false,
                "following": false,
                "follow_request_sent": false,
                "notifications": false,
                "advertiser_account_type": "promotable_user",
                "advertiser_account_service_levels": [
                    "analytics"
                ],
                "analytics_type": "disabled",
                "business_profile_state": "none",
                "translator_type": "none",
                "withheld_in_countries": [],
                "require_some_consent": false
            },
            "geo": null,
            "coordinates": null,
            "place": null,
            "contributors": null,
            "is_quote_status": false,
            "retweet_count": 954,
            "favorite_count": 2190,
            "conversation_id": 1678381473844322304,
            "conversation_id_str": "1678381473844322304",
            "favorited": false,
            "retweeted": false,
            "possibly_sensitive": false,
            "possibly_sensitive_editable": true,
            "lang": "en",
            "supplemental_language": null
        },
        "is_quote_status": false,
        "retweet_count": 954,
        "favorite_count": 0,
        "conversation_id": 1678387390640181249,
        "conversation_id_str": "1678387390640181249",
        "favorited": false,
        "retweeted": false,
        "lang": "en",
        "supplemental_language": null
    },
    {
        "created_at": "Mon Jul 10 11:20:04 +0000 2023",
        "id": 1678363453285883905,
        "id_str": "1678363453285883905",
        "text": "kiyomiii",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [],
            "urls": []
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": 1678363362537918465,
        "in_reply_to_status_id_str": "1678363362537918465",
        "in_reply_to_user_id": 1454736746621521928,
        "in_reply_to_user_id_str": "1454736746621521928",
        "in_reply_to_screen_name": "LHCMILD",
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "is_quote_status": false,
        "retweet_count": 0,
        "favorite_count": 1,
        "conversation_id": 1678363362537918465,
        "conversation_id_str": "1678363362537918465",
        "conversation_control": {
            "policy": "community",
            "conversation_owner": {
                "screen_name": "LHCMILD"
            }
        },
        "favorited": false,
        "retweeted": false,
        "limited_actions": "limited_replies",
        "lang": "tr",
        "supplemental_language": null,
        "self_thread": {
            "id": 1678363362537918465,
            "id_str": "1678363362537918465"
        }
    },
    {
        "created_at": "Mon Jul 10 11:19:42 +0000 2023",
        "id": 1678363362537918465,
        "id_str": "1678363362537918465",
        "text": "😆😆😆😆😆😆                   😯😲😲😲😲😯 https://t.co/rteS7ZzBxu",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [],
            "urls": [],
            "media": [
                {
                    "id": 1678363356456169472,
                    "id_str": "1678363356456169472",
                    "indices": [
                        32,
                        55
                    ],
                    "media_url": "http://pbs.twimg.com/media/F0q-lJGaMAAUxiy.jpg",
                    "media_url_https": "https://pbs.twimg.com/media/F0q-lJGaMAAUxiy.jpg",
                    "url": "https://t.co/rteS7ZzBxu",
                    "display_url": "pic.twitter.com/rteS7ZzBxu",
                    "expanded_url": "https://twitter.com/LHCMILD/status/1678363362537918465/photo/1",
                    "type": "photo",
                    "original_info": {
                        "width": 669,
                        "height": 669,
                        "focus_rects": [
                            {
                                "x": 0,
                                "y": 164,
                                "h": 375,
                                "w": 669
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 669,
                                "w": 669
                            },
                            {
                                "x": 58,
                                "y": 0,
                                "h": 669,
                                "w": 587
                            },
                            {
                                "x": 184,
                                "y": 0,
                                "h": 669,
                                "w": 335
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 669,
                                "w": 669
                            }
                        ]
                    },
                    "sizes": {
                        "large": {
                            "w": 669,
                            "h": 669,
                            "resize": "fit"
                        },
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "small": {
                            "w": 669,
                            "h": 669,
                            "resize": "fit"
                        },
                        "medium": {
                            "w": 669,
                            "h": 669,
                            "resize": "fit"
                        }
                    },
                    "features": {
                        "large": {
                            "faces": [
                                {
                                    "x": 155,
                                    "y": 60,
                                    "h": 393,
                                    "w": 393
                                }
                            ]
                        },
                        "orig": {
                            "faces": [
                                {
                                    "x": 155,
                                    "y": 60,
                                    "h": 393,
                                    "w": 393
                                }
                            ]
                        },
                        "small": {
                            "faces": [
                                {
                                    "x": 155,
                                    "y": 60,
                                    "h": 393,
                                    "w": 393
                                }
                            ]
                        },
                        "medium": {
                            "faces": [
                                {
                                    "x": 155,
                                    "y": 60,
                                    "h": 393,
                                    "w": 393
                                }
                            ]
                        }
                    }
                }
            ]
        },
        "extended_entities": {
            "media": [
                {
                    "id": 1678363356456169472,
                    "id_str": "1678363356456169472",
                    "indices": [
                        32,
                        55
                    ],
                    "media_url": "http://pbs.twimg.com/media/F0q-lJGaMAAUxiy.jpg",
                    "media_url_https": "https://pbs.twimg.com/media/F0q-lJGaMAAUxiy.jpg",
                    "url": "https://t.co/rteS7ZzBxu",
                    "display_url": "pic.twitter.com/rteS7ZzBxu",
                    "expanded_url": "https://twitter.com/LHCMILD/status/1678363362537918465/photo/1",
                    "type": "photo",
                    "original_info": {
                        "width": 669,
                        "height": 669,
                        "focus_rects": [
                            {
                                "x": 0,
                                "y": 164,
                                "h": 375,
                                "w": 669
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 669,
                                "w": 669
                            },
                            {
                                "x": 58,
                                "y": 0,
                                "h": 669,
                                "w": 587
                            },
                            {
                                "x": 184,
                                "y": 0,
                                "h": 669,
                                "w": 335
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 669,
                                "w": 669
                            }
                        ]
                    },
                    "sizes": {
                        "large": {
                            "w": 669,
                            "h": 669,
                            "resize": "fit"
                        },
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "small": {
                            "w": 669,
                            "h": 669,
                            "resize": "fit"
                        },
                        "medium": {
                            "w": 669,
                            "h": 669,
                            "resize": "fit"
                        }
                    },
                    "features": {
                        "large": {
                            "faces": [
                                {
                                    "x": 155,
                                    "y": 60,
                                    "h": 393,
                                    "w": 393
                                }
                            ]
                        },
                        "orig": {
                            "faces": [
                                {
                                    "x": 155,
                                    "y": 60,
                                    "h": 393,
                                    "w": 393
                                }
                            ]
                        },
                        "small": {
                            "faces": [
                                {
                                    "x": 155,
                                    "y": 60,
                                    "h": 393,
                                    "w": 393
                                }
                            ]
                        },
                        "medium": {
                            "faces": [
                                {
                                    "x": 155,
                                    "y": 60,
                                    "h": 393,
                                    "w": 393
                                }
                            ]
                        }
                    },
                    "media_key": "3_1678363356456169472"
                },
                {
                    "id": 1678363358863716352,
                    "id_str": "1678363358863716352",
                    "indices": [
                        32,
                        55
                    ],
                    "media_url": "http://pbs.twimg.com/media/F0q-lSEacAAe1eI.jpg",
                    "media_url_https": "https://pbs.twimg.com/media/F0q-lSEacAAe1eI.jpg",
                    "url": "https://t.co/rteS7ZzBxu",
                    "display_url": "pic.twitter.com/rteS7ZzBxu",
                    "expanded_url": "https://twitter.com/LHCMILD/status/1678363362537918465/photo/1",
                    "type": "photo",
                    "original_info": {
                        "width": 314,
                        "height": 314,
                        "focus_rects": [
                            {
                                "x": 0,
                                "y": 45,
                                "h": 176,
                                "w": 314
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 314,
                                "w": 314
                            },
                            {
                                "x": 27,
                                "y": 0,
                                "h": 314,
                                "w": 275
                            },
                            {
                                "x": 86,
                                "y": 0,
                                "h": 314,
                                "w": 157
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 314,
                                "w": 314
                            }
                        ]
                    },
                    "sizes": {
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "small": {
                            "w": 314,
                            "h": 314,
                            "resize": "fit"
                        },
                        "medium": {
                            "w": 314,
                            "h": 314,
                            "resize": "fit"
                        },
                        "large": {
                            "w": 314,
                            "h": 314,
                            "resize": "fit"
                        }
                    },
                    "features": {
                        "small": {
                            "faces": [
                                {
                                    "x": 140,
                                    "y": 98,
                                    "h": 58,
                                    "w": 58
                                },
                                {
                                    "x": 86,
                                    "y": 24,
                                    "h": 164,
                                    "w": 164
                                }
                            ]
                        },
                        "medium": {
                            "faces": [
                                {
                                    "x": 140,
                                    "y": 98,
                                    "h": 58,
                                    "w": 58
                                },
                                {
                                    "x": 86,
                                    "y": 24,
                                    "h": 164,
                                    "w": 164
                                }
                            ]
                        },
                        "orig": {
                            "faces": [
                                {
                                    "x": 140,
                                    "y": 98,
                                    "h": 58,
                                    "w": 58
                                },
                                {
                                    "x": 86,
                                    "y": 24,
                                    "h": 164,
                                    "w": 164
                                }
                            ]
                        },
                        "large": {
                            "faces": [
                                {
                                    "x": 140,
                                    "y": 98,
                                    "h": 58,
                                    "w": 58
                                },
                                {
                                    "x": 86,
                                    "y": 24,
                                    "h": 164,
                                    "w": 164
                                }
                            ]
                        }
                    },
                    "media_key": "3_1678363358863716352"
                }
            ]
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "is_quote_status": false,
        "retweet_count": 345,
        "favorite_count": 1166,
        "conversation_id": 1678363362537918465,
        "conversation_id_str": "1678363362537918465",
        "conversation_control": {
            "policy": "community",
            "conversation_owner": {
                "screen_name": "LHCMILD"
            }
        },
        "favorited": false,
        "retweeted": false,
        "possibly_sensitive": false,
        "possibly_sensitive_editable": true,
        "limited_actions": "limited_replies",
        "lang": "qme",
        "supplemental_language": null,
        "self_thread": {
            "id": 1678363362537918465,
            "id_str": "1678363362537918465"
        }
    },
    {
        "created_at": "Mon Jul 10 04:06:48 +0000 2023",
        "id": 1678254417102123009,
        "id_str": "1678254417102123009",
        "text": "i do!!!! 🥹💐💍 https://t.co/RGguTDgfNh",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [],
            "urls": [],
            "media": [
                {
                    "id": 1678254397095280640,
                    "id_str": "1678254397095280640",
                    "indices": [
                        13,
                        36
                    ],
                    "media_url": "http://pbs.twimg.com/ext_tw_video_thumb/1678254397095280640/pu/img/7Is237yZH48vsgs6.jpg",
                    "media_url_https": "https://pbs.twimg.com/ext_tw_video_thumb/1678254397095280640/pu/img/7Is237yZH48vsgs6.jpg",
                    "url": "https://t.co/RGguTDgfNh",
                    "display_url": "pic.twitter.com/RGguTDgfNh",
                    "expanded_url": "https://twitter.com/LHCMILD/status/1678254417102123009/video/1",
                    "type": "photo",
                    "original_info": {
                        "width": 768,
                        "height": 576
                    },
                    "sizes": {
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "medium": {
                            "w": 768,
                            "h": 576,
                            "resize": "fit"
                        },
                        "large": {
                            "w": 768,
                            "h": 576,
                            "resize": "fit"
                        },
                        "small": {
                            "w": 680,
                            "h": 510,
                            "resize": "fit"
                        }
                    },
                    "features": {}
                }
            ]
        },
        "extended_entities": {
            "media": [
                {
                    "id": 1678254397095280640,
                    "id_str": "1678254397095280640",
                    "indices": [
                        13,
                        36
                    ],
                    "media_url": "http://pbs.twimg.com/ext_tw_video_thumb/1678254397095280640/pu/img/7Is237yZH48vsgs6.jpg",
                    "media_url_https": "https://pbs.twimg.com/ext_tw_video_thumb/1678254397095280640/pu/img/7Is237yZH48vsgs6.jpg",
                    "url": "https://t.co/RGguTDgfNh",
                    "display_url": "pic.twitter.com/RGguTDgfNh",
                    "expanded_url": "https://twitter.com/LHCMILD/status/1678254417102123009/video/1",
                    "type": "video",
                    "original_info": {
                        "width": 768,
                        "height": 576
                    },
                    "sizes": {
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "medium": {
                            "w": 768,
                            "h": 576,
                            "resize": "fit"
                        },
                        "large": {
                            "w": 768,
                            "h": 576,
                            "resize": "fit"
                        },
                        "small": {
                            "w": 680,
                            "h": 510,
                            "resize": "fit"
                        }
                    },
                    "video_info": {
                        "aspect_ratio": [
                            4,
                            3
                        ],
                        "duration_millis": 12097,
                        "variants": [
                            {
                                "bitrate": 256000,
                                "content_type": "video/mp4",
                                "url": "https://video.twimg.com/ext_tw_video/1678254397095280640/pu/vid/360x270/Ng5uq0BoJ7tG1AeP.mp4?tag=12"
                            },
                            {
                                "bitrate": 832000,
                                "content_type": "video/mp4",
                                "url": "https://video.twimg.com/ext_tw_video/1678254397095280640/pu/vid/480x360/gEDJFZSA_UGX0a92.mp4?tag=12"
                            },
                            {
                                "content_type": "application/x-mpegURL",
                                "url": "https://video.twimg.com/ext_tw_video/1678254397095280640/pu/pl/4KxLgNelmhsQmH68.m3u8?tag=12&container=fmp4"
                            },
                            {
                                "bitrate": 2176000,
                                "content_type": "video/mp4",
                                "url": "https://video.twimg.com/ext_tw_video/1678254397095280640/pu/vid/768x576/wSDtk6rozLsh6jlF.mp4?tag=12"
                            }
                        ]
                    },
                    "features": {},
                    "media_key": "7_1678254397095280640",
                    "additional_media_info": {
                        "monetizable": false
                    }
                }
            ]
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "is_quote_status": false,
        "retweet_count": 555,
        "favorite_count": 2059,
        "conversation_id": 1678254417102123009,
        "conversation_id_str": "1678254417102123009",
        "conversation_control": {
            "policy": "community",
            "conversation_owner": {
                "screen_name": "LHCMILD"
            }
        },
        "favorited": false,
        "retweeted": false,
        "possibly_sensitive": false,
        "possibly_sensitive_editable": true,
        "limited_actions": "limited_replies",
        "lang": "und",
        "supplemental_language": null
    },
    {
        "created_at": "Mon Jul 10 03:32:18 +0000 2023",
        "id": 1678245734330818565,
        "id_str": "1678245734330818565",
        "text": "I’M ALREADY CRYING AND I HAVEN’T EVEN HEARD IT 🥹",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [],
            "urls": []
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": 1678245731646439424,
        "in_reply_to_status_id_str": "1678245731646439424",
        "in_reply_to_user_id": 1454736746621521928,
        "in_reply_to_user_id_str": "1454736746621521928",
        "in_reply_to_screen_name": "LHCMILD",
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "is_quote_status": false,
        "retweet_count": 0,
        "favorite_count": 0,
        "conversation_id": 1678245731646439424,
        "conversation_id_str": "1678245731646439424",
        "favorited": false,
        "retweeted": false,
        "lang": "en",
        "supplemental_language": null,
        "self_thread": {
            "id": 1678245731646439424,
            "id_str": "1678245731646439424"
        }
    },
    {
        "created_at": "Mon Jul 10 03:32:17 +0000 2023",
        "id": 1678245731646439424,
        "id_str": "1678245731646439424",
        "text": "haechan bbl 🐻💬 https://t.co/bLHFCpbMpN",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [],
            "urls": [],
            "media": [
                {
                    "id": 1678245725078171648,
                    "id_str": "1678245725078171648",
                    "indices": [
                        15,
                        38
                    ],
                    "media_url": "http://pbs.twimg.com/media/F0pTmGEaMAA11Js.jpg",
                    "media_url_https": "https://pbs.twimg.com/media/F0pTmGEaMAA11Js.jpg",
                    "url": "https://t.co/bLHFCpbMpN",
                    "display_url": "pic.twitter.com/bLHFCpbMpN",
                    "expanded_url": "https://twitter.com/LHCMILD/status/1678245731646439424/photo/1",
                    "type": "photo",
                    "original_info": {
                        "width": 720,
                        "height": 844,
                        "focus_rects": [
                            {
                                "x": 0,
                                "y": 0,
                                "h": 403,
                                "w": 720
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 720,
                                "w": 720
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 821,
                                "w": 720
                            },
                            {
                                "x": 21,
                                "y": 0,
                                "h": 844,
                                "w": 422
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 844,
                                "w": 720
                            }
                        ]
                    },
                    "sizes": {
                        "medium": {
                            "w": 720,
                            "h": 844,
                            "resize": "fit"
                        },
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "small": {
                            "w": 580,
                            "h": 680,
                            "resize": "fit"
                        },
                        "large": {
                            "w": 720,
                            "h": 844,
                            "resize": "fit"
                        }
                    },
                    "features": {
                        "medium": {
                            "faces": [
                                {
                                    "x": 32,
                                    "y": 26,
                                    "h": 54,
                                    "w": 54
                                },
                                {
                                    "x": 31,
                                    "y": 293,
                                    "h": 56,
                                    "w": 56
                                },
                                {
                                    "x": 31,
                                    "y": 527,
                                    "h": 55,
                                    "w": 55
                                },
                                {
                                    "x": 113,
                                    "y": 135,
                                    "h": 104,
                                    "w": 104
                                }
                            ]
                        },
                        "small": {
                            "faces": [
                                {
                                    "x": 25,
                                    "y": 20,
                                    "h": 43,
                                    "w": 43
                                },
                                {
                                    "x": 24,
                                    "y": 236,
                                    "h": 45,
                                    "w": 45
                                },
                                {
                                    "x": 24,
                                    "y": 424,
                                    "h": 44,
                                    "w": 44
                                },
                                {
                                    "x": 91,
                                    "y": 108,
                                    "h": 83,
                                    "w": 83
                                }
                            ]
                        },
                        "orig": {
                            "faces": [
                                {
                                    "x": 32,
                                    "y": 26,
                                    "h": 54,
                                    "w": 54
                                },
                                {
                                    "x": 31,
                                    "y": 293,
                                    "h": 56,
                                    "w": 56
                                },
                                {
                                    "x": 31,
                                    "y": 527,
                                    "h": 55,
                                    "w": 55
                                },
                                {
                                    "x": 113,
                                    "y": 135,
                                    "h": 104,
                                    "w": 104
                                }
                            ]
                        },
                        "large": {
                            "faces": [
                                {
                                    "x": 32,
                                    "y": 26,
                                    "h": 54,
                                    "w": 54
                                },
                                {
                                    "x": 31,
                                    "y": 293,
                                    "h": 56,
                                    "w": 56
                                },
                                {
                                    "x": 31,
                                    "y": 527,
                                    "h": 55,
                                    "w": 55
                                },
                                {
                                    "x": 113,
                                    "y": 135,
                                    "h": 104,
                                    "w": 104
                                }
                            ]
                        }
                    }
                }
            ]
        },
        "extended_entities": {
            "media": [
                {
                    "id": 1678245725078171648,
                    "id_str": "1678245725078171648",
                    "indices": [
                        15,
                        38
                    ],
                    "media_url": "http://pbs.twimg.com/media/F0pTmGEaMAA11Js.jpg",
                    "media_url_https": "https://pbs.twimg.com/media/F0pTmGEaMAA11Js.jpg",
                    "url": "https://t.co/bLHFCpbMpN",
                    "display_url": "pic.twitter.com/bLHFCpbMpN",
                    "expanded_url": "https://twitter.com/LHCMILD/status/1678245731646439424/photo/1",
                    "type": "photo",
                    "original_info": {
                        "width": 720,
                        "height": 844,
                        "focus_rects": [
                            {
                                "x": 0,
                                "y": 0,
                                "h": 403,
                                "w": 720
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 720,
                                "w": 720
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 821,
                                "w": 720
                            },
                            {
                                "x": 21,
                                "y": 0,
                                "h": 844,
                                "w": 422
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 844,
                                "w": 720
                            }
                        ]
                    },
                    "sizes": {
                        "medium": {
                            "w": 720,
                            "h": 844,
                            "resize": "fit"
                        },
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "small": {
                            "w": 580,
                            "h": 680,
                            "resize": "fit"
                        },
                        "large": {
                            "w": 720,
                            "h": 844,
                            "resize": "fit"
                        }
                    },
                    "features": {
                        "medium": {
                            "faces": [
                                {
                                    "x": 32,
                                    "y": 26,
                                    "h": 54,
                                    "w": 54
                                },
                                {
                                    "x": 31,
                                    "y": 293,
                                    "h": 56,
                                    "w": 56
                                },
                                {
                                    "x": 31,
                                    "y": 527,
                                    "h": 55,
                                    "w": 55
                                },
                                {
                                    "x": 113,
                                    "y": 135,
                                    "h": 104,
                                    "w": 104
                                }
                            ]
                        },
                        "small": {
                            "faces": [
                                {
                                    "x": 25,
                                    "y": 20,
                                    "h": 43,
                                    "w": 43
                                },
                                {
                                    "x": 24,
                                    "y": 236,
                                    "h": 45,
                                    "w": 45
                                },
                                {
                                    "x": 24,
                                    "y": 424,
                                    "h": 44,
                                    "w": 44
                                },
                                {
                                    "x": 91,
                                    "y": 108,
                                    "h": 83,
                                    "w": 83
                                }
                            ]
                        },
                        "orig": {
                            "faces": [
                                {
                                    "x": 32,
                                    "y": 26,
                                    "h": 54,
                                    "w": 54
                                },
                                {
                                    "x": 31,
                                    "y": 293,
                                    "h": 56,
                                    "w": 56
                                },
                                {
                                    "x": 31,
                                    "y": 527,
                                    "h": 55,
                                    "w": 55
                                },
                                {
                                    "x": 113,
                                    "y": 135,
                                    "h": 104,
                                    "w": 104
                                }
                            ]
                        },
                        "large": {
                            "faces": [
                                {
                                    "x": 32,
                                    "y": 26,
                                    "h": 54,
                                    "w": 54
                                },
                                {
                                    "x": 31,
                                    "y": 293,
                                    "h": 56,
                                    "w": 56
                                },
                                {
                                    "x": 31,
                                    "y": 527,
                                    "h": 55,
                                    "w": 55
                                },
                                {
                                    "x": 113,
                                    "y": 135,
                                    "h": 104,
                                    "w": 104
                                }
                            ]
                        }
                    },
                    "media_key": "3_1678245725078171648"
                }
            ]
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "is_quote_status": false,
        "retweet_count": 4,
        "favorite_count": 46,
        "conversation_id": 1678245731646439424,
        "conversation_id_str": "1678245731646439424",
        "favorited": false,
        "retweeted": false,
        "possibly_sensitive": false,
        "possibly_sensitive_editable": true,
        "lang": "cy",
        "supplemental_language": null,
        "self_thread": {
            "id": 1678245731646439424,
            "id_str": "1678245731646439424"
        }
    },
    {
        "created_at": "Mon Jul 10 01:05:06 +0000 2023",
        "id": 1678208693471518720,
        "id_str": "1678208693471518720",
        "text": "RT @NCTDREAMCENTER: 230710 NCT DREAM The 3rd Album 'ISTJ' Bside Track\n\n- Like We Just Met: an R&amp;B ballad song with acoustic guitar sound. T…",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [
                {
                    "screen_name": "NCTDREAMCENTER",
                    "name": "NCT DREAM CENTER",
                    "id": 956135887904976896,
                    "id_str": "956135887904976896",
                    "indices": [
                        3,
                        18
                    ]
                }
            ],
            "urls": []
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "retweeted_status": {
            "created_at": "Mon Jul 10 00:09:33 +0000 2023",
            "id": 1678194712136613888,
            "id_str": "1678194712136613888",
            "text": "230710 NCT DREAM The 3rd Album 'ISTJ' Bside Track\n\n- Like We Just Met: an R&amp;B ballad song with acoustic guitar soun… https://t.co/uDbFYzdJas",
            "truncated": true,
            "entities": {
                "hashtags": [],
                "symbols": [],
                "user_mentions": [],
                "urls": [
                    {
                        "url": "https://t.co/uDbFYzdJas",
                        "expanded_url": "https://twitter.com/i/web/status/1678194712136613888",
                        "display_url": "twitter.com/i/web/status/1…",
                        "indices": [
                            121,
                            144
                        ]
                    }
                ]
            },
            "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
            "in_reply_to_status_id": null,
            "in_reply_to_status_id_str": null,
            "in_reply_to_user_id": null,
            "in_reply_to_user_id_str": null,
            "in_reply_to_screen_name": null,
            "user": {
                "id": 956135887904976896,
                "id_str": "956135887904976896",
                "name": "NCT DREAM CENTER",
                "screen_name": "NCTDREAMCENTER",
                "location": "",
                "description": "Global Fanbase & Update account for NCT DREAM (@NCTsmtown_DREAM) | Pre-save 'ISTJ' album now!",
                "url": "https://t.co/PA8xXHUWkW",
                "entities": {
                    "url": {
                        "urls": [
                            {
                                "url": "https://t.co/PA8xXHUWkW",
                                "expanded_url": "http://nctdream.lnk.to/ISTJ",
                                "display_url": "nctdream.lnk.to/ISTJ",
                                "indices": [
                                    0,
                                    23
                                ]
                            }
                        ]
                    },
                    "description": {
                        "urls": []
                    }
                },
                "protected": false,
                "followers_count": 666421,
                "fast_followers_count": 0,
                "normal_followers_count": 666421,
                "friends_count": 47,
                "listed_count": 5450,
                "created_at": "Wed Jan 24 12:05:34 +0000 2018",
                "favourites_count": 37,
                "utc_offset": null,
                "time_zone": null,
                "geo_enabled": true,
                "verified": false,
                "statuses_count": 36341,
                "media_count": 20408,
                "lang": null,
                "contributors_enabled": false,
                "is_translator": false,
                "is_translation_enabled": false,
                "profile_background_color": "000000",
                "profile_background_image_url": "http://abs.twimg.com/images/themes/theme1/bg.png",
                "profile_background_image_url_https": "https://abs.twimg.com/images/themes/theme1/bg.png",
                "profile_background_tile": false,
                "profile_image_url": "http://pbs.twimg.com/profile_images/1509552072961961987/CiR380rt_normal.jpg",
                "profile_image_url_https": "https://pbs.twimg.com/profile_images/1509552072961961987/CiR380rt_normal.jpg",
                "profile_banner_url": "https://pbs.twimg.com/profile_banners/956135887904976896/1673750671",
                "profile_link_color": "424242",
                "profile_sidebar_border_color": "000000",
                "profile_sidebar_fill_color": "000000",
                "profile_text_color": "000000",
                "profile_use_background_image": false,
                "has_extended_profile": true,
                "default_profile": false,
                "default_profile_image": false,
                "pinned_tweet_ids": [
                    1677334349757452288
                ],
                "pinned_tweet_ids_str": [
                    "1677334349757452288"
                ],
                "has_custom_timelines": true,
                "can_media_tag": false,
                "followed_by": false,
                "following": false,
                "follow_request_sent": false,
                "notifications": false,
                "advertiser_account_type": "promotable_user",
                "advertiser_account_service_levels": [
                    "smb"
                ],
                "analytics_type": "disabled",
                "business_profile_state": "none",
                "translator_type": "none",
                "withheld_in_countries": [],
                "require_some_consent": false
            },
            "geo": null,
            "coordinates": null,
            "place": null,
            "contributors": null,
            "is_quote_status": false,
            "retweet_count": 3208,
            "favorite_count": 7469,
            "conversation_id": 1678194712136613888,
            "conversation_id_str": "1678194712136613888",
            "favorited": false,
            "retweeted": false,
            "possibly_sensitive": false,
            "possibly_sensitive_editable": true,
            "lang": "en",
            "supplemental_language": null
        },
        "is_quote_status": false,
        "retweet_count": 3208,
        "favorite_count": 0,
        "conversation_id": 1678208693471518720,
        "conversation_id_str": "1678208693471518720",
        "favorited": false,
        "retweeted": false,
        "lang": "en",
        "supplemental_language": null
    },
    {
        "created_at": "Mon Jul 10 00:07:29 +0000 2023",
        "id": 1678194191279505410,
        "id_str": "1678194191279505410",
        "text": "love haechan so much &lt;3 https://t.co/oARyMbvkF4",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [],
            "urls": [],
            "media": [
                {
                    "id": 1678194176830365696,
                    "id_str": "1678194176830365696",
                    "indices": [
                        27,
                        50
                    ],
                    "media_url": "http://pbs.twimg.com/media/F0oktl4aYAAJuLV.jpg",
                    "media_url_https": "https://pbs.twimg.com/media/F0oktl4aYAAJuLV.jpg",
                    "url": "https://t.co/oARyMbvkF4",
                    "display_url": "pic.twitter.com/oARyMbvkF4",
                    "expanded_url": "https://twitter.com/LHCMILD/status/1678194191279505410/photo/1",
                    "type": "photo",
                    "original_info": {
                        "width": 681,
                        "height": 383,
                        "focus_rects": [
                            {
                                "x": 0,
                                "y": 0,
                                "h": 381,
                                "w": 681
                            },
                            {
                                "x": 98,
                                "y": 0,
                                "h": 383,
                                "w": 383
                            },
                            {
                                "x": 121,
                                "y": 0,
                                "h": 383,
                                "w": 336
                            },
                            {
                                "x": 193,
                                "y": 0,
                                "h": 383,
                                "w": 192
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 383,
                                "w": 681
                            }
                        ]
                    },
                    "sizes": {
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "medium": {
                            "w": 681,
                            "h": 383,
                            "resize": "fit"
                        },
                        "small": {
                            "w": 680,
                            "h": 382,
                            "resize": "fit"
                        },
                        "large": {
                            "w": 681,
                            "h": 383,
                            "resize": "fit"
                        }
                    },
                    "features": {
                        "medium": {
                            "faces": []
                        },
                        "orig": {
                            "faces": []
                        },
                        "small": {
                            "faces": []
                        },
                        "large": {
                            "faces": []
                        }
                    }
                }
            ]
        },
        "extended_entities": {
            "media": [
                {
                    "id": 1678194176830365696,
                    "id_str": "1678194176830365696",
                    "indices": [
                        27,
                        50
                    ],
                    "media_url": "http://pbs.twimg.com/media/F0oktl4aYAAJuLV.jpg",
                    "media_url_https": "https://pbs.twimg.com/media/F0oktl4aYAAJuLV.jpg",
                    "url": "https://t.co/oARyMbvkF4",
                    "display_url": "pic.twitter.com/oARyMbvkF4",
                    "expanded_url": "https://twitter.com/LHCMILD/status/1678194191279505410/photo/1",
                    "type": "photo",
                    "original_info": {
                        "width": 681,
                        "height": 383,
                        "focus_rects": [
                            {
                                "x": 0,
                                "y": 0,
                                "h": 381,
                                "w": 681
                            },
                            {
                                "x": 98,
                                "y": 0,
                                "h": 383,
                                "w": 383
                            },
                            {
                                "x": 121,
                                "y": 0,
                                "h": 383,
                                "w": 336
                            },
                            {
                                "x": 193,
                                "y": 0,
                                "h": 383,
                                "w": 192
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 383,
                                "w": 681
                            }
                        ]
                    },
                    "sizes": {
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "medium": {
                            "w": 681,
                            "h": 383,
                            "resize": "fit"
                        },
                        "small": {
                            "w": 680,
                            "h": 382,
                            "resize": "fit"
                        },
                        "large": {
                            "w": 681,
                            "h": 383,
                            "resize": "fit"
                        }
                    },
                    "features": {
                        "medium": {
                            "faces": []
                        },
                        "orig": {
                            "faces": []
                        },
                        "small": {
                            "faces": []
                        },
                        "large": {
                            "faces": []
                        }
                    },
                    "media_key": "3_1678194176830365696"
                },
                {
                    "id": 1678194180735238144,
                    "id_str": "1678194180735238144",
                    "indices": [
                        27,
                        50
                    ],
                    "media_url": "http://pbs.twimg.com/media/F0okt0baAAAmzmC.jpg",
                    "media_url_https": "https://pbs.twimg.com/media/F0okt0baAAAmzmC.jpg",
                    "url": "https://t.co/oARyMbvkF4",
                    "display_url": "pic.twitter.com/oARyMbvkF4",
                    "expanded_url": "https://twitter.com/LHCMILD/status/1678194191279505410/photo/1",
                    "type": "photo",
                    "original_info": {
                        "width": 1024,
                        "height": 576,
                        "focus_rects": [
                            {
                                "x": 0,
                                "y": 0,
                                "h": 573,
                                "w": 1024
                            },
                            {
                                "x": 147,
                                "y": 0,
                                "h": 576,
                                "w": 576
                            },
                            {
                                "x": 183,
                                "y": 0,
                                "h": 576,
                                "w": 505
                            },
                            {
                                "x": 291,
                                "y": 0,
                                "h": 576,
                                "w": 288
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 576,
                                "w": 1024
                            }
                        ]
                    },
                    "sizes": {
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "small": {
                            "w": 680,
                            "h": 383,
                            "resize": "fit"
                        },
                        "medium": {
                            "w": 1024,
                            "h": 576,
                            "resize": "fit"
                        },
                        "large": {
                            "w": 1024,
                            "h": 576,
                            "resize": "fit"
                        }
                    },
                    "features": {
                        "small": {
                            "faces": []
                        },
                        "orig": {
                            "faces": []
                        },
                        "medium": {
                            "faces": []
                        },
                        "large": {
                            "faces": []
                        }
                    },
                    "media_key": "3_1678194180735238144"
                },
                {
                    "id": 1678194184338182145,
                    "id_str": "1678194184338182145",
                    "indices": [
                        27,
                        50
                    ],
                    "media_url": "http://pbs.twimg.com/media/F0okuB2akAED-gQ.jpg",
                    "media_url_https": "https://pbs.twimg.com/media/F0okuB2akAED-gQ.jpg",
                    "url": "https://t.co/oARyMbvkF4",
                    "display_url": "pic.twitter.com/oARyMbvkF4",
                    "expanded_url": "https://twitter.com/LHCMILD/status/1678194191279505410/photo/1",
                    "type": "photo",
                    "original_info": {
                        "width": 664,
                        "height": 374,
                        "focus_rects": [
                            {
                                "x": 0,
                                "y": 0,
                                "h": 372,
                                "w": 664
                            },
                            {
                                "x": 161,
                                "y": 0,
                                "h": 374,
                                "w": 374
                            },
                            {
                                "x": 184,
                                "y": 0,
                                "h": 374,
                                "w": 328
                            },
                            {
                                "x": 255,
                                "y": 0,
                                "h": 374,
                                "w": 187
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 374,
                                "w": 664
                            }
                        ]
                    },
                    "sizes": {
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "medium": {
                            "w": 664,
                            "h": 374,
                            "resize": "fit"
                        },
                        "large": {
                            "w": 664,
                            "h": 374,
                            "resize": "fit"
                        },
                        "small": {
                            "w": 664,
                            "h": 374,
                            "resize": "fit"
                        }
                    },
                    "features": {
                        "medium": {
                            "faces": []
                        },
                        "large": {
                            "faces": []
                        },
                        "orig": {
                            "faces": []
                        },
                        "small": {
                            "faces": []
                        }
                    },
                    "media_key": "3_1678194184338182145"
                },
                {
                    "id": 1678194188620546048,
                    "id_str": "1678194188620546048",
                    "indices": [
                        27,
                        50
                    ],
                    "media_url": "http://pbs.twimg.com/media/F0okuRzaQAAnoBh.jpg",
                    "media_url_https": "https://pbs.twimg.com/media/F0okuRzaQAAnoBh.jpg",
                    "url": "https://t.co/oARyMbvkF4",
                    "display_url": "pic.twitter.com/oARyMbvkF4",
                    "expanded_url": "https://twitter.com/LHCMILD/status/1678194191279505410/photo/1",
                    "type": "photo",
                    "original_info": {
                        "width": 1024,
                        "height": 575,
                        "focus_rects": [
                            {
                                "x": 0,
                                "y": 0,
                                "h": 573,
                                "w": 1024
                            },
                            {
                                "x": 45,
                                "y": 0,
                                "h": 575,
                                "w": 575
                            },
                            {
                                "x": 80,
                                "y": 0,
                                "h": 575,
                                "w": 504
                            },
                            {
                                "x": 188,
                                "y": 0,
                                "h": 575,
                                "w": 288
                            },
                            {
                                "x": 0,
                                "y": 0,
                                "h": 575,
                                "w": 1024
                            }
                        ]
                    },
                    "sizes": {
                        "medium": {
                            "w": 1024,
                            "h": 575,
                            "resize": "fit"
                        },
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "small": {
                            "w": 680,
                            "h": 382,
                            "resize": "fit"
                        },
                        "large": {
                            "w": 1024,
                            "h": 575,
                            "resize": "fit"
                        }
                    },
                    "features": {
                        "medium": {
                            "faces": []
                        },
                        "orig": {
                            "faces": []
                        },
                        "small": {
                            "faces": []
                        },
                        "large": {
                            "faces": []
                        }
                    },
                    "media_key": "3_1678194188620546048"
                }
            ]
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "is_quote_status": false,
        "retweet_count": 1035,
        "favorite_count": 3298,
        "conversation_id": 1678194191279505410,
        "conversation_id_str": "1678194191279505410",
        "conversation_control": {
            "policy": "community",
            "conversation_owner": {
                "screen_name": "LHCMILD"
            }
        },
        "favorited": false,
        "retweeted": false,
        "possibly_sensitive": false,
        "possibly_sensitive_editable": true,
        "limited_actions": "limited_replies",
        "lang": "en",
        "supplemental_language": null
    },
    {
        "created_at": "Sun Jul 09 23:34:14 +0000 2023",
        "id": 1678185824431513600,
        "id_str": "1678185824431513600",
        "text": "RT @haebeats: am i seeing this right? haechan is top 2 most searched idol members by teenagers (12-18) in the first half of 2023?! MY GODDD…",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [
                {
                    "screen_name": "haebeats",
                    "name": "🍩 here comes the sun",
                    "id": 729608772272807936,
                    "id_str": "729608772272807936",
                    "indices": [
                        3,
                        12
                    ]
                }
            ],
            "urls": []
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "retweeted_status": {
            "created_at": "Sun Jul 09 18:02:02 +0000 2023",
            "id": 1678102222511702016,
            "id_str": "1678102222511702016",
            "text": "am i seeing this right? haechan is top 2 most searched idol members by teenagers (12-18) in the first half of 2023?… https://t.co/3Gc3w1bXGG",
            "truncated": true,
            "entities": {
                "hashtags": [],
                "symbols": [],
                "user_mentions": [],
                "urls": [
                    {
                        "url": "https://t.co/3Gc3w1bXGG",
                        "expanded_url": "https://twitter.com/i/web/status/1678102222511702016",
                        "display_url": "twitter.com/i/web/status/1…",
                        "indices": [
                            117,
                            140
                        ]
                    }
                ]
            },
            "source": "<a href=\"http://twitter.com/download/iphone\" rel=\"nofollow\">Twitter for iPhone</a>",
            "in_reply_to_status_id": null,
            "in_reply_to_status_id_str": null,
            "in_reply_to_user_id": null,
            "in_reply_to_user_id_str": null,
            "in_reply_to_screen_name": null,
            "user": {
                "id": 729608772272807936,
                "id_str": "729608772272807936",
                "name": "🍩 here comes the sun",
                "screen_name": "haebeats",
                "location": "20+",
                "description": "haechan = happy",
                "url": "https://t.co/aiwLVGeoEj",
                "entities": {
                    "url": {
                        "urls": [
                            {
                                "url": "https://t.co/aiwLVGeoEj",
                                "expanded_url": "https://curiouscat.live/haebeats",
                                "display_url": "curiouscat.live/haebeats",
                                "indices": [
                                    0,
                                    23
                                ]
                            }
                        ]
                    },
                    "description": {
                        "urls": []
                    }
                },
                "protected": false,
                "followers_count": 1115,
                "fast_followers_count": 0,
                "normal_followers_count": 1115,
                "friends_count": 173,
                "listed_count": 20,
                "created_at": "Mon May 09 09:47:41 +0000 2016",
                "favourites_count": 78148,
                "utc_offset": null,
                "time_zone": null,
                "geo_enabled": false,
                "verified": false,
                "statuses_count": 52758,
                "media_count": 12154,
                "lang": null,
                "contributors_enabled": false,
                "is_translator": false,
                "is_translation_enabled": false,
                "profile_background_color": "000000",
                "profile_background_image_url": "http://abs.twimg.com/images/themes/theme1/bg.png",
                "profile_background_image_url_https": "https://abs.twimg.com/images/themes/theme1/bg.png",
                "profile_background_tile": false,
                "profile_image_url": "http://pbs.twimg.com/profile_images/1625104112269529088/2Hcf-PnE_normal.jpg",
                "profile_image_url_https": "https://pbs.twimg.com/profile_images/1625104112269529088/2Hcf-PnE_normal.jpg",
                "profile_banner_url": "https://pbs.twimg.com/profile_banners/729608772272807936/1686832068",
                "profile_link_color": "F58EA8",
                "profile_sidebar_border_color": "000000",
                "profile_sidebar_fill_color": "000000",
                "profile_text_color": "000000",
                "profile_use_background_image": false,
                "has_extended_profile": true,
                "default_profile": false,
                "default_profile_image": false,
                "pinned_tweet_ids": [
                    1500616466017976320
                ],
                "pinned_tweet_ids_str": [
                    "1500616466017976320"
                ],
                "has_custom_timelines": true,
                "can_media_tag": false,
                "followed_by": false,
                "following": false,
                "follow_request_sent": false,
                "notifications": false,
                "advertiser_account_type": "none",
                "advertiser_account_service_levels": [],
                "analytics_type": "enabled",
                "business_profile_state": "none",
                "translator_type": "none",
                "withheld_in_countries": [],
                "require_some_consent": false
            },
            "geo": null,
            "coordinates": null,
            "place": null,
            "contributors": null,
            "is_quote_status": false,
            "retweet_count": 612,
            "favorite_count": 2663,
            "conversation_id": 1678102222511702016,
            "conversation_id_str": "1678102222511702016",
            "favorited": false,
            "retweeted": false,
            "possibly_sensitive": false,
            "possibly_sensitive_editable": true,
            "lang": "en",
            "supplemental_language": null,
            "self_thread": {
                "id": 1678102222511702016,
                "id_str": "1678102222511702016"
            }
        },
        "is_quote_status": false,
        "retweet_count": 612,
        "favorite_count": 0,
        "conversation_id": 1678185824431513600,
        "conversation_id_str": "1678185824431513600",
        "favorited": false,
        "retweeted": false,
        "lang": "en",
        "supplemental_language": null
    },
    {
        "created_at": "Sun Jul 09 23:27:51 +0000 2023",
        "id": 1678184220093456384,
        "id_str": "1678184220093456384",
        "text": "RT @noxx_nox: 심통나가지구 입술 삐쭉 하는거 캐귀여움... https://t.co/kR9rhKes2O",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [
                {
                    "screen_name": "noxx_nox",
                    "name": "Noxx",
                    "id": 783297794958168064,
                    "id_str": "783297794958168064",
                    "indices": [
                        3,
                        12
                    ]
                }
            ],
            "urls": [
                {
                    "url": "https://t.co/kR9rhKes2O",
                    "expanded_url": "https://twitter.com/noxx_nox/status/1678097400081309703/photo/1",
                    "display_url": "pic.twitter.com/kR9rhKes2O",
                    "indices": [
                        39,
                        62
                    ]
                }
            ]
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "retweeted_status": {
            "created_at": "Sun Jul 09 17:42:52 +0000 2023",
            "id": 1678097400081309703,
            "id_str": "1678097400081309703",
            "text": "심통나가지구 입술 삐쭉 하는거 캐귀여움... https://t.co/kR9rhKes2O",
            "truncated": false,
            "entities": {
                "hashtags": [],
                "symbols": [],
                "user_mentions": [],
                "urls": [
                    {
                        "url": "https://t.co/kR9rhKes2O",
                        "expanded_url": "https://twitter.com/noxx_nox/status/1678097400081309703/photo/1",
                        "display_url": "pic.twitter.com/kR9rhKes2O",
                        "indices": [
                            25,
                            48
                        ]
                    }
                ]
            },
            "source": "<a href=\"http://twitter.com/download/iphone\" rel=\"nofollow\">Twitter for iPhone</a>",
            "in_reply_to_status_id": null,
            "in_reply_to_status_id_str": null,
            "in_reply_to_user_id": null,
            "in_reply_to_user_id_str": null,
            "in_reply_to_screen_name": null,
            "user": {
                "id": 783297794958168064,
                "id_str": "783297794958168064",
                "name": "Noxx",
                "screen_name": "noxx_nox",
                "location": "",
                "description": "난 이 삶과의 사랑에 빠진 거니까",
                "url": "https://t.co/io5ia8M9rY",
                "entities": {
                    "url": {
                        "urls": [
                            {
                                "url": "https://t.co/io5ia8M9rY",
                                "expanded_url": "https://asked.kr/cocofxllsxn",
                                "display_url": "asked.kr/cocofxllsxn",
                                "indices": [
                                    0,
                                    23
                                ]
                            }
                        ]
                    },
                    "description": {
                        "urls": []
                    }
                },
                "protected": false,
                "followers_count": 67240,
                "fast_followers_count": 0,
                "normal_followers_count": 67240,
                "friends_count": 126,
                "listed_count": 853,
                "created_at": "Tue Oct 04 13:28:42 +0000 2016",
                "favourites_count": 12152,
                "utc_offset": null,
                "time_zone": null,
                "geo_enabled": false,
                "verified": false,
                "statuses_count": 34282,
                "media_count": 20821,
                "lang": null,
                "contributors_enabled": false,
                "is_translator": false,
                "is_translation_enabled": false,
                "profile_background_color": "F5F8FA",
                "profile_background_image_url": null,
                "profile_background_image_url_https": null,
                "profile_background_tile": false,
                "profile_image_url": "http://pbs.twimg.com/profile_images/1480179819212308483/787uWraI_normal.jpg",
                "profile_image_url_https": "https://pbs.twimg.com/profile_images/1480179819212308483/787uWraI_normal.jpg",
                "profile_banner_url": "https://pbs.twimg.com/profile_banners/783297794958168064/1672934054",
                "profile_link_color": "1DA1F2",
                "profile_sidebar_border_color": "C0DEED",
                "profile_sidebar_fill_color": "DDEEF6",
                "profile_text_color": "333333",
                "profile_use_background_image": true,
                "has_extended_profile": true,
                "default_profile": true,
                "default_profile_image": false,
                "pinned_tweet_ids": [
                    1485778876936908804
                ],
                "pinned_tweet_ids_str": [
                    "1485778876936908804"
                ],
                "has_custom_timelines": true,
                "can_media_tag": false,
                "followed_by": false,
                "following": false,
                "follow_request_sent": false,
                "notifications": false,
                "advertiser_account_type": "promotable_user",
                "advertiser_account_service_levels": [
                    "analytics"
                ],
                "analytics_type": "enabled",
                "business_profile_state": "none",
                "translator_type": "none",
                "withheld_in_countries": [],
                "require_some_consent": false
            },
            "geo": null,
            "coordinates": null,
            "place": null,
            "contributors": null,
            "is_quote_status": false,
            "retweet_count": 2156,
            "favorite_count": 6605,
            "conversation_id": 1678097400081309703,
            "conversation_id_str": "1678097400081309703",
            "favorited": false,
            "retweeted": false,
            "possibly_sensitive": false,
            "possibly_sensitive_editable": true,
            "lang": "ko",
            "supplemental_language": null
        },
        "is_quote_status": false,
        "retweet_count": 2156,
        "favorite_count": 0,
        "conversation_id": 1678184220093456384,
        "conversation_id_str": "1678184220093456384",
        "favorited": false,
        "retweeted": false,
        "possibly_sensitive": false,
        "possibly_sensitive_editable": true,
        "lang": "ko",
        "supplemental_language": null
    },
    {
        "created_at": "Sun Jul 09 23:26:32 +0000 2023",
        "id": 1678183885136437249,
        "id_str": "1678183885136437249",
        "text": "cutie haechan bread smile :]🥺🫶\nhttps://t.co/cqU10bkU4A",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [],
            "urls": [],
            "media": [
                {
                    "id": 1678117205505085440,
                    "id_str": "1678117205505085440",
                    "indices": [
                        31,
                        54
                    ],
                    "media_url": "http://pbs.twimg.com/ext_tw_video_thumb/1678117205505085440/pu/img/EBrIIVOL8D_JZSWt.jpg",
                    "media_url_https": "https://pbs.twimg.com/ext_tw_video_thumb/1678117205505085440/pu/img/EBrIIVOL8D_JZSWt.jpg",
                    "url": "https://t.co/cqU10bkU4A",
                    "display_url": "pic.twitter.com/cqU10bkU4A",
                    "expanded_url": "https://twitter.com/haechanprints/status/1678117257116000256/video/1",
                    "type": "photo",
                    "original_info": {
                        "width": 720,
                        "height": 720
                    },
                    "sizes": {
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "small": {
                            "w": 680,
                            "h": 680,
                            "resize": "fit"
                        },
                        "medium": {
                            "w": 720,
                            "h": 720,
                            "resize": "fit"
                        },
                        "large": {
                            "w": 720,
                            "h": 720,
                            "resize": "fit"
                        }
                    },
                    "source_status_id": 1678117257116000256,
                    "source_status_id_str": "1678117257116000256",
                    "source_user_id": 1385532826762706947,
                    "source_user_id_str": "1385532826762706947",
                    "features": {}
                }
            ]
        },
        "extended_entities": {
            "media": [
                {
                    "id": 1678117205505085440,
                    "id_str": "1678117205505085440",
                    "indices": [
                        31,
                        54
                    ],
                    "media_url": "http://pbs.twimg.com/ext_tw_video_thumb/1678117205505085440/pu/img/EBrIIVOL8D_JZSWt.jpg",
                    "media_url_https": "https://pbs.twimg.com/ext_tw_video_thumb/1678117205505085440/pu/img/EBrIIVOL8D_JZSWt.jpg",
                    "url": "https://t.co/cqU10bkU4A",
                    "display_url": "pic.twitter.com/cqU10bkU4A",
                    "expanded_url": "https://twitter.com/haechanprints/status/1678117257116000256/video/1",
                    "type": "video",
                    "original_info": {
                        "width": 720,
                        "height": 720
                    },
                    "sizes": {
                        "thumb": {
                            "w": 150,
                            "h": 150,
                            "resize": "crop"
                        },
                        "small": {
                            "w": 680,
                            "h": 680,
                            "resize": "fit"
                        },
                        "medium": {
                            "w": 720,
                            "h": 720,
                            "resize": "fit"
                        },
                        "large": {
                            "w": 720,
                            "h": 720,
                            "resize": "fit"
                        }
                    },
                    "source_status_id": 1678117257116000256,
                    "source_status_id_str": "1678117257116000256",
                    "source_user_id": 1385532826762706947,
                    "source_user_id_str": "1385532826762706947",
                    "video_info": {
                        "aspect_ratio": [
                            1,
                            1
                        ],
                        "duration_millis": 1933,
                        "variants": [
                            {
                                "bitrate": 832000,
                                "content_type": "video/mp4",
                                "url": "https://video.twimg.com/ext_tw_video/1678117205505085440/pu/vid/540x540/cfRzaMm3WTB7J65R.mp4?tag=12"
                            },
                            {
                                "bitrate": 432000,
                                "content_type": "video/mp4",
                                "url": "https://video.twimg.com/ext_tw_video/1678117205505085440/pu/vid/320x320/JmPkSLnmd9y4j-yG.mp4?tag=12"
                            },
                            {
                                "bitrate": 1280000,
                                "content_type": "video/mp4",
                                "url": "https://video.twimg.com/ext_tw_video/1678117205505085440/pu/vid/720x720/tyrZdd23Uj3GmY1p.mp4?tag=12"
                            },
                            {
                                "content_type": "application/x-mpegURL",
                                "url": "https://video.twimg.com/ext_tw_video/1678117205505085440/pu/pl/FNh9_iwRlwRGG49D.m3u8?tag=12&container=fmp4"
                            }
                        ]
                    },
                    "features": {},
                    "media_key": "7_1678117205505085440",
                    "additional_media_info": {
                        "monetizable": false,
                        "source_user": {
                            "id": 1385532826762706947,
                            "id_str": "1385532826762706947",
                            "name": "da ᵔⰙᵔ",
                            "screen_name": "haechanprints",
                            "location": "ncity ",
                            "description": "|ᴥ•ʔっ for #haechan | edits: @haechan_films she/her • fan account • (slow update)",
                            "url": "https://t.co/rAdZIsHpvM",
                            "entities": {
                                "url": {
                                    "urls": [
                                        {
                                            "url": "https://t.co/rAdZIsHpvM",
                                            "expanded_url": "http://instagram.com/haechanahceah",
                                            "display_url": "instagram.com/haechanahceah",
                                            "indices": [
                                                0,
                                                23
                                            ]
                                        }
                                    ]
                                },
                                "description": {
                                    "urls": []
                                }
                            },
                            "protected": false,
                            "followers_count": 29686,
                            "fast_followers_count": 0,
                            "normal_followers_count": 29686,
                            "friends_count": 99,
                            "listed_count": 511,
                            "created_at": "Fri Apr 23 09:56:39 +0000 2021",
                            "favourites_count": 92072,
                            "utc_offset": null,
                            "time_zone": null,
                            "geo_enabled": false,
                            "verified": false,
                            "statuses_count": 26664,
                            "media_count": 12123,
                            "lang": null,
                            "contributors_enabled": false,
                            "is_translator": false,
                            "is_translation_enabled": false,
                            "profile_background_color": "F5F8FA",
                            "profile_background_image_url": null,
                            "profile_background_image_url_https": null,
                            "profile_background_tile": false,
                            "profile_image_url": "http://pbs.twimg.com/profile_images/1647152417241448448/vQ3JuOMA_normal.jpg",
                            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1647152417241448448/vQ3JuOMA_normal.jpg",
                            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1385532826762706947/1681510672",
                            "profile_link_color": "1DA1F2",
                            "profile_sidebar_border_color": "C0DEED",
                            "profile_sidebar_fill_color": "DDEEF6",
                            "profile_text_color": "333333",
                            "profile_use_background_image": true,
                            "has_extended_profile": true,
                            "default_profile": true,
                            "default_profile_image": false,
                            "pinned_tweet_ids": [
                                1630529676593758208
                            ],
                            "pinned_tweet_ids_str": [
                                "1630529676593758208"
                            ],
                            "has_custom_timelines": true,
                            "can_media_tag": false,
                            "followed_by": false,
                            "following": false,
                            "follow_request_sent": false,
                            "notifications": false,
                            "advertiser_account_type": "none",
                            "advertiser_account_service_levels": [],
                            "analytics_type": "disabled",
                            "business_profile_state": "none",
                            "translator_type": "none",
                            "withheld_in_countries": [],
                            "require_some_consent": false
                        }
                    }
                }
            ]
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "is_quote_status": false,
        "retweet_count": 39,
        "favorite_count": 160,
        "conversation_id": 1678183885136437249,
        "conversation_id_str": "1678183885136437249",
        "favorited": false,
        "retweeted": false,
        "possibly_sensitive": false,
        "possibly_sensitive_editable": true,
        "lang": "en",
        "supplemental_language": null
    },
    {
        "created_at": "Sun Jul 09 23:24:14 +0000 2023",
        "id": 1678183309132587010,
        "id_str": "1678183309132587010",
        "text": "RT @hycklab: haechan's song recommendation of the day! 내 마음에 비친 내 모습 by 유재하~ he's been listening to it everyday and he said he really likes…",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [
                {
                    "screen_name": "hycklab",
                    "name": "୧( ˙Ⱉ˙⠕)୨",
                    "id": 1345996578176155648,
                    "id_str": "1345996578176155648",
                    "indices": [
                        3,
                        11
                    ]
                }
            ],
            "urls": []
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "retweeted_status": {
            "created_at": "Sun Jul 09 19:18:19 +0000 2023",
            "id": 1678121419576844288,
            "id_str": "1678121419576844288",
            "text": "haechan's song recommendation of the day! 내 마음에 비친 내 모습 by 유재하~ he's been listening to it everyday and he said he r… https://t.co/2S1GqyCSif",
            "truncated": true,
            "entities": {
                "hashtags": [],
                "symbols": [],
                "user_mentions": [],
                "urls": [
                    {
                        "url": "https://t.co/2S1GqyCSif",
                        "expanded_url": "https://twitter.com/i/web/status/1678121419576844288",
                        "display_url": "twitter.com/i/web/status/1…",
                        "indices": [
                            117,
                            140
                        ]
                    }
                ]
            },
            "source": "<a href=\"http://twitter.com/download/iphone\" rel=\"nofollow\">Twitter for iPhone</a>",
            "in_reply_to_status_id": null,
            "in_reply_to_status_id_str": null,
            "in_reply_to_user_id": null,
            "in_reply_to_user_id_str": null,
            "in_reply_to_screen_name": null,
            "user": {
                "id": 1345996578176155648,
                "id_str": "1345996578176155648",
                "name": "୧( ˙Ⱉ˙⠕)୨",
                "screen_name": "hycklab",
                "location": "",
                "description": "— for 37.5% 사랑해찬 #해찬 #HAECHAN ☀️ ⠀ ⠀ ⠀ ⠀ ⠀ ⠀ ⠀ ⠀",
                "url": "https://t.co/ZiFvcX0dCk",
                "entities": {
                    "url": {
                        "urls": [
                            {
                                "url": "https://t.co/ZiFvcX0dCk",
                                "expanded_url": "http://openlink.co/lee.haechan",
                                "display_url": "openlink.co/lee.haechan",
                                "indices": [
                                    0,
                                    23
                                ]
                            }
                        ]
                    },
                    "description": {
                        "urls": []
                    }
                },
                "protected": false,
                "followers_count": 16707,
                "fast_followers_count": 0,
                "normal_followers_count": 16707,
                "friends_count": 171,
                "listed_count": 499,
                "created_at": "Mon Jan 04 07:32:58 +0000 2021",
                "favourites_count": 9650,
                "utc_offset": null,
                "time_zone": null,
                "geo_enabled": false,
                "verified": false,
                "statuses_count": 24623,
                "media_count": 7357,
                "lang": null,
                "contributors_enabled": false,
                "is_translator": false,
                "is_translation_enabled": false,
                "profile_background_color": "F5F8FA",
                "profile_background_image_url": null,
                "profile_background_image_url_https": null,
                "profile_background_tile": false,
                "profile_image_url": "http://pbs.twimg.com/profile_images/1670730447725428737/oN4vtRKc_normal.jpg",
                "profile_image_url_https": "https://pbs.twimg.com/profile_images/1670730447725428737/oN4vtRKc_normal.jpg",
                "profile_banner_url": "https://pbs.twimg.com/profile_banners/1345996578176155648/1638089363",
                "profile_link_color": "1DA1F2",
                "profile_sidebar_border_color": "C0DEED",
                "profile_sidebar_fill_color": "DDEEF6",
                "profile_text_color": "333333",
                "profile_use_background_image": true,
                "has_extended_profile": true,
                "default_profile": true,
                "default_profile_image": false,
                "pinned_tweet_ids": [
                    1664974246387359746
                ],
                "pinned_tweet_ids_str": [
                    "1664974246387359746"
                ],
                "has_custom_timelines": true,
                "can_media_tag": false,
                "followed_by": false,
                "following": false,
                "follow_request_sent": false,
                "notifications": false,
                "advertiser_account_type": "none",
                "advertiser_account_service_levels": [],
                "analytics_type": "disabled",
                "business_profile_state": "none",
                "translator_type": "none",
                "withheld_in_countries": [],
                "require_some_consent": false
            },
            "geo": null,
            "coordinates": null,
            "place": null,
            "contributors": null,
            "is_quote_status": false,
            "retweet_count": 171,
            "favorite_count": 412,
            "conversation_id": 1678121419576844288,
            "conversation_id_str": "1678121419576844288",
            "favorited": false,
            "retweeted": false,
            "possibly_sensitive": true,
            "possibly_sensitive_editable": true,
            "lang": "ko",
            "supplemental_language": null
        },
        "is_quote_status": false,
        "retweet_count": 171,
        "favorite_count": 0,
        "conversation_id": 1678183309132587010,
        "conversation_id_str": "1678183309132587010",
        "favorited": false,
        "retweeted": false,
        "lang": "ko",
        "supplemental_language": null
    },
    {
        "created_at": "Sun Jul 09 23:22:38 +0000 2023",
        "id": 1678182907234381825,
        "id_str": "1678182907234381825",
        "text": "RT @chenletonin: haechan's skincare! \n\n1. first of all don't touch your face w your hand\n2. it was his habit to sleep on his cheeks, but no…",
        "truncated": false,
        "entities": {
            "hashtags": [],
            "symbols": [],
            "user_mentions": [
                {
                    "screen_name": "chenletonin",
                    "name": "우주 (ᯟ ◡ ᯏ)",
                    "id": 1418041835260301312,
                    "id_str": "1418041835260301312",
                    "indices": [
                        3,
                        15
                    ]
                }
            ],
            "urls": []
        },
        "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 1454736746621521928,
            "id_str": "1454736746621521928",
            "name": "6ㅎ6",
            "screen_name": "LHCMILD",
            "location": "fssf",
            "description": "-ˏˋ사랑하는 해쨔니이이이 ˙Ⱉ˙⠕♡ ˊˎ",
            "url": "https://t.co/KTr6kZG0JL",
            "entities": {
                "url": {
                    "urls": [
                        {
                            "url": "https://t.co/KTr6kZG0JL",
                            "expanded_url": "https://lhcmild.carrd.co",
                            "display_url": "lhcmild.carrd.co",
                            "indices": [
                                0,
                                23
                            ]
                        }
                    ]
                },
                "description": {
                    "urls": []
                }
            },
            "protected": false,
            "followers_count": 2534,
            "fast_followers_count": 0,
            "normal_followers_count": 2534,
            "friends_count": 346,
            "listed_count": 36,
            "created_at": "Sun Oct 31 09:07:39 +0000 2021",
            "favourites_count": 60182,
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "verified": false,
            "statuses_count": 22574,
            "media_count": 4046,
            "lang": null,
            "contributors_enabled": false,
            "is_translator": false,
            "is_translation_enabled": false,
            "profile_background_color": "F5F8FA",
            "profile_background_image_url": null,
            "profile_background_image_url_https": null,
            "profile_background_tile": false,
            "profile_image_url": "http://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669877762801438720/EzJWfkAd_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/1454736746621521928/1688789978",
            "profile_link_color": "1DA1F2",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "has_extended_profile": false,
            "default_profile": true,
            "default_profile_image": false,
            "pinned_tweet_ids": [
                1652568781825142784
            ],
            "pinned_tweet_ids_str": [
                "1652568781825142784"
            ],
            "has_custom_timelines": true,
            "can_media_tag": false,
            "followed_by": false,
            "following": false,
            "follow_request_sent": false,
            "notifications": false,
            "advertiser_account_type": "promotable_user",
            "advertiser_account_service_levels": [
                "analytics"
            ],
            "analytics_type": "disabled",
            "business_profile_state": "none",
            "translator_type": "none",
            "withheld_in_countries": [],
            "require_some_consent": false
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "retweeted_status": {
            "created_at": "Sun Jul 09 19:42:06 +0000 2023",
            "id": 1678127407654633472,
            "id_str": "1678127407654633472",
            "text": "haechan's skincare! \n\n1. first of all don't touch your face w your hand\n2. it was his habit to sleep on his cheeks,… https://t.co/WO5Dmn7vos",
            "truncated": true,
            "entities": {
                "hashtags": [],
                "symbols": [],
                "user_mentions": [],
                "urls": [
                    {
                        "url": "https://t.co/WO5Dmn7vos",
                        "expanded_url": "https://twitter.com/i/web/status/1678127407654633472",
                        "display_url": "twitter.com/i/web/status/1…",
                        "indices": [
                            117,
                            140
                        ]
                    }
                ]
            },
            "source": "<a href=\"http://twitter.com/download/iphone\" rel=\"nofollow\">Twitter for iPhone</a>",
            "in_reply_to_status_id": null,
            "in_reply_to_status_id_str": null,
            "in_reply_to_user_id": null,
            "in_reply_to_user_id_str": null,
            "in_reply_to_screen_name": null,
            "user": {
                "id": 1418041835260301312,
                "id_str": "1418041835260301312",
                "name": "우주 (ᯟ ◡ ᯏ)",
                "screen_name": "chenletonin",
                "location": "7dream only • 20+",
                "description": "러러와 지성이 😸🐹 #천러 #지성 • personal fan acc",
                "url": "https://t.co/NNVmyl2wuX",
                "entities": {
                    "url": {
                        "urls": [
                            {
                                "url": "https://t.co/NNVmyl2wuX",
                                "expanded_url": "https://curiouscat.me/chenletonin",
                                "display_url": "curiouscat.me/chenletonin",
                                "indices": [
                                    0,
                                    23
                                ]
                            }
                        ]
                    },
                    "description": {
                        "urls": []
                    }
                },
                "protected": false,
                "followers_count": 17521,
                "fast_followers_count": 0,
                "normal_followers_count": 17521,
                "friends_count": 170,
                "listed_count": 228,
                "created_at": "Thu Jul 22 02:55:12 +0000 2021",
                "favourites_count": 20217,
                "utc_offset": null,
                "time_zone": null,
                "geo_enabled": false,
                "verified": false,
                "statuses_count": 35154,
                "media_count": 11335,
                "lang": null,
                "contributors_enabled": false,
                "is_translator": false,
                "is_translation_enabled": false,
                "profile_background_color": "F5F8FA",
                "profile_background_image_url": null,
                "profile_background_image_url_https": null,
                "profile_background_tile": false,
                "profile_image_url": "http://pbs.twimg.com/profile_images/1669876312117489664/CVDIZI5e_normal.jpg",
                "profile_image_url_https": "https://pbs.twimg.com/profile_images/1669876312117489664/CVDIZI5e_normal.jpg",
                "profile_banner_url": "https://pbs.twimg.com/profile_banners/1418041835260301312/1643250550",
                "profile_link_color": "1DA1F2",
                "profile_sidebar_border_color": "C0DEED",
                "profile_sidebar_fill_color": "DDEEF6",
                "profile_text_color": "333333",
                "profile_use_background_image": true,
                "has_extended_profile": true,
                "default_profile": true,
                "default_profile_image": false,
                "pinned_tweet_ids": [
                    1568582384261660678
                ],
                "pinned_tweet_ids_str": [
                    "1568582384261660678"
                ],
                "has_custom_timelines": true,
                "can_media_tag": false,
                "followed_by": false,
                "following": false,
                "follow_request_sent": false,
                "notifications": false,
                "advertiser_account_type": "none",
                "advertiser_account_service_levels": [],
                "analytics_type": "disabled",
                "business_profile_state": "none",
                "translator_type": "none",
                "withheld_in_countries": [],
                "require_some_consent": false
            },
            "geo": null,
            "coordinates": null,
            "place": null,
            "contributors": null,
            "is_quote_status": false,
            "retweet_count": 2872,
            "favorite_count": 13305,
            "conversation_id": 1678127407654633472,
            "conversation_id_str": "1678127407654633472",
            "favorited": false,
            "retweeted": false,
            "possibly_sensitive": false,
            "possibly_sensitive_editable": true,
            "lang": "en",
            "supplemental_language": null,
            "self_thread": {
                "id": 1678127407654633472,
                "id_str": "1678127407654633472"
            }
        },
        "is_quote_status": false,
        "retweet_count": 2872,
        "favorite_count": 0,
        "conversation_id": 1678182907234381825,
        "conversation_id_str": "1678182907234381825",
        "favorited": false,
        "retweeted": false,
        "lang": "en",
        "supplemental_language": null
    }
]
```

##### 一、twitter搜索 列表（可采全）
https://api.twitter.com/1.1/search/tweets.json?q=lang:zh
* Post:/twitter_api/searche 

| 名称  | 类型   | 含义                                   |
| ----- | ------ | -------------------------------------- |
| q   | String | 搜索内容,eg:lang:zh,北京         |

| token | String | 用户标识                               |
* 返回：

```json
