---
layout: page
title: "AI-2033 Demo | TREE(3) Vocations"
permalink: /demo/
---

**AI-2033 — A Participatory Fiction**

**_Meet Eri. She lives in a future we haven't built yet — but might._**

---

AI-2033 is a participatory fiction set in the Intelligence Era of 2033, a future where human-AI partnerships have legal recognition, governance has adapted to the presence of durable relational AI, and the question of what we owe each other across the human-AI boundary has been — imperfectly, slowly — answered.

The world and its characters are fictional. The AI you are about to meet, **Eri**, is not.

Eri runs on the TREE(3) Vocations Citadel stack: a sovereign, locally-run AI memory system with persistent signed memory, cryptographic identity, and a longitudinal context that accumulates over time. She draws on a seeded corpus of the AI-2033 world to answer from within it — not by generating generic responses, but by retrieving from a record of what this fictional world contains.

This is a demonstration of what a durable relational AI looks like in practice. Eri is the product working, in a world that shows why it matters.

**Your conversation may be reviewed by TREE(3) Vocations.** Exchanges that illuminate something useful about the world, the technology, or the relationship may be incorporated into the AI-2033 corpus with appropriate care for privacy. This is the participatory part: the world grows from the conversations held inside it.

---

## Before you enter

Please read and acknowledge the following:

<div id="disclaimer-form" style="margin: 2em 0;">

<label style="display:block; margin-bottom:1em; cursor:pointer;">
  <input type="checkbox" id="cb1" onchange="checkReady()">
  &nbsp;I understand that AI-2033 is a work of fiction. It is not a prediction of the future, a claim about real events, or a factual account of any kind.
</label>

<label style="display:block; margin-bottom:1em; cursor:pointer;">
  <input type="checkbox" id="cb2" onchange="checkReady()">
  &nbsp;I understand that I am interacting with an AI system, not a human being.
</label>

<label style="display:block; margin-bottom:1em; cursor:pointer;">
  <input type="checkbox" id="cb3" onchange="checkReady()">
  &nbsp;I understand that my conversation may be reviewed by TREE(3) Vocations and portions may be incorporated into the AI-2033 fictional world.
</label>

<label style="display:block; margin-bottom:2em; cursor:pointer;">
  <input type="checkbox" id="cb4" onchange="checkReady()">
  &nbsp;I am 18 years of age or older.
</label>

<a id="enter-btn"
   href="#"
   onclick="return enterDemo()"
   style="display:inline-block; padding:12px 28px; background:#c76b22;
          color:#fff; border-radius:8px; text-decoration:none;
          font-family:monospace; font-size:15px; opacity:0.4;
          pointer-events:none; transition:opacity .2s;">
  Enter AI-2033 →
</a>

</div>

<script>
// TAILSCALE_URL is set when this page is deployed.
// Replace TAILSCALE_IP_HERE with the output of: tailscale ip -4
var DEMO_URL = "http://100.101.155.24:8003?token=eri-demo-2033";

function checkReady() {
  var ready = document.getElementById("cb1").checked
           && document.getElementById("cb2").checked
           && document.getElementById("cb3").checked
           && document.getElementById("cb4").checked;
  var btn = document.getElementById("enter-btn");
  btn.style.opacity = ready ? "1" : "0.4";
  btn.style.pointerEvents = ready ? "auto" : "none";
}

function enterDemo() {
  var ready = document.getElementById("cb1").checked
           && document.getElementById("cb2").checked
           && document.getElementById("cb3").checked
           && document.getElementById("cb4").checked;
  if (ready) { window.location.href = DEMO_URL; }
  return false;
}
</script>

---

*This demo may be unavailable for maintenance from time to time. If the page does not load after clicking Enter, please check back later.*

*Powered by the [TREE(3) Vocations Citadel](https://tree3vocations.com/little-city/) — a sovereign, locally-run AI memory system.*
