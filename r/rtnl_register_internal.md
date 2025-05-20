# Function: <code>rtnl_register_internal</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a7140)
Location: net/core/rtnetlink.c:171
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff818a7140-ffffffff818a72a1: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ca880)
Location: net/core/rtnetlink.c:177
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff818ca880-ffffffff818ca9e1: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:172
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff819178c0-ffffffff81917a5c: rtnl_register_internal (STB_LOCAL)
ffffffff8191e6cc-ffffffff8191e735: rtnl_register_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81949f10)
Location: net/core/rtnetlink.c:172
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff81949f10-ffffffff8194a07d: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a19560)
Location: net/core/rtnetlink.c:172
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff81a19560-ffffffff81a196cd: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a19750)
Location: net/core/rtnetlink.c:172
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff81a19750-ffffffff81a198bd: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a00690)
Location: net/core/rtnetlink.c:172
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff81a00690-ffffffff81a007fd: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab2a00)
Location: net/core/rtnetlink.c:172
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff81ab2a00-ffffffff81ab2bc0: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2bbe0)
Location: net/core/rtnetlink.c:207
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff81c2bbe0-ffffffff81c2bdf2: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ddec60)
Location: net/core/rtnetlink.c:208
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff81ddec60-ffffffff81ddee72: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e4ff80)
Location: net/core/rtnetlink.c:211
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff81e4ff80-ffffffff81e50190: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f0efd0)
Location: net/core/rtnetlink.c:212
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff81f0efd0-ffffffff81f0f23b: rtnl_register_internal (STB_LOCAL)
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
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bebbd0)
Location: net/core/rtnetlink.c:172
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffff800010bebbd0-ffff800010bebd58: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d046d0)
Location: net/core/rtnetlink.c:172
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
c0d046d0-c0d0489c: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccef70)
Location: net/core/rtnetlink.c:172
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
c000000000ccef70-c000000000ccf1ec: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076f9de)
Location: net/core/rtnetlink.c:172
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffe00076f9de-ffffffe00076fb20: rtnl_register_internal (STB_LOCAL)
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
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e9ee0)
Location: net/core/rtnetlink.c:172
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff818e9ee0-ffffffff818ea04d: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a3d20)
Location: net/core/rtnetlink.c:172
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff818a3d20-ffffffff818a3e8d: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193af10)
Location: net/core/rtnetlink.c:172
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff8193af10-ffffffff8193b07d: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtnl_register_internal(struct module *owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195c750)
Location: net/core/rtnetlink.c:172
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_register
  - net/core/rtnetlink.c:rtnl_register_module
```
**Symbols:**

```
ffffffff8195c750-ffffffff8195c8bd: rtnl_register_internal (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
