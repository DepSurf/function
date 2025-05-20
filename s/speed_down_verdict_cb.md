# Function: <code>speed_down_verdict_cb</code>

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
In drivers/ata/libata-eh.c (ffffffff815d6968)
Location: drivers/ata/libata-eh.c:1904
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff81630443)
Location: drivers/ata/libata-eh.c:1988
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff81661593)
Location: drivers/ata/libata-eh.c:1988
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff8167658c)
Location: drivers/ata/libata-eh.c:1925
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff816dfd58)
Location: drivers/ata/libata-eh.c:1923
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff8171c6be)
Location: drivers/ata/libata-eh.c:1876
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff8173f0a8)
Location: drivers/ata/libata-eh.c:1872
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff8177af0c)
Location: drivers/ata/libata-eh.c:1857
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff8179e9d0)
Location: drivers/ata/libata-eh.c:1857
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int speed_down_verdict_cb(struct ata_ering_entry *ent, void *void_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81861810)
Location: drivers/ata/libata-eh.c:1659
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_speed_down_verdict
  - drivers/ata/libata-eh.c:ata_eh_speed_down_verdict
```
**Symbols:**

```
ffffffff81861810-ffffffff8186188c: speed_down_verdict_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int speed_down_verdict_cb(struct ata_ering_entry *ent, void *void_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81870630)
Location: drivers/ata/libata-eh.c:1659
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_speed_down_verdict
  - drivers/ata/libata-eh.c:ata_eh_speed_down_verdict
```
**Symbols:**

```
ffffffff81870630-ffffffff818706ac: speed_down_verdict_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int speed_down_verdict_cb(struct ata_ering_entry *ent, void *void_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81852e40)
Location: drivers/ata/libata-eh.c:1659
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff81852e40-ffffffff81852ec1: speed_down_verdict_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int speed_down_verdict_cb(struct ata_ering_entry *ent, void *void_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818e0df0)
Location: drivers/ata/libata-eh.c:1667
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff818e0df0-ffffffff818e0e71: speed_down_verdict_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int speed_down_verdict_cb(struct ata_ering_entry *ent, void *void_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81a31d40)
Location: drivers/ata/libata-eh.c:1663
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff81a31d40-ffffffff81a31de9: speed_down_verdict_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int speed_down_verdict_cb(struct ata_ering_entry *ent, void *void_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb6380)
Location: drivers/ata/libata-eh.c:1668
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff81bb6380-ffffffff81bb6429: speed_down_verdict_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int speed_down_verdict_cb(struct ata_ering_entry *ent, void *void_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c0d720)
Location: drivers/ata/libata-eh.c:1678
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff81c0d720-ffffffff81c0d7dd: speed_down_verdict_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int speed_down_verdict_cb(struct ata_ering_entry *ent, void *void_arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c62940)
Location: drivers/ata/libata-eh.c:1685
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff81c62940-ffffffff81c629fd: speed_down_verdict_cb (STB_LOCAL)
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
In drivers/ata/libata-eh.c (ffff8000109aa414)
Location: drivers/ata/libata-eh.c:1857
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c0a79cd8)
Location: drivers/ata/libata-eh.c:1857
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c000000000a71090)
Location: drivers/ata/libata-eh.c:1857
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffe000607cac)
Location: drivers/ata/libata-eh.c:1857
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
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
In drivers/ata/libata-eh.c (ffffffff81763ac0)
Location: drivers/ata/libata-eh.c:1857
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81743920)
Location: drivers/ata/libata-eh.c:1857
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81793850)
Location: drivers/ata/libata-eh.c:1857
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff817ad6a9)
Location: drivers/ata/libata-eh.c:1857
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
