# Function: <code>i2cdev_ioctl_rdwr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff8167e3c0)
Location: drivers/i2c/i2c-dev.c:238
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff8167e3c0-ffffffff8167e61b: i2cdev_ioctl_rdwr.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff816df140)
Location: drivers/i2c/i2c-dev.c:240
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff816df140-ffffffff816df3d2: i2cdev_ioctl_rdwr.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff8170f520)
Location: drivers/i2c/i2c-dev.c:240
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff8170f520-ffffffff8170f7b2: i2cdev_ioctl_rdwr.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81725760)
Location: drivers/i2c/i2c-dev.c:240
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff81725760-ffffffff817259fc: i2cdev_ioctl_rdwr.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81796bf0)
Location: drivers/i2c/i2c-dev.c:241
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff81796bf0-ffffffff81796e05: i2cdev_ioctl_rdwr.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff817d9770)
Location: drivers/i2c/i2c-dev.c:241
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff817d9770-ffffffff817d99ad: i2cdev_ioctl_rdwr.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81800910)
Location: drivers/i2c/i2c-dev.c:241
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff81800910-ffffffff81800b4d: i2cdev_ioctl_rdwr.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81841c30)
Location: drivers/i2c/i2c-dev.c:233
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff81841c30-ffffffff81841e5c: i2cdev_ioctl_rdwr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff818735b0)
Location: drivers/i2c/i2c-dev.c:233
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff818735b0-ffffffff818737dc: i2cdev_ioctl_rdwr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int i2cdev_ioctl_rdwr(struct i2c_client *client, unsigned int nmsgs, struct i2c_msg *msgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81947790)
Location: drivers/i2c/i2c-dev.c:235
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff81947790-ffffffff819479be: i2cdev_ioctl_rdwr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int i2cdev_ioctl_rdwr(struct i2c_client *client, unsigned int nmsgs, struct i2c_msg *msgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff8194d5a0)
Location: drivers/i2c/i2c-dev.c:235
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff8194d5a0-ffffffff8194d7d5: i2cdev_ioctl_rdwr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int i2cdev_ioctl_rdwr(struct i2c_client *client, unsigned int nmsgs, struct i2c_msg *msgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81930d30)
Location: drivers/i2c/i2c-dev.c:236
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff81930d30-ffffffff81930f5c: i2cdev_ioctl_rdwr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int i2cdev_ioctl_rdwr(struct i2c_client *client, unsigned int nmsgs, struct i2c_msg *msgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff819d4000)
Location: drivers/i2c/i2c-dev.c:235
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff819d4000-ffffffff819d422c: i2cdev_ioctl_rdwr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int i2cdev_ioctl_rdwr(struct i2c_client *client, unsigned int nmsgs, struct i2c_msg *msgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81b36ca0)
Location: drivers/i2c/i2c-dev.c:235
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff81b36ca0-ffffffff81b36ecf: i2cdev_ioctl_rdwr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2cdev_ioctl_rdwr(struct i2c_client *client, unsigned int nmsgs, struct i2c_msg *msgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81ccc0b0)
Location: drivers/i2c/i2c-dev.c:235
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff81ccc0b0-ffffffff81ccc2df: i2cdev_ioctl_rdwr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2cdev_ioctl_rdwr(struct i2c_client *client, unsigned int nmsgs, struct i2c_msg *msgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81d33e20)
Location: drivers/i2c/i2c-dev.c:235
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff81d33e20-ffffffff81d34045: i2cdev_ioctl_rdwr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2cdev_ioctl_rdwr(struct i2c_client *client, unsigned int nmsgs, struct i2c_msg *msgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81de9ed0)
Location: drivers/i2c/i2c-dev.c:235
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff81de9ed0-ffffffff81dea0f9: i2cdev_ioctl_rdwr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffff800010ab7960)
Location: drivers/i2c/i2c-dev.c:233
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffff800010ab7960-ffff800010ab7c9c: i2cdev_ioctl_rdwr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int i2cdev_ioctl_rdwr(struct i2c_client *client, unsigned int nmsgs, struct i2c_msg *msgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (c0b97618)
Location: drivers/i2c/i2c-dev.c:233
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
c0b97618-c0b97890: i2cdev_ioctl_rdwr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i2cdev_ioctl_rdwr(struct i2c_client *client, unsigned int nmsgs, struct i2c_msg *msgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (c000000000b9aeb0)
Location: drivers/i2c/i2c-dev.c:233
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
c000000000b9aeb0-c000000000b9b1ac: i2cdev_ioctl_rdwr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int i2cdev_ioctl_rdwr(struct i2c_client *client, unsigned int nmsgs, struct i2c_msg *msgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffe0006bd4b2)
Location: drivers/i2c/i2c-dev.c:233
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffe0006bd4b2-ffffffe0006bd6a0: i2cdev_ioctl_rdwr (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81867740)
Location: drivers/i2c/i2c-dev.c:233
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff81867740-ffffffff8186796c: i2cdev_ioctl_rdwr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff818829f0)
Location: drivers/i2c/i2c-dev.c:233
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff818829f0-ffffffff81882c1c: i2cdev_ioctl_rdwr.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
