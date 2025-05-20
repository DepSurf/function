# Function: <code>mod_sysfs_teardown</code>

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
Location: kernel/module.c:1841
Inline: True
Inline callers:
  - kernel/module.c:free_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110e1a0)
Location: kernel/module.c:1845
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8110e1a0-ffffffff8110e310: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115b80)
Location: kernel/module.c:1837
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81115b80-ffffffff81115cf0: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81116ae0)
Location: kernel/module.c:1864
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81116ae0-ffffffff81116b9a: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811220e0)
Location: kernel/module.c:1872
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff811220e0-ffffffff8112219a: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112fbf0)
Location: kernel/module.c:1871
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8112fbf0-ffffffff8112fca6: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113b4a0)
Location: kernel/module.c:1872
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8113b4a0-ffffffff8113b556: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81146ae0)
Location: kernel/module.c:1879
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81146ae0-ffffffff81146b9f: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811526c0)
Location: kernel/module.c:1936
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff811526c0-ffffffff8115277f: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81163ef0)
Location: kernel/module.c:1958
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81163ef0-ffffffff811640a2: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115f700)
Location: kernel/module.c:2017
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8115f700-ffffffff8115f8b2: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81160de0)
Location: kernel/module.c:1927
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81160de0-ffffffff81160f8b: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81185fb0)
Location: kernel/module.c:1929
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81185fb0-ffffffff8118615b: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff81192af0)
Location: kernel/module/sysfs.c:423
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff81192af0-ffffffff81192ca9: mod_sysfs_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811d02a0)
Location: kernel/module/sysfs.c:423
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff811d02a0-ffffffff811d0459: mod_sysfs_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811e44a0)
Location: kernel/module/sysfs.c:423
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff811e44a0-ffffffff811e4659: mod_sysfs_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811fa1f0)
Location: kernel/module/sysfs.c:423
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff811fa1f0-ffffffff811fa3ad: mod_sysfs_teardown (STB_GLOBAL)
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
In kernel/module.c (ffff8000101c3128)
Location: kernel/module.c:1936
Inline: True
Inline callers:
  - kernel/module.c:free_module
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
In kernel/module.c (c040a330)
Location: kernel/module.c:1936
Inline: True
Inline callers:
  - kernel/module.c:free_module
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000227e40)
Location: kernel/module.c:1936
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
c000000000227e40-c000000000227f3c: mod_sysfs_teardown (STB_LOCAL)
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
In kernel/module.c (ffffffe0001440d4)
Location: kernel/module.c:1936
Inline: True
Inline callers:
  - kernel/module.c:free_module
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
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114ace0)
Location: kernel/module.c:1936
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8114ace0-ffffffff8114ad9f: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113df90)
Location: kernel/module.c:1936
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8113df90-ffffffff8113e04f: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81148b90)
Location: kernel/module.c:1936
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81148b90-ffffffff81148c4f: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81155810)
Location: kernel/module.c:1936
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81155810-ffffffff811558cf: mod_sysfs_teardown (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
