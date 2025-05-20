# Function: <code>del_usage_links</code>

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
In kernel/module.c (ffffffff811075da)
Location: kernel/module.c:1665
Inline: True
Inline callers:
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff8110e1b3)
Location: kernel/module.c:1670
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
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
In kernel/module.c (ffffffff81115b93)
Location: kernel/module.c:1662
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void del_usage_links(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115580)
Location: kernel/module.c:1664
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
```
**Symbols:**

```
ffffffff81115580-ffffffff811155ed: del_usage_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void del_usage_links(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81120b30)
Location: kernel/module.c:1672
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
```
**Symbols:**

```
ffffffff81120b30-ffffffff81120b9d: del_usage_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void del_usage_links(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112e460)
Location: kernel/module.c:1671
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff8112e460-ffffffff8112e4cd: del_usage_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void del_usage_links(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81139d60)
Location: kernel/module.c:1672
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81139d60-ffffffff81139dcd: del_usage_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void del_usage_links(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81145470)
Location: kernel/module.c:1667
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81145470-ffffffff811454dd: del_usage_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void del_usage_links(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81150f80)
Location: kernel/module.c:1722
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81150f80-ffffffff81150fed: del_usage_links (STB_LOCAL)
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
In kernel/module.c (ffffffff81163f2a)
Location: kernel/module.c:1744
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (ffffffff8115f73a)
Location: kernel/module.c:1805
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (ffffffff81160e1a)
Location: kernel/module.c:1715
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
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
In kernel/module.c (ffffffff81185fea)
Location: kernel/module.c:1717
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
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
In kernel/module/sysfs.c (ffffffff81192b2a)
Location: kernel/module/sysfs.c:243
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
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
In kernel/module/sysfs.c (ffffffff811d02da)
Location: kernel/module/sysfs.c:243
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
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
In kernel/module/sysfs.c (ffffffff811e44da)
Location: kernel/module/sysfs.c:243
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
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
In kernel/module/sysfs.c (ffffffff811fa22a)
Location: kernel/module/sysfs.c:243
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
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
void del_usage_links(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101bfe18)
Location: kernel/module.c:1722
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffff8000101bfe18-ffff8000101bfe98: del_usage_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void del_usage_links(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040756c)
Location: kernel/module.c:1722
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
c040756c-c04075d4: del_usage_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void del_usage_links(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000225980)
Location: kernel/module.c:1722
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
c000000000225980-c000000000225a30: del_usage_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void del_usage_links(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000142286)
Location: kernel/module.c:1722
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffe000142286-ffffffe0001422f8: del_usage_links (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void del_usage_links(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811495a0)
Location: kernel/module.c:1722
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811495a0-ffffffff8114960d: del_usage_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void del_usage_links(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113c850)
Location: kernel/module.c:1722
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff8113c850-ffffffff8113c8bd: del_usage_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void del_usage_links(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81147450)
Location: kernel/module.c:1722
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81147450-ffffffff811474bd: del_usage_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void del_usage_links(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81154060)
Location: kernel/module.c:1722
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81154060-ffffffff811540cd: del_usage_links (STB_LOCAL)
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
