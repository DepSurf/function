# Function: <code>cec_notifier_cec_adap_register</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct cec_notifier *cec_notifier_cec_adap_register(struct device *hdmi_dev, const char *conn_name, struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-notifier.c (0)
Location: drivers/media/cec/cec-notifier.c:134
Inline: False
```
**Symbols:**

```
ffffffff8184aae4-ffffffff8184aafa: cec_notifier_cec_adap_register.cold (STB_LOCAL)
ffffffff8184a730-ffffffff8184a804: cec_notifier_cec_adap_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cec_notifier *cec_notifier_cec_adap_register(struct device *hdmi_dev, const char *conn_name, struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff8187bf20)
Location: drivers/media/cec/cec-notifier.c:134
Inline: False
```
**Symbols:**

```
ffffffff8187bf20-ffffffff8187c002: cec_notifier_cec_adap_register (STB_GLOBAL)
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
struct cec_notifier *cec_notifier_cec_adap_register(struct device *hdmi_dev, const char *conn_name, struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffff800010ac38b8)
Location: drivers/media/cec/cec-notifier.c:134
Inline: False
```
**Symbols:**

```
ffff800010ac38b8-ffff800010ac3974: cec_notifier_cec_adap_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cec_notifier *cec_notifier_cec_adap_register(struct device *hdmi_dev, const char *conn_name, struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (c0ba537c)
Location: drivers/media/cec/cec-notifier.c:134
Inline: False
```
**Symbols:**

```
c0ba537c-c0ba5404: cec_notifier_cec_adap_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cec_notifier *cec_notifier_cec_adap_register(struct device *hdmi_dev, const char *conn_name, struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (c000000000ba6850)
Location: drivers/media/cec/cec-notifier.c:134
Inline: False
```
**Symbols:**

```
c000000000ba6850-c000000000ba6924: cec_notifier_cec_adap_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct cec_notifier *cec_notifier_cec_adap_register(struct device *hdmi_dev, const char *conn_name, struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffe0006c4500)
Location: drivers/media/cec/cec-notifier.c:134
Inline: False
```
**Symbols:**

```
ffffffe0006c4500-ffffffe0006c45bc: cec_notifier_cec_adap_register (STB_GLOBAL)
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
struct cec_notifier *cec_notifier_cec_adap_register(struct device *hdmi_dev, const char *conn_name, struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff81824490)
Location: drivers/media/cec/cec-notifier.c:134
Inline: False
```
**Symbols:**

```
ffffffff81824490-ffffffff81824572: cec_notifier_cec_adap_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cec_notifier *cec_notifier_cec_adap_register(struct device *hdmi_dev, const char *conn_name, struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff817ebb30)
Location: drivers/media/cec/cec-notifier.c:134
Inline: False
```
**Symbols:**

```
ffffffff817ebb30-ffffffff817ebc12: cec_notifier_cec_adap_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cec_notifier *cec_notifier_cec_adap_register(struct device *hdmi_dev, const char *conn_name, struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff818713d0)
Location: drivers/media/cec/cec-notifier.c:134
Inline: False
```
**Symbols:**

```
ffffffff818713d0-ffffffff818714b2: cec_notifier_cec_adap_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cec_notifier *cec_notifier_cec_adap_register(struct device *hdmi_dev, const char *conn_name, struct cec_adapter *adap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff8188b390)
Location: drivers/media/cec/cec-notifier.c:134
Inline: False
```
**Symbols:**

```
ffffffff8188b390-ffffffff8188b472: cec_notifier_cec_adap_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
