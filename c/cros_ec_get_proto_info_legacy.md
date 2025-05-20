# Function: <code>cros_ec_get_proto_info_legacy</code>

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
int cros_ec_get_proto_info_legacy(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d71b20)
Location: drivers/platform/chrome/cros_ec_proto.c:369
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff81d71b20-ffffffff81d71ce5: cros_ec_get_proto_info_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cros_ec_get_proto_info_legacy(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81ddf800)
Location: drivers/platform/chrome/cros_ec_proto.c:369
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff81ddf800-ffffffff81ddf9c5: cros_ec_get_proto_info_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cros_ec_get_proto_info_legacy(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e95750)
Location: drivers/platform/chrome/cros_ec_proto.c:369
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff81e95750-ffffffff81e95944: cros_ec_get_proto_info_legacy (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
