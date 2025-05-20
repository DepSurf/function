# Function: <code>__bpf_trace_napi_poll</code>

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
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c3880)
Location: include/trace/events/napi.h:14
Inline: False
```
**Symbols:**

```
ffffffff818c3880-ffffffff818c388f: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818ec780)
Location: include/trace/events/napi.h:14
Inline: False
```
**Symbols:**

```
ffffffff818ec780-ffffffff818ec78f: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8193c900)
Location: include/trace/events/napi.h:14
Inline: False
```
**Symbols:**

```
ffffffff8193c900-ffffffff8193c90f: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8196f790)
Location: include/trace/events/napi.h:14
Inline: False
```
**Symbols:**

```
ffffffff8196f790-ffffffff8196f79f: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a436a0)
Location: include/trace/events/napi.h:14
Inline: True
```
**Symbols:**

```
ffffffff81a436a0-ffffffff81a436af: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a472a0)
Location: include/trace/events/napi.h:14
Inline: True
```
**Symbols:**

```
ffffffff81a472a0-ffffffff81a472af: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a2bf50)
Location: include/trace/events/napi.h:14
Inline: True
```
**Symbols:**

```
ffffffff81a2bf50-ffffffff81a2bf5f: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81ae0fd0)
Location: include/trace/events/napi.h:14
Inline: True
```
**Symbols:**

```
ffffffff81ae0fd0-ffffffff81ae0fdf: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81c641d0)
Location: include/trace/events/napi.h:14
Inline: True
```
**Symbols:**

```
ffffffff81c641d0-ffffffff81c641eb: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e1b230)
Location: include/trace/events/napi.h:14
Inline: True
```
**Symbols:**

```
ffffffff81e1b230-ffffffff81e1b24b: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e8f5f0)
Location: include/trace/events/napi.h:14
Inline: True
```
**Symbols:**

```
ffffffff81e8f5f0-ffffffff81e8f60b: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f51600)
Location: include/trace/events/napi.h:14
Inline: True
```
**Symbols:**

```
ffffffff81f51600-ffffffff81f5161b: __bpf_trace_napi_poll (STB_LOCAL)
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
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c14ed0)
Location: include/trace/events/napi.h:14
Inline: False
```
**Symbols:**

```
ffff800010c14ed0-ffff800010c14eec: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d2dcc4)
Location: include/trace/events/napi.h:14
Inline: False
```
**Symbols:**

```
c0d2dcc4-c0d2dcfc: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d04810)
Location: include/trace/events/napi.h:14
Inline: False
```
**Symbols:**

```
c000000000d04810-c000000000d04844: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8190f760)
Location: include/trace/events/napi.h:14
Inline: False
```
**Symbols:**

```
ffffffff8190f760-ffffffff8190f76f: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c9520)
Location: include/trace/events/napi.h:14
Inline: False
```
**Symbols:**

```
ffffffff818c9520-ffffffff818c952f: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81960790)
Location: include/trace/events/napi.h:14
Inline: False
```
**Symbols:**

```
ffffffff81960790-ffffffff8196079f: __bpf_trace_napi_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_napi_poll(void *__data, struct napi_struct *napi, int work, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81982a00)
Location: include/trace/events/napi.h:14
Inline: False
```
**Symbols:**

```
ffffffff81982a00-ffffffff81982a0f: __bpf_trace_napi_poll (STB_LOCAL)
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
