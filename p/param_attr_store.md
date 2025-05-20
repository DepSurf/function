# Function: <code>param_attr_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8109f550)
Location: kernel/params.c:612
Inline: False
```
**Symbols:**

```
ffffffff8109f550-ffffffff8109f610: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a2c00)
Location: kernel/params.c:612
Inline: False
```
**Symbols:**

```
ffffffff810a2c00-ffffffff810a2cc0: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a7ea0)
Location: kernel/params.c:612
Inline: False
```
**Symbols:**

```
ffffffff810a7ea0-ffffffff810a7f60: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a4e40)
Location: kernel/params.c:560
Inline: False
```
**Symbols:**

```
ffffffff810a4e40-ffffffff810a4f00: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810ab1d0)
Location: kernel/params.c:571
Inline: False
```
**Symbols:**

```
ffffffff810ab1d0-ffffffff810ab2b0: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810b1c60)
Location: kernel/params.c:571
Inline: False
```
**Symbols:**

```
ffffffff810b1c60-ffffffff810b1d52: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810bada0)
Location: kernel/params.c:571
Inline: False
```
**Symbols:**

```
ffffffff810bada0-ffffffff810bae92: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c0cc0)
Location: kernel/params.c:559
Inline: False
```
**Symbols:**

```
ffffffff810c0cc0-ffffffff810c0db3: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c70c0)
Location: kernel/params.c:554
Inline: False
```
**Symbols:**

```
ffffffff810c70c0-ffffffff810c71b0: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:554
Inline: False
```
**Symbols:**

```
ffffffff810cf670-ffffffff810cf76e: param_attr_store (STB_LOCAL)
ffffffff810cfe13-ffffffff810cfe28: param_attr_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:555
Inline: False
```
**Symbols:**

```
ffffffff810ca1c0-ffffffff810ca2be: param_attr_store (STB_LOCAL)
ffffffff81bdc1e3-ffffffff81bdc1f8: param_attr_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:555
Inline: False
```
**Symbols:**

```
ffffffff810cbb00-ffffffff810cbbfe: param_attr_store (STB_LOCAL)
ffffffff81bce2ed-ffffffff81bce302: param_attr_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:573
Inline: False
```
**Symbols:**

```
ffffffff810ded00-ffffffff810dedfe: param_attr_store (STB_LOCAL)
ffffffff81ca562b-ffffffff81ca5640: param_attr_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810f8540)
Location: kernel/params.c:573
Inline: False
```
**Symbols:**

```
ffffffff810f8540-ffffffff810f8643: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8111afd0)
Location: kernel/params.c:573
Inline: False
```
**Symbols:**

```
ffffffff8111afd0-ffffffff8111b0d3: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81128240)
Location: kernel/params.c:574
Inline: False
```
**Symbols:**

```
ffffffff81128240-ffffffff81128343: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81132860)
Location: kernel/params.c:576
Inline: False
```
**Symbols:**

```
ffffffff81132860-ffffffff81132963: param_attr_store (STB_LOCAL)
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
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffff8000101260c0)
Location: kernel/params.c:554
Inline: False
```
**Symbols:**

```
ffff8000101260c0-ffff8000101261c4: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (c0378fc8)
Location: kernel/params.c:554
Inline: False
```
**Symbols:**

```
c0378fc8-c03790a0: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (c0000000001704f0)
Location: kernel/params.c:554
Inline: False
```
**Symbols:**

```
c0000000001704f0-c00000000017066c: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffe0000ddbb6)
Location: kernel/params.c:554
Inline: False
```
**Symbols:**

```
ffffffe0000ddbb6-ffffffe0000ddc8c: param_attr_store (STB_LOCAL)
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
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c1440)
Location: kernel/params.c:554
Inline: False
```
**Symbols:**

```
ffffffff810c1440-ffffffff810c1530: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810afc30)
Location: kernel/params.c:554
Inline: False
```
**Symbols:**

```
ffffffff810afc30-ffffffff810afd20: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c0990)
Location: kernel/params.c:554
Inline: False
```
**Symbols:**

```
ffffffff810c0990-ffffffff810c0a80: param_attr_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t param_attr_store(struct module_attribute *mattr, struct module_kobject *mk, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c8f40)
Location: kernel/params.c:554
Inline: False
```
**Symbols:**

```
ffffffff810c8f40-ffffffff810c9030: param_attr_store (STB_LOCAL)
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
