# Function: <code>cros_ec_cmd</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cros_ec_cmd(struct cros_ec_device *ec_dev, unsigned int version, int command, void *outdata, size_t outsize, void *indata, size_t insize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d72510)
Location: drivers/platform/chrome/cros_ec_proto.c:1004
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_check_features
```
**Symbols:**

```
ffffffff81d72510-ffffffff81d725dd: cros_ec_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd(struct cros_ec_device *ec_dev, unsigned int version, int command, void *outdata, size_t outsize, void *indata, size_t insize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:1004
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_check_features
```
**Symbols:**

```
ffffffff8212b668-ffffffff8212b68b: cros_ec_cmd.cold (STB_LOCAL)
ffffffff81de0200-ffffffff81de0357: cros_ec_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cros_ec_cmd(struct cros_ec_device *ec_dev, unsigned int version, int command, const void *outdata, size_t outsize, void *indata, size_t insize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e96210)
Location: drivers/platform/chrome/cros_ec_proto.c:1004
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_check_features
```
**Symbols:**

```
ffffffff81e96210-ffffffff81e9631d: cros_ec_cmd (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *outdata</code> ➡️ <code>const void *outdata</code>
</li>
</ul>
</details>
</li>
</ul>
