# Function: <code>mls_write_level</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81351007)
Location: security/selinux/ss/policydb.c:2523
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81387067)
Location: security/selinux/ss/policydb.c:2523
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
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
In security/selinux/ss/policydb.c (ffffffff8139db17)
Location: security/selinux/ss/policydb.c:2527
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mls_write_level(struct mls_level *l, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b4170)
Location: security/selinux/ss/policydb.c:2566
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
**Symbols:**

```
ffffffff813b4170-ffffffff813b4195: mls_write_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mls_write_level(struct mls_level *l, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813da2c0)
Location: security/selinux/ss/policydb.c:2566
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
**Symbols:**

```
ffffffff813da2c0-ffffffff813da2e5: mls_write_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mls_write_level(struct mls_level *l, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8140a850)
Location: security/selinux/ss/policydb.c:2566
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
**Symbols:**

```
ffffffff8140a850-ffffffff8140a875: mls_write_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mls_write_level(struct mls_level *l, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81426b00)
Location: security/selinux/ss/policydb.c:2591
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
**Symbols:**

```
ffffffff81426b00-ffffffff81426b25: mls_write_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mls_write_level(struct mls_level *l, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814543d0)
Location: security/selinux/ss/policydb.c:2537
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
**Symbols:**

```
ffffffff814543d0-ffffffff814543f5: mls_write_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mls_write_level(struct mls_level *l, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8146e170)
Location: security/selinux/ss/policydb.c:2539
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
**Symbols:**

```
ffffffff8146e170-ffffffff8146e195: mls_write_level (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff814c50dc)
Location: security/selinux/ss/policydb.c:2681
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
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
In security/selinux/ss/policydb.c (ffffffff814e2ebc)
Location: security/selinux/ss/policydb.c:2723
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
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
In security/selinux/ss/policydb.c (ffffffff814e9e2c)
Location: security/selinux/ss/policydb.c:2721
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
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
In security/selinux/ss/policydb.c (ffffffff8154379c)
Location: security/selinux/ss/policydb.c:2720
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
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
In security/selinux/ss/policydb.c (ffffffff815dbfb9)
Location: security/selinux/ss/policydb.c:2714
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
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
In security/selinux/ss/policydb.c (ffffffff8168aa8c)
Location: security/selinux/ss/policydb.c:2714
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816bf76c)
Location: security/selinux/ss/policydb.c:2718
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816fbfac)
Location: security/selinux/ss/policydb.c:2743
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
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
int mls_write_level(struct mls_level *l, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffff80001055d630)
Location: security/selinux/ss/policydb.c:2539
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
**Symbols:**

```
ffff80001055d630-ffff80001055d680: mls_write_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mls_write_level(struct mls_level *l, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0711b4c)
Location: security/selinux/ss/policydb.c:2539
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
**Symbols:**

```
c0711b4c-c0711b8c: mls_write_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mls_write_level(struct mls_level *l, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006bd3b0)
Location: security/selinux/ss/policydb.c:2539
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
**Symbols:**

```
c0000000006bd3b0-c0000000006bd40c: mls_write_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mls_write_level(struct mls_level *l, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b3f32)
Location: security/selinux/ss/policydb.c:2539
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
**Symbols:**

```
ffffffe0003b3f32-ffffffe0003b3f98: mls_write_level (STB_LOCAL)
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
int mls_write_level(struct mls_level *l, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81466750)
Location: security/selinux/ss/policydb.c:2539
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
**Symbols:**

```
ffffffff81466750-ffffffff81466775: mls_write_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int mls_write_level(struct mls_level *l, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81457180)
Location: security/selinux/ss/policydb.c:2539
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
**Symbols:**

```
ffffffff81457180-ffffffff814571a5: mls_write_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mls_write_level(struct mls_level *l, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814627f0)
Location: security/selinux/ss/policydb.c:2539
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
**Symbols:**

```
ffffffff814627f0-ffffffff81462815: mls_write_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mls_write_level(struct mls_level *l, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81479ff0)
Location: security/selinux/ss/policydb.c:2539
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:sens_write
```
**Symbols:**

```
ffffffff81479ff0-ffffffff8147a015: mls_write_level (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
