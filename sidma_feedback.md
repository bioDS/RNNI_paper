 Referee 1 (Remarks to the Author):

Review of GEOMETRY OF RANKED NEAREST NEIGHBOUR INTERCHANGE SPACE OF PHYLOGENETIC TREES
by Collienne et al.

The manuscript focuses on a new metric for comparing trees, ranked nearest neighor interchange, which extends to the well-known nearest neighbor interchange distance to trees with a ranking on the their internal nodes. The traditional nearest neigbor exchange move is augmented with an additional move that interchanges the rank of two adjacent internal nodes. The paper establishes the radius and diameter of the space of this new metric and develops heuristics for computing ranked NNI distance.

I would suggest accepting the paper with major revision, since the results are interesting but there the following major issues need to be addressed:

* The title does not fit paper. The focus of the paper is on the distance between trees and on the distance when restricting only to caterpillar trees and not on the geometric properties of the family of discrete spaces induced by this metric.

* The abstract does not capture the results in the paper. Instead, it reads more as an introduction and does not summarize the actual results of the paper.

* The results are interesting, but the proofs read as sketches you would present on a whiteboard, not as formal proofs. They are likely to be true, but it is hard to verify in their current form. For proofs about the correctness and running time of algorithms, there are standard ways to present them in concise and verifiable manner. See for examples the proofs in Cormen, Leiserson, and Rivest or an algorithms-focused conference such as STOC or FOCS.

Comments & Small Typos:

* p 5, last paragraph: Since this is the crux of the paper, expand, add images, and work through an example of the algorithm.
* p 6, Algorithm, l 5: Replace "T' is T'..." with "T' is T'...", since line 8 will overwrite T' with T'.
* p 6, Algorithm, l 5: Reword line and/or expand discussion in text to demonstrate what this is doing.
* p 6, Proof, first line: Remove the sentence "It is not hard to see that the algorithm..." or move to before the proof in the informal discussion of what the algorithm is doing. In the formal discussion (i.e. the proof), state why the algorithm terminates (i.e. expand on the rest of that first paragraph).
* p 6, Proof, second paragraph: Include an argument about why line 5 makes sense in the algorithm, in the explanation of it before the proof, and here, in the proof.
* p 6, Proof, third paragraph: Remove "it is not hard to see" and replace with images or written explanation.
* p 6, Proof, Case k > 1: Fill in the missing words before starting the subcases.
* p 6, Proof, Case k > 1, (1): Define the term "supress" in terms of ranked trees.
* p 6, Proof, After (3): The end of the proof is missing. Complete the proof.
* p 6, l 9-: While is highly likely that the worst-case complexity is quadratic, you need to demonstrate why that is the case. The simplest, and most convincing way would be to write this as a proposition and then go line-by-line detailing the running time.
* p 7, Caterpillar sort: Since these algorithms are central to your paper, write out the proofs of their running time and correctness.
* p 7, l 21-: Define "number of inversions".
* p 7, l 17-: Define "appear in opposite orders".
* p 7, l 13-: Not sure why the statement starting with "Hence" about the shortest caterpillar path follows from the previous statements about Kendal tau distances. Explain the connection or reword.
* p 8, first paragarph: Explain or prove why the MDTree only produces caterpillars. Add images and work through the algorithm.
* p 8, l 12-: State whether you are including the root in your set of taxa. If not, then it would be good to explain why different rooted trees have the same set of splits (e.g., the rooted trees (1,(2,3)) and ((1,2),3) have the same split set) so that the later discussion on clusters is clearer.
* p 8, Lemma 3: Include example and image for this lemma.
* p 9, Proof of Lemma 3: This is an good motivation of the lemma and would be better as a lead-in to the proof, and then fill in a rigorous proof in its place.
* p 10, Proof of Lemma 4: Second sentence runs on and does not make sense. What is a step? If it is a single move on the caterpillar tree, then moves one per step? Rewrite to make this clear.
p 15, l 1: Replace "one to one" with "one-to-one".
p 15, Proof: Most of the proof is missing. Add in rest of proof.