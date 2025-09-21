# Campfire-Storytelling-Insurance

## Overview

Campfire-Storytelling-Insurance is a parametric insurance system designed specifically for outdoor storytelling events around campfires. This innovative smart contract platform provides automated insurance coverage based on real-time environmental conditions, ensuring that storytelling events can proceed safely or receive compensation when weather or safety conditions make them impossible.

## Project Description

This system provides parametric insurance for outdoor storytelling events using fire safety and weather monitoring. The platform automatically monitors environmental conditions and provides claims processing for event cancellations due to safety concerns.

## Architecture

The system consists of three main smart contracts:

### 1. Fire Safety Oracle (`fire-safety-oracle`)
- Real-time monitoring of wind conditions
- Fire restriction alerts and drought level assessment
- Weather pattern analysis for fire safety
- Automated risk level calculation

### 2. Audience Comfort Tracker (`audience-comfort-tracker`)
- Assessment of seating conditions and comfort levels
- Temperature monitoring and comfort indexing  
- Smoke management and air quality tracking
- Audience safety metrics

### 3. Event Cancellation Claims (`event-cancellation-claims`)
- Automated refund processing
- Claims validation based on oracle data
- Weather-based cancellation triggers
- Fire ban enforcement and compensation

## Features

- **Parametric Insurance**: Automatic payouts based on predefined conditions
- **Real-time Monitoring**: Continuous assessment of environmental conditions
- **Automated Claims**: No manual claim filing required
- **Weather Integration**: Advanced weather pattern analysis
- **Fire Safety Compliance**: Adherence to local fire restrictions
- **Audience Safety**: Comprehensive comfort and safety tracking

## Smart Contract Functionality

### Fire Safety Oracle
- Monitors wind speed and direction
- Tracks local fire restrictions and bans
- Assesses drought conditions and fire danger levels
- Provides safety recommendations

### Audience Comfort Tracker
- Evaluates seating arrangements and capacity
- Monitors ambient temperature and humidity
- Tracks smoke dispersion and air quality
- Calculates overall comfort indices

### Event Cancellation Claims
- Processes automatic refunds for weather cancellations
- Handles fire ban related cancellations
- Validates claims against oracle data
- Manages payout schedules and amounts

## Use Cases

1. **Weather-based Cancellations**: Automatic compensation when severe weather prevents events
2. **Fire Restriction Compliance**: Immediate alerts and refunds when fire bans are implemented  
3. **Safety-first Operations**: Continuous monitoring ensures participant safety
4. **Comfort Assurance**: Environmental monitoring maintains optimal conditions
5. **Risk Management**: Proactive assessment prevents dangerous situations

## Technology Stack

- **Blockchain**: Stacks blockchain
- **Smart Contracts**: Clarity language
- **Development**: Clarinet framework
- **Testing**: Automated unit tests
- **Deployment**: Mainnet/Testnet ready

## Getting Started

### Prerequisites
- Clarinet CLI installed
- Node.js and npm/yarn
- Git version control

### Installation

1. Clone the repository:
```bash
git clone https://github.com/musahamza3152-hue/Campfire-Storytelling-Insurance.git
cd Campfire-Storytelling-Insurance
```

2. Install dependencies:
```bash
npm install
```

3. Run tests:
```bash
clarinet test
```

4. Check contracts:
```bash
clarinet check
```

## Contract Deployment

The contracts are designed to work independently without cross-contract calls, making them simple to deploy and maintain.

### Mainnet Deployment
```bash
clarinet deployments generate --mainnet
clarinet deployments apply --mainnet
```

### Testnet Deployment
```bash
clarinet deployments generate --testnet
clarinet deployments apply --testnet
```

## Configuration

Configuration files are located in the `settings/` directory:
- `Mainnet.toml` - Mainnet deployment settings
- `Testnet.toml` - Testnet deployment settings  
- `Devnet.toml` - Local development settings

## Testing

Each contract includes comprehensive unit tests:
```bash
# Run all tests
clarinet test

# Run specific contract tests
clarinet test tests/fire-safety-oracle_test.ts
clarinet test tests/audience-comfort-tracker_test.ts
clarinet test tests/event-cancellation-claims_test.ts
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For questions or support, please open an issue in the GitHub repository or contact the development team.

## Roadmap

- [ ] Oracle integration for real-time weather data
- [ ] Mobile app for event organizers
- [ ] Advanced analytics dashboard
- [ ] Multi-region deployment support
- [ ] Integration with weather services APIs

## Acknowledgments

- Stacks blockchain community
- Clarity language developers
- Clarinet framework contributors
- Open source insurance protocol research