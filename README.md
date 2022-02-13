## CP-Badges
As the [kehsihba19/CP-Badges's](https://github.com/kehsihba19/CP-Badges) server was dead, `i decided to host this API myself` using [deta micros](https://docs.deta.sh/docs/micros/about). 

This repo helps you to create your custom profile badges with Max rating in Codechef, Codeforces and many more.

## Endpoints

```python
https://cp-badges.deta.dev/codeforces/<user_name>
https://cp-badges.deta.dev/codechef/<user_name>
https://cp-badges.deta.dev/atcoder/<user_name>
https://cp-badges.deta.dev/topcoder/<user_name>
https://cp-badges.deta.dev/yukicoder/<user_name>
https://cp-badges.deta.dev/uri/<user_name>
https://cp-badges.deta.dev/leetcode/<user_name>
https://cp-badges.deta.dev/leetcode-cn/<user_name>
```
## Usage

```python
[![Badge](https://cp-badges.deta.dev/codechef/gennady.korotkevich)]
```

This corresponds to

![Badge](https://cp-badges.deta.dev/codechef/gennady.korotkevich)

You can also show the logo along with the website name and rating by including the query parameter with the URL `?logo=true`

For example
```python
[![Badge](https://cp-badges.deta.dev/codechef/gennady.korotkevich?logo=true)]
```


This corresponds to

![Badge](https://cp-badges.deta.dev/codechef/gennady.korotkevich?logo=true)


You can add custom links also to the badge for reference :

```python
[![Badge](https://cp-badges.deta.dev/codechef/gennady.korotkevich)]
(https://www.codechef.com/users/gennady.korotkevich)
```

This will add a link to the badge

[![Badge](https://cp-badges.deta.dev/codechef/gennady.korotkevich)](https://www.codechef.com/users/gennady.korotkevich)

## Fun Fact

The colour of the badge changes as your maximum rating changes according to the website policy.

Some examples are -

![Badge](https://cp-badges.deta.dev/atcoder/tourist)
![Badge](https://cp-badges.deta.dev/codeforces/sladkayaKlubnichka)
![Badge](https://cp-badges.deta.dev/atcoder/sansen)

![Badge](https://cp-badges.deta.dev/codeforces/ujjawalrana001)
![Badge](https://cp-badges.deta.dev/atcoder/kehsihba)
![Badge](https://cp-badges.deta.dev/codeforces/errichto)

![Badge](https://cp-badges.deta.dev/atcoder/anzuof)
![Badge](https://cp-badges.deta.dev/codeforces/abhishek.kehsihba)
![Badge](https://cp-badges.deta.dev/atcoder/zhouzhendong)

![Badge](https://cp-badges.deta.dev/yukicoder/hos.lyric)
![Badge](https://cp-badges.deta.dev/yukicoder/ganariya)
![Badge](https://cp-badges.deta.dev/yukicoder/imulan)

![Badge](https://cp-badges.deta.dev/uri/40926)
![Badge](https://cp-badges.deta.dev/uri/440377)
![Badge](https://cp-badges.deta.dev/uri/40980)

![Badge](https://cp-badges.deta.dev/topcoder/AmAtUrECoDeR)
![Badge](https://cp-badges.deta.dev/topcoder/tourist)
![Badge](https://cp-badges.deta.dev/topcoder/forgotter)

![Badge](https://cp-badges.deta.dev/leetcode/Errichto)

![Badge](https://cp-badges.deta.dev/leetcode-cn/bitethed4t)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.