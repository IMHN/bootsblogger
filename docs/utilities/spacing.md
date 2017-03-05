---
layout: docs
title: Spacing
description: Kelas tambahan untuk Bootstrap spacing utilities.
group: utilities
---

Kelas tambahan untuk [Bootstrap spacing utilities](https://v4-alpha.getbootstrap.com/utilities/spacing/).

## Negative margin

Format kelasnya tidak jauh berbeda dengan [Bootstrap spacing utilities](https://v4-alpha.getbootstrap.com/utilities/spacing/), hanya menambahkan `n` di antara `{property} (m)` dan `{sides}`, format kelasnya adalah `.mn{sides}-{size}` untuk `xs` dan `.mn{sides}-{breakpoint}-{size}` untuk `sm`, `md`, `lg`, dan `xl`.

**Catatan:** kelas utilitas *margin* negatif tidak memiliki `.*-0`.

### Example

{% example html %}
<div class="p-3 bg-purple-50">
  <div class="mnt-3 bg-orange-50" style="height: 100px;"></div>
</div>
{% endexample %}

{% example html %}
<div class="p-3 bg-purple-50">
  <div class="mnr-3 bg-orange-50" style="height: 100px;"></div>
</div>
{% endexample %}

{% example html %}
<div class="p-3 bg-purple-50">
  <div class="mnb-3 bg-orange-50" style="height: 100px;"></div>
</div>
{% endexample %}

{% example html %}
<div class="p-3 bg-purple-50">
  <div class="mnl-3 bg-orange-50" style="height: 100px;"></div>
</div>
{% endexample %}

{% example html %}
<div class="p-3 bg-purple-50">
  <div class="mnx-3 bg-orange-50" style="height: 100px;"></div>
</div>
{% endexample %}

{% example html %}
<div class="p-3 bg-purple-50">
  <div class="mny-3 bg-orange-50" style="height: 100px;"></div>
</div>
{% endexample %}

{% example html %}
<div class="p-3 bg-purple-50">
  <div class="mn-3 bg-orange-50" style="height: 100px;"></div>
</div>
{% endexample %}