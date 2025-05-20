# Function: <code>selinux_sb_clone_mnt_opts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81345910)
Location: security/selinux/hooks.c:891
Inline: False
```
**Symbols:**

```
ffffffff81345910-ffffffff81345ab3: selinux_sb_clone_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137be70)
Location: security/selinux/hooks.c:965
Inline: False
```
**Symbols:**

```
ffffffff8137be70-ffffffff8137c054: selinux_sb_clone_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81392940)
Location: security/selinux/hooks.c:966
Inline: False
```
**Symbols:**

```
ffffffff81392940-ffffffff81392b24: selinux_sb_clone_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a6e80)
Location: security/selinux/hooks.c:918
Inline: False
```
**Symbols:**

```
ffffffff813a6e80-ffffffff813a7160: selinux_sb_clone_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cc8d0)
Location: security/selinux/hooks.c:921
Inline: False
```
**Symbols:**

```
ffffffff813cc8d0-ffffffff813ccbb0: selinux_sb_clone_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1007
Inline: False
```
**Symbols:**

```
ffffffff81400a00-ffffffff81400c95: selinux_sb_clone_mnt_opts (STB_LOCAL)
ffffffff81402c80-ffffffff81402ca4: selinux_sb_clone_mnt_opts.cold.83 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:887
Inline: False
```
**Symbols:**

```
ffffffff8141caf0-ffffffff8141cdf0: selinux_sb_clone_mnt_opts (STB_LOCAL)
ffffffff8141e7ed-ffffffff8141e811: selinux_sb_clone_mnt_opts.cold.78 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:912
Inline: False
```
**Symbols:**

```
ffffffff8144a520-ffffffff8144a826: selinux_sb_clone_mnt_opts (STB_LOCAL)
ffffffff8144c45a-ffffffff8144c480: selinux_sb_clone_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:914
Inline: False
```
**Symbols:**

```
ffffffff81464240-ffffffff81464546: selinux_sb_clone_mnt_opts (STB_LOCAL)
ffffffff8146624a-ffffffff81466270: selinux_sb_clone_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b8560)
Location: security/selinux/hooks.c:865
Inline: False
```
**Symbols:**

```
ffffffff814b8560-ffffffff814b8730: selinux_sb_clone_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d6470)
Location: security/selinux/hooks.c:866
Inline: False
```
**Symbols:**

```
ffffffff814d6470-ffffffff814d663d: selinux_sb_clone_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:923
Inline: False
```
**Symbols:**

```
ffffffff814dd440-ffffffff814dd694: selinux_sb_clone_mnt_opts (STB_LOCAL)
ffffffff81be25f3-ffffffff81be2619: selinux_sb_clone_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:905
Inline: False
```
**Symbols:**

```
ffffffff81536920-ffffffff81536b85: selinux_sb_clone_mnt_opts (STB_LOCAL)
ffffffff81cd3f31-ffffffff81cd3f89: selinux_sb_clone_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:866
Inline: False
```
**Symbols:**

```
ffffffff815ccb70-ffffffff815ccde5: selinux_sb_clone_mnt_opts (STB_LOCAL)
ffffffff81e86e37-ffffffff81e86e91: selinux_sb_clone_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:868
Inline: False
```
**Symbols:**

```
ffffffff81679e40-ffffffff8167a0d0: selinux_sb_clone_mnt_opts (STB_LOCAL)
ffffffff820737d9-ffffffff8207380e: selinux_sb_clone_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:874
Inline: False
```
**Symbols:**

```
ffffffff816b1f90-ffffffff816b221e: selinux_sb_clone_mnt_opts (STB_LOCAL)
ffffffff820f33d3-ffffffff820f33fc: selinux_sb_clone_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:915
Inline: False
```
**Symbols:**

```
ffffffff816ef020-ffffffff816ef2ae: selinux_sb_clone_mnt_opts (STB_LOCAL)
ffffffff821d054a-ffffffff821d0573: selinux_sb_clone_mnt_opts.cold (STB_LOCAL)
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
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff8000105522d0)
Location: security/selinux/hooks.c:914
Inline: False
```
**Symbols:**

```
ffff8000105522d0-ffff8000105525ec: selinux_sb_clone_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0704598)
Location: security/selinux/hooks.c:914
Inline: False
```
**Symbols:**

```
c0704598-c07048dc: selinux_sb_clone_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a8bb0)
Location: security/selinux/hooks.c:914
Inline: False
```
**Symbols:**

```
c0000000006a8bb0-c0000000006a8fe8: selinux_sb_clone_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003ab2b4)
Location: security/selinux/hooks.c:914
Inline: False
```
**Symbols:**

```
ffffffe0003ab2b4-ffffffe0003ab534: selinux_sb_clone_mnt_opts (STB_LOCAL)
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
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:914
Inline: False
```
**Symbols:**

```
ffffffff8145c820-ffffffff8145cb26: selinux_sb_clone_mnt_opts (STB_LOCAL)
ffffffff8145e82a-ffffffff8145e850: selinux_sb_clone_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:914
Inline: False
```
**Symbols:**

```
ffffffff8144d250-ffffffff8144d556: selinux_sb_clone_mnt_opts (STB_LOCAL)
ffffffff8144f25a-ffffffff8144f280: selinux_sb_clone_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:914
Inline: False
```
**Symbols:**

```
ffffffff814588c0-ffffffff81458bc6: selinux_sb_clone_mnt_opts (STB_LOCAL)
ffffffff8145a8ca-ffffffff8145a8f0: selinux_sb_clone_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int selinux_sb_clone_mnt_opts(const struct super_block *oldsb, struct super_block *newsb, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:914
Inline: False
```
**Symbols:**

```
ffffffff8146db60-ffffffff8146de66: selinux_sb_clone_mnt_opts (STB_LOCAL)
ffffffff81472047-ffffffff8147206d: selinux_sb_clone_mnt_opts.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int kern_flags</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int *set_kern_flags</code>
</li>
</ul>
</details>
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
