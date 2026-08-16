AI Security Engineering Knowledge Base — 22 Chapters

01-AI-Security-Engineering-Foundations

The technical foundation for securing AI systems.

What is AI Security Engineering?
AI security vs cybersecurity
AI security vs AI safety
AI attack surface
AI assets and trust boundaries
AI security principles
Secure-by-design AI
Defense-in-depth for AI
AI security lifecycle
AI security architecture principles
AI security engineering roles
AI security engineering maturity
AI security engineering vs AI governance

02-AI-Systems-and-ML-Architecture

Understand the technology before securing it.

Machine learning architecture
Deep learning architecture
Training pipelines
Inference pipelines
Model serving
Model registries
Feature stores
Data pipelines
Training infrastructure
GPU infrastructure
AI APIs
Foundation models
LLM architecture
Multimodal AI
Edge AI
AI SaaS
AI cloud architecture
AI system trust boundaries
AI data-flow architecture

03-AI-Threat-Modeling

Build the ability to identify threats before attacks occur.

AI threat modeling fundamentals
AI assets
Threat actors
Attack surfaces
Trust boundaries
Data-flow diagrams
AI attack trees
STRIDE for AI
MITRE ATLAS
Attack paths
Threat scenarios
Abuse cases
Misuse cases
AI threat libraries
Threat likelihood
Threat impact
AI threat prioritization
Threat modeling workshops
AI threat-model documentation

Core frameworks: MITRE ATLAS, STRIDE, attack trees, NIST AI RMF.

04-AI-Attack-Surface-and-Attack-Vectors

Map where AI systems can actually be attacked.

Training data
Datasets
Data pipelines
Models
Model repositories
Model APIs
Inference endpoints
Prompts
Context windows
RAG pipelines
Vector databases
Embedding systems
Plugins
Tools
Function calling
AI agents
AI memory
Cloud infrastructure
Containers
GPUs
CI/CD pipelines
Third-party AI services
Machine Learning Security

05-Machine-Learning-Security

Security of conventional ML systems.

ML security lifecycle
Training security
Model security
Inference security
Feature security
Feature manipulation
Model integrity
Model confidentiality
Model availability
ML authentication
ML authorization
ML access control
Model versioning
Model provenance
Model integrity verification
Model deployment security
Model monitoring

06-Adversarial-Machine-Learning

A dedicated chapter for adversarial ML.

Adversarial machine learning fundamentals
Adversarial examples
Evasion attacks
Poisoning attacks
Backdoor attacks
Trojan attacks
Model manipulation
Data manipulation
Transfer attacks
Black-box attacks
White-box attacks
Query-based attacks
Gradient-based attacks
Robustness
Adversarial training
Defensive distillation
Input validation
Detection mechanisms
Robust ML architecture

07-Data-Poisoning-and-Training-Security

Focus specifically on protecting the training process.

Training-data attacks
Data poisoning
Targeted poisoning
Availability poisoning
Backdoor poisoning
Label manipulation
Dataset contamination
Malicious datasets
Data provenance
Dataset integrity
Dataset authentication
Data validation
Data lineage
Training pipeline security
Secure data ingestion
Dataset versioning
Dataset signing
Training environment isolation
Secure training infrastructure

08-Model-Attacks-and-Model-Protection

Protect the model itself.

Model extraction
Model stealing
Model inversion
Membership inference
Model fingerprinting
Model replication
Model theft
Model tampering
Malicious model files
Model serialization attacks
Model supply-chain attacks
Model access control
Model encryption
Model watermarking
Model signing
Model provenance
Model integrity monitoring
Secure model repositories
Generative AI and LLM Security

09-LLM-Security-Engineering

The core technical security chapter for large language models.

LLM architecture
LLM attack surface
Prompt security
Context security
System prompt security
Token security
Context-window attacks
LLM access control
LLM API security
LLM authentication
LLM authorization
LLM output security
LLM input validation
LLM content filtering
LLM abuse prevention
LLM security architecture

10-Prompt-Injection-and-Jailbreaking

A dedicated deep-dive into prompt attacks.

Prompt injection
Direct prompt injection
Indirect prompt injection
Persistent prompt injection
Context manipulation
Jailbreaking
Instruction hierarchy attacks
System prompt extraction
Prompt leakage
Role manipulation
Multi-turn attacks
Delayed attacks
Malicious documents
Web-based prompt injection
RAG prompt injection
Agent prompt injection
Prompt attack detection
Prompt defense techniques
Prompt security testing

11-RAG-and-Vector-Database-Security

Secure Retrieval-Augmented Generation systems.

RAG architecture
Retrieval pipeline
Document ingestion
Chunking
Embeddings
Vector databases
Vector indexes
Retrieval security
Data poisoning
Malicious documents
Embedding attacks
Vector manipulation
Cross-tenant data leakage
Access-control failures
Unauthorized retrieval
Prompt injection through documents
RAG data isolation
Secure retrieval
RAG monitoring
RAG security testing

12-LLM-Application-and-API-Security

Secure applications built around AI models.

LLM application architecture
AI APIs
API authentication
API authorization
Rate limiting
Input validation
Output validation
Secure prompt construction
Secrets management
Session management
Context isolation
Data leakage prevention
Output encoding
Insecure output handling
Excessive consumption
Denial-of-service
Model abuse
AI application security testing
Secure LLM application patterns

Core reference: OWASP Top 10 for LLM Applications.

Agentic AI Security

13-Agentic-AI-Security

This should be one of the flagship chapters of the repository.

Agent architecture
AI agents
Autonomous agents
Multi-agent systems
Agent planning
Agent memory
Agent reasoning
Agent tools
Tool calling
Function calling
Agent permissions
Agent identity
Agent authentication
Agent authorization
Agent-to-agent communication
Agent trust boundaries
Agent attack surfaces
Agent security architecture

14-Agent-Tool-and-Identity-Security

Go deeper into the unique security problem of autonomous AI.

Agent identity
Machine identity
Non-human identities
Agent credentials
API keys
OAuth
Service accounts
Tool authorization
Least privilege
Just-in-time access
Tool allowlists
Tool deny lists
Function authorization
Privileged tools
Dangerous actions
Human approval
Transaction authorization
Agent delegation
Agent impersonation
Agent hijacking

15-Agent-Memory-Autonomy-and-Execution-Security

Protect what makes agents different from normal LLM applications.

Short-term memory
Long-term memory
Persistent context
Memory poisoning
Memory injection
Cross-user memory leakage
Context contamination
Autonomous execution
Action validation
Action boundaries
Human-in-the-loop
Human-on-the-loop
Approval gates
Transaction limits
Kill switches
Agent sandboxing
Execution isolation
Agent rollback
Autonomous failure containment
Secure AI Engineering Lifecycle

16-MLSecOps-and-Secure-AI-SDLC

Build security into the AI development lifecycle.

Secure AI SDLC
MLSecOps
DevSecOps for AI
Secure requirements
Secure architecture
Secure coding
Secure data engineering
Secure model development
Secure experimentation
Secure training
Secure deployment
CI/CD security
Model CI/CD
Security gates
Model approval gates
Artifact security
Dependency management
Secrets management
Infrastructure-as-code security
Production security

17-AI-Supply-Chain-and-Model-Security

Secure the entire AI software and model supply chain.

AI supply-chain threats
Open-source models
Model repositories
Hugging Face ecosystem
Third-party models
Foundation-model providers
AI APIs
Third-party datasets
Python dependencies
ML libraries
Containers
Docker
Kubernetes
Model artifacts
Model provenance
SBOM
AI/ML BOM
Software signing
Model signing
Dependency scanning
Supply-chain monitoring
AI Security Testing

18-AI-Security-Testing-and-Red-Teaming

Your practical offensive-security chapter.

AI penetration testing
LLM penetration testing
AI vulnerability assessment
AI red teaming
LLM red teaming
Agent red teaming
Adversarial testing
Prompt testing
Jailbreak testing
RAG testing
Model testing
Data poisoning testing
Model extraction testing
Privacy attack testing
Abuse-case testing
Security regression testing
Automated AI security testing
AI security test cases
AI security test reports

19-AI-Security-Validation-and-Continuous-Testing

Move beyond one-time testing.

AI security validation
TEVV
Security benchmarks
Model robustness
Model reliability
Security evaluation
Red-team metrics
Attack success rate
Jailbreak success rate
Prompt injection success rate
Data leakage rate
Hallucination security testing
Continuous evaluation
Continuous red teaming
Regression testing
Production validation
Model drift
Security drift
AI security gates
Continuous assurance
Defensive AI Security

20-AI-Security-Operations-and-Defense

How to operate AI securely in production.

AI SOC
AI security monitoring
AI telemetry
AI logs
Prompt logging
Model logging
Agent activity logging
Tool-call logging
SIEM integration
SOAR integration
AI anomaly detection
AI abuse detection
Threat detection
AI security alerts
AI security dashboards
Runtime protection
Runtime policy enforcement
AI security posture management
Continuous monitoring

21-AI-Incident-Response-and-Forensics

Respond when AI security fails.

AI security incident response
LLM incidents
Prompt injection incidents
Data poisoning incidents
Model compromise
Model theft
AI data leakage
Agent compromise
Agent hijacking
Malicious tool execution
Deepfake incidents
AI-enabled fraud
Incident containment
Model isolation
Model rollback
Agent shutdown
Kill switches
Evidence preservation
AI forensics
Prompt forensics
Model forensics
Post-incident analysis

22-AI-Security-Engineering-Tools-Labs-and-Case-Studies

This should become the hands-on/practical chapter of the repository.

AI Security Tools
MITRE ATLAS
OWASP GenAI Security Project
LLM security tools
Prompt-injection testing tools
AI red-team tools
Model scanning tools
Dataset security tools
AI supply-chain tools
Model monitoring tools
AI runtime security tools
AI security platforms
Practical Labs
Build a vulnerable LLM application
Attack prompt injection
Defend against prompt injection
Build a vulnerable RAG application
Attack a vector database
Secure RAG
Perform model extraction
Simulate data poisoning
Test adversarial examples
Build an AI agent
Attack an AI agent
Secure agent tool access
Implement least privilege for agents
Build an AI security monitoring pipeline
Perform an AI red-team exercise
Case Studies
Enterprise ChatGPT breach
LLM data leakage
Prompt injection attack
RAG poisoning
Model theft
AI supply-chain compromise
AI agent compromise
AI-powered phishing
Deepfake attack
AI-enabled fraud
Autonomous-agent failure
Recommended Repository Structure

AI-security-engineering-knowledge-base/
│
├── 01-AI-Security-Engineering-Foundations/
├── 02-AI-Systems-and-ML-Architecture/
├── 03-AI-Threat-Modeling/
├── 04-AI-Attack-Surface-and-Attack-Vectors/
├── 05-Machine-Learning-Security/
├── 06-Adversarial-Machine-Learning/
├── 07-Data-Poisoning-and-Training-Security/
├── 08-Model-Attacks-and-Model-Protection/
├── 09-LLM-Security-Engineering/
├── 10-Prompt-Injection-and-Jailbreaking/
├── 11-RAG-and-Vector-Database-Security/
├── 12-LLM-Application-and-API-Security/
├── 13-Agentic-AI-Security/
├── 14-Agent-Tool-and-Identity-Security/
├── 15-Agent-Memory-Autonomy-and-Execution-Security/
├── 16-MLSecOps-and-Secure-AI-SDLC/
├── 17-AI-Supply-Chain-and-Model-Security/
├── 18-AI-Security-Testing-and-Red-Teaming/
├── 19-AI-Security-Validation-and-Continuous-Testing/
├── 20-AI-Security-Operations-and-Defense/
├── 21-AI-Incident-Response-and-Forensics/
├── 22-AI-Security-Engineering-Tools-Labs-and-Case-Studies/
│
└── README.md

GRC Knowledge Base	How do we govern the organization?
AI Security Governance Knowledge Base	How do we govern AI securely?
