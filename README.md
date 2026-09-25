# AttainXR Budget Estimator
dude this is just a calculator

Self-serve training budget estimator for a HubSpot CMS page. Total = headsets × per-headset annual price, summed over the selected VR apps.

Prices in this repo are **example values**. Set real ones in the `APPS` list before deploying.

## Deploy to HubSpot

1. Create a page on your theme and add a rich text module containing `<div class="axr-est"></div>`.
2. Paste everything from `<style>` to the end of `budget-estimator.html` into **Page settings → Advanced → Head HTML**.
3. Optional lead gate: set `PORTAL_ID` and `FORM_ID` to a HubSpot form with firstname, lastname, email, company and message fields. The estimate summary is sent in `message`.
4. Password-protect the page (**Settings → Audience access**) and publish.

Open `budget-estimator.html` in a browser to try it locally.
