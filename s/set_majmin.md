# Function: <code>set_majmin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/device_cgroup.c (ffffffff81395940)
Location: security/device_cgroup.c:268
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff81395940-ffffffff81395953: set_majmin.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/device_cgroup.c (ffffffff813d1dbd)
Location: security/device_cgroup.c:268
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff813d1680-ffffffff813d1693: set_majmin.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/device_cgroup.c (ffffffff813e94da)
Location: security/device_cgroup.c:268
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff813e8db0-ffffffff813e8dc3: set_majmin.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/device_cgroup.c (ffffffff813f591a)
Location: security/device_cgroup.c:268
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff813f5170-ffffffff813f51d5: set_majmin.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void set_majmin(char *str, unsigned int m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff8141d330)
Location: security/device_cgroup.c:260
Inline: True
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff8141d330-ffffffff8141d357: set_majmin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_majmin(char *str, unsigned int m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff8144f5f0)
Location: security/device_cgroup.c:260
Inline: True
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff8144f5f0-ffffffff8144f617: set_majmin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_majmin(char *str, unsigned int m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff8146c5d0)
Location: security/device_cgroup.c:260
Inline: True
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff8146c5d0-ffffffff8146c5f7: set_majmin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void set_majmin(char *str, unsigned int m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81499cd0)
Location: security/device_cgroup.c:259
Inline: True
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff81499cd0-ffffffff81499cf7: set_majmin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_majmin(char *str, unsigned int m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff814b3ed0)
Location: security/device_cgroup.c:259
Inline: True
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff814b3ed0-ffffffff814b3ef7: set_majmin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81513c04)
Location: security/device_cgroup.c:261
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81530d54)
Location: security/device_cgroup.c:261
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
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
In security/device_cgroup.c (ffffffff81536f54)
Location: security/device_cgroup.c:261
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
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
In security/device_cgroup.c (ffffffff815956c4)
Location: security/device_cgroup.c:261
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
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
In security/device_cgroup.c (ffffffff81637936)
Location: security/device_cgroup.c:262
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
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
In security/device_cgroup.c (ffffffff816eec5e)
Location: security/device_cgroup.c:273
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void set_majmin(char *str, unsigned int m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff817291db)
Location: security/device_cgroup.c:273
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff81728850-ffffffff8172888f: set_majmin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void set_majmin(char *str, unsigned int m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff8176a53b)
Location: security/device_cgroup.c:273
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff81769b80-ffffffff81769bbf: set_majmin (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void set_majmin(char *str, unsigned int m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffff8000105abdd8)
Location: security/device_cgroup.c:259
Inline: True
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffff8000105abdd8-ffff8000105abe30: set_majmin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_majmin(char *str, unsigned int m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (c075b8c8)
Location: security/device_cgroup.c:259
Inline: True
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
c075b8c8-c075b90c: set_majmin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void set_majmin(char *str, unsigned int m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (c000000000729f80)
Location: security/device_cgroup.c:259
Inline: True
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
c000000000729f80-c000000000729fe0: set_majmin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/device_cgroup.c (ffffffe0003f4da8)
Location: security/device_cgroup.c:259
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffe0003f4756-ffffffe0003f477e: set_majmin.part.0 (STB_LOCAL)
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
void set_majmin(char *str, unsigned int m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff814ac4b0)
Location: security/device_cgroup.c:259
Inline: True
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff814ac4b0-ffffffff814ac4d7: set_majmin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_majmin(char *str, unsigned int m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff8149ced0)
Location: security/device_cgroup.c:259
Inline: True
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff8149ced0-ffffffff8149cef7: set_majmin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_majmin(char *str, unsigned int m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff814a8550)
Location: security/device_cgroup.c:259
Inline: True
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff814a8550-ffffffff814a8577: set_majmin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_majmin(char *str, unsigned int m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff814c0f00)
Location: security/device_cgroup.c:259
Inline: True
Direct callers:
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
  - security/device_cgroup.c:devcgroup_seq_show
```
**Symbols:**

```
ffffffff814c0f00-ffffffff814c0f27: set_majmin (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
