# Function: <code>watchdog_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8168b020)
Location: drivers/watchdog/watchdog_dev.c:465
Inline: False
```
**Symbols:**

```
ffffffff8168b020-ffffffff8168b0dd: watchdog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff816ec430)
Location: drivers/watchdog/watchdog_dev.c:735
Inline: False
```
**Symbols:**

```
ffffffff816ec430-ffffffff816ec584: watchdog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8171d420)
Location: drivers/watchdog/watchdog_dev.c:825
Inline: False
```
**Symbols:**

```
ffffffff8171d420-ffffffff8171d577: watchdog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817355f0)
Location: drivers/watchdog/watchdog_dev.c:833
Inline: False
```
**Symbols:**

```
ffffffff817355f0-ffffffff8173573d: watchdog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817a72f0)
Location: drivers/watchdog/watchdog_dev.c:836
Inline: False
```
**Symbols:**

```
ffffffff817a72f0-ffffffff817a7443: watchdog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:856
Inline: False
```
**Symbols:**

```
ffffffff817eee10-ffffffff817eef49: watchdog_release (STB_LOCAL)
ffffffff817ef7fa-ffffffff817ef817: watchdog_release.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:856
Inline: False
```
**Symbols:**

```
ffffffff8181ace0-ffffffff8181ae19: watchdog_release (STB_LOCAL)
ffffffff8181b6cc-ffffffff8181b6e9: watchdog_release.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:882
Inline: False
```
**Symbols:**

```
ffffffff8185cf10-ffffffff8185d055: watchdog_release (STB_LOCAL)
ffffffff8185d95b-ffffffff8185d976: watchdog_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:881
Inline: False
```
**Symbols:**

```
ffffffff8188ec40-ffffffff8188ed7d: watchdog_release (STB_LOCAL)
ffffffff8188f55e-ffffffff8188f579: watchdog_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:901
Inline: False
```
**Symbols:**

```
ffffffff8195d8e0-ffffffff8195da1d: watchdog_release (STB_LOCAL)
ffffffff8195e200-ffffffff8195e21b: watchdog_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:902
Inline: False
```
**Symbols:**

```
ffffffff819642e0-ffffffff8196441d: watchdog_release (STB_LOCAL)
ffffffff81c25f9c-ffffffff81c25fb7: watchdog_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:902
Inline: False
```
**Symbols:**

```
ffffffff81948700-ffffffff8194883d: watchdog_release (STB_LOCAL)
ffffffff81c18121-ffffffff81c1813c: watchdog_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:908
Inline: False
```
**Symbols:**

```
ffffffff819ed700-ffffffff819ed83d: watchdog_release (STB_LOCAL)
ffffffff81d2751d-ffffffff81d27538: watchdog_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:912
Inline: False
```
**Symbols:**

```
ffffffff81b54010-ffffffff81b54157: watchdog_release (STB_LOCAL)
ffffffff81ef33b0-ffffffff81ef33cb: watchdog_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81ceccb0)
Location: drivers/watchdog/watchdog_dev.c:920
Inline: False
```
**Symbols:**

```
ffffffff81ceccb0-ffffffff81cecd92: watchdog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81d559d0)
Location: drivers/watchdog/watchdog_dev.c:942
Inline: False
```
**Symbols:**

```
ffffffff81d559d0-ffffffff81d55ab2: watchdog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c8e0)
Location: drivers/watchdog/watchdog_dev.c:942
Inline: False
```
**Symbols:**

```
ffffffff81e0c8e0-ffffffff81e0c9c2: watchdog_release (STB_LOCAL)
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
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffff800010adfac0)
Location: drivers/watchdog/watchdog_dev.c:881
Inline: False
```
**Symbols:**

```
ffff800010adfac0-ffff800010adfc88: watchdog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (c0bc1484)
Location: drivers/watchdog/watchdog_dev.c:881
Inline: False
```
**Symbols:**

```
c0bc1484-c0bc1600: watchdog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (c000000000bc7c40)
Location: drivers/watchdog/watchdog_dev.c:881
Inline: False
```
**Symbols:**

```
c000000000bc7c40-c000000000bc7e5c: watchdog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d765a)
Location: drivers/watchdog/watchdog_dev.c:881
Inline: False
```
**Symbols:**

```
ffffffe0006d765a-ffffffe0006d7794: watchdog_release (STB_LOCAL)
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
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:881
Inline: False
```
**Symbols:**

```
ffffffff81834ac0-ffffffff81834bfd: watchdog_release (STB_LOCAL)
ffffffff818353de-ffffffff818353f9: watchdog_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:881
Inline: False
```
**Symbols:**

```
ffffffff817fc150-ffffffff817fc28d: watchdog_release (STB_LOCAL)
ffffffff817fca6e-ffffffff817fca89: watchdog_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:881
Inline: False
```
**Symbols:**

```
ffffffff818840f0-ffffffff8188422d: watchdog_release (STB_LOCAL)
ffffffff81884a0e-ffffffff81884a29: watchdog_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int watchdog_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:881
Inline: False
```
**Symbols:**

```
ffffffff8189fbb0-ffffffff8189fced: watchdog_release (STB_LOCAL)
ffffffff818a04ce-ffffffff818a04e9: watchdog_release.cold (STB_LOCAL)
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
