# Function: <code>__audit_fanotify</code>

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
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81149bd0)
Location: kernel/auditsc.c:2416
Inline: False
```
**Symbols:**

```
ffffffff81149bd0-ffffffff81149c04: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811584d0)
Location: kernel/auditsc.c:2424
Inline: False
```
**Symbols:**

```
ffffffff811584d0-ffffffff81158504: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811654d0)
Location: kernel/auditsc.c:2409
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff811654d0-ffffffff81165504: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81171f60)
Location: kernel/auditsc.c:2513
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81171f60-ffffffff81171f94: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117de10)
Location: kernel/auditsc.c:2513
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff8117de10-ffffffff8117de44: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811910c0)
Location: kernel/auditsc.c:2565
Inline: False
```
**Symbols:**

```
ffffffff811910c0-ffffffff811910f4: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118e2e0)
Location: kernel/auditsc.c:2582
Inline: False
```
**Symbols:**

```
ffffffff8118e2e0-ffffffff8118e314: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118f260)
Location: kernel/auditsc.c:2580
Inline: False
```
**Symbols:**

```
ffffffff8118f260-ffffffff8118f294: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b8140)
Location: kernel/auditsc.c:2598
Inline: False
```
**Symbols:**

```
ffffffff811b8140-ffffffff811b8174: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811eb0c0)
Location: kernel/auditsc.c:2880
Inline: False
```
**Symbols:**

```
ffffffff811eb0c0-ffffffff811eb105: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81231420)
Location: kernel/auditsc.c:2858
Inline: False
```
**Symbols:**

```
ffffffff81231420-ffffffff81231465: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __audit_fanotify(u32 response, struct fanotify_response_info_audit_rule *friar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81247fc0)
Location: kernel/auditsc.c:2857
Inline: False
```
**Symbols:**

```
ffffffff81247fc0-ffffffff8124807e: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __audit_fanotify(u32 response, struct fanotify_response_info_audit_rule *friar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81261e20)
Location: kernel/auditsc.c:2847
Inline: False
```
**Symbols:**

```
ffffffff81261e20-ffffffff81261ede: __audit_fanotify (STB_GLOBAL)
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
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f2c58)
Location: kernel/auditsc.c:2513
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffff8000101f2c58-ffff8000101f2c9c: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c04331d4)
Location: kernel/auditsc.c:2513
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
c04331d4-c0433224: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000267580)
Location: kernel/auditsc.c:2513
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
c000000000267580-c0000000002675d0: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000166274)
Location: kernel/auditsc.c:2513
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffe000166274-ffffffe0001662b4: __audit_fanotify (STB_GLOBAL)
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
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81176430)
Location: kernel/auditsc.c:2513
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81176430-ffffffff81176464: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811695d0)
Location: kernel/auditsc.c:2513
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff811695d0-ffffffff81169604: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81174200)
Location: kernel/auditsc.c:2513
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81174200-ffffffff81174234: __audit_fanotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __audit_fanotify(unsigned int response);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81181ae0)
Location: kernel/auditsc.c:2513
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81181ae0-ffffffff81181b14: __audit_fanotify (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fanotify_response_info_audit_rule *friar</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int response</code> ➡️ <code>u32 response</code>
</li>
</ul>
</details>
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
