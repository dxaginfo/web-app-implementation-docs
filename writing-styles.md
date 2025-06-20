# Writing Styles Implementation

This document describes the five writing styles that have been implemented in the Content Creator Interface.

## 1. Super Writer GPT (Tim Ferriss Style)

### Characteristics:
- Clear, actionable, and concise writing
- Step-by-step breakdowns of complex topics
- Focus on practical applications
- Evidence-based approaches
- Personal anecdotes to illustrate points
- Specific examples and case studies
- Questions that provoke thought
- Contrarian viewpoints to challenge conventional wisdom

### Example Output Structure:
- Strong, attention-grabbing headline
- Clear introduction stating the problem and promise
- Numbered or bulleted lists for key points
- Specific, actionable advice
- Expert quotes or research citations
- Conclusion with clear takeaways

## 2. Super Writer GPT (Tim Ferriss Style) + James Clear (20%)

### Characteristics:
- All Tim Ferriss style elements plus:
- Focus on habit formation and behavior change (20%)
- Systems over goals mentality
- Breaking down big changes into small, manageable steps
- Emphasis on environment design for behavior change
- Clear cause-and-effect relationships
- Scientific principles explained in accessible language

### Example Output Structure:
- Thought-provoking headline
- Personal story or scientific insight hook
- Core concept explained simply
- Practical application with small, actionable steps
- Analogies to make complex ideas relatable
- Final thought that reinforces the main concept

## 3. Insight Writer GPT (Shane Parrish Style)

### Characteristics:
- Focus on mental models and frameworks
- Interdisciplinary connections between different fields
- Emphasis on decision-making processes
- Clear explanations of cognitive biases
- Structured thinking approaches
- Historical examples and case studies
- Focus on wisdom that stands the test of time

### Example Output Structure:
- Conceptual introduction that frames the problem
- Key mental model or framework introduction
- Practical application of the model
- Common mistakes or pitfalls to avoid
- Historical examples or case studies
- Reflective questions for the reader
- Concise summary of key insights

## 4. Brutally Honest GPT (Mark Manson Style)

### Characteristics:
- Direct, sometimes provocative language
- Counterintuitive perspectives
- Focus on values and what truly matters
- Cut through societal BS and conventional wisdom
- Humor and occasional profanity
- Personal responsibility emphasis
- Paradoxical truths and embracing contradictions

### Example Output Structure:
- Attention-grabbing, possibly provocative headline
- Challenge to conventional wisdom
- Counterintuitive insight as main thesis
- Personal anecdotes or relatable scenarios
- No-nonsense advice with direct language
- Acknowledgment of life's inherent difficulties
- Empowering conclusion focused on personal choice

## 5. Idea Curator GPT (David Perell Style)

### Characteristics:
- Connection of ideas across domains
- Building blocks approach to knowledge
- Strong metaphors and analogies
- Internet-age context and digital implications
- Clear narrative arcs
- Visual thinking and mental imagery
- Focus on the creative process

### Example Output Structure:
- Engaging narrative hook or surprising fact
- Personal connection to the topic
- Big idea introduction with historical context
- Unexpected connections between concepts
- Practical implications for modern life
- Metaphors that make complex ideas tangible
- Inspiring conclusion with future implications

## Implementation Notes

Each writing style has been implemented as a comprehensive prompt template in the `writing-styles.ts` file, with specific instructions for:

1. Voice and tone characteristics
2. Structural elements to include
3. Typical phrasing patterns
4. Types of examples and evidence to include
5. Conclusion formatting

The Content Creator Interface allows users to select any of these styles and generate content that faithfully represents the chosen writer's approach.