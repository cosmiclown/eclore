+++
title = "Prendre rendez-vous"
template = "page.html"
+++

Les séances ont lieu en **visio** et durent environ **une heure**.

Le **tarif** est de **60€** par séance *(paiement par virement après la séance)*.

La **réservation** se fait directement en ligne *(via l'agenda ci-dessous)*.

Pour tout **renseignement** préalable, vous pouvez me joindre par email *({% include "partials/email.html" %})*.

<div id="my-cal-inline-seance">
  <script type="text/javascript">
    (function (C, A, L) { let p = function (a, ar) { a.q.push(ar); }; let d = C.document; C.Cal = C.Cal || function () { let cal = C.Cal; let ar = arguments; if (!cal.loaded) { cal.ns = {}; cal.q = cal.q || []; d.head.appendChild(d.createElement("script")).src = A; cal.loaded = true; } if (ar[0] === L) { const api = function () { p(api, arguments); }; const namespace = ar[1]; api.q = api.q || []; if(typeof namespace === "string"){cal.ns[namespace] = cal.ns[namespace] || api;p(cal.ns[namespace], ar);p(cal, ["initNamespace", namespace]);} else p(cal, ar); return;} p(cal, ar); }; })(window, "https://app.cal.eu/embed/embed.js", "init");
    Cal("init", "seance", {origin:"https://app.cal.eu"});
    Cal.config = Cal.config || {};
    Cal.config.forwardQueryParams = true;
    Cal.ns.seance("inline", {elementOrSelector:"#my-cal-inline-seance", config: {"layout":"month_view","useSlotsViewOnSmallScreen":"true","theme":"light"}, calLink: "ecloretherapie/seance",});
    Cal.ns.seance("ui", {"theme":"light","hideEventTypeDetails":false,"layout":"month_view"});
  </script>
</div>
