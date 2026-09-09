+++
title = "Prendre rendez-vous"
template = "page.html"
+++

Les séances durent environ **une heure**, et ont lieu en **visio** ou par **téléphone**.

Le tarif est de **60€** par séance.

La prise de **rendez-vous** se fait via l’outil de  réservation en bas de cette page, et vaut pour acceptation des [Conditions Générales de Vente](/legal#conditions-generales-de-vente).

Pour tout **renseignement** préalable, vous pouvez me joindre par email (**{% include "partials/email.html" %}**).

>## Attention
>
>Les séances reportées ou annulées moins de 48h à l'avance, ou non honorées, sont considérées comme dues et leur paiement sera demandé (sauf cas de force majeure).
>
>Les séances ne constituent pas un acte médical, et en aucun cas ne remplacent un suivi auprès d’un professionnel de santé lorsque celui-ci est nécessaire.

## Réservation
<!-- Cal inline embed code begins -->
<div style="margin-top:1rem;margin-bottom:-5rem;width:100%;height:100%;overflow:scroll" id="my-cal-inline-seance"></div>
<script type="text/javascript">
  (function (C, A, L) { let p = function (a, ar) { a.q.push(ar); }; let d = C.document; C.Cal = C.Cal || function () { let cal = C.Cal; let ar = arguments; if (!cal.loaded) { cal.ns = {}; cal.q = cal.q || []; d.head.appendChild(d.createElement("script")).src = A; cal.loaded = true; } if (ar[0] === L) { const api = function () { p(api, arguments); }; const namespace = ar[1]; api.q = api.q || []; if(typeof namespace === "string"){cal.ns[namespace] = cal.ns[namespace] || api;p(cal.ns[namespace], ar);p(cal, ["initNamespace", namespace]);} else p(cal, ar); return;} p(cal, ar); }; })(window, "https://app.cal.eu/embed/embed.js", "init");
  Cal("init", "seance", {origin:"https://app.cal.eu"});
  Cal.config = Cal.config || {};
  Cal.config.forwardQueryParams = true;
  Cal.ns.seance("inline", {elementOrSelector:"#my-cal-inline-seance", config: {"layout":"month_view","useSlotsViewOnSmallScreen":"true"}, calLink: "ecloretherapie/seance",});
  Cal.ns.seance("ui", {"hideEventTypeDetails":false,"layout":"month_view"});
</script>
<!-- Cal inline embed code ends -->