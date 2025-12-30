---
layout: post
title: Why Plasticity?
date: 2025-12-30
---

Having an ML model that is capable of learning new tasks after deployment would be useful. This capability would mean that cases outside of those recognised during model development could be handled gracefully.

Current approaches achieve impressive flexibility by learning in-context. This is not all that far removed from biological attention spans and works very well. However, a limited context window means long-horizon tasks are not handled well. Careful software design is required to manage context, which is hard and expensive.

Building plasticity into a model acknowledges that the world is complex enough that no amount of curated pretraining is sufficient to prepare for every scenario.

A model with the capability of adjusting connections during inference would be able to develop more useful representations of it's environment over time.