# Function: <code>rproc_set_firmware</code>

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
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rproc_set_firmware(struct rproc *rproc, const char *fw_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:1955
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
```
**Symbols:**

```
ffffffff81c2e106-ffffffff81c2e15a: rproc_set_firmware.cold (STB_LOCAL)
ffffffff819c8d20-ffffffff819c8dd8: rproc_set_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rproc_set_firmware(struct rproc *rproc, const char *fw_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:2212
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
```
**Symbols:**

```
ffffffff81c201df-ffffffff81c20233: rproc_set_firmware.cold (STB_LOCAL)
ffffffff819add40-ffffffff819addf8: rproc_set_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rproc_set_firmware(struct rproc *rproc, const char *fw_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:2232
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
```
**Symbols:**

```
ffffffff81d31a82-ffffffff81d31ad6: rproc_set_firmware.cold (STB_LOCAL)
ffffffff81a5c2a0-ffffffff81a5c358: rproc_set_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rproc_set_firmware(struct rproc *rproc, const char *fw_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:2242
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
```
**Symbols:**

```
ffffffff81efdf53-ffffffff81efdfa7: rproc_set_firmware.cold (STB_LOCAL)
ffffffff81bcc2a0-ffffffff81bcc35c: rproc_set_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_set_firmware(struct rproc *rproc, const char *fw_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d75f10)
Location: drivers/remoteproc/remoteproc_core.c:2166
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
```
**Symbols:**

```
ffffffff81d75f10-ffffffff81d7600f: rproc_set_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_set_firmware(struct rproc *rproc, const char *fw_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de3e50)
Location: drivers/remoteproc/remoteproc_core.c:2167
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
```
**Symbols:**

```
ffffffff81de3e50-ffffffff81de3f4f: rproc_set_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_set_firmware(struct rproc *rproc, const char *fw_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e99f40)
Location: drivers/remoteproc/remoteproc_core.c:2167
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
```
**Symbols:**

```
ffffffff81e99f40-ffffffff81e9a03f: rproc_set_firmware (STB_GLOBAL)
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
