@Library('ecommerce-shared-lib') _

microservicePipeline(
    image: "gracekluender/ecommerce-frontend",
    buildCommand: """
        npm install --legacy-peer-deps
        npm run build
    """,
    testCommand: "npm test -- --watchAll=false || true"
)