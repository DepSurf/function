# Function: <code>restore_pirqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c9bb5)
Location: drivers/xen/events/events_base.c:1388
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8151a731)
Location: drivers/xen/events/events_base.c:1411
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81546c23)
Location: drivers/xen/events/events_base.c:1406
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8155aa03)
Location: drivers/xen/events/events_base.c:1405
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bee2c)
Location: drivers/xen/events/events_base.c:1405
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f7463)
Location: drivers/xen/events/events_base.c:1403
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81612503)
Location: drivers/xen/events/events_base.c:1403
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81646273)
Location: drivers/xen/events/events_base.c:1412
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816687f3)
Location: drivers/xen/events/events_base.c:1412
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void restore_pirqs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1414
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
**Symbols:**

```
ffffffff817170f0-ffffffff81717192: restore_pirqs (STB_LOCAL)
ffffffff81718a5b-ffffffff81718a9c: restore_pirqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void restore_pirqs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1886
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
**Symbols:**

```
ffffffff817347d0-ffffffff81734873: restore_pirqs (STB_LOCAL)
ffffffff81c04f6c-ffffffff81c04fad: restore_pirqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817199e9)
Location: drivers/xen/events/events_base.c:1933
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81797a4e)
Location: drivers/xen/events/events_base.c:1939
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818d0ab6)
Location: drivers/xen/events/events_base.c:1939
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a222be)
Location: drivers/xen/events/events_base.c:1941
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a6b655)
Location: drivers/xen/events/events_base.c:1938
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abd6da)
Location: drivers/xen/events/events_base.c:1918
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010832868)
Location: drivers/xen/events/events_base.c:1412
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162e523)
Location: drivers/xen/events/events_base.c:1416
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165c633)
Location: drivers/xen/events/events_base.c:1412
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81676c23)
Location: drivers/xen/events/events_base.c:1412
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
