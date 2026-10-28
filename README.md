# Last MCP owned public static test fixture

Owner: GitHub account **lastmcp**. Intentionally retained, non-production static provider-test infrastructure. No secrets, private data, external scripts, analytics, forms, uploads or service workers. GitHub Pages branch publication only; no custom workflow, runner, domain or payment commitment.

## Fixtures and licensing scope

- `index.html`, `fixture-red.png`, `fixture-blue.png` and `tone.wav` are the existing original Last MCP static HTML, tiny synthetic PNGs and mathematical **non-speech** tone. Those four files are preserved byte-for-byte.
- `spoken-fixture.wav` is **synthesized speech**, generated with CMU Flite 2.2 and its bundled `cmu_us_kal` voice, using unchanged libraries. Its authored input text is: "Hello world. This is a synthetic Last MCP audio test."
- The synthesized voice and its third-party components are **not claimed to be wholly original Last MCP work or CC0**. This README does not grant a blanket repository-wide CC0 license, assert ownership of the CMU voice, or replace any third-party terms.
- The full supplied Flite distribution notices are retained unmodified in [flite-COPYING.txt](flite-COPYING.txt). The supplied KAL source/provenance, including its complete CMU permission notice, disclaimer and author attribution, is retained unmodified in [flite-kal-source-provenance.txt](flite-kal-source-provenance.txt). See [spoken-fixture-provenance.txt](spoken-fixture-provenance.txt) for exact audio metadata and hash. Original authors' names and notices are preserved.
- CMU and the original contributors do **not** endorse or promote Last MCP or this test. This is a plainly labeled synthetic test, not an impersonation or a recording of the test author.

## Synthetic speech asset

[spoken-fixture.wav](spoken-fixture.wav): 72,768 bytes; mono 8 kHz, 16-bit PCM; 4.54525 seconds.

SHA-256: `53d0c7b2698228d006802ac30aac739fd9ab776c64fca0630eff6e4e2d17df18`

Publication and byte verification are fixture infrastructure evidence only, **not** GitHub declarative action coverage, speech-recognition/transcription proof, or authorization to upload audio to AssemblyAI or any other provider.
