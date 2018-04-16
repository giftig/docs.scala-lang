---
layout: style-guide
title: Imports

partof: style
overview-name: "Style Guide"

num: 3

previous-page: indentation
next-page: naming-conventions
---

We opt for an import organisation style which makes imports easy to read and
separate, and matches typical community and industry practices.

## Import order

Please arrange imports into three alphabetised blocks for ease of reference;
stdlib (scala/java) imports first, then third-party, then our own libraries
and service imports:

    import java.util.UUID
    import scala.concurrent.Future

    import com.typesafe.config.Config
    import play.json._

    import com.adstream.gdam.ordering.OrderingRepository
    import com.adstream.gdam.utils.RestUtils
