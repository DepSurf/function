# Function: <code>vma_ra_enabled_show</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81224f20)
Location: mm/swap_state.c:768
Inline: False
```
**Symbols:**

```
ffffffff81224f20-ffffffff81224f55: vma_ra_enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812474f0)
Location: mm/swap_state.c:800
Inline: False
```
**Symbols:**

```
ffffffff812474f0-ffffffff81247525: vma_ra_enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8125b960)
Location: mm/swap_state.c:762
Inline: False
```
**Symbols:**

```
ffffffff8125b960-ffffffff8125b995: vma_ra_enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81276ae0)
Location: mm/swap_state.c:790
Inline: False
```
**Symbols:**

```
ffffffff81276ae0-ffffffff81276b15: vma_ra_enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812865d0)
Location: mm/swap_state.c:790
Inline: False
```
**Symbols:**

```
ffffffff812865d0-ffffffff81286605: vma_ra_enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812b8b60)
Location: mm/swap_state.c:808
Inline: False
```
**Symbols:**

```
ffffffff812b8b60-ffffffff812b8b95: vma_ra_enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812c3fc0)
Location: mm/swap_state.c:902
Inline: False
```
**Symbols:**

```
ffffffff812c3fc0-ffffffff812c3ff5: vma_ra_enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812cadb0)
Location: mm/swap_state.c:871
Inline: False
```
**Symbols:**

```
ffffffff812cadb0-ffffffff812cade5: vma_ra_enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:858
Inline: False
```
**Symbols:**

```
ffffffff8130fdb0-ffffffff8130fdfa: vma_ra_enabled_show (STB_LOCAL)
ffffffff81cbe960-ffffffff81cbe974: vma_ra_enabled_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:872
Inline: False
```
**Symbols:**

```
ffffffff8137a780-ffffffff8137a7d7: vma_ra_enabled_show (STB_LOCAL)
ffffffff81e70aba-ffffffff81e70acf: vma_ra_enabled_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:856
Inline: False
```
**Symbols:**

```
ffffffff813f8280-ffffffff813f82d7: vma_ra_enabled_show (STB_LOCAL)
ffffffff82065aa2-ffffffff82065ab7: vma_ra_enabled_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:865
Inline: False
```
**Symbols:**

```
ffffffff8142b290-ffffffff8142b2e7: vma_ra_enabled_show (STB_LOCAL)
ffffffff820e5282-ffffffff820e5297: vma_ra_enabled_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:897
Inline: False
```
**Symbols:**

```
ffffffff81464a80-ffffffff81464ad7: vma_ra_enabled_show (STB_LOCAL)
ffffffff821c23f9-ffffffff821c240e: vma_ra_enabled_show.cold (STB_LOCAL)
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
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffff800010320d20)
Location: mm/swap_state.c:790
Inline: False
```
**Symbols:**

```
ffff800010320d20-ffff800010320d78: vma_ra_enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c0539694)
Location: mm/swap_state.c:790
Inline: False
```
**Symbols:**

```
c0539694-c05396e4: vma_ra_enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c0000000003f6120)
Location: mm/swap_state.c:790
Inline: False
```
**Symbols:**

```
c0000000003f6120-c0000000003f6184: vma_ra_enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffe00022221c)
Location: mm/swap_state.c:790
Inline: False
```
**Symbols:**

```
ffffffe00022221c-ffffffe000222268: vma_ra_enabled_show (STB_LOCAL)
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
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127ec20)
Location: mm/swap_state.c:748
Inline: False
```
**Symbols:**

```
ffffffff8127ec20-ffffffff8127ec55: vma_ra_enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81270a50)
Location: mm/swap_state.c:790
Inline: False
```
**Symbols:**

```
ffffffff81270a50-ffffffff81270a85: vma_ra_enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127c9c0)
Location: mm/swap_state.c:790
Inline: False
```
**Symbols:**

```
ffffffff8127c9c0-ffffffff8127c9f5: vma_ra_enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t vma_ra_enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8128c590)
Location: mm/swap_state.c:790
Inline: False
```
**Symbols:**

```
ffffffff8128c590-ffffffff8128c5c5: vma_ra_enabled_show (STB_LOCAL)
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
