# Function: <code>ata_hpa_resize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ata_hpa_resize(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cc4a0)
Location: drivers/ata/libata-core.c:1330
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff815cc4a0-ffffffff815cc9e3: ata_hpa_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ata_hpa_resize(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81624cb0)
Location: drivers/ata/libata-core.c:1333
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81624cb0-ffffffff816251f5: ata_hpa_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ata_hpa_resize(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81655850)
Location: drivers/ata/libata-core.c:1340
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81655850-ffffffff81655d95: ata_hpa_resize (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffff8166a5e8)
Location: drivers/ata/libata-core.c:1340
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff816d3c38)
Location: drivers/ata/libata-core.c:1340
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ata_hpa_resize(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1340
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff8170fc50-ffffffff81710080: ata_hpa_resize (STB_LOCAL)
ffffffff81713384-ffffffff817134da: ata_hpa_resize.cold.57 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ata_hpa_resize(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1340
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81732100-ffffffff81732530: ata_hpa_resize (STB_LOCAL)
ffffffff81735833-ffffffff81735989: ata_hpa_resize.cold.58 (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffff8176e16a)
Location: drivers/ata/libata-core.c:1324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff817921da)
Location: drivers/ata/libata-core.c:1324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ata_hpa_resize(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1267
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81856ed0-ffffffff81857085: ata_hpa_resize (STB_LOCAL)
ffffffff8185987c-ffffffff81859960: ata_hpa_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ata_hpa_resize(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1267
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81867150-ffffffff81867305: ata_hpa_resize (STB_LOCAL)
ffffffff81c1788f-ffffffff81c17973: ata_hpa_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ata_hpa_resize(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1267
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81849550-ffffffff818499ab: ata_hpa_resize (STB_LOCAL)
ffffffff81c09479-ffffffff81c095fe: ata_hpa_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ata_hpa_resize(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1271
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff818d65b0-ffffffff818d6a0b: ata_hpa_resize (STB_LOCAL)
ffffffff81d0dcc6-ffffffff81d0de4b: ata_hpa_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_hpa_resize(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1264
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81a27440-ffffffff81a2775c: ata_hpa_resize (STB_LOCAL)
ffffffff81ed6c86-ffffffff81ed6dda: ata_hpa_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ata_hpa_resize(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba98d0)
Location: drivers/ata/libata-core.c:1264
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81ba98d0-ffffffff81ba9d2a: ata_hpa_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_hpa_resize(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c00930)
Location: drivers/ata/libata-core.c:1298
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81c00930-ffffffff81c00d8a: ata_hpa_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_hpa_resize(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c569a0)
Location: drivers/ata/libata-core.c:1298
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81c569a0-ffffffff81c56dfa: ata_hpa_resize (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffff80001099c238)
Location: drivers/ata/libata-core.c:1324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (c0a6c18c)
Location: drivers/ata/libata-core.c:1324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (c000000000a5fc8c)
Location: drivers/ata/libata-core.c:1324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffe0005fc598)
Location: drivers/ata/libata-core.c:1324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff8175731a)
Location: drivers/ata/libata-core.c:1324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff817371ba)
Location: drivers/ata/libata-core.c:1324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff8178705a)
Location: drivers/ata/libata-core.c:1324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff817a0eaa)
Location: drivers/ata/libata-core.c:1324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
