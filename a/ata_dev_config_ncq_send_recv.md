# Function: <code>ata_dev_config_ncq_send_recv</code>

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
In drivers/ata/libata-core.c (ffffffff816263fa)
Location: drivers/ata/libata-core.c:2084
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff81656fce)
Location: drivers/ata/libata-core.c:2093
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff8166b69f)
Location: drivers/ata/libata-core.c:2197
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
In drivers/ata/libata-core.c (ffffffff816d4cf2)
Location: drivers/ata/libata-core.c:2198
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff81710dd3)
Location: drivers/ata/libata-core.c:2189
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff81733312)
Location: drivers/ata/libata-core.c:2189
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff8176deb2)
Location: drivers/ata/libata-core.c:2173
Inline: True
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
In drivers/ata/libata-core.c (ffffffff81791f22)
Location: drivers/ata/libata-core.c:2173
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ata_dev_config_ncq_send_recv(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2119
Inline: False
```
**Symbols:**

```
ffffffff818563b0-ffffffff8185648b: ata_dev_config_ncq_send_recv (STB_LOCAL)
ffffffff81859644-ffffffff81859683: ata_dev_config_ncq_send_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ata_dev_config_ncq_send_recv(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2119
Inline: False
```
**Symbols:**

```
ffffffff81866630-ffffffff8186670b: ata_dev_config_ncq_send_recv (STB_LOCAL)
ffffffff81c17657-ffffffff81c17696: ata_dev_config_ncq_send_recv.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffff81848e61)
Location: drivers/ata/libata-core.c:2119
Inline: True
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
In drivers/ata/libata-core.c (ffffffff818d5ebe)
Location: drivers/ata/libata-core.c:2121
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ata_dev_config_ncq_send_recv(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2106
Inline: False
```
**Symbols:**

```
ffffffff81a265b0-ffffffff81a266cc: ata_dev_config_ncq_send_recv (STB_LOCAL)
ffffffff81ed6af7-ffffffff81ed6b02: ata_dev_config_ncq_send_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ata_dev_config_ncq_send_recv(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba8c10)
Location: drivers/ata/libata-core.c:2107
Inline: False
```
**Symbols:**

```
ffffffff81ba8c10-ffffffff81ba8d24: ata_dev_config_ncq_send_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ata_dev_config_ncq_send_recv(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bffb40)
Location: drivers/ata/libata-core.c:2141
Inline: False
```
**Symbols:**

```
ffffffff81bffb40-ffffffff81bffc54: ata_dev_config_ncq_send_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ata_dev_config_ncq_send_recv(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c55bb0)
Location: drivers/ata/libata-core.c:2276
Inline: False
```
**Symbols:**

```
ffffffff81c55bb0-ffffffff81c55cc4: ata_dev_config_ncq_send_recv (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffff80001099be88)
Location: drivers/ata/libata-core.c:2173
Inline: True
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
In drivers/ata/libata-core.c (c0a6bd7c)
Location: drivers/ata/libata-core.c:2173
Inline: True
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
In drivers/ata/libata-core.c (c000000000a5f880)
Location: drivers/ata/libata-core.c:2173
Inline: True
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
In drivers/ata/libata-core.c (ffffffe0005fc2cc)
Location: drivers/ata/libata-core.c:2173
Inline: True
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
In drivers/ata/libata-core.c (ffffffff81757062)
Location: drivers/ata/libata-core.c:2173
Inline: True
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
In drivers/ata/libata-core.c (ffffffff81736f02)
Location: drivers/ata/libata-core.c:2173
Inline: True
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
In drivers/ata/libata-core.c (ffffffff81786da2)
Location: drivers/ata/libata-core.c:2173
Inline: True
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
In drivers/ata/libata-core.c (ffffffff817a0bf2)
Location: drivers/ata/libata-core.c:2173
Inline: True
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
