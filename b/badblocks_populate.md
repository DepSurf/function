# Function: <code>badblocks_populate</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff815ebdfa)
Location: drivers/nvdimm/core.c:477
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/core.c (ffffffff816189ea)
Location: drivers/nvdimm/core.c:448
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/core.c (ffffffff8162c876)
Location: drivers/nvdimm/core.c:449
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffff816a2427)
Location: drivers/nvdimm/badrange.c:221
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffff816de5c6)
Location: drivers/nvdimm/badrange.c:221
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffff81700986)
Location: drivers/nvdimm/badrange.c:221
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffff8173a7f6)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffff8175e4c6)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void badblocks_populate(struct badrange *badrange, struct badblocks *bb, const struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8181df80)
Location: drivers/nvdimm/badrange.c:213
Inline: False
Direct callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
**Symbols:**

```
ffffffff8181df80-ffffffff8181e035: badblocks_populate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void badblocks_populate(struct badrange *badrange, struct badblocks *bb, const struct range *range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8182cf00)
Location: drivers/nvdimm/badrange.c:213
Inline: False
Direct callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
**Symbols:**

```
ffffffff8182cf00-ffffffff8182cfb5: badblocks_populate (STB_LOCAL)
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
In drivers/nvdimm/badrange.c (ffffffff81810296)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffff8189a8b6)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffff819e3fe6)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffff81b5fcd6)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffff81bb3276)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffff81c07766)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffff80001095fbdc)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (c000000000a12750)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffe0005cd7c6)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffff81712bb6)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffff816e6636)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffff81751986)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
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
In drivers/nvdimm/badrange.c (ffffffff8176cee6)
Location: drivers/nvdimm/badrange.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct range *range</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct resource *res</code>
</li>
</ul>
</details>
</li>
</ul>
