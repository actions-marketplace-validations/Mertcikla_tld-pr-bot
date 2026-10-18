Change group 1 of 2 (disconnected in the selected scope):

```mermaid
flowchart LR
%% tld-scene repo=1 key=166170d994fbd1f7e8430b469fcea762535ca67b39bb3896de6f062c0a6badd0
%% impact files=5 added=23 removed=23 complete=true basis=net_tree binary=0 affected=5 neighbours=0 authored=0 containers=0 radius=0

subgraph view_neg1["Changes"]
  direction LR
  el_neg1_neg1531887050["client_ip.go<br/>modified +2 −2"]
  el_neg1_neg499666324["logger.go<br/>modified +5 −5"]
  el_neg1_neg842292033["recoverer.go<br/>modified +3 −3"]
  el_neg1_neg471625360["terminal.go<br/>modified +1 −1"]
  el_neg1_neg1402201633["wrap_writer.go<br/>modified +12 −12"]
  el_neg1_neg499666324 --> el_neg1_neg1531887050
  el_neg1_neg499666324 --> el_neg1_neg842292033
  el_neg1_neg499666324 --> el_neg1_neg471625360
  el_neg1_neg499666324 --> el_neg1_neg1402201633
  el_neg1_neg842292033 --> el_neg1_neg499666324
  el_neg1_neg842292033 --> el_neg1_neg471625360
end
```

Change group 2 of 2 (disconnected in the selected scope):

```mermaid
flowchart LR
%% tld-scene repo=1 key=166170d994fbd1f7e8430b469fcea762535ca67b39bb3896de6f062c0a6badd0
%% impact files=3 added=7 removed=10 complete=true basis=net_tree binary=0 affected=3 neighbours=0 authored=0 containers=0 radius=0

subgraph view_neg1["Changes"]
  direction LR
  el_neg1_neg30531451["context.go<br/>modified +4 −7"]
  el_neg1_neg1104064361["mux.go<br/>modified +1 −1"]
  el_neg1_neg704988200["tree.go<br/>modified +2 −2"]
  el_neg1_neg30531451 --> el_neg1_neg704988200
  el_neg1_neg1104064361 --> el_neg1_neg30531451
  el_neg1_neg1104064361 --> el_neg1_neg704988200
  el_neg1_neg704988200 --> el_neg1_neg30531451
end
```

Also changed (no relationships in the selected scope):

- <code>.github/workflows/ci.yml</code> — modified (+1 / −1)
- <code>go.mod</code> — modified (+1 / −1)
- <code>middleware/basic_auth_test.go</code> — added (+59 / −0)
- <code>middleware/clean_path_test.go</code> — added (+23 / −0)
- <code>middleware/client_ip_bench_test.go</code> — modified (+2 / −2)
- <code>middleware/compress.go</code> — modified (+1 / −1)
- <code>middleware/heartbeat_test.go</code> — added (+31 / −0)
- <code>middleware/middleware_test.go</code> — modified (+60 / −1)
- <code>middleware/path_rewrite_test.go</code> — added (+26 / −0)
- <code>middleware/recoverer_test.go</code> — modified (+1 / −1)
- <code>middleware/terminal_test.go</code> — added (+36 / −0)
- <code>middleware/throttle_test.go</code> — modified (+1 / −2)
- <code>middleware/value.go</code> — modified (+1 / −1)
- <code>middleware/value_test.go</code> — added (+33 / −0)
- <code>middleware/wrap_writer_test.go</code> — modified (+88 / −15)
- <code>mux_test.go</code> — modified (+1 / −3)
- <code>tree_test.go</code> — modified (+1 / −3)
