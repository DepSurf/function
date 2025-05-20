# Function: <code>cec_register_cec_notifier</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cec_register_cec_notifier(struct cec_adapter *adap, struct cec_notifier *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffff818031e0)
Location: drivers/media/cec/cec-core.c:190
Inline: False
```
**Symbols:**

```
ffffffff818031e0-ffffffff81803219: cec_register_cec_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cec_register_cec_notifier(struct cec_adapter *adap, struct cec_notifier *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-core.c (0)
Location: drivers/media/cec/cec-core.c:192
Inline: False
```
**Symbols:**

```
ffffffff81844ef0-ffffffff81844f03: cec_register_cec_notifier.cold (STB_LOCAL)
ffffffff818446b0-ffffffff818446ed: cec_register_cec_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_register_cec_notifier(struct cec_adapter *adap, struct cec_notifier *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffff81875fe0)
Location: drivers/media/cec/cec-core.c:192
Inline: False
```
**Symbols:**

```
ffffffff81875fe0-ffffffff81876018: cec_register_cec_notifier (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void cec_register_cec_notifier(struct cec_adapter *adap, struct cec_notifier *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffff800010abd828)
Location: drivers/media/cec/cec-core.c:192
Inline: False
```
**Symbols:**

```
ffff800010abd828-ffff800010abd884: cec_register_cec_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_register_cec_notifier(struct cec_adapter *adap, struct cec_notifier *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (c0b9f6c4)
Location: drivers/media/cec/cec-core.c:192
Inline: False
```
**Symbols:**

```
c0b9f6c4-c0b9f724: cec_register_cec_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_register_cec_notifier(struct cec_adapter *adap, struct cec_notifier *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (c000000000b9eac0)
Location: drivers/media/cec/cec-core.c:192
Inline: False
```
**Symbols:**

```
c000000000b9eac0-c000000000b9eb28: cec_register_cec_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_register_cec_notifier(struct cec_adapter *adap, struct cec_notifier *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffe0006bf568)
Location: drivers/media/cec/cec-core.c:192
Inline: False
```
**Symbols:**

```
ffffffe0006bf568-ffffffe0006bf5bc: cec_register_cec_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void cec_register_cec_notifier(struct cec_adapter *adap, struct cec_notifier *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffff8181e550)
Location: drivers/media/cec/cec-core.c:192
Inline: False
```
**Symbols:**

```
ffffffff8181e550-ffffffff8181e588: cec_register_cec_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_register_cec_notifier(struct cec_adapter *adap, struct cec_notifier *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffff817e5bf0)
Location: drivers/media/cec/cec-core.c:192
Inline: False
```
**Symbols:**

```
ffffffff817e5bf0-ffffffff817e5c28: cec_register_cec_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_register_cec_notifier(struct cec_adapter *adap, struct cec_notifier *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffff8186b490)
Location: drivers/media/cec/cec-core.c:192
Inline: False
```
**Symbols:**

```
ffffffff8186b490-ffffffff8186b4c8: cec_register_cec_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_register_cec_notifier(struct cec_adapter *adap, struct cec_notifier *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffff81885420)
Location: drivers/media/cec/cec-core.c:192
Inline: False
```
**Symbols:**

```
ffffffff81885420-ffffffff81885458: cec_register_cec_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
