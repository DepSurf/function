# Function: <code>__hvc_poll</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8164b700)
Location: drivers/tty/hvc/hvc_console.c:643
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff8164b700-ffffffff8164ba38: __hvc_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8167ff60)
Location: drivers/tty/hvc/hvc_console.c:643
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff8167ff60-ffffffff81680298: __hvc_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff816a2610)
Location: drivers/tty/hvc/hvc_console.c:643
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff816a2610-ffffffff816a2948: __hvc_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81754ab0)
Location: drivers/tty/hvc/hvc_console.c:632
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff81754ab0-ffffffff81754de9: __hvc_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8176fdb0)
Location: drivers/tty/hvc/hvc_console.c:632
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff8176fdb0-ffffffff817700e4: __hvc_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81753860)
Location: drivers/tty/hvc/hvc_console.c:632
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff81753860-ffffffff81753b97: __hvc_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff817d6d40)
Location: drivers/tty/hvc/hvc_console.c:632
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff817d6d40-ffffffff817d70e3: __hvc_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81914e30)
Location: drivers/tty/hvc/hvc_console.c:632
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff81914e30-ffffffff8191523d: __hvc_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:632
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff81a70080-ffffffff81a704b5: __hvc_poll (STB_LOCAL)
ffffffff82095b81-ffffffff82095bf7: __hvc_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:632
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff81aba840-ffffffff81abac72: __hvc_poll (STB_LOCAL)
ffffffff821169c1-ffffffff82116a37: __hvc_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:632
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff81b0d590-ffffffff81b0d9e2: __hvc_poll (STB_LOCAL)
ffffffff821f4715-ffffffff821f478a: __hvc_poll.cold (STB_LOCAL)
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
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffff80001087aad8)
Location: drivers/tty/hvc/hvc_console.c:643
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffff80001087aad8-ffff80001087af68: __hvc_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (c097c968)
Location: drivers/tty/hvc/hvc_console.c:643
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
c097c968-c097cca8: __hvc_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (c000000000921b40)
Location: drivers/tty/hvc/hvc_console.c:643
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
c000000000921b40-c000000000921fdc: __hvc_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffe00054a8b6)
Location: drivers/tty/hvc/hvc_console.c:643
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffe00054a8b6-ffffffe00054ab8a: __hvc_poll (STB_LOCAL)
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
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81668070)
Location: drivers/tty/hvc/hvc_console.c:643
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff81668070-ffffffff816683a8: __hvc_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff816483f0)
Location: drivers/tty/hvc/hvc_console.c:643
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff816483f0-ffffffff81648728: __hvc_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81696450)
Location: drivers/tty/hvc/hvc_console.c:643
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff81696450-ffffffff81696788: __hvc_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct *hp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff816b0a10)
Location: drivers/tty/hvc/hvc_console.c:643
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff816b0a10-ffffffff816b0d3e: __hvc_poll (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
