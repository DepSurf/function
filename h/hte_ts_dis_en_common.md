# Function: <code>hte_ts_dis_en_common</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hte_ts_dis_en_common(struct hte_ts_desc *desc, bool en);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hte/hte.c (0)
Location: drivers/hte/hte.c:239
Inline: False
Direct callers:
  - drivers/hte/hte.c:hte_enable_ts
  - drivers/hte/hte.c:hte_disable_ts
```
**Symbols:**

```
ffffffff81be4420-ffffffff81be4580: hte_ts_dis_en_common (STB_LOCAL)
ffffffff81f00d78-ffffffff81f00da8: hte_ts_dis_en_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hte_ts_dis_en_common(struct hte_ts_desc *desc, bool en);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81d90450)
Location: drivers/hte/hte.c:239
Inline: False
Direct callers:
  - drivers/hte/hte.c:hte_enable_ts
  - drivers/hte/hte.c:hte_disable_ts
```
**Symbols:**

```
ffffffff81d90450-ffffffff81d905be: hte_ts_dis_en_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hte_ts_dis_en_common(struct hte_ts_desc *desc, bool en);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81dfe700)
Location: drivers/hte/hte.c:239
Inline: False
Direct callers:
  - drivers/hte/hte.c:hte_enable_ts
  - drivers/hte/hte.c:hte_disable_ts
```
**Symbols:**

```
ffffffff81dfe700-ffffffff81dfe86e: hte_ts_dis_en_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hte_ts_dis_en_common(struct hte_ts_desc *desc, bool en);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81eb5720)
Location: drivers/hte/hte.c:237
Inline: False
Direct callers:
  - drivers/hte/hte.c:hte_enable_ts
  - drivers/hte/hte.c:hte_disable_ts
```
**Symbols:**

```
ffffffff81eb5720-ffffffff81eb588e: hte_ts_dis_en_common (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
