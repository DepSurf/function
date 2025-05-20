# Function: <code>__devlink_compat_running_version</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81951b96)
Location: net/core/devlink.c:6839
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
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
In net/core/devlink.c (ffffffff819885d6)
Location: net/core/devlink.c:8003
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __devlink_compat_running_version(struct devlink *devlink, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a515c0)
Location: net/core/devlink.c:9234
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_compat_running_version
```
**Symbols:**

```
ffffffff81a515c0-ffffffff81a51715: __devlink_compat_running_version (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __devlink_compat_running_version(struct devlink *devlink, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a576d0)
Location: net/core/devlink.c:10188
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_compat_running_version
```
**Symbols:**

```
ffffffff81a576d0-ffffffff81a57825: __devlink_compat_running_version (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a4be95)
Location: net/core/devlink.c:10452
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
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
In net/core/devlink.c (ffffffff81b0428c)
Location: net/core/devlink.c:11394
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c89be0)
Location: net/core/devlink.c:11992
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e447b0)
Location: net/core/devlink.c:12881
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __devlink_compat_running_version(struct devlink *devlink, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82042b50)
Location: net/devlink/dev.c:1087
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_compat_running_version
```
**Symbols:**

```
ffffffff82042b50-ffffffff82042d49: __devlink_compat_running_version (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __devlink_compat_running_version(struct devlink *devlink, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82101ed0)
Location: net/devlink/dev.c:1188
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_compat_running_version
```
**Symbols:**

```
ffffffff82101ed0-ffffffff821020d0: __devlink_compat_running_version (STB_LOCAL)
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
In net/core/devlink.c (ffff800010c304f8)
Location: net/core/devlink.c:8003
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
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
In net/core/devlink.c (c0d474e8)
Location: net/core/devlink.c:8003
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
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
In net/core/devlink.c (c000000000d292b4)
Location: net/core/devlink.c:8003
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
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
In net/core/devlink.c (ffffffe0007a66e8)
Location: net/core/devlink.c:8003
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
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
In net/core/devlink.c (ffffffff81928446)
Location: net/core/devlink.c:8003
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
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
In net/core/devlink.c (ffffffff818e21f6)
Location: net/core/devlink.c:8003
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
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
In net/core/devlink.c (ffffffff819795d6)
Location: net/core/devlink.c:8003
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
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
In net/core/devlink.c (ffffffff8199bac6)
Location: net/core/devlink.c:8003
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
