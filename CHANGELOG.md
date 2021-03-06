# Change Log #

## 0.9.0 - 2018-02-16

* Update logger to 0.4 and env_logger to 0.5.

## 0.8.1 - 2017-07-02

* Implement unimplemented deserialize methods.

## 0.8.0 - 2017-06-28

* API CHANGE: Switch to Serde for deserialization. Data structures being
  deserialized to must implement the `Deserialize` trait. Pull request by
  Wesley Moore. GitHub #5.

## 0.7.2 - 2017-04-16

* Update `log` to 0.3.7 and `rustc-serialize` to 0.3.23.

## 0.7.1 - 2016-11-13

* Update `rustc-serialize` to 0.3.21.

## 0.7.0 - 2016-05-15

* API CHANGE: `lookup` takes an `IpAddr` again instead of a `SocketAddr`. We
  previously switched to `SocketAddr` after `IpAddr` had been deprecated, but
  it has since been re-added.
