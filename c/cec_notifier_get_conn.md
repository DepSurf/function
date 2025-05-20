# Function: <code>cec_notifier_get_conn</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cec_notifier *cec_notifier_get_conn(struct device *dev, const char *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff81808c70)
Location: drivers/media/cec/cec-notifier.c:34
Inline: True
```
**Symbols:**

```
ffffffff81808c70-ffffffff81808d85: cec_notifier_get_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct cec_notifier *cec_notifier_get_conn(struct device *hdmi_dev, const char *conn_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff8184a4e0)
Location: drivers/media/cec/cec-notifier.c:37
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff8184a4e0-ffffffff8184a622: cec_notifier_get_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct cec_notifier *cec_notifier_get_conn(struct device *hdmi_dev, const char *conn_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff8187bcd0)
Location: drivers/media/cec/cec-notifier.c:37
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff8187bcd0-ffffffff8187be12: cec_notifier_get_conn (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct cec_notifier *cec_notifier_get_conn(struct device *hdmi_dev, const char *conn_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffff800010ac36a0)
Location: drivers/media/cec/cec-notifier.c:37
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffff800010ac36a0-ffff800010ac37f0: cec_notifier_get_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct cec_notifier *cec_notifier_get_conn(struct device *hdmi_dev, const char *conn_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (c0ba51b0)
Location: drivers/media/cec/cec-notifier.c:37
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
c0ba51b0-c0ba52f8: cec_notifier_get_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct cec_notifier *cec_notifier_get_conn(struct device *hdmi_dev, const char *conn_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (c000000000ba63b0)
Location: drivers/media/cec/cec-notifier.c:37
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
c000000000ba63b0-c000000000ba6764: cec_notifier_get_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct cec_notifier *cec_notifier_get_conn(struct device *hdmi_dev, const char *conn_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffe0006c4338)
Location: drivers/media/cec/cec-notifier.c:37
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffe0006c4338-ffffffe0006c4466: cec_notifier_get_conn (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct cec_notifier *cec_notifier_get_conn(struct device *hdmi_dev, const char *conn_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff81824240)
Location: drivers/media/cec/cec-notifier.c:37
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff81824240-ffffffff81824382: cec_notifier_get_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct cec_notifier *cec_notifier_get_conn(struct device *hdmi_dev, const char *conn_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff817eb8e0)
Location: drivers/media/cec/cec-notifier.c:37
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff817eb8e0-ffffffff817eba22: cec_notifier_get_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct cec_notifier *cec_notifier_get_conn(struct device *hdmi_dev, const char *conn_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff81871180)
Location: drivers/media/cec/cec-notifier.c:37
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff81871180-ffffffff818712c2: cec_notifier_get_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct cec_notifier *cec_notifier_get_conn(struct device *hdmi_dev, const char *conn_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff8188b140)
Location: drivers/media/cec/cec-notifier.c:37
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff8188b140-ffffffff8188b282: cec_notifier_get_conn (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *hdmi_dev</code>
</li>
<li>
<b>Param added. </b>
<code>const char *conn_name</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *conn</code>
</li>
</ul>
</details>
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
