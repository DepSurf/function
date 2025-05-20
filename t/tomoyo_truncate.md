# Function: <code>tomoyo_truncate</code>

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
In security/tomoyo/common.c (ffffffff81368575)
Location: security/tomoyo/common.c:1919
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
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
In security/tomoyo/common.c (ffffffff813a0f59)
Location: security/tomoyo/common.c:1919
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
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
In security/tomoyo/common.c (ffffffff813b7ade)
Location: security/tomoyo/common.c:1919
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813cb4a0)
Location: security/tomoyo/common.c:1919
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
**Symbols:**

```
ffffffff813cb4a0-ffffffff813cb4c7: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813f1930)
Location: security/tomoyo/common.c:1920
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
**Symbols:**

```
ffffffff813f1930-ffffffff813f1957: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81422760)
Location: security/tomoyo/common.c:1920
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
**Symbols:**

```
ffffffff81422760-ffffffff81422787: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8143edc0)
Location: security/tomoyo/common.c:1921
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
**Symbols:**

```
ffffffff8143edc0-ffffffff8143ede7: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8146ca10)
Location: security/tomoyo/common.c:1979
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
**Symbols:**

```
ffffffff8146ca10-ffffffff8146ca37: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814867f0)
Location: security/tomoyo/common.c:1981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
**Symbols:**

```
ffffffff814867f0-ffffffff81486817: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814dc8c0)
Location: security/tomoyo/common.c:1981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
```
**Symbols:**

```
ffffffff814dc8c0-ffffffff814dc8e7: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814f9ce0)
Location: security/tomoyo/common.c:1981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
```
**Symbols:**

```
ffffffff814f9ce0-ffffffff814f9d07: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81500a20)
Location: security/tomoyo/common.c:1981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
```
**Symbols:**

```
ffffffff81500a20-ffffffff81500a47: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8155bd30)
Location: security/tomoyo/common.c:1981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
```
**Symbols:**

```
ffffffff8155bd30-ffffffff8155bd57: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff815f6db0)
Location: security/tomoyo/common.c:1972
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
```
**Symbols:**

```
ffffffff815f6db0-ffffffff815f6ddd: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff816a7950)
Location: security/tomoyo/common.c:1972
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
```
**Symbols:**

```
ffffffff816a7950-ffffffff816a797d: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff816e0350)
Location: security/tomoyo/common.c:1972
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
```
**Symbols:**

```
ffffffff816e0350-ffffffff816e037d: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8171cfd0)
Location: security/tomoyo/common.c:1973
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
```
**Symbols:**

```
ffffffff8171cfd0-ffffffff8171cffd: tomoyo_truncate (STB_LOCAL)
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
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffff800010578ce8)
Location: security/tomoyo/common.c:1981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
**Symbols:**

```
ffff800010578ce8-ffff800010578d38: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (c072bd64)
Location: security/tomoyo/common.c:1981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
**Symbols:**

```
c072bd64-c072bda8: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (c0000000006e2be0)
Location: security/tomoyo/common.c:1981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
**Symbols:**

```
c0000000006e2be0-c0000000006e2c44: tomoyo_truncate (STB_LOCAL)
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
In security/tomoyo/common.c (ffffffe0003ce17c)
Location: security/tomoyo/common.c:1981
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
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
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8147edd0)
Location: security/tomoyo/common.c:1981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
**Symbols:**

```
ffffffff8147edd0-ffffffff8147edf7: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8146f7f0)
Location: security/tomoyo/common.c:1981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
**Symbols:**

```
ffffffff8146f7f0-ffffffff8146f817: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8147ae70)
Location: security/tomoyo/common.c:1981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
**Symbols:**

```
ffffffff8147ae70-ffffffff8147ae97: tomoyo_truncate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tomoyo_truncate(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81492a60)
Location: security/tomoyo/common.c:1981
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
**Symbols:**

```
ffffffff81492a60-ffffffff81492a87: tomoyo_truncate (STB_LOCAL)
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
