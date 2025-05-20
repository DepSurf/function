# Function: <code>cec_notifier_register</code>

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
void cec_notifier_register(struct cec_notifier *n, struct cec_adapter *adap, void (*callback)(struct cec_adapter *, u16));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff81808e00)
Location: drivers/media/cec/cec-notifier.c:109
Inline: False
Direct callers:
  - drivers/media/cec/cec-core.c:cec_register_cec_notifier
```
**Symbols:**

```
ffffffff81808e00-ffffffff81808e49: cec_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cec_notifier_register(struct cec_notifier *n, struct cec_adapter *adap, void (*callback)(struct cec_adapter *, u16));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff8184aa70)
Location: drivers/media/cec/cec-notifier.c:200
Inline: False
Direct callers:
  - drivers/media/cec/cec-core.c:cec_register_cec_notifier
```
**Symbols:**

```
ffffffff8184aa70-ffffffff8184aac6: cec_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_notifier_register(struct cec_notifier *n, struct cec_adapter *adap, void (*callback)(struct cec_adapter *, u16));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff8187c290)
Location: drivers/media/cec/cec-notifier.c:200
Inline: False
Direct callers:
  - drivers/media/cec/cec-core.c:cec_register_cec_notifier
```
**Symbols:**

```
ffffffff8187c290-ffffffff8187c2e6: cec_notifier_register (STB_GLOBAL)
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
void cec_notifier_register(struct cec_notifier *n, struct cec_adapter *adap, void (*callback)(struct cec_adapter *, u16));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffff800010ac3540)
Location: drivers/media/cec/cec-notifier.c:200
Inline: False
Direct callers:
  - drivers/media/cec/cec-core.c:cec_register_cec_notifier
```
**Symbols:**

```
ffff800010ac3540-ffff800010ac359c: cec_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_notifier_register(struct cec_notifier *n, struct cec_adapter *adap, void (*callback)(struct cec_adapter *, u16));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (c0ba5070)
Location: drivers/media/cec/cec-notifier.c:200
Inline: False
Direct callers:
  - drivers/media/cec/cec-core.c:cec_register_cec_notifier
```
**Symbols:**

```
c0ba5070-c0ba50c0: cec_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_notifier_register(struct cec_notifier *n, struct cec_adapter *adap, void (*callback)(struct cec_adapter *, u16));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (c000000000ba5e50)
Location: drivers/media/cec/cec-notifier.c:200
Inline: False
Direct callers:
  - drivers/media/cec/cec-core.c:cec_register_cec_notifier
```
**Symbols:**

```
c000000000ba5e50-c000000000ba5eec: cec_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_notifier_register(struct cec_notifier *n, struct cec_adapter *adap, void (*callback)(struct cec_adapter *, u16));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffe0006c4128)
Location: drivers/media/cec/cec-notifier.c:200
Inline: False
Direct callers:
  - drivers/media/cec/cec-core.c:cec_register_cec_notifier
```
**Symbols:**

```
ffffffe0006c4128-ffffffe0006c4182: cec_notifier_register (STB_GLOBAL)
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
void cec_notifier_register(struct cec_notifier *n, struct cec_adapter *adap, void (*callback)(struct cec_adapter *, u16));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff81824800)
Location: drivers/media/cec/cec-notifier.c:200
Inline: False
Direct callers:
  - drivers/media/cec/cec-core.c:cec_register_cec_notifier
```
**Symbols:**

```
ffffffff81824800-ffffffff81824856: cec_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_notifier_register(struct cec_notifier *n, struct cec_adapter *adap, void (*callback)(struct cec_adapter *, u16));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff817ebea0)
Location: drivers/media/cec/cec-notifier.c:200
Inline: False
Direct callers:
  - drivers/media/cec/cec-core.c:cec_register_cec_notifier
```
**Symbols:**

```
ffffffff817ebea0-ffffffff817ebef6: cec_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_notifier_register(struct cec_notifier *n, struct cec_adapter *adap, void (*callback)(struct cec_adapter *, u16));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff81871740)
Location: drivers/media/cec/cec-notifier.c:200
Inline: False
Direct callers:
  - drivers/media/cec/cec-core.c:cec_register_cec_notifier
```
**Symbols:**

```
ffffffff81871740-ffffffff81871796: cec_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_notifier_register(struct cec_notifier *n, struct cec_adapter *adap, void (*callback)(struct cec_adapter *, u16));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff8188b700)
Location: drivers/media/cec/cec-notifier.c:200
Inline: False
Direct callers:
  - drivers/media/cec/cec-core.c:cec_register_cec_notifier
```
**Symbols:**

```
ffffffff8188b700-ffffffff8188b756: cec_notifier_register (STB_GLOBAL)
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
