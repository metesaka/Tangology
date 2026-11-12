# Tangology

A knowledge graph of everything knowable about Argentine tango.

## Vision

Tango has a small, well-bounded and deeply interconnected body of knowledge: a few
thousand works, tens of thousands of recordings, the orchestras, singers, composers and
lyricists behind them, and the dancers, events and places that keep the music alive.
That knowledge is scattered across discographies, collector sites, liner notes and
people's heads. Tangology aims to bring it together in one curated, open, queryable
database.

## What it will contain

**Music** — works, recordings, orchestras, singers, composers, lyricists, sessions,
releases and transfers, with dates, genres, credits and lyrics.

**Audio** — links between the metadata and real audio files: fingerprints, tempo, key,
transfer quality.

**Dance** — performances on video, connected to the dancers, the recording they danced
to and the event where it happened.

**Events** — festivals, marathons, championships and local milongas, with their DJs,
teachers and venues.

## What it will enable

- Organising and tagging a large tango music archive
- A music player that knows the full story behind every recording
- Audio cleaning, remastering and light editing tools
- Tanda building and milonga planning
- An automatic DJ
- Exploring who danced what, where and when

## Approach

- The data is served as an RDF knowledge graph, built on the
  [Music Ontology](https://github.com/motools/musicontology) and extended for tango,
  with SHACL shapes for validation.
- The main graph holds one curated truth. Where sources disagree, the decision and its
  provenance are kept separately.
- The project is also a place to experiment with storage models — relational, RDF and
  property graph — over the same data.

## Status

Early stage. Data collection and modelling are under way; nothing is published yet.

## License

MIT
