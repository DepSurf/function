# Function: <code>audit_hash_ino</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/audit.h:222
Inline: True
```
```
In kernel/auditsc.c (0)
Location: kernel/audit.h:222
Inline: True
```
```
In kernel/audit_watch.c (0)
Location: kernel/audit.h:222
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8112be85)
Location: kernel/audit.h:223
Inline: True
```
```
In kernel/auditsc.c (0)
Location: kernel/audit.h:223
Inline: True
```
```
In kernel/audit_watch.c (ffffffff811325f6)
Location: kernel/audit.h:223
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81135b95)
Location: kernel/audit.h:223
Inline: True
```
```
In kernel/auditsc.c (0)
Location: kernel/audit.h:223
Inline: True
```
```
In kernel/audit_watch.c (ffffffff8113c35a)
Location: kernel/audit.h:223
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81137135)
Location: kernel/audit.h:227
Inline: True
```
```
In kernel/auditsc.c (0)
Location: kernel/audit.h:227
Inline: True
```
```
In kernel/audit_watch.c (ffffffff8113da2f)
Location: kernel/audit.h:227
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81143e35)
Location: kernel/audit.h:227
Inline: True
```
```
In kernel/auditsc.c (0)
Location: kernel/audit.h:227
Inline: True
```
```
In kernel/audit_watch.c (ffffffff8114a807)
Location: kernel/audit.h:227
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81152841)
Location: kernel/audit.h:227
Inline: True
```
```
In kernel/auditsc.c (ffffffff81156d93)
Location: kernel/audit.h:227
Inline: True
```
```
In kernel/audit_watch.c (ffffffff811592f4)
Location: kernel/audit.h:227
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8115f4f1)
Location: kernel/audit.h:229
Inline: True
```
```
In kernel/auditsc.c (ffffffff81163de3)
Location: kernel/audit.h:229
Inline: True
```
```
In kernel/audit_watch.c (ffffffff81166298)
Location: kernel/audit.h:229
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116bac1)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/auditsc.c (ffffffff81170a03)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/audit_watch.c (ffffffff81172d2d)
Location: kernel/audit.h:208
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811779a1)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/auditsc.c (ffffffff8117c883)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/audit_watch.c (ffffffff8117ebdf)
Location: kernel/audit.h:208
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118a751)
Location: kernel/audit.h:209
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_find_rule
```
```
In kernel/auditsc.c (ffffffff8118ec4d)
Location: kernel/audit.h:209
Inline: True
```
```
In kernel/audit_watch.c (ffffffff811920a7)
Location: kernel/audit.h:209
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811879c1)
Location: kernel/audit.h:209
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_find_rule
```
```
In kernel/auditsc.c (ffffffff8118bfed)
Location: kernel/audit.h:209
Inline: True
```
```
In kernel/audit_watch.c (ffffffff8118f237)
Location: kernel/audit.h:209
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81188a1f)
Location: kernel/audit.h:209
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_find_rule
```
```
In kernel/auditsc.c (ffffffff8118d41a)
Location: kernel/audit.h:209
Inline: True
```
```
In kernel/audit_watch.c (ffffffff8119014f)
Location: kernel/audit.h:209
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811b0f84)
Location: kernel/audit.h:212
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_find_rule
```
```
In kernel/auditsc.c (ffffffff811b60cc)
Location: kernel/audit.h:212
Inline: True
```
```
In kernel/audit_watch.c (ffffffff811b902f)
Location: kernel/audit.h:212
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811e2f42)
Location: kernel/audit.h:228
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_find_rule
```
```
In kernel/auditsc.c (ffffffff811e8a12)
Location: kernel/audit.h:228
Inline: True
```
```
In kernel/audit_watch.c (ffffffff811ec058)
Location: kernel/audit.h:228
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81228e52)
Location: kernel/audit.h:228
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_find_rule
```
```
In kernel/auditsc.c (ffffffff8122f87b)
Location: kernel/audit.h:228
Inline: True
```
```
In kernel/audit_watch.c (ffffffff812324b8)
Location: kernel/audit.h:228
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8123f452)
Location: kernel/audit.h:228
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_find_rule
```
```
In kernel/auditsc.c (ffffffff8124636b)
Location: kernel/audit.h:228
Inline: True
```
```
In kernel/audit_watch.c (ffffffff81249148)
Location: kernel/audit.h:228
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff812592b2)
Location: kernel/audit.h:228
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_find_rule
```
```
In kernel/auditsc.c (ffffffff812601fb)
Location: kernel/audit.h:228
Inline: True
```
```
In kernel/audit_watch.c (ffffffff81262fd8)
Location: kernel/audit.h:228
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffff8000101ecb38)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/auditsc.c (ffff8000101f1718)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/audit_watch.c (ffff8000101f3adc)
Location: kernel/audit.h:208
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c042c720)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/auditsc.c (c0431be4)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/audit_watch.c (c0433f68)
Location: kernel/audit.h:208
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c00000000025ea70)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/auditsc.c (c000000000265930)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/audit_watch.c (c0000000002688a0)
Location: kernel/audit.h:208
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffe000161020)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/auditsc.c (ffffffe0001650d8)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/audit_watch.c (ffffffe000166eca)
Location: kernel/audit.h:208
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116ffc1)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/auditsc.c (ffffffff81174ea3)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/audit_watch.c (ffffffff811771ff)
Location: kernel/audit.h:208
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81163161)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/auditsc.c (ffffffff81168043)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/audit_watch.c (ffffffff8116a39f)
Location: kernel/audit.h:208
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116dd91)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/auditsc.c (ffffffff81172c73)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/audit_watch.c (ffffffff81174fcf)
Location: kernel/audit.h:208
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8117b581)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/auditsc.c (ffffffff811804d6)
Location: kernel/audit.h:208
Inline: True
```
```
In kernel/audit_watch.c (ffffffff811828af)
Location: kernel/audit.h:208
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
</details>
</li>
</ul>

## Differences
