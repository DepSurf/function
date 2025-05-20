# Function: <code>tomoyo_select_domain</code>

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
In security/tomoyo/common.c (ffffffff8136b3f4)
Location: security/tomoyo/common.c:970
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (ffffffff813a1602)
Location: security/tomoyo/common.c:970
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (ffffffff813b8182)
Location: security/tomoyo/common.c:970
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (ffffffff813ced33)
Location: security/tomoyo/common.c:970
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (ffffffff813f4edd)
Location: security/tomoyo/common.c:971
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (ffffffff8142610b)
Location: security/tomoyo/common.c:971
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (ffffffff81442806)
Location: security/tomoyo/common.c:971
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (ffffffff814703b6)
Location: security/tomoyo/common.c:989
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (ffffffff8148a17a)
Location: security/tomoyo/common.c:990
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tomoyo_select_domain(struct tomoyo_io_buffer *head, const char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814de3a0)
Location: security/tomoyo/common.c:990
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
**Symbols:**

```
ffffffff814de3a0-ffffffff814de635: tomoyo_select_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tomoyo_select_domain(struct tomoyo_io_buffer *head, const char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814fb7c0)
Location: security/tomoyo/common.c:990
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
**Symbols:**

```
ffffffff814fb7c0-ffffffff814fba5a: tomoyo_select_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tomoyo_select_domain(struct tomoyo_io_buffer *head, const char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81501f60)
Location: security/tomoyo/common.c:990
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
**Symbols:**

```
ffffffff81501f60-ffffffff815021f9: tomoyo_select_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool tomoyo_select_domain(struct tomoyo_io_buffer *head, const char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:990
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
**Symbols:**

```
ffffffff8155dd60-ffffffff8155e003: tomoyo_select_domain (STB_LOCAL)
ffffffff81cd5804-ffffffff81cd581f: tomoyo_select_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool tomoyo_select_domain(struct tomoyo_io_buffer *head, const char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
**Symbols:**

```
ffffffff815f9310-ffffffff815f95ba: tomoyo_select_domain (STB_LOCAL)
ffffffff81e88613-ffffffff81e88628: tomoyo_select_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool tomoyo_select_domain(struct tomoyo_io_buffer *head, const char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
**Symbols:**

```
ffffffff816a9ff0-ffffffff816aa29a: tomoyo_select_domain (STB_LOCAL)
ffffffff820741a2-ffffffff820741b7: tomoyo_select_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool tomoyo_select_domain(struct tomoyo_io_buffer *head, const char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
**Symbols:**

```
ffffffff816e2a30-ffffffff816e2cda: tomoyo_select_domain (STB_LOCAL)
ffffffff820f3d2b-ffffffff820f3d40: tomoyo_select_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool tomoyo_select_domain(struct tomoyo_io_buffer *head, const char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:982
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
**Symbols:**

```
ffffffff8171f6e0-ffffffff8171f98a: tomoyo_select_domain (STB_LOCAL)
ffffffff821d1170-ffffffff821d1185: tomoyo_select_domain.cold (STB_LOCAL)
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
In security/tomoyo/common.c (ffff80001057d5c4)
Location: security/tomoyo/common.c:990
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (c072fb80)
Location: security/tomoyo/common.c:990
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (c0000000006e8f38)
Location: security/tomoyo/common.c:990
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (ffffffe0003ce756)
Location: security/tomoyo/common.c:990
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (ffffffff8148275a)
Location: security/tomoyo/common.c:990
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (ffffffff8147317a)
Location: security/tomoyo/common.c:990
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (ffffffff8147e7fa)
Location: security/tomoyo/common.c:990
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
In security/tomoyo/common.c (ffffffff8149630a)
Location: security/tomoyo/common.c:990
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
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
