---
layout: page
title: Subjects
permalink: /subjects/
---

<!-- Required for booking embed -->
<script>
  (function (C, A, L) {
    let p = function (a, ar) {
      a.q.push(ar);
    };
    let d = C.document;
    C.Cal =
      C.Cal ||
      function () {
        let cal = C.Cal;
        let ar = arguments;
        if (!cal.loaded) {
          cal.ns = {};
          cal.q = cal.q || [];
          d.head.appendChild(d.createElement("script")).src = A;
          cal.loaded = true;
        }
        if (ar[0] === L) {
          const api = function () {
            p(api, arguments);
          };
          const namespace = ar[1];
          api.q = api.q || [];
          typeof namespace === "string" ? (cal.ns[namespace] = api) && p(api, ar) : p(cal, ar);
          return;
        }
        p(cal, ar);
      };
    })(window, "https://cal.com/embed.js", "init");
    Cal("init")
  </script>

Although I specialize in SAT Math, I also have experience tutoring other subjects! These include:
<li>Algebra 2</li>
<li>Precalculus / Trigonometry</li>
<li>AP Computer Science A</li>
<li>College Consulting / Essay Reviewing</li>

<br>
For all of the subjects above, my rate and policies are the same as with SAT Math. You can book a trial session just like you would for SAT tutoring with the button below:

<div align="center">
  <a data-cal-link="ericwolpert/trial" class="button button--large section-button">Book a Trial Session</a>
</div>

<br>
Want tutoring for a subject that's not listed here? Please ask about it in the [Contact](https://learnsatmath.com/contact/) page!