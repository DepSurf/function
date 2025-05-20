# Function: <code>security_overwrite</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81762504)
Location: drivers/nvdimm/security.c:367
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_overwrite(struct nvdimm *nvdimm, unsigned int keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff818216b0)
Location: drivers/nvdimm/security.c:367
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff818216b0-ffffffff81821857: security_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_overwrite(struct nvdimm *nvdimm, unsigned int keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff818303c0)
Location: drivers/nvdimm/security.c:367
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff818303c0-ffffffff81830567: security_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_overwrite(struct nvdimm *nvdimm, unsigned int keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81813630)
Location: drivers/nvdimm/security.c:367
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81813630-ffffffff8181380b: security_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_overwrite(struct nvdimm *nvdimm, unsigned int keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff8189dc60)
Location: drivers/nvdimm/security.c:367
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff8189dc60-ffffffff8189de35: security_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_overwrite(struct nvdimm *nvdimm, unsigned int keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff819e7730)
Location: drivers/nvdimm/security.c:367
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff819e7730-ffffffff819e78c4: security_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_overwrite(struct nvdimm *nvdimm, unsigned int keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81b63980)
Location: drivers/nvdimm/security.c:390
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81b63980-ffffffff81b63b1d: security_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_overwrite(struct nvdimm *nvdimm, unsigned int keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81bb6f70)
Location: drivers/nvdimm/security.c:390
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81bb6f70-ffffffff81bb7108: security_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_overwrite(struct nvdimm *nvdimm, unsigned int keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81c0b5c0)
Location: drivers/nvdimm/security.c:390
Inline: False
Direct callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
```
**Symbols:**

```
ffffffff81c0b5c0-ffffffff81c0b758: security_overwrite (STB_LOCAL)
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
In drivers/nvdimm/security.c (ffff8000109622cc)
Location: drivers/nvdimm/security.c:367
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
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
In drivers/nvdimm/security.c (c000000000a17f64)
Location: drivers/nvdimm/security.c:367
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
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
In drivers/nvdimm/security.c (ffffffe0005cf7fe)
Location: drivers/nvdimm/security.c:367
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
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
In drivers/nvdimm/security.c (ffffffff81716bf4)
Location: drivers/nvdimm/security.c:367
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
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
In drivers/nvdimm/security.c (ffffffff816ea674)
Location: drivers/nvdimm/security.c:367
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
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
In drivers/nvdimm/security.c (ffffffff817559c4)
Location: drivers/nvdimm/security.c:367
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
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
In drivers/nvdimm/security.c (ffffffff81770e34)
Location: drivers/nvdimm/security.c:367
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
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
