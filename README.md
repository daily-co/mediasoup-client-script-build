# <script> build of mediasoup-client

Test of building mediasoup-client v3 as a standalone library that can
be imported using a "traditional" <script> tag or used in a <script
type="module"> context.

## building

You should be able to just:

```
npm install
npm build
```

## and seeing if the build worked

Load `demo/script-tag.html` or `demo/script-module-import.html` in a
browser, after building. Both tests are very, very simple and just try
to construct a mediasoup-client `Device`.


