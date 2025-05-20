# Function: <code>dm_hash_remove_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff816a8310)
Location: drivers/md/dm-ioctl.c:279
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:dm_interface_exit
```
**Symbols:**

```
ffffffff816a8310-ffffffff816a845f: dm_hash_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81708790)
Location: drivers/md/dm-ioctl.c:279
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff81708790-ffffffff817088cb: dm_hash_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8173a660)
Location: drivers/md/dm-ioctl.c:279
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff8173a660-ffffffff8173a79b: dm_hash_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81756730)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff81756730-ffffffff8175686c: dm_hash_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff817c8940)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff817c8940-ffffffff817c8a7c: dm_hash_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff818113e0-ffffffff8181150f: dm_hash_remove_all (STB_LOCAL)
ffffffff81811ad2-ffffffff81811ae6: dm_hash_remove_all.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff8183d3e0-ffffffff8183d50c: dm_hash_remove_all (STB_LOCAL)
ffffffff8183da7a-ffffffff8183da8e: dm_hash_remove_all.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff8187ffb0-ffffffff818800db: dm_hash_remove_all (STB_LOCAL)
ffffffff81880705-ffffffff81880719: dm_hash_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff818b1e70-ffffffff818b1f9b: dm_hash_remove_all (STB_LOCAL)
ffffffff818b25c5-ffffffff818b25d9: dm_hash_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff81981950-ffffffff81981a7b: dm_hash_remove_all (STB_LOCAL)
ffffffff81982bac-ffffffff81982bc0: dm_hash_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff81985f70-ffffffff8198609b: dm_hash_remove_all (STB_LOCAL)
ffffffff81c284ea-ffffffff81c284fe: dm_hash_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:317
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff81969800-ffffffff81969949: dm_hash_remove_all (STB_LOCAL)
ffffffff81c1a54e-ffffffff81c1a562: dm_hash_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:318
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff81a11c70-ffffffff81a11dd3: dm_hash_remove_all (STB_LOCAL)
ffffffff81d2a385-ffffffff81d2a399: dm_hash_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:319
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff81b7a420-ffffffff81b7a5cf: dm_hash_remove_all (STB_LOCAL)
ffffffff81ef659f-ffffffff81ef65b3: dm_hash_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d18800)
Location: drivers/md/dm-ioctl.c:319
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff81d18800-ffffffff81d189ba: dm_hash_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d81b70)
Location: drivers/md/dm-ioctl.c:336
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff81d81b70-ffffffff81d81d2a: dm_hash_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81e391e0)
Location: drivers/md/dm-ioctl.c:336
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff81e391e0-ffffffff81e3939a: dm_hash_remove_all (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffff800010b08c98)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffff800010b08c98-ffff800010b08df4: dm_hash_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c0be769c)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
c0be769c-c0be77f4: dm_hash_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c000000000bfa830)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
c000000000bfa830-c000000000bfaa2c: dm_hash_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffe0006f7558)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffe0006f7558-ffffffe0006f76b4: dm_hash_remove_all (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff81857cf0-ffffffff81857e1b: dm_hash_remove_all (STB_LOCAL)
ffffffff81858445-ffffffff81858459: dm_hash_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff8181f300-ffffffff8181f42b: dm_hash_remove_all (STB_LOCAL)
ffffffff8181fa55-ffffffff8181fa69: dm_hash_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff818a7320-ffffffff818a744b: dm_hash_remove_all (STB_LOCAL)
ffffffff818a7a75-ffffffff818a7a89: dm_hash_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dm_hash_remove_all(bool keep_open_devices, bool mark_deferred, bool only_deferred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:280
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - drivers/md/dm-ioctl.c:dm_interface_init
  - drivers/md/dm-ioctl.c:remove_all
  - drivers/md/dm-ioctl.c:dm_deferred_remove
```
**Symbols:**

```
ffffffff818c3560-ffffffff818c368b: dm_hash_remove_all (STB_LOCAL)
ffffffff818c3cb5-ffffffff818c3cc9: dm_hash_remove_all.cold (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
