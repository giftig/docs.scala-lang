---
layout: style-guide
title: Imports

partof: style
overview-name: "Style Guide"

num: 1

previous-page: indentation
next-page: naming-conventions
---

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
