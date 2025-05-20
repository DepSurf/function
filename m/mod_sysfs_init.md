# Function: <code>mod_sysfs_init</code>

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
In kernel/module.c (ffffffff8110952b)
Location: kernel/module.c:1728
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff8111114d)
Location: kernel/module.c:1732
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff81118264)
Location: kernel/module.c:1724
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81119f37)
Location: kernel/module.c:1746
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811254eb)
Location: kernel/module.c:1754
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81130605)
Location: kernel/module.c:1753
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113beb5)
Location: kernel/module.c:1754
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811474f5)
Location: kernel/module.c:1761
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (ffffffff81153315)
Location: kernel/module.c:1818
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mod_sysfs_init(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1840
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81164280-ffffffff81164390: mod_sysfs_init (STB_LOCAL)
ffffffff81167ba9-ffffffff81167be5: mod_sysfs_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mod_sysfs_init(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1901
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81160410-ffffffff81160520: mod_sysfs_init (STB_LOCAL)
ffffffff81be40bb-ffffffff81be40f7: mod_sysfs_init.cold (STB_LOCAL)
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
In kernel/module.c (ffffffff811618a6)
Location: kernel/module.c:1811
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (ffffffff81186a76)
Location: kernel/module.c:1813
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module/sysfs.c (ffffffff81192841)
Location: kernel/module/sysfs.c:338
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
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
In kernel/module/sysfs.c (ffffffff811cfffb)
Location: kernel/module/sysfs.c:338
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
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
In kernel/module/sysfs.c (ffffffff811e41f7)
Location: kernel/module/sysfs.c:338
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
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
In kernel/module/sysfs.c (ffffffff811f9f47)
Location: kernel/module/sysfs.c:338
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
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
In kernel/module.c (ffff8000101c1c48)
Location: kernel/module.c:1818
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (c0409854)
Location: kernel/module.c:1818
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (c000000000228c64)
Location: kernel/module.c:1818
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (ffffffe00014399a)
Location: kernel/module.c:1818
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (ffffffff8114b935)
Location: kernel/module.c:1818
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (ffffffff8113ebe5)
Location: kernel/module.c:1818
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (ffffffff811497e5)
Location: kernel/module.c:1818
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (ffffffff811564a5)
Location: kernel/module.c:1818
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
</ul>
